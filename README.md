# RequireTracker
Project for Require Management

How to setup the server
1. Navigate to the ProjMgmt directory
	open the ProjMgmt directory in a command prompt
2. Run the migrations to create the database
	py manage.py migrate
3. Create a super user
	py manage.py createsuperuser
4. If you modify the model files. Please do the following command before step 2.
	py manage.py makemigrations
	