# test_backend_omninext
Instructions:
$ git clone https://github.com/msabetta/test_backend_omninext
$ cd manageusers
$ pip3 install -r requirements.txt
$ serverless dynamodb start
$ serverless wsgi serve
- leave the first terminal opened with DynamoDB instance in running 
- Open another terminal and execute this command below:
$ serverless wsgi serve


references errors:
- https://stackoverflow.com/questions/67090756/serverless-command-wsgi-serve-not-found
