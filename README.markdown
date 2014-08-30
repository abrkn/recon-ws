recon-ws
===

Auto reconnecting websocket client.

Install
---

`npm install recon-ws`

Usage
---

```javascript
var ReconWs = require('recon-ws')
var ws = new ReconWs('wss://localhost')
ws.on('message', function(msg) {
	console.log('<-- %s', msg)  
})
ws.send('Hello world!')
```

Author
---

Andreas Brekken &lt;<a href="mailto:a@abrkn.com">a@abrkn.com</a>&gt;

Tips
---

Like this? Send bitcoins to 1<b>abrkn</b>ajSFpnz7MHjLkVnuvCbwd96wSYt

[![1abrknajSFpnz7MHjLkVnuvCbwd96wSYt](https://chart.googleapis.com/chart?chs=100x100&chld=L|0&cht=qr&chl=bitcoin:1abrknajSFpnz7MHjLkVnuvCbwd96wSYt)](https://chart.googleapis.com/chart?chs=200x200&chld=L|0&cht=qr&chl=bitcoin:1abrknajSFpnz7MHjLkVnuvCbwd96wSYt)

License
---

ISC
