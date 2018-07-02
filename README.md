Unofficial repo for installing hassbian-config (hassbian-script) with `sudo apt install hassbian-scripts`
  
For this to work you first need to run this:
```
$ sudo apt install -y apt-transport-https
$ echo "deb [trusted=yes] https://gitlab.com/hassbian/repository/raw/master $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hassbian.list
$ sudo apt-get update
```
