# RPC Packets

<style>
    .status { padding: 5px; }
    .status_not_started { background: red; }
    .status_progress { background: orange; }
    .status_done { background: green; }
</style>

### Client RPC #### 

| OPCode | Name                                                    | Status                                     | 
|--------|---------------------------------------------------------|--------------------------------------------|
| 0x05   | [CLIENT_SPAWN_READY](/research/rpc/client_spawn_ready) | <div class="status status_done">100%</div> | 
| 0x28   | [CLIENT_CHAT](/research/rpc/client_chat)              | <div class="status status_done">100%</div> |
| 0x29   | CLIENT_WHISPER                                          | <div class="status status_done">100%</div> |
| 0x2a   | CLIENT_SET_AFK                                          | <div class="status status_done">100%</div> |

## Server RPC

| OPCode | Name                             | Status                                     | 
|--------|----------------------------------|--------------------------------------------|
| 0x003a | SERVER_FEATURE_EVENT             | <div class="status status_not_started">100%</div> | 
| 0x8102 | SERVER_TUTORIAL_BLINK | <div class="status status_not_started">100%</div> |
