# sainsburys-test
Front-end responsive test

Front-end Test from Sainsburys. Only desktop and mobile wireframes supplied and needed.

Setup of static front-end via yeoman scaffolding generating tool, see here for more information - http://yeoman.io/

installation instructions:

1. download and install nodejs from http://nodejs.org/en
2. download and install git from http://git-scm.com/downloads 
3. open command prompt as administrator if on pc or open terminal if on mac
4. type npm install -g grunt-cli on windows or sudo npm install -g grunt-cli on mac and enter password if asked
5. type npm install -g bower on windows or sudo npm install -g bower on mac and enter password if asked
6. download and unzip my files from my github repository
7. navigate to directory usign command prompt (administrator mode) or terminal
6. type npm install - may need to type 'sudo npm install' if you have errors on mac
7. type bower install - may need to type 'sudo bower install' if you have errors on mac
8. type grunt build in order to build the project and output into dist file (in the same directory, i.e sainsburys-test-master/dist)
9. type grunt serve:dist which will run the built project on a server and automatically serve on your default browser

* note in order to stop the batch processor, press Ctrl + c to quit, and it will stop the server.

The built files automatically have a version control on the styles, and the js src attr on the homepage. This can easily be removed and customised within gruntfile.js




