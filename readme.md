# EC2 Homework

## Setup
1. Go to AWS EC2 and launch a new instance.
2. Pick Amazon Linux 2023 and t3.micro.
3. Allow HTTP (80) and SSH (22) in security settings.
4. In Advanced details → User data, paste the script from `start up script.txt`.
5. Launch the instance.
6. Copy the Public DNS and open it in the browser.

## Teardown
1. Go to EC2 console.
2. Select the instance.
3. Click Stop if you want to pause it.
4. Click Terminate if you are done with it.
5. Delete the security group and key pair if you don’t need them anymore.


