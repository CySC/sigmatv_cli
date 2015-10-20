# sigmalive_cli
sigmalive cli is a command line client for accessing sigma.com on demand shows.
The name ids somehow misleading as this is not a client for  sigmalive news website but sigma.co video on demand service. Although the name is a result of initial confusion on the difference between the two services, live was kept in the name in orderto demonstrate that this app is dedicated to streaming episodes to your mplayer client rather than downloading their files.
###Example usage: 
```sh
./sigmalive_cli <show_name> <season (optional,Default:1)> <episode_number(optional, Default:1)>
```
To check the list of shows simply run without arguments:
```sh
./sigmalive_cli
```
###Dependencies:
mplayer
