# Build an Item Catalog Application
This is a project that builds an item catalog for udacity nano full stack web courses.

## Requirement
Please seup an environment with Python installed first.

## Setup
1. download or repo to your machine
2. with command windows, go to `/vagrant/` directory
3. key in `vagrant up` to set up vm
4. key in `vagrant shh` to connect
5. `cd /vagrant/catalog`
6. `python database_setup.py` to set up database which you should see `sportscategory.db` generated
7. `python lotsofitems.py` to generate some data
8. `python application.py` to run the website on your local
9. open browser and connect to `http://localhost:8000/`