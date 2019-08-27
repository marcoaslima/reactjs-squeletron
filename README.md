#ReactJS and Electron united

This project aims to create a way to develop desktop and webapps using the same base code with Electron and ReactJS.
You can check a example using this template on https://github.com/marckdx/react-electron-calculator

![Home Screen](https://s3.us-east-2.amazonaws.com/blascke.com/images/react-squeleton-example-welcome.png)

### Running electron desktop app
    yarn electron-dev

### Running web app standalone
    yarn start
Open your browser and go to http://localhost:3000

### Running web app with docker
    docker-compose up -d --build

### Generating Package
    yarn build
    cd build/
Change the content on electron.js 
    const isDev =  true;
    yarn start

### On the build directory

Once we built and prepared all the files needed it is just pack
    yarn add electron-packager
Be sure to have electron installed, otherwise run 
    yarn add electron
You can test using 
    electron .
Packaging:
    electron-packager .
