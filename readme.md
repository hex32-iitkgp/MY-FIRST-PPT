$ FROM ubuntu
// Creates a layer for base ubuntu

$ RUN apt update
// Creates another layer for Updated Packages

$ RUN apt install python3
// Makes another layer for installed python 

$ COPY app.py /app/
// Creates another layer for copied app.py