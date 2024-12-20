## Reset server 
### Stop process
```js
pkill -kill -u username
```
### Delete files and their folders
```js
chmod -R 755 ~/* 
```
```js
chmod -R 755 ~/.* 
```
```js
rm -rf ~/* 
```
```js
rm -rf ~/.* 
```
### Recover folders and index.html files
HOME: [mail  , repo  , domains]

domains: [username.serv00.net]

username.serv00.net: [logs , public_html]

logs: [access]

public_html: [index.html]
