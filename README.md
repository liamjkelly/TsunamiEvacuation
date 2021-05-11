# TsunamiEvacuation

## IMPORTANT: In order to run the model, you must follow the following steps:

1. Make sure your Netlogo version is configured to work with your machine. The docs are [here](https://ccl.northwestern.edu/netlogo/docs/r.html). You will have to ensure you have R downloaded on your machine and have the package rJava installed.
2. Once R and rJava are installed, you must copy the path of your R and your jri folders from the command line into the user.properties file provided in this repository. That file must be placed in the corresponding directory. For windows, that directory is: '''C:\Users\YOUR_USERNAME\AppData\Roaming\NetLogo\6.1\r\'''
3. Once the r extension compiles you must modify the absolute path of the tsunami inundation data to match its location on your local machine. This is the line '''r:eval "data<-nc_open(\"C:/YOUR_PATH_HERE/TsunamiEvacuation/GISData/inundation/finalflowdeptht45-200.nc\")"'''
4. Any issues/to just view the simulation over zoom, please do not hesitate to reach out!
