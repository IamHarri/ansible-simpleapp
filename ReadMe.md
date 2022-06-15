# Describe
- I apply roles in ansible, I try to seperate all the module into folder roles
- Roles included: python, mysql_db, flask_app, alb, alb_target, mail
- the tructure that I have applied to deploy the app is cloud, specifially, I apply two EC2 as a server, that is controlled by local node
- I also applied alb and target group on AWS through module elb_target_group and elb_application_lb
- I applied ansible vault to encrypt all the credential for the app included: aws credential, gmail account...
- when ever control node finish apply, it automatically sends an email to register account, I choose to use mail module
 