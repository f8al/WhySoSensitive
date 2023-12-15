# WhySoSensitive


Based on FGDS.sh by [Ivan Glinkin](https://github.com/ivanglinkin) WhySoSensitive aims to be a 1 stop automated tool for running google dorks specifically for the purposes of finding sensitive files exposed on the web

Usage example:
--------------
```
chmod +x YSoSensitive.sh
./YSoSensitive.sh megacorp.one
```
or
```
bash ./YSoSensitive.sh megacorp.one
```

Usage example with proxy:
--------------

```
bash ./YSoSensitive.sh megacorp.one 192.168.1.1 8080
```

This will work beatifully on any unix with the "bc" package installed, but an ultimately universal way is through Docker. 

Docker usage example:
---------------
```
docker build -t FOO .
docker run -it --rm FOO mysite.com
```

Screenshots:
---------------
![](https://github.com/f8al/media/blob/main/WhySoSerious3.png?raw=true)


Issues:
---------------
- Colors dont properly display in bash on MacOS
