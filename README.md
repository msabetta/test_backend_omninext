# test_backend_omninext
Instructions: <br />
$ git clone https://github.com/msabetta/test_backend_omninext <br />
$ cd manageusers <br />
$ pip3 install -r requirements.txt <br />
$ serverless dynamodb start <br />
$ serverless wsgi serve <br />
- leave the first terminal opened with DynamoDB instance in running <br />
- Open another terminal and execute this command below: <br />
$ serverless wsgi serve <br />
<br />
<br />
references errors: <br />
- https://stackoverflow.com/questions/67090756/serverless-command-wsgi-serve-not-found <br />
