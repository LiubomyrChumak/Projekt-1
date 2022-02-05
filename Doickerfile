FROM python:3.8.0
COPY app.py
RUN apt update
RUN python -m pip install -U pip
RUN pip install -r Projekt-1/requirements.txt
RUN pip install -e app.py
CMD ["app.py"]
