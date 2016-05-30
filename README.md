# sigmatv
sigmatv cli is a command line client for accessing sigma.com on demand shows.
CLI tool used to play sigma tv on demand on your linux machine using mplayer.
###Example usage: 
```sh
./sigmatv <show_name> <season (optional,Default:1)> <episode_number(optional, Default:1)>
```
To check the list of shows simply run without arguments:
```sh
./sigmatv
```
###Dependencies:
mplayer
bash 4+
###Optional dependencies:
npm(for installation via npm)

###Install via npm
`sudo npm install -g "git+https://github.com/CySC/sigmatv_cli.git"`
