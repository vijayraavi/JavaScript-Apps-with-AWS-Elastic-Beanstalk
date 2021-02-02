1. Change directory (`cd`) into the folder with your JavaScript app
2. Run the following command:
   `zip ../myapp.zip -r * .[^.]*`

Your code will now be zipped and ready to be deployed to Elastic Beanstalk (https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/applications-sourcebundle.html#using-features.deployment.source.commandline)

The reason why you must zip your code like this is because by default, Elastic Beanstalk looks for the app in a top-level directory