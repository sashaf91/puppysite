# puppysite
in a command window
workon my_django
python manage.py runserver
navigate to 127.0.0.1:8000

# Docker
docker build -t puppysite -f Dockerfile .
docker run -p 8000:8000 puppysite
