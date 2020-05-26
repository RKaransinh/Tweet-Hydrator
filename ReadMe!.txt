karan@Karansinh MINGW64 ~
$ cd hydrator/

karan@Karansinh MINGW64 ~/hydrator (master)
$ yarn install


Install Hydartor! 

1) Download the package file from: https://drive.google.com/open?id=1qL6k5cW8l7FFYeMVkAjjE5hihsV9B_yI
2) Run "Hydrator-Setup-0.0.8.exe" file as administrator
3) For Win, you might get a security error, click on "more info" and force install the setup

Connect to Tweeter APi!

1) Open Hydartor app
2) In the "Settings" section you'll find a "Link Twitter Account" button which should take you to tweeter api page, for security permissions
3) "Allow" the permissions

Add a New Dataset!

1) Open the "Add" section
2) Create a .txt file which consist of only tweet ids in each line (use python code in "Hydrator_Feed.ipynb" located in this g-drive)
3) Locate this .txt file and add it to "Select Tweet Id File"
4) Fill below credentials (which are not mendatory)
5) Press "Add Dataset"

This will start the conversion of TweetIds to Tweet data

Extratct to csv

1) Once the conversion is done, press "csv" button
2) Select the path where you want to save the file
3) Write the name of file with ".csv" as extension (just mention this extension in file name itself)

##################   Final File is Ready !  #########################