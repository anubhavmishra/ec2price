ec2price
===============
AWS EC2 Pricing Tool

# Installation
```sudo python setup.py install```

# Usage
```ec2price --region us-east-1```
```
Region: us-east-1
==============================================
Type	                 OS	Price (USD)
==============================================

m3.xlarge	         linux	0.450
m3.2xlarge	         linux	0.900
m1.small	         linux	0.060
m1.medium	         linux	0.120
.....
.....
```

```ec2price -h```
```
usage: ec2price [-h] [--region REGION [REGION ...]]

Tool for getting pricing for EC2 Instances.

optional arguments:
  -h, --help            show this help message and exit
  --region REGION [REGION ...]
                        AWS Region for the EC2 Instance. eg: us-east-1, us-
                        west-1.
```

```ec2price --help```
```
usage: ec2price [-h] [--region REGION [REGION ...]]

Tool for getting pricing for EC2 Instances.

optional arguments:
  -h, --help            show this help message and exit
  --region REGION [REGION ...]
                        AWS Region for the EC2 Instance. eg: us-east-1, us-
                        west-1.
```
```ec2price ```
```
Please specify a region!. eg: ec2-price.py --region REGION NAME
---------------------------------------------------------------------
Available Regions:
=====================================================================
us-east
us-west-2
us-west
eu-ireland
apac-sin
apac-tokyo
apac-syd
sa-east-1
```
