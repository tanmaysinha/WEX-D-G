# FAQ
 - On Windows installation, the window to input the username/password for mounting the volume may not appear in front. 

   - You may need to search if the screen is found behind the installer.  (Installation itself will be succeeded once you input the username/password, but may be confusing.)

   - ![](https://github.com/ibm-wex/WEX-D-G/blob/master/images/docker_msg_windows.png)

 - While installation, if there is an interruption in internet connection. The Application waits till the connection is back, and continues after. But there are cases when the percentage may go beyond 100% because of the interruption. In this case, close the application, restart the Docker Daemon and relaunch the application.

 - If the Application redirects to error page right after installation, after multiple tries. In this case check run the command `docker ps -a` on the terminal and check to see if the status of the container is in 'Created' state. If it is in Created state then run `docker rm -f wex-d-g` to remove the container. Finally relaunch the Application.

 - For users who would like to look at the mounts on the terminal. Run the command `docker exec -it wex-d-g ls /mnt`.

 - For users using windows machine with AsureAD. When trying to mount a folder, the docker prompts for user credentials. Even after the user enters the password, as the password stored for the AzureAD account is not local, it will not succeed. This is a issue from Docker and Windows with Azure AD. The workarounds are provided here:
 https://github.com/docker/for-win/issues/257
 https://github.com/docker/for-win/issues/263
