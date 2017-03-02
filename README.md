Packaged using [fpm](https://github.com/jordansissel/fpm).

Installation
-----------
```
sudo apt-get install libnss3
sudo dpkg -i <chrome-headless_package_name.deb>
```

Run
-----------
`chrome-headless --headless --disable-gpu --no-sandbox --remote-debugging-port=9222`

Uninstallation
-----------
`sudo dpkg -r chrome-headless`
