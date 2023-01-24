# Completing Oracle Exercise
I had given a task to completely install and run docker desktop in my laptop. After installing, i had to run a sample app on docker.  

## Installing Docker Desktop
Installation of Docker Desktop was easy as we follows the documentation provided to us.  
refer:
https://docs.docker.com/desktop/

## Running Docker Dekstop
It was a difficult task to launch Docker Desktop successfully.

### Problems Occuring
Docker was not able to launch.  
Error Shown: Unable to Calculate image disk size.  
Window Subsystem for Linux was missing. Also the setting up distro was missing.  

### Solution: Troubleshooted with some commands on Powershell (by running as Administration).  
Command for checking the state : wsl -l -v  
Command for checking the list of valid distributions : wsl -l -o  
Command for installing distribution : wsl --install <distro>  
Command for switching Daemon :  & 'C:\Program Files\Docker\Docker\DockerCli.exe' -SwitchDaemon  
  
## Steps that can be more clear 
Cloning and unzipping of the github file should be more clear.  
  
Addition of docker file should be explained more.  

## Running app as a container
Documentation : https://docs.docker.com/get-started/02_our_app/  present here provides enough guide to run file as a docker container and can be used to deploy 
and maintain applications.  

### Examples of Docker Containers running:
strange_chaplygin :  
  Images used:  
  https://github.com/nginxinc/docker-nginx  
  https://github.com/alpinelinux/docker-alpine  
  
  
  

  
  
  
  
 
  
  
  

