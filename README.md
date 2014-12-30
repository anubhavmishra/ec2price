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

```ec2price --region us-east-1 --type m3.xlarge```
```

```
Region: us-east-1
======================================================
Type	                 OS	  Price (USD/hour)
======================================================

m3.xlarge	         linux	  0.280

```

```ec2price --region us-east-1 --type m1.large --old```
```

```
Region: us-east-1
======================================================
Type	                 OS	  Price (USD/hour)
======================================================

m1.large	         linux	  0.175

```

```ec2price -h```
```
usage: ec2pr.py [-h] [--region REGION] [--type TYPE] [--old]

Tool for getting pricing for EC2 Instances.

optional arguments:
  -h, --help       show this help message and exit
  --region REGION  AWS Region for the EC2 Instance. eg: us-east-1, us-west-1.
  --type TYPE      The type of EC2 Instance. eg: m3.medium, m2.2xlarge.
  --old            Specify '--old' for previous generation instances price
                   search.
```

```ec2price --help```
```
usage: ec2pr.py [-h] [--region REGION] [--type TYPE] [--old]

Tool for getting pricing for EC2 Instances.

optional arguments:
  -h, --help       show this help message and exit
  --region REGION  AWS Region for the EC2 Instance. eg: us-east-1, us-west-1.
  --type TYPE      The type of EC2 Instance. eg: m3.medium, m2.2xlarge.
  --old            Specify '--old' for previous generation instances price
                   search.
```
```ec2price ```
```
Please specify a region!. eg: ec2-price.py --region REGION NAME
---------------------------------------------------------------------
Available Regions:
=====================================================================
us-east-1
us-west-2
us-west-1
eu-west-1
eu-central-1
ap-southeast-1
ap-northeast-1
ap-southeast-2
sa-east-1
us-gov-west-1

```
