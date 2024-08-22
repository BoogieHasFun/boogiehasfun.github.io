# boogiehasfun.github.io
i will attempt to make a good [website](https://boogiehasfun.github.io)

## Self-hosting
If you ever want to self-host my website. You're gonna need something like python, and other stuff like ngnix if you are hosting it publicly. Also, please don't make your fork of my website a ip grabber ~~(sounds like something galaticlemonade would do)~~. I am not an expert at self-hosting, it's best if you figure it out on your own. <br>

**please don't host this website on your own domain unless there is major modifications to it, don't waste your time**

### Local hosting w/ python
Step 1: download `python`. you can do this using `choco install python`, or using `scoop install main/python`, going onto their [website](https://www.python.org/downloads/), or using apt-get:
```
sudo apt-get update
sudo apt-get install python3.6
```

Step 2: run this command: `python -m http.server` or `python3 -m http.server`. this will serve your website over http, on your pc's localhost, on port 8000. if you, for example, want to test your website on mobile to see if it works on small screens, you can find your localhost on windows by running `ipconfig` in cmd, or on ubuntu you can run `ip address` to find your local ip. if you want to test your website on your computer that you are running the server on it is as simple as putting in `localhost:8000` into your address bar.

### that's it. you don't have to run your website like this (and probably shouldn't), but for testing it's simple and easy as most people have python installed anyways. have fun playing around with your creations!
<!--hehe secret fail-->
