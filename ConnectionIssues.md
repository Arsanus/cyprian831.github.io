First off, there are two ways to fix this issue, One is from [ske's github](https://xske.github.io/garlium/) and one I learned from the friendly folks in the wallet-help section of the discord.

1.
  -Under the `tools` option on the top bar select `network`
  -In the new window select the "server" tab on the top
  -Uncheck the box that says `select server automatically`
  -In the `server` box input one of the servers below and the port in the adjescent box
  -Click on `close` and wait a couple minutes for it to update
  -If this doesnt work, repeat with a different serer
  -If youve tried all the servers and its still not working recheck the box and restart the wallet client
  
2.
  -Navigate to your garlium system file (`/home/username/.garlicoin/` on linux and `C:\users\username\AppData\Roaming\Garlium` for windows)
  -Edit the `recent_servers` with a notepad program
  -Paste this into the file:
  
  ```
  [
    "ske.wtf:50004:s",
    "84.245.14.110:50002:s",
    "garlium.kenzierocks.me:50002:s",
    "172.93.54.31:50002:s",
    "mhamburger.net:50002:s",
    "electrum.garlicsoup.xyz:50002:s"
  ]
  ```
  -Save the file
  -Restart your wallet

## Addresses
| Server        | Port          | Owner(discord name)  |
| ------------- |:-------------:| -----:|
| ske.wtf      | 50004 | @Ske#6201 |
| 172.93.54.31      | 50002      |  @DBN#1688 |
| 84.245.14.110 | 50002      |    @Bonobo#8875 |
