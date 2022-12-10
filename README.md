# test_backend_omninext <br />
# Instructions: <br />
$ git clone https://github.com/msabetta/test_backend_omninext <br />
$ cd test_backend_omninext/manageusers <br />
# Windows requirements <br />
$ pip3 install -r requirements.txt <br />
# Oracle Linux 8 requirements <br />
$ pip3 install -r requirements_linux.txt <br />
$ serverless dynamodb start <br />
- leave the first terminal opened with DynamoDB instance in running <br />
- Open another terminal and execute this command below: <br />
$ serverless wsgi serve <br />
<br />
references errors: <br />
- https://stackoverflow.com/questions/67090756/serverless-command-wsgi-serve-not-found <br />
<br />
other references: <br />
- https://github.com/aws-samples/aws-serverless-workshops <br />
- https://github.com/aws-samples/aws-dynamodb-examples/tree/master/DynamoDB-SDK-Examples/python <br />
- https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication <br />
- https://docs.github.com/en/repositories/working-with-files/managing-large-files/resolving-git-large-file-storage-upload-failures <br />
<br />
# setup python3.6 lib64 packages <br />
$ cd test_backend_omninext/manageusers/venv/lib64 <br />
$ sudo cp -r python3.6/ /usr/local/lib64/ <br />
<br />
# How to install serverless environment (Oracle Linux 8) <br />
$ sudo yum install npm <br />
$ sudo npm install -g serverless <br />
<br />
# update node.js <br />
$ sudo npm install -g n <br />
$ sudo npm install n -g <br />
<br />
