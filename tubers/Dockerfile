FROM python:3.8.2
RUN mkdir /code
WORKDIR /code
COPY . /code/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD python manage.py runserver 0.0.0.0:8000