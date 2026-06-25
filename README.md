


 Create a virtual environment
python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows
 Install dependencies

pip install -r requirements.txt
Apply migrations

python manage.py migrate
##Create a superuser

python manage.py createsuperuser
## Run the development server

python manage.py runserver
go to the url: http://127.0.0.1:8000

Docker Deployment (Production-Ready)
## Build & run containers

docker-compose build
docker-compose up -d


## Stop containers

docker-compose down



internship_platform/
│── accounts/           
│── applications/      
│── opportunities/     
│── templates/          
│── static/              
│── media/               
│── nginx/        
│── Dockerfile          
│── docker-compose.yml  
│── requirements.txt
│── README.md
