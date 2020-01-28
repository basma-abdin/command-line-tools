# Server to launch command line tools
## Backend
    Java Spring
## Frontend
    ReactJs (my partner worked on it)

Content :
 - src: Contains server source files (Java files)
 - Frontend: Contains client source files (Javascript and html files)
 - doc: Contains server decoumentation (javadoc)
 - Testfile: Contains files to test the project grouped by name of the order
 - pom.xml: Server configuration file
 - Dockerfile: Docker configuration file

# Launch of tools and execution:
## Prerequisites to execute correctly
    Have Docker installed...

Install the JarAndDocker.zip folder on this link: http://tiny.cc/xjlajz. This folder contains (Dockerfile and a "target" folder contains the project jar)

     Unzip the installed folder JarAndDocker.zip
     Move to the JarAndDocker folder: cd /JarAndDocker
     You type in the terminal: (docker build -f Dockerfile -t springdocker.)
     After you have Built successful, you type in the terminal: (docker run -it -p 8080: 8080 springdocker)

Once the server is launched you see the spring logo, the server is launched on the door 8080 (localhost: 8080).
Your turn to try!
    On the browser, you launch (http: // localhost: 8080
    you can try gcc, latex and dot command
