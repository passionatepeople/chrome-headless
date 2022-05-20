# chrome-headless

Based on https://github.com/NiNiyas/headless-chrome but with some extra flags.
Only builds that image for amd64 + arm64 so it also works on Apple Silicon macs.

# usage

```
$ docker run -it --rm -p=0.0.0.0:9222:9222 --name=chrome-headless -v /tmp/chromedata/:/data timvdeijnden/chrome-headless
```