# golang-hello-web

# Quick How to Develop and Deploy on Go App Engine

## Install Go App Engine SDK
https://cloud.google.com/appengine/downloads

## Add go_appgengine to PATH
export PATH=$HOME/go_appengine:$PATH

## Clone this repo
git clone ...

## Run locally
goapp serve golang-hello-web/ 

## Create new project on App Engine
https://console.developers.google.com

## Update app.yaml 
application: [app_engine_project_name_here]

## Deploy to App Engine
goapp serve golang-hello-web/ 

# Reference:
https://medium.com/google-cloud/go-cloud-endpoints-and-app-engine-e3413c01c484

