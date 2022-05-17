# chrome-headless

Inspired by https://github.com/alpeware/chrome-headless-trunk but with ARM64 & AMD64 architecture support.

# usage

```
$ docker run -it --rm -p=0.0.0.0:9222:9222 --name=chrome-headless -v /tmp/chromedata/:/data timvdeijnden/chrome-headless
```