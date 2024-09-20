<<Important to READ below intructions to make docker-compose.yml work correctly>>

1)First make sure that you have docker engine installed and running properly on your operating system.

2)Then install docker-compose tool from official docker documentation.The link is given below:
https://docs.docker.com/desktop/install/linux/

3)Now, go to frontend directory and open /src/App.js in any editor. Edit the url with the hosting machine's url.
I have already made comments in frontend/src/App.js where you will replace url with your own url. 

4)Now, the multi-container application is ready to run.

5)Run docker-compose up -d command in the terminal and open your browser, visit the URL on which the frontend application
is running. You will see the app running.
