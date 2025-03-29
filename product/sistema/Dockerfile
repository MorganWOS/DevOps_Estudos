# syntax=docker/dockerfile:1
FROM python
WORKDIR /home
RUN pip install django flask
COPY . .
EXPOSE 8050
CMD ["python3", "manage.py", "runserver", "0.0.0.0:8050"]
