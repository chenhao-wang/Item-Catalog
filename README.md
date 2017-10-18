# Item Catalog

## Prepare:
- Installing the Vagrant VM
- Git
- VirtualBox
- Vagrant
- python

## To run:
- install virtualBox and vagrant
- in vagrant file run 'vagrant up' to start and 'vagrant ssh' to connect to it
- git clone this project
- run 'python database_setup.py' to initialize database
- run 'python lotsofmenus.py' to populate initial fake data
- run 'python project.py' to run web app
- open web browser and go to 'http://localhost:5000/'

## API endpoint format
- http://localhost:5000/restaurant/JSON
- http://localhost:5000/restaurant/<int:restaurant_id>/menu/JSON
- http://localhost:5000/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON
