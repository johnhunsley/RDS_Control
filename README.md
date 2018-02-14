# RDS Control
enables an RDS db to be started or stopped using a json command -

{"instances":["INSTANCE_NAME"],"action":"command"}

where the command is either 'stop'' or 'start'

This is designed to be run as a Lambda function to ensure that RDS stopped instances dont get turned on by AWS and cost you money!