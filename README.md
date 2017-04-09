To work on this project, issue the following command to get the repository

git clone https://github.com/ankur748/MyPortfolio.git

This project can be used to create a responsive portfolio of your featured projects

- You need to edit the index.html file to add your projects and update information for yourself in the page.
- For images, we have added a grunt framework which automates the process of producing images required across devices ranging from mobiles to HD desktops. More information about it can be found below

1) Upload your cover and portfolio work images in original_images folder. This folder acts as input for grunt script.
2) Sizes needed are already configured in Gruntfile.js file under js/grunt folder. If required, you can modify the sizes based on your convenience.
3) Grunt script needs ImageMagik to be installed on your laptop. For reference, ImageMagik can be installed on Mac by issuing the command "brew install imagemagik"
4) After installing imagemagik, grunt framework needs few npm modules to run successfully. Go to js/grunt folder and issue the command "npm init"
5) After npm has downloaded the modules required, we just need to run "grunt" and grunt will push all the required size images into images/ folder
6) You can reference the images in index.html as per your convenience.