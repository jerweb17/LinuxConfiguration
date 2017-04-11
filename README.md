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










