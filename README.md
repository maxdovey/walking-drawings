# Fluxus Event Scores SMS

[FLUXUS SPACE](www.fluxus.space)

index.js is the main application does the lifting in terms of processing the form input and writing it to a txt file called 'numbers.txt'

things easily forgotten -
*production ENV numbers directory is full root path /max/flux-fone/
*this text file is used by flux fone to send out messages 
* if your having write issues to remote node modules folder try 
`sudo chown -R $(whoami) /var/www/fluxus.space/node_modules/`


to do >

* ~~send to some friends for feedback (george, Ruth, Liam, Jon D, Juliette)~~
* ~~update about text~~
* update all json files on server with clean edited local versions (KEn Friendman >)
* create stop / remove function (e.g. look for senders number from numbers.txt file and remove that item from list)~~
* remove duplicates from numbers.txt (clean santize data)~~
* flux-fone add time interval between sending messages 

