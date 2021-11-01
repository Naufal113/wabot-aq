# wabot-aq

Simple WhatsApp Bot

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Nurutomo/wabot-aq)

## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
apt install imagemagick -y
git clone https://github.com/Nurutomo/wabot-aq
cd wabot-aq
npm install
npm update
```

## INSTALL ON TERMUX WITH UBUNTU

[ INSTALLING UBUNTU ]

```bash
apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
```
---------

[ INSTALLING REQUIRED PACKAGES ]

```bash
ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
```

---------

[ INSTALLING NODEJS & WABOT-AQ ]

```bash
ubuntu
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/Nurutomo/wabot-aq
cd wabot-aq
npm install
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/Nurutomo/wabot-aq
cd wabot-aq
npm install
npm update
```

---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

### `--self`

Activate self mode (Ignores other)

### `--pconly`

If that chat not from private bot, bot will ignore

### `--gconly`

If that chat not from group, bot will ignore

### `--swonly`

If that chat not from status, bot will ignore

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--db <json-server-url>`

Use external db instead of local db, 
Example Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

The server should have like this specification

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

If small qr unicode doesn't support

### `--restrict`

Enables restricted plugins (which can lead your number to be **banned** if used too often)

* Group Administration `add, kick`

### `--img`

Enable image inspector through terminal

### `--autoread`

If enabled, all incoming messages will be marked as read

### `--nyimak`

No bot, just print received messages and add users to database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

## `ON 24JAM?`
`Tapi harus login dulu`

[`klik`](https://replit.com)

[`klik`](https://heroku.com)


## `ADD BUILDPACK`

```
> https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
```

## `CHANGE SESSION`

[`Click Here`](https://github.com/naufal132/Alphabot7/edit/master/session.json#L1)

## `SETTING`

- Owner number [Here](https://github.com/naufal132/Alphabot7/edit/master/settings.json#L4)
- Owner name [Here](https://github.com/naufal132/Alphabot7/edit/master/settings.json#L13)
- Botname [Here](https://github.com/naufal132/Alphabot7/edit/master/settings.json#L14)

## `Jasa Logo`

[`click`](https://6285157160906)
----------

<p align="center">
  <a href="https://wa.me/13193433799"><img src="https://c.top4top.io/s_2131e2mop0.jpg" />
</p>

## ```HOW TO DEPLOY```

[`Click Here For Tutorial`](https://youtu.be/_CP2_1Yqauo)<br>

----------

<p align="center">
  <a href="https://youtu.be/_CP2_1Yqauo"><img src="https://a.top4top.io/p_2081imvxm1.jpg" />
</p>
    
## `Naufal Tutor`

[`click`](https://youtube.com/channel/UC1fmmnFo25NO3jzlca-A-jQ)
----------

<p align="center">
  <a href="https://youtube.com/channel/UC1fmmnFo25NO3jzlca-A-jQ"><img src="https://b.top4top.io/s_21315ayx81.jpg" />
</p>
 
## `AtakBotz`

[`click`](https://youtube.com/channel/UCT76Agxm4N_MbefBoywjDRA)
----------

<p align="center">
  <a href="https://youtube.com/channel/UCT76Agxm4N_MbefBoywjDRA"><img src="https://a.top4top.io/s_2131888pb0.jpg" />
</p>

## ```wa kami```

- [`No bot`](wa.me/13193433799)
- [`No owner Naufal`](wa.me/6282266467066)


## ```GC BOT```
- [`GC botnaufal×atakbot`](bit.ly/naufal×ridho)
- [`GC HENGCKER WIBU Tyz`](bit.ly/WibuTyz)

