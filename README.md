Unofficial repo for installing hassbian-config (hassbian-script) with `sudo apt install hassbian-config`
  
For this to work you first need to run this:
```
echo "deb [trusted=yes] https://raw.githubusercontent.com/ludeeus/hassbian-config/master stretch main" | sudo tee -a /etc/apt/sources.list
sudo apt-get update
```
### Release notes
**0.6.0**:  
- Added dependencies for home-assistant upgrade  
- Added fix for TRADFRI install script  
- Added Appdeamon install script  
- Adden DuckDNS install script  
  
  
  
  
 - [Making sure wheel and setuptools are up to date](https://github.com/home-assistant/hassbian-scripts/pull/62) [@ludeeus](https://github.com/ludeeus)
 - [Fiexes Trådfri on HASSBian](https://github.com/home-assistant/hassbian-scripts/pull/59) [@ludeeus](https://github.com/ludeeus)
 - [Attempt to fix Tradfri after 0.55](https://github.com/home-assistant/hassbian-scripts/pull/58) [@Landrash](https://github.com/Landrash)
 - [Razberry install script.](https://github.com/home-assistant/hassbian-scripts/pull/57) [@Landrash](https://github.com/Landrash)
 - [Additional database install scripts](https://github.com/home-assistant/hassbian-scripts/pull/56) [@Landrash](https://github.com/Landrash)
 - [Install script for MariaDB](https://github.com/home-assistant/hassbian-scripts/pull/53) [@Landrash](https://github.com/Landrash)
 - [Appdeamon install script](https://github.com/home-assistant/hassbian-scripts/pull/52) [@Landrash](https://github.com/Landrash)
 - [Preperation for 0.6](https://github.com/home-assistant/hassbian-scripts/pull/51) [@ludeeus](https://github.com/ludeeus)
 - [Update scripts from dev branch](https://github.com/home-assistant/hassbian-scripts/pull/50) [@ludeeus](https://github.com/ludeeus)
 - [Changed function of show commad](https://github.com/home-assistant/hassbian-scripts/pull/49) [@ludeeus](https://github.com/ludeeus)
 - [Support for duckdns](https://github.com/home-assistant/hassbian-scripts/pull/48) [@ludeeus](https://github.com/ludeeus)
 - [Added installation script for an web terminal.](https://github.com/home-assistant/hassbian-scripts/pull/46) [@ludeeus](https://github.com/ludeeus)
