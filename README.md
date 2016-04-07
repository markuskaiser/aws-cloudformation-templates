# Template Collection for AWS CloudFormation

This repo contains my templates for AWS CloudFormation. 

## Table of Content
* AutoScalingWebServerWithLoadBalancerAndGithubPull.template
* AutoScalingWebServerWithLoadBalancerAndCodeDeploy.template

### AutoScalingWebServerWithLoadBalancerAndGithubPull
* based on: AWS Samples template AutoScalingMultiAZWithNotifications.template
* adapted to Ubuntu 14.04 
* downloads website content from Github using the credentials provided by the user

### AutoScalingWebServerWithLoadBalancerAndCodeDeploy
* based on: AutoScalingWebServerWithLoadBalancerAndGithubPull
* installs codedeploy agent which enables you to deploy new software releases via AWS CodeDeploy
* removed Github stuff
