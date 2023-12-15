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

with proxy

```
bash ./YSoSensitive.sh megacorp.one 192.168.1.1 8080
```

This will work beatifully on Kali but an ultimately universal way is through Docker. Just run 

```
docker build -t FOO .
```

and then run it with your argument for the URL such as this:

```
docker run -it --rm FOO mysite.com
```

