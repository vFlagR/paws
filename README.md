Paws
====
Keyboard shortcuts for the AWS Console

Credit
-------
This script was originally created by @tombenner. All credit goes to him. This fork is intended to clean up the readme and add new shortcuts.

Overview
--------

Paws adds Vim-like keyboard shortcuts to the AWS Management Console.

<img src="https://raw.github.com/tombenner/paws/master/example.gif" />

Installation
------------

Paws can be used by installing [paws.user.js](https://raw.github.com/vflagr/paws/master/paws.user.js) in [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en) (Chrome) or [Greasemonkey](https://addons.mozilla.org/en-us/firefox/addon/greasemonkey/) (Firefox).

Shortcuts
---------

### Services

Open the default view of a service.

<table>
  <tr><td>Home</td><td>home</td></tr>
  <tr><td>CloudTrail</td><td>ct</td></tr>
  <tr><td>EC2</td><td>ec2</td></tr>
  <tr><td>ElastiCache</td><td>sec</td></tr>
  <tr><td>IAM</td><td>iam</td></tr>
  <tr><td>Redshift</td><td>red</td></tr>
  <tr><td>RDS</td><td>rds</td></tr>
  <tr><td>Route 53</td><td>r53</td></tr>
  <tr><td>S3</td><td>s3</td></tr>
  <tr><td>VPC</td><td>vpc</td></tr>
  <tr><td>Lambda</td><td>da</td></tr>
  <tr><td>Cloudformation</td><td>cfn</td></tr>
  <tr><td>Cloudfront</td><td>cdn</td></tr>
  <tr><td>ECS</td><td>ecs</td></tr>
  <tr><td>ECR</td><td>ecr</td></tr>
  <tr><td>API Gateway</td><td>api</td></tr>
  <tr><td>ACM</td><td>acm</td></tr>
  <tr><td>CloudWatch</td><td>cw</td></tr>
  <tr><td>SNS</td><td>sns</td></tr>
  <tr><td>SQS</td><td>sqs</td></tr>

</table>

### Pages

Open a specific page within a service.

<table>
  <tr><td>AMIs</td><td>img</td></tr>
  <tr><td>EBS</td><td>vol</td></tr>
  <tr><td>ELBs</td><td>elb</td></tr>
  <tr><td>Security Groups</td><td>scg</td></tr>
</table>

### Sidebar navigation

Use the left sidebar navigation menu.

<table>
  <tr><td>Select next nav link</td><td>j</td></tr>
  <tr><td>Select previous nav link</td><td>k</td></tr>
  <tr><td>Click on selected nav link</td><td>return</td></tr>
</table>

### Miscellaneous

<table>
  <tr><td>Show shortcuts</td><td>?</td></tr>
  <tr><td>Focus search box</td><td>/</td></tr>
  <tr><td>Open services menu</td><td>z</td></tr>
</table>

License
-------

Paws is released under the MIT License. Please see the MIT-LICENSE file for details.
