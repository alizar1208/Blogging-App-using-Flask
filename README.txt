Steps: 

Required dependencies and platforms to run the web app

1. Install Visual studio
Windows: 
	https://code.visualstudio.com/Download
Mac: 
	https://go.microsoft.com/fwlink/?LinkID=620882

2. Create a virtual environment and activate it
Windows:
        Create:py -3 -m venv .ven1(name of environment)  
        Activate: .\ven1(name of environment)\Scripts\activate
Mac:
        Create: python3 -m venv env
 	Activate: source env/bin/activate

3. Install Flask:
       			pip install flask

4. Install SQLAlchemy:
			pip install flask-sqlalchemyconda

##############################################################################################################################################################################################################################################################################################################################################

Freeze and get the requirement.txt(containing all the required libraries and packages that needs to be installed) for your project
	pip freeze > requirements.txt

#######################################################################################################################################################################

If you have reuirements.txt, you can download all the libraries and packages all at once using the command shown below:
	$ pip install -r requirements.txt

#######################################################################################################################################################################