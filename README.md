# LinuxConfiguration
LinuxServerSetup

For this project, I set up an Amazon Lightsail Ubuntu Server at the following IP Address:
34.204.80.56
SSH Port:
2200

The grader may log in with the username 'grader' using the key provided in the "Notes to Reviewer" field.

I have configured this environment to serve my Product Catalog Project from an earlier Udacity Project. Following is the URL:
http://34.204.80.56/main

I configured the server's firewall to allow only outgoing connections and inbound connections on ports 80(www), 123(ntp), and 2200(SSH).
I created the user 'grader' and gave it sudo access. 
I created a postgresql database which serves data to the application.
I setup a wsgi application to serve the project located at /var/www/ProductCatalog/ProductCatalog.wsgi


Below is a list of the installed site packages on the virtual environment (venv) located at /var/www/ProductCatalog/ProductCatalog/venv:

appdirs-1.4.3.dist-info  Flask_SQLAlchemy-2.2.dist-info  markupsafe                    pyasn1                          rsa-3.4.2.dist-info              Werkzeug-0.12.1.dist-info
appdirs.py               flask_wtf                       MarkupSafe-1.0.dist-info      pyasn1-0.2.3.dist-info          setuptools                       wheel
appdirs.pyc              Flask_WTF-0.14.2.dist-info      oauth2client                  pyasn1_modules                  setuptools-34.3.3.dist-info      wheel-0.29.0.dist-info
click                    httplib2                        oauth2client-4.0.0.dist-info  pyasn1_modules-0.0.8.dist-info  six-1.10.0.dist-info             wtforms
click-6.7.dist-info      httplib2-0.10.3-py2.7.egg-info  packaging                     pyparsing-2.2.0.dist-info       six.py                           WTForms-2.1-py2.7.egg-info
easy_install.py          itsdangerous-0.24.dist-info     packaging-16.8.dist-info      pyparsing.py                    six.pyc
easy_install.pyc         itsdangerous.py                 pip                           pyparsing.pyc                   sqlalchemy
flask                    itsdangerous.pyc                pip-9.0.1.dist-info           requests                        SQLAlchemy-1.1.7-py2.7.egg-info
Flask-0.12.1.dist-info   jinja2                          pkg_resources                 requests-2.13.0.dist-info       tests
flask_sqlalchemy         Jinja2-2.9.5.dist-info          psycopg2                      rsa                             werkzeug







