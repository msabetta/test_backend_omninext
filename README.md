# test_backend_omninext
- Instructions: <br />
$ git clone https://github.com/msabetta/test_backend_omninext <br />
$ cd test_backend_omninext/manageusers <br />
$ pip3 install -r requirements.txt <br />
$ serverless dynamodb start <br />
- leave the first terminal opened with DynamoDB instance in running <br />
- Open another terminal and execute this command below: <br />
$ serverless wsgi serve <br />
<br />
<br />
references errors: <br />
- https://stackoverflow.com/questions/67090756/serverless-command-wsgi-serve-not-found <br />
<br />
other references:<br />
- https://github.com/aws-samples/aws-serverless-workshops <br />
- https://github.com/aws-samples/aws-dynamodb-examples/tree/master/DynamoDB-SDK-Examples/python <br />
- https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication <br />
- https://docs.github.com/en/repositories/working-with-files/managing-large-files/resolving-git-large-file-storage-upload-failures <br />
<br />
<br />

installation requirements by environment: <br />
$ sudo apt-get install python3-pip <br />
$ sudo apt-get install npm <br />
$ sudo npm install -g serverless <br />
$ sudo apt install openjdk-19-jre-headless <br />
$ sudo apt update <br />
$ sudo apt install software-properties-common <br />
$ sudo add-apt-repository ppa:deadsnakes/ppa <br />
$ sudo apt install python3.8 <br />
