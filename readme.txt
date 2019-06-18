*****DEPLOY******:

gcloud auth application-default login
gcloud config set project <PROJECT_ID>
gcloud init
gcloud app deploy app.yaml



https://weatherapp-236707.appspot.com




You can stream logs from the command line by running:
  $ gcloud app logs tail -s default

To view your application in the web browser run:
  $ gcloud app browse