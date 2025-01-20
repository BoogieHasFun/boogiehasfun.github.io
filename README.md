# boogiehasfun.github.io
i will attempt to make a good [website](https://boogiehas.fun)

hosted on: 
- https://boogiehas.fun
- https://github.boogiehas.fun (github pages custom domain feature)
- https://boogiehasfun.github.io

## Self-hosting
Please don't make your fork of my website a ip grabber then self-host it and give me the link so you can tell me my ip address ~~(sounds like something galaticlemonade would do)~~. I am not an expert at self-hosting, it's best if you figure it out on your own. <br>

**~~please~~ don't host this website on your own domain unless there is major modifications to it, don't waste your time**

### Local hosting w/ python
Step 1: download `python`. you can do this using `choco install python`, or using `scoop install main/python`, going onto their [website](https://www.python.org/downloads/), or using apt-get:
```
sudo apt-get update
sudo apt-get install 3.12
```

Step 2: run this command: `python -m http.server` or `python3 -m http.server`, or `py -m http.server`. this will serve your website over http, on your pc's localhost, on port 8000. if you, for example, want to test your website on mobile to see if it works on small screens, you can find your localhost on windows by running `ipconfig` in cmd, or on some linux distros like Ubuntu you can run `ip address` to find your local ip, for other operating systems or distros you gotta find out on your own. if you want to test your website on your computer that you are running the server on it's as simple as putting in `localhost:8000` into your address bar.

### that's it. you don't have to run your website like this (and probably shouldn't), but for testing it's simple and easy as most people have python installed anyways.

