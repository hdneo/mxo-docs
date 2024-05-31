# Setup your developmemnt enviroment 

### 1. Choosing an IDE
As this is a .NET Core project you might want to choose your favorite IDE. 
You can use Visual Studio, VSCode or Rider (recommend).

### 2. Download and configure the Client 
See [Download](../development/downloads) Section on how you can download the client.
Extract the client somewhere. 

In the client files there is a file useropts.cfg.
- Edit it with your favorite Editor of your choice (notepad or something
- Add the following lines:

  AuthServerDNSName = "recursion.localserver"

  MarginServerDNSSuffix = ".localserver"

  UseLaunchPad=0 

 
Create a "matrix2.bat" file inside the folder and add the following line:
matrix2.exe -clone -noeula -nopatch -user loluser -pwd lolpass

As loluser is the default testuser you could mostly leave it as it is but also change to your own.
This batch file just starts the game.

Now Start notepad with Administrator rights (right click on notepad "open as administrator").
Choose "File" -> "Open" and navigate to "C:\Windows\System32\drivers\etc" and open hosts.
If you don't see any files change to "all files" instead of txt. 

Add the following line:

127.0.0.1	reality.localserver

Make sure there is a tab between 127.0.0.1 and reality.localserver.
Save the file and exit notepad.

### 3. Checkout the Hardline Dreams Project
TBD


