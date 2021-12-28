## Test app for s3, sqs, sns, lambda.

### How to install
- download repo
- install node with npm
- install serverless `npm install -g serverless`
- in dir "file-handler-python" assing new values for variables in .env file (just rename buckets)
- in dir "file-handler-python" run command `sls deploy`
- in dir "sqs-handler-python" run command `pip install -r requirements.txt  -t .`
- in dir "sqs-handler-python" run command `sls deploy`
- confirm subscription for subscribers

| email  | password |
|:-------------:|:-------------:|
| aws-condition1@rambler.ru      | Aws-condition1     |
| aws-condition2@rambler.ru      | Aws-condition1      |

- to enable Server access logging - enable its in `console-properties-Server access logging`

### How to use
- load in "SOURCE_BUCKET" some files with keys: /input/{file-name}.txt(csv)
- check emails