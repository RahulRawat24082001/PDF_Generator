# PDF_Generator

Command to build the application. PLease remeber to change the project name and application name

gcloud builds submit --tag gcr.io/vat-generator-project/vat-generator-project  --project=vat-generator-project

Command to deploy the application

gcloud run deploy --image gcr.io/vat-generator-project/vat-generator-project --platform managed  --project=vat-generator-project --allow-unauthenticated
