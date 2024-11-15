# Car Dealers Website

Environment setup

Open another new terminal, run git clone or pull

Run the following to set up the Django environment:

cd /home/project/xrwvm-fullstack_developer_capstone/server\
pip install virtualenv\
virtualenv djangoenv\
source djangoenv/bin/activate

Install the required packages by running the following command:

python3 -m pip install -U -r requirements.txt

Run the following command to perform model migration:\
python3 manage.py makemigrations\
python3 manage.py migrate\
python3 manage.py runserver

cd /home/project/xrwvm-fullstack_developer_capstone/server/frontend\
npm install\
npm run build

go to server/database
docker build -t nodeapp .
docker-compose up
