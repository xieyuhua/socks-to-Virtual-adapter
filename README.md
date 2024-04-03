# win-socks-to-Virtual-adapter4.0
<h3>帮助你将socks代理转到一张虚拟网卡上，所有经过虚拟网卡的流量会被发送到代理for windows </h3>
<p>感谢badvpn，windows tap项目  <br>
<p>udp需要服务端支持<br>
将tcp转发至虚拟网卡转发至socks，udp通过tcp方式转发到socks然后在服务端转换为udp发送出去</p>
<h3>注意事项</h3>
适用于IPV6服务端，服务端为ipv4需自行修改route<br>
<p>看对应版本的readme</p>




```
Usage of E:\socks5\gotun2socks.exe:
  -enable-dns-cache
        enable local dns cache if specified
  -local-socks-addr string
        local SOCKS proxy address (default "127.0.0.1:1080")
  -public-only
        only forward packets with public address destination
  -tun-address string
        tun device address (default "10.0.0.2")
  -tun-device string
        tun device name (default "tun0")
  -tun-dns string
        tun dns servers (default "8.8.8.8,8.8.4.4")
  -tun-gw string
        tun device gateway (default "10.0.0.1")
  -tun-mask string
        tun device netmask (default "255.255.255.0")
```

