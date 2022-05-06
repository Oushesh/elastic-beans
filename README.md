"# elastic-beans" 

## Installation instructions
   * Follow the instructions from [click here](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html)

   * Elastic Beanstalk Flask
     * 1. Create a project directory
     	  		mkdir eb-flask
     	  		cd eb-flask

     * 2. Setup Virtual environment for Flask named virt
          Go to the folder of the project eb-flask
          		virtualenv virt
          		source virt/bin/activate
          		virt/bin/activate

          		On windows:
          		virt/Scripts/activate

      * 3. You will see (virt) prepended to your command prompt.
      * 4. Install Flask: pip install flask==2.0.3
      * 5. pip freeze will freeze the requirements 
      * 6. Then do pip freeze > requirements.txt to write the 
        dependencies for 

      * 7. Next, we create an application to be deployed on elastic beanstalk. 

