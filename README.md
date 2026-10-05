# KJY_QR_SCANNER
## QR Code scanner for login hotspot MikroTik

### How to Use.

1. Add a button in login.html
```html
<a class="hp-qrscan" href="https://angelrekcah1987.github.io/KJY_QR_SCANNER" target="_blank" rel="noopener noreferrer">
```
2. Add the following script in MikroTik via Terminal.
```
/ip hotspot walled-garden ip

add action=accept comment="KJY QR Code Scanner" disabled=no dst-host=angelrekcah1987.github.io
```

### Powered by webqr.com
