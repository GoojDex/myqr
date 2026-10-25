# myqr
## QR Code scanner for login hotspot Apna WiFi

### 

1. Tambahkan button di login.html
```html
<button onclick="window.location='https://goojdex.github.io/myqr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="Apna WiFi QR Code Scanner" disabled=no dst-host=goojdex.github.io
```

### Powered by GoojDex
