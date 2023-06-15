# project-3

## How to run the POC implemetation locally with fastapi



1. Clone the repo and cd into the server_fastapi directory. # We are using fastapi sever for now.
   
2. Create a python virtual environment 
    python -m venv venv

3. Activate the virtual environment
    source ./myenv/Scripts/activate

4. Install python dependencies using the requirements.txt
    pip install -r requirements.txt

5. Create a .env file and store your openai api key in it
    OPENAI_API_KEY='xxxxxxx'

6. Create a Data folder and copy the file you want pull data from there. # I gitgnored the folder because I did't want any data on github

6. Run your fast api server
    uvicorn app:app --reload

# Frontend
1. cd into the client and npm run start to start React frontend.

2. User is able to end prompts

