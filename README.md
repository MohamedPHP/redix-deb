# Redix DEBIAN Package

Here is the debian package for [RedixDB](https://github.com/alash3al/redix)

## For Developing (Technical requirements):

[build-essential](https://packages.ubuntu.com/trusty/build-essential)
```
sudo apt update && apt install build-essential
```
[devscripts](https://packages.debian.org/search?keywords=devscripts)
```
sudo apt update && apt install devscripts
```
[debhelper](https://packages.debian.org/search?keywords=debhelper) debhelper version 9 or higher
```
sudo apt update && apt install debhelper
```

### Installing

Compiling to .deb file

```
dpkg-deb --build redix-deb
```

Installing .deb file

```
sudo dpkg -i redix-deb.deb
```

## Authors

* **Mohamed Zayed** - [Mohamed Zayed](https://github.com/MohamedPHP)
* **Mohammed Alash3al** - [Mohammed Alash3al](https://github.com/alash3al)

## License

This project is licensed under the MIT License.
