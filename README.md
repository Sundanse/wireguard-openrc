<h1 align="center">[AUTOSTART WIREGUARD WITH OPENRC]</h1>

``` bash
>
 sudo su
 mv wireguard /etc/init.d/ && chmod +x /etc/init.d/wireguard
```

``` bash
>
 rc-update add wireguard default
 rc-service wireguard start
```


> change "VPN?????" to wireguard config name (wg0.conf)
