FROM python:3.9.0
# exposing default port for streamlit
EXPOSE 8501
WORKDIR /streamlit_server
COPY requirements.txt ./requirements.txt
# install pip then packages
RUN pip3 install -r requirements.txt
# copying all files over
COPY . .
ENTRYPOINT ["streamlit", "run"]
CMD ["app.py"]

