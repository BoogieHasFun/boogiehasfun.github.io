# Hosted on: 
  - https://boogiehas.fun (thanks galacticlemonade)
  - https://github.boogiehas.fun (github pages custom domain feature)
  - https://boogiehasfun.github.io

> [!NOTE]
> Ignore the rest if you are not a developer or plan to contribute.
# Self-hosting
### Local hosting w/ python
  Step 1: download `python`. you can do this using `choco install python`, or using `scoop install main/python`, going onto their [website](https://www.python.org/downloads/), or using apt-get:
  ```
  sudo apt-get update
  sudo apt-get install 3.12
  ```

  Step 2: run this command: `python -m http.server` or `python3 -m http.server`, or `py -m http.server`.  
  access the website with `localhost:8080`, for testing on other devices on your network you must find your machines local ip.
_
### Finding your local ip
  Local IP address usually follow this format: 192.168.\*.*** (\* is a random number)
  
  Windows: Run `ipconfig` in CMD or Powershell, look for an adapter with `IPv4 Address.....`  
  Linux Machines (systemctl?): Run `ip address`, can be shortened to `ip a`  
  for other operating systems or distros a quick google search should do.  

