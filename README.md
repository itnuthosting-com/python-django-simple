# python (django) simple page for webuzo 

## Create the Application
Login to your webuzo control panel and go to __Add Applicaton__ set __Application Name__, __Deployment Domain__, __Base Application URL__, __Application Path__, __Application type:__ *Python 3*

| Option | Description |
| --- | --- |
| Application Name | Your Application Name |
| Deployment Domain | Select Domain from dropdown |
| Base Application URL | If you want to add a directory, enter the directory name, Otherwise leave it blank |
| Application Path | add your application file location |
| Application type | python 3 |
| Application startup file | manage.py |
| Start Command | /usr/local/apps/python3/bin/python3 manage.py runserver |
| Stop Command | stop |

## Change the default port from manayge.py
```runserver.default_port = "30011"```

*Replace __30011__ with your application port*

