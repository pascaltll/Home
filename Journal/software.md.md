**

1.  Language: any
    
2.  It should be a web service: use Flask etc
    
3.  There are no requirements for the database. 
    
4.  Restrictions on the size of the source code >= 100 lines
    
5.  It will be a plus:
	1.  Ease of deployment (ideally, the entire deployment using kubectl apply-f <YOUR_FILE>).
    
	1.  The presence of Ingress.
    
	1.  Availability of permanent disk storage.
    
	1.  The presence of autoscaling settings.
    
	1.  Availability of a publicly available version (Internet access to the deployed application) 
    

6.  For development, you can use:
    

	1.  A cluster on a Google or Yandex public cloud (when registering using an @edu account, a quota is given sufficient to perform the HW).
    
	1.  Mini cube, Micro cube, or Kubernetes from Docker for Mac (Windows).
    



**
**

# Homework submission

Commit to the git repository the following data:

1.  The source code
    
2.  A set of Kubernetes yaml configs and related codes and Docker files.
    
3.  Description of the test request and the result of this request (input and output files or screenshots).
    
4.  Instructions for launching the service in your environment.
    

**
# tutorials
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world