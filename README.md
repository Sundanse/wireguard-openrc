<h1 align="center">[AUTOSTART WIREGUARD WITH OPENRC]</h1>

![image](https://user-images.githubusercontent.com/96197813/150184226-4d237aed-59c8-403c-bf5d-3e688a0d9b78.png)


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
