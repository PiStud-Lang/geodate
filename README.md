![Banner](https://github.com/user-attachments/assets/1b5b5684-1cdc-4d1b-98df-7c73a56bf789)


<h1 align="center"> geodate </h1>
<p align="center"> How to use | About | How to setup | Download </p>
<br><br>

### About
- **How it works**: When putting the raw link on a package reader, it'll read that package and decode it into Pust code
- **Info**: When creating the package for pust, please program it into pust, python is also ok

### How to setup
- **1.** Get geodate, and load it up to program your package (Use PiStud or Python to program), please note that you need to use the ide version of PiStud to make a package
- **2.** Open geomain.py, and you'll get a small tutorial

### How to use
- **1.** After your done, publish your package to github as one file
- **2.** Add it into the "package.py" (You need the ide), like this:
   ```py
    [""" Package """]
    import urllib.request
    version = 6.5
    name = "versions"
    exec(urllib.request.urlopen("https://tinyurl.com/geodate").read().decode())
    exec(urllib.request.urlopen("raw link here").read().decode()) # This is where you put your package by adding an extra exec raw
   
    [""" DECODED """]
   ```

### Download
Use git clone to get Gopust
```bash
git clone https://github.com/PiStud-Lang/geodate
```
