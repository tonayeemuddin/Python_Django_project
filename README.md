### Run Project in your PC

1. Install Python and pip

       sudo apt-get update && sudo apt-get -y upgrade

       sudo apt-get install python3

       sudo apt-get install -y python3-pip
2. Install Virtualenv

       pip3 install virtualenv

       virtualenv --version

3. Clone the Repository

       git clone <repository_url>

4. Setup Virtual Environment

       cd your_project_directory

       source venv_name/bin/activate

5. Install Django

       pip install django

6. Start the Django Server

       python manage.py runserver

The server should now be running locally on the other PC. Access it through a web browser by navigating to http://127.0.0.1:8000/
