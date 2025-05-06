# Python-boto3
To automate the provisioning of an EC2 instance on AWS using a simple Python script via the Boto3 library.

1. Install Boto3
Use pip to install the Boto3 library in your Python environment:

<code>pip install boto3</code></br>

2. Configure AWS Credentials
You need AWS credentials (Access Key ID and Secret Access Key) to authenticate your requests. Configure them using the AWS CLI:

<code>aws configure </code></br>
This command will prompt you to enter your AWS credentials and region. These settings are saved locally and used by Boto3 to make authenticated API calls.
