# Python-boto3
To automate the provisioning of an EC2 instance on AWS using a simple Python script via the Boto3 library.

1. Install Boto3
Use pip to install the Boto3 library in your Python environment:

<centre><code>pip install boto3</code></centre></br>
![image](https://github.com/user-attachments/assets/691557fe-7595-41f9-8a80-a2cdd2177af4)

2. Configure AWS Credentials
You need AWS credentials (Access Key ID and Secret Access Key) to authenticate your requests. Configure them using the AWS CLI:
![image](https://github.com/user-attachments/assets/5c4ca971-5000-4981-831b-a7607448915f)

<centre><code>aws configure </code></centre></br>
![image](https://github.com/user-attachments/assets/e4506788-86a3-4478-9449-3e32dc5e9dd0)

This command will prompt you to enter your AWS credentials and region. These settings are saved locally and used by Boto3 to make authenticated API calls.
