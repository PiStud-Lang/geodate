![Banner](https://github.com/user-attachments/assets/6c0d476e-b86b-42b3-a081-99a4a7b3763c)

<h1 align="center"> gopust </h1>
<p align="center"> How to use | About | How to setup | Download </p>
<br><br>

### About
- **How it works**: When putting the raw link on a package reader, it'll read that package and decode it into Pust code
- **Info**: When creating the package for pust, please program it into pust, python is also ok

### How to setup
- **1.** Get Gopust, and load it up to program your package (Use Pust to program), please note that you need to use PustIDE to make a package
- **2.** Open go-main.py, and you'll get a small tutorial

### How to use
- **1.** After your done, publish your package to github as one file
- **2.** Add it into the "package.py" (You need PustIDE), like this:
   ```py
    [""" Package """]
    import urllib.request
    version = 6.5
    name = "versions"
    exec(urllib.request.urlopen("https://tinyurl.com/gopust").read().decode())
    exec(urllib.request.urlopen("raw link here").read().decode()) // This is where you put your package by adding an extra exec raw
   
    [""" DECODED """]
   ```

### Download
Use git clone to get Gopust
```bash
git clone https://pust-lang/gopust
```
