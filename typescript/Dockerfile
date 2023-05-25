FROM alpine:latest
LABEL Version="1.0.0"
LABEL Description="Dev Env for Typescript projects."
#Run things as ROOT
RUN apk add --update nodejs npm jq nano tree doas
WORKDIR /home/app
ENV ENV="/root/.ashinit"
RUN echo -e "\n#Aliases for all Profiles \nalias ll='ls -la'\nalias dev='cd /home/app'" >> ~/.ashinit
