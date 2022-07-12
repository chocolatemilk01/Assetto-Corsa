# Complete Extension Pack
For Assetto Corsa (2014) Requirements:
- LATEST CSP! *make sure your CSP is the preview/paid version to have rain*
- USE Sol WEATHER for **controller** but either Pure or Sol for script is fine

## How-to
**Copy-paste ext_config.ini**
1. Make a folder name it "extension" inside the track's folder
2. Make a blank .txt file and name it "ext_config"
3. Copy all the content from .ini from here to the .txt previously made
4. Paste & save it
5. Rename the extension file from .txt to .ini and if there's warning proceed it
--------------------------------------------------------------------------------
**Copy-paste models.ini**

Overall the same as the **Copy-paste ext_config.ini** but most track already
come with models.ini but if your track doesn't, make one. By simply create .txt file, name it models and rename the extension name to .ini
then you want to copy the .kn5 name and paste it on there with this line...
```
[MODEL_0]
FILE=[.kn5 name].kn5
POSITION=0,0,0
ROTATION=0,0,0
```
If you want add more objects or models to it, make another and rename the number to a sequence

You want add a moving object like birds? Still the same but with this line...

And if you want to add more dynamic object to it, it's still the same as the previous one
```
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
--------------------------------------------------------------------------------
**Install a VAO Patch file**
1. Download it, because this isn't a classic code lines like .ini or .txt
2. Put it to the track's folder
3. Done
--------------------------------------------------------------------------------
## Troubleshooting
If you have any problems or wanted to ask the guide How-to, just ask me by creating an "Issue"

Enjoy! :)
