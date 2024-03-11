WizTools.org RESTClient via Docker using Lando

- To start:

lando start

- To run app:
lando restclient

- Bash script to run app:
./restclient.sh

- To exit:

lando stop
lando poweroff

- The folder where this readme is was mounted to /app. You can save your request/response files there:
  /app/requests
  /app/responses

- if you need to access the built-in Trace Server on your computer at address 0.0.0.0:10101, in .lando.yml uncomment the ports setting.
