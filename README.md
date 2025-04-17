# PDF_Generator


Steps to pull this repo in your local system just use these commands : 

1. Open VS Code in the desired folder to install this repo.
2. Open the terminal and type the command :
   git clone <repository-url>
3. Then type : 
   pip install -r requirements.txt
4. Then run the file by using the below command, as it is usingthe  streamlit Framework, we will use the  command:
     streamlit run main.py




To upload this in GCP : 
Command to build the application. Please remember to change the project name and application name

gcloud builds submit --tag gcr.io/vat-generator-project/vat-generator-project  --project=vat-generator-project

Command to deploy the application

gcloud run deploy --image gcr.io/vat-generator-project/vat-generator-project --platform managed  --project=vat-generator-project --allow-unauthenticated
