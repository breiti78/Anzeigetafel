FROM nodered/node-red:latest

# installing an editor
#USER root
#RUN apt-get update && apt-get install nano
USER root

RUN npm install node-red-dashboard


# install node-red-admin which is needed if you want to created hashed password for the node-red editor.
#RUN sudo npm install -g --unsafe-perm node-red-admin

COPY settings.js /data/settings.js
