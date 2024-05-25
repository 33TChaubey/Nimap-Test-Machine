cd nimap_test

python3 -m venv venv

source venv/bin/activate

pip3 install -r requirements.txt

<!-- Uses Postgresql -->
python3 manage.py makemigrations

python3 manage.py migrate

python3 manage.py runserver

## Here's the link of the client and projects

{
    "clients": "http://localhost:8000/api/clients/",
    "projects": "http://localhost:8000/api/projects/"
}