For Assetto Corsa (2014) Requirements:

- LATEST CSP
- USE Sol WEATHER! If you got Pure it's ok
- Extension of FX for tracks

|HOW TO COPY-PASTE IT:|

1. Create .txt file rename it to 'ext_config'
2. Copy all the lines
3. Paste
4. Save it
5.Rename the .txt to .ini and apply
6. Move it to the game directory (...\assettocorsa\content\tracks\ **TrackID** \extension)

- *NOTE. Create folder name it 'extension' inside the track folder

|HOW TO ADD [DYNAMIC_OBJECT_*n*] TO models.ini:|
1. Download the dynamic object (e.g. birds)
2. Extract the archive and copy the contents to ...\content\objects3D\ **folder name** (or you can leave it there)
3. Make custom [DYNAMIC_OBJECT_*n*] to track's models.ini (if the track doesn't have one, make one)
  
  **example**
  
  [DYNAMIC_OBJECT_*n*]
  PROBABILITY=150
  MULT=1,1
  FILE=..\..\objects3D\birds\birds_1.kn5
  POS_MODE=RANDOM
  RND_POS_CENTER=-240,250,380
  RND_POS_RANGE=700,125,700
  VEL_MODE=RANDOM
  RND_VEL_BASE=3,1,3
  RND_VEL_RANGE=1,1,1
  
4. If the track already has models.ini, just copy-paste it to the models.ini... **BUT, RENAME THE *n* TO THE NEXT NUMBER FROM THE EXISTING NUMBER IN [DYNAMIC_OBJECT]**

- *NOTE. *n* indicates number
- *NOTE. For 4th instruction, make the number sequence, so if the existing is 4 then continue it with 5 and so on

![image](https://user-images.githubusercontent.com/106296453/177900252-c849e279-84e4-4ef6-8e62-05346d431417.png)
^if you're confused

Enjoy! :)
