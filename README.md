# python (django) simple page for webuzo 

## Create the Application
Login to your webuzo control panel and go to __Add Applicaton__
*On this page please note the port number*
| Option | Description |
| --- | --- |
| Application Name | Your Application Name |
| Deployment Domain | Select Domain from dropdown |
| Base Application URL | If you want to add a directory, enter the directory name, Otherwise leave it blank |
| Application Path | add your application file location |
| Application type | python 3 |
| Application startup file | ```manage.py``` |
| Start Command | ```/usr/local/apps/python3/bin/python3 manage.py runserver``` |
| Stop Command | stop |

After fill the all filds perfectly click on __Create__

## Change the default port from manayge.py
Now go to the app directory from the File Manager and open the __manayge.py__ from a editor and replace the port number with 30011
```runserver.default_port = "30011"```

After complete it go to */myproject/* and open the *settings.py* from a editor.
In this file you need to allow your application domain.
Replace/Add *ALLOWED_HOSTS = []* with ```ALLOWED_HOSTS = ['127.0.0.1:30000','localhost','127.0.0.1','your_domain_name.com']```


