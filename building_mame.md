1. install dependencies
```
sudo apt-get update && sudo apt-get -y install git build-essential python libsdl2-dev libsdl2-ttf-dev libfontconfig-dev qt5-default
```


2. Clone the repo
```
git clone -b mame0228 --depth 1 https://github.com/mamedev/mame.git mame0228
```

3. Build Mame
```
cd mame0228
make -j 4
```
