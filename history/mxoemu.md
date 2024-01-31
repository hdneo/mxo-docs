# The History of MxO Emulation

Ok mates lets talk a little bit about the History of Server Emulation in Matrix Online.

**2004 - Damienstone and "MxOEmu"**

This was the very first approach. MxO was still in Closed Beta and Damien was searching for people who wants to help him.

He build a small "crappy" Server that just patch the Client (and maybe does login?) but as the files was never released , no one knows how far he was or not.

The Sourceforge Project still exist but it isnt active since Years.

URL : [sourceforge.net/projects/mxoemu/](http://sourceforge.net/projects/mxoemu/)

[](http://sourceforge.net/projects/mxoemu/screenshots/4454)

-   ![mxoemu](./images/mxoemu.598.449.s.jpg)

**2005 - Tequila and MXOemu.de\
**

In 2005 some German Person tried to make an Emulator (or just had some Server Files from Damienstone ? we dont know...) .

It isnt much known about the Project. Just it wasnt long online.

Refering to the Webarchive (Url : [web.archive.org/web/20070204143007/http://www.mxoemu.de/files/index.php](http://web.archive.org/web/20070204143007/http://www.mxoemu.de/files/index.php) ) you can see that it was a small page with just a useropts.cfg to download.

The "News" from 01.09.2005 was interesting :

*Good News :)\
We are able to get Ingame using the newest version of the Game (with SOE Station Login) with our Server.

If someone is able to help us with the Serverlist we would be able to build a our own Serverlist. For now we are using a modified captured Serverlist:****\
***\
As far as i can remember Rajko told us that Tequila had just this "stripped" login server.

If you just want to lol to see what it is, you can find it in our download section.

**2005/2006 - Rajkosto first try\
**\
Somewhere in this time , rajko decided to start his own Server Emulation Project.\
I can remember as well he had several Domains and Names lol.

Starting with **tmosim.cjb.net** where he first released the stripped login server and starts his work for an emulator.

Since 2009 the Name and the URL changed a lot of time (from mxosim.us.to , mxosim.co.nr to some others).

Progress at the beginning goes slow as for the high amount of researching and reversing. Mr. X joined his project but dont know how much he had done in the background.

Then somewhere in 2008 i think his domains where all unavailable and you didnt heard much from rajko.

No files or source wasnt released in this time. But as far as i know he had broke the encryption for the World Server and he build a packet sniffer somewhere in this time.

**2009 - When the world ends...**

As Rarebit announce that he left SOE , i thought about the give the MxO Emulation for myself a try. After many research what still exists i came to the results above in this site :)

So the first thing i had done was contacting rajko , but he didnt really cared about MxO in this time. Somewhere in this time morpheus contacted me (i think it was on elitepvpers ) and we both started researching.

As SOE announce in May 2009 that MxO will be shut down , we started tmoemu.tk (The Matrix Online Information Center lol - which is today mxoemu.info).

Again - i contacted Rajko with no big result in the first case. As our Website in Forum was online i decided to contact him the last time - and was suprised that he was willing to give it a try again.

Rajko released his sniffer and the Reality (v1) source code he had.

While Rajko and Morpheus was working on encryption for Margin and Auth, i sniffed as most packets as possible and tried some researching too.

Just World Packets but hell - you saw the packet logs :) You saw how had the most count of packet logs rofl.

On 7.7.2009 Auth Encryption was broken (see this thread : [mxoemu.info/forum/thread-35.html](http://mxoemu.info/forum/thread-35.html) ).

I didnt believed at this time that it is possible to break the encryption - but 2 days before end it was fully broken and rajko released the full proxy / sniffer (Thread : [mxoemu.info/forum/thread-50.html](http://mxoemu.info/forum/thread-50.html) ).

With this we all was able to sniff auth and margin packets too.

At this case Rajko and Morpheus does the Major Work - without broken encryption , no MXO Emulation :)

After some day the first Version from Reality was released (just to enter the world without any official server) .

A Month later the lovely **Reality V2** (on 25th September 2009) was released which was used to test packets .

**2010 Hardline Dreams**

I think it was in Feburar 2010 . There was some trouble between valaro/morpheus and rajko. However i woke up and saw that my Admin Rights were revoked on the mxoemu.info .\
After a little talk with rajko and the question why i got the response "you deserved it".\
There happens other things short before too .

After talking with morpheus we decided to launch our own project with a Source Code that is Reality Independent (Thread : [mxoemu.info/forum/thread-367.html](http://mxoemu.info/forum/thread-367.html) ).

It took some time to write a server from scratch again (as we had first an own World Server in C++ then a full version in Python and then decided to switch to c# and stay on it :)).