<img src="public/static/scan.png" alt="pc_home" width="30%" />

# :: Prism X · Integrated lightweight cross-platform penetration system

---

<p align="center">
  <a href="https://prismx.io/guide" target="_blank">Use documentation</a> ·
  <a href="">Host management</a> ·
  <a href="">risk scan</a> ·
  <a href="">exploit</a> ·
  <a href="">Emergency assistance</a>
</p>

## start up

### · WEB system

Download the software package corresponding to OS ARCH [Prism X releases](https://github.com/yqcs/prismx/releases/)
，After unzipping, grant executable permissions and run it directly.。

<img src="public/static/pc_home.jpg" alt="pc_home"/>

Linux Amd64 Run the example：

```bash
$ wget https://github.com/yqcs/prismx/releases/download/{new version}/built.zip
$ wget https://github.com/yqcs/prismx/releases/download/{new version}/lib.zip
$ wget https://github.com/yqcs/prismx/releases/download/{new version}/prismx_linux_amd64
$ unzip built.zip
$ unzip lib.zip
$ chmod +x prismx_linux_amd64
$ ./prismx_linux_amd64
```

### WEB model

WEB mode requires a License file, which is built in lib.zip. Run the `./prismx_linux_amd64` command and access `https://yourIP:443` to enter the login page. Use the -port parameter to specify the port. System default account `prismx/prismx@passw0rd`
, please change your account name and password for first time use!

### CLI Command Line

The command line mode does not require any dependent files, but it only has a basic scanning module and cannot use advanced functions such as WEB mode scanning configuration and information collection. Execute -h
Command to get related help。

```bash
$ ./prismx_linux_amd64_cli -h
$ ./prismx_linux_amd64_cli -t 127.0.0.1 -p 1-500,3000-6000
```

### · Interface preview

<img src="public/static/view.jpg" alt="pc_home"/>

---

## QQ Security Research Group:

### [Click to join：528118163](https://jq.qq.com/?_wv=1027&k=azWZhmSy)

## Join the group/contact (left) | Public account: Zhetian Laboratory (right)

<img src="public/static/wx.jpg" width="200"><img src="public/static/wx_qrcode.jpg" width="200">
