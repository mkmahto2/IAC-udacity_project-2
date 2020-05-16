---
# Udacity DevOps Nanodegree Project2

# Udagram
This is my solution for the Deploy a high-availability web app using using Cloudformation project for the Udacity Devops Nanodegree course.

#### WEBSITE LINK-http://iac-s-webap-uixlea2cwoxq-965090477.us-west-2.elb.amazonaws.com/
# Basic usage
This project uses a cloudformation script to launch autoscaling EC2 instances. Running the script will create two stacks named IAC-Network and IAC-Servers, starting with the network stack.

To get started run: ./create-stack-IAC

To delete stacks first run: ./delete IAC-Servers. Once complete you can delete the network stack with ./delete IAC-Network.
