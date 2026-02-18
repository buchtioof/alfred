# alfred
the grabber companion, it sends computer informations in a json package then send it to the server (grabber), need the server to be listening for the response.

## build

to use it, clone the git then use this command
`makeself ./alfred alfred.run ./alfred/alfred.sh`

## usage

run alfred with this command
`./alfred.run "add ip:port of your server without double quotes ofc"`

## dependencies
- inxi (lastest release)
- jq (1.8.1 tested)
