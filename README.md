# Using google+ open api to Login.

This project demonstrate a login flow using google open api. <https://developers.google.com/+/web/signin/#enable_the_google_api>

## Register App Engine

Register test-project at here.
<https://console.developers.google.com/project>
- Make project
- Enable Google+ Api Service
- In Credential Tab, make OAuth client ID, and select Web application.

## Boot server

python -m SimpleHTTPServer

## Login via webbrowser

127.0.0.1:8000 or localhost:8000

### Simple Explanation

When initialize **gapi.auth2.init** this, you can get the users data, defining scope.

### This document written in 2016.04.27
