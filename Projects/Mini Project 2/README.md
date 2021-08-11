# streamlit-reg-mlapp-project2
A simple streamlit app that uses linear regression to predict car co2 emissions

Datasource: https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6

- App repository is located at https://github.com/adireksa/streamlit-linregapp-project2
- App url shared is at https://share.streamlit.io/adireksa/streamlit-linregapp-project2/main/app.py

## clone this repository to your own local folder
- cd to local folder and follow below instructions

## build Docker image
- docker build -t streamlitapp:latest .
Note: builds from pip

## create docker container for streamlit app.py from Dockerfile
- docker run -p 8501:8501 streamlitapp:latest

## view app on localhost at following port after building from Dockerfile
- http://localhost:8501/
