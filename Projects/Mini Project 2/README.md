# streamlit-reg-mlapp-project2
App repository is located at https://github.com/adireksa/streamlit-linregapp-project2
App url shared is at https://share.streamlit.io/adireksa/streamlit-linregapp-project2/main/app.py

#build Docker image
docker build -t streamlitapp:latest .

# create docker container for streamlit app.py from Dockerfile
docker run -p 8501:8501 streamlitapp:latest

#view app on localhost at following port
http://localhost:8501/