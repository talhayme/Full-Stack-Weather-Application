*****DEPLOY******:

gcloud auth application-default login
gcloud config set project <PROJECT_ID>
gcloud init
gcloud app deploy app.yaml







Logs:
  $ gcloud app logs tail -s default

View in browser:
  $ gcloud app browse
