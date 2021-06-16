
git clone https://github.com/ruipinghe/Search_Ensembl.git
cd Search_Ensembl
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate --run-syncdb
python manage.py runserver

'''
git clone git@cseegit.essex.ac.uk:yw19282/methylation_database.git
cd methylation_database
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate --run-syncdb
python manage.py runserver
'''
