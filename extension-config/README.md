# Extension Config

For Assetto Corsa (2014) **Requirements**:

- LATEST CSP!
- USE Sol WEATHER for **controller** but either Pure or Sol for script is fine

> *NOTE.* If you want rain, get the [Preview CSP](https://www.patreon.com/x4fab)

## How-to

### Copy-paste ext_config.ini

1. Make a folder name it "extension" inside the track's folder
2. Make a blank .txt file and name it "ext_config"
3. Copy all the content from .ini from here to the .txt previously made
4. Paste & save it
5. Rename the extension file from .txt to .ini and if there's warning proceed it

###### Directory

```
assettocorsa
|__content
   |__tracks
      |__[track's folder name]
         |__extension
```

---

### Copy-paste models.ini

Overall the same as the **Copy-paste ext_config.ini** but most track already
come with models.ini but if your track doesn't, make one. By simply create .txt file, name it **"models"** and rename the extension name to .ini
then you want to copy the .kn5 name and paste it inside the **models.ini** with this line...

```ini
[MODEL_0]
FILE=[.kn5 name].kn5
POSITION=0,0,0
ROTATION=0,0,0
```

This is the same as `MODEL_0` but this time is a dynamic object (e.g. Birds, planes)

```ini
[DYNAMIC_OBJECT_0]
PROBABILITY=100
MULT=1,1
FILE=[.kn5 name].kn5
POS_MODE=RANDOM
RND_POS_CENTER=-300,250,-900
RND_POS_RANGE=100,50,100
VEL_MODE=RANDOM
RND_VEL_BASE=2,0,2
```

> *NOTE.* Make a sequence if you want to make another `MODEL_n` and/or `DYNAMIC_OBJECT_n` whereas **n** is a number

---

### Install a VAO Patch file

1. Download it
2. Put it to the track's folder
3. Done

> *NOTE.* You can check whether the VAO Patch has been installed correctly, you can check it [here](https://github.com/ac-custom-shaders-patch/acc-extension-apps)

## Troubleshooting

If you have any problems or wanted to ask the guide How-to, just ask me by creating an "Issue"

Enjoy! :)
