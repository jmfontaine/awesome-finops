# Awesome FinOps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome FinOps resources

**FinOps, also called Cloud Financial Management, is a set of principles, practices and tools to increase an organization's ability to understand cloud costs, make business tradeoffs, and ultimately get the most value out of their cloud spending.**

## Contents

- [Awesome FinOps ](#awesome-finops-)
  - [Contents](#contents)
  - [Communities](#communities)
  - [Education](#education)
    - [Articles](#articles)
  - [Blogs and Newsletters](#blogs-and-newsletters)
  - [Podcasts](#podcasts)
    - [Books](#books)
    - [Online Courses](#online-courses)
    - [Certifications](#certifications)
    - [KPIs](#kpis)
  - [Tools](#tools)
    - [Open Source Tools](#open-source-tools)
    - [Commercial Tools](#commercial-tools)
  - [Service providers](#service-providers)
    - [Consultancies](#consultancies)
    - [Freelancers](#freelancers)
  - [FinOps Jobs](#finops-jobs)
    - [Job Postings](#job-postings)
    - [Recruiters](#recruiters)
  - [Contribute](#contribute)
  - [License](#license)

## Communities

- [FinOps Foundation](https://www.finops.org/) - Its goal is to advance the discipline of FinOps and cloud financial management through best practices, education and standards. It is a member of [The Linux Foundation](https://www.linuxfoundation.org/).
- [LinkedIn - Cloud FinOps Practitioners](https://www.linkedin.com/groups/10538269/)
- [Reddit - r/FinOps](https://www.reddit.com/r/FinOps/)

## Education

### Articles

- [Understanding Data Transfer in AWS](https://www.lastweekinaws.com/blog/understanding-data-transfer-in-aws/) - Make sense of the complex world of data transfer cost in AWS.

## Blogs and Newsletters

- [Corey Quinn / Last Week In AWS](https://www.lastweekinaws.com/newsletter/)
- [Cristian Magherusan-Stanciu / LeanerCloud](https://leanercloud.beehiiv.com)
- [Jean Latiere / OptimNow](https://www.optimnow.io/en/blog)

## Podcasts

- [Corey Quinn / Screaming in the Cloud](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/) - interviews people in the cloud space.
- [Cristian Magherusan-Stanciu / LeanerCloud](https://podcasters.spotify.com/pod/show/leanercloud) - technical deep-dives on cloud optimization topics.
- [Jon Myer](https://jonmyer.com/) - FinOps insights, interviews with FinOps people and tooling vendors.

### Books

- [Cloud FinOps - J.R. Storment, Mike Fuller](https://www.oreilly.com/library/view/cloud-finops/9781492054610/) - Seminal book by founders of the FinOps Foundation.
- [Mastering AWS Cost Optimization - Eli Mansoor](https://www.amazon.de/-/en/Eli-Mansoor/dp/B087HDKMKH)

### Online Courses

- [edX - Introduction to FinOps](https://courses.edx.org/courses/course-v1:LinuxFoundationX+LFS175x+2T2020/course/) - Self-paced, 1-2 hour introduction.

### Certifications

- [FinOps Certified Practitioner](https://www.finops.org/certification/) - Two-day training course and certification by the FinOps Foundation.

### KPIs

- [finopsfoundation/kpis](finopsfoundation/kpis) - List of common KPIs by the FinOps Foundation.

## Tools

### Open Source Tools

- [AutoSpotting Community Edition](https://github.com/LeanerCloud/AutoSpotting) - Converts AWS Autoscaling groups to Spot instances with diversification, failover to on-demand instances and without the need for configuration changes. Tags: automated_optimization, AWS, ASG, Kubernetes, EKS, ECS, EC2_Spot
- [Cloud Custodian](https://cloudcustodian.io/) - Stateless rules engine for policy definition and enforcement, with metrics, structured outputs and detailed reporting for clouds infrastructure. Tags: cost_visibility, automated_optimization, multi_cloud
- [ec2instances.info](https://github.com/vantage-sh/ec2instances.info) - Information about cloud infrastructure, such as EC2 and RDS instance types. Tags: cost_visibility, AWS, EC2, RDS
- [EBS Optimizer Community Edition](https://github.com/LeanerCloud/EBS-Optimizer) - Automatically converts AWS EBS volumes to GP3, provisioning IOPs and throughout without the need for configuration changes. Tags: automated_optimization, EBS, storage
- [Karpenter](https://karpenter.sh) - Just-in-time capacity provisioner for Kubernetes. Tags: automated_optimization, Kubernetes, AWS, Spot
- [OptScale](https://github.com/hystax/optscale) - FinOps and cloud cost optimization platform combined with ML/AI developer tools to profile and instrument ML experiments and optimize their performance and cloud expenses. Tags: cost_visibility, multi_cloud, ML
- [Savings Estimator](https://github.com/LeanerCloud/savings-estimator) - Desktop GUI for estimating Spot savings, and easily creating AutoSpotting configuration. Tags: cost_visibility, Spot

### Commercial Tools

- [AutoSpotting](https://autospotting.io) - Enhanced version of AutoSpotting Community Edition (see OSS tools above), with improved reliability and performance. Tags: automated_optimization, AWS, ASG, Kubernetes, EKS, ECS
- [BlueArch](https://www.bluearch.io/) - Automated tagging and cost optimization recommendations. Tags: cost_visibility, recommendations
- [Cast.ai](https://cast.ai) - Automated cost optimization for Kubernetes. Tags: automated_optimization, multi_cloud, Kubernetes, EKS, EC2_Spot
- [Cloudability](https://www.cloudability.com/) Tags: cost_visibility, multi_cloud
- [CloudCheckr](https://www.cloudhealthtech.com/) Tags: cost_visibility, multi_cloud
- [CloudHealth](https://www.cloudhealthtech.com/) Tags: cost_visibility, multi_cloud
- [CloudThread](https://www.cloudhealthtech.com/) Tags: cost_visibility, multi_cloud
- [CloudZero](https://www.cloudzero.com/) Tags: cost_visibility, multi_cloud
- [Densify](https://www.densify.com/) Tags: cost_visibility automated_optimization, Kubernetes, EKS, ASG
- [EBS Optimizer](https://leanercloud.com/ebs-optimizer) - Enhanced version of EBS Optimizer Community Edition (see OSS tools above). Tags: automated_optimization, EBS, storage
- [Hystax](https://hystax.com/) - FinOps and MLOps open source platform (see OptScale in the OSS tools). Tags: cost_visibility, recommendations, ML, multi_cloud
- [InfraCost](https://www.infracost.io/) - Shows the cost of Terraform code changes. Tags: cost_visibility, Terraform, multi_cloud
- [KubeCost](https://kubecost.com) - Automated cost optimization for Kubernetes. Tags: cost_visibility, multi_cloud, Kubernetes, EKS, rightsizing_recommendations
- [MemVerge](https://memverge.com/) - Pptimizes cost and performance for data intensive workloads on public clouds. Tags: automated_optimization, Spot, rightsizing
- [nOps](https://nops.io) - Al-Powered AWS FinOps Automation Platform. Tags: automated_optimization, Spot, rightsizing, Kubernetes, RIs, scheduling, EBS, RDS.
- [ProsperOps](https://www.prosperops.com/) - Automates RI and savings plans purchasing. Tags: automated_optimization, AWS, RIs.
- [Pump](https://pump.co/) - Cost optimization through automated purchasing of RIs, Savings Plans and group buying. Tags: automated_optimization, AWS, RIs, savings_plans
- [ScaleOps](https://scaleops.com/) - Automated rightsizing for Kubernetes pods.  Tags: automated_optimization, multi_cloud, Kubernetes, rightsizing
- [Spot.io](https://spot.io) - Set of tools for cloud compute optimization. Tags: automated_optimization, multi_cloud, Spot, Kubernetes, RIs
- [Stacklet](https://stacklet.io/) - Enterprise version of Cloud Custodian (see OSS tools above). Tags: cost_visibility, automated_optimization, multi_cloud
- [Unusd](https://unusd.cloud/) - Detects unused cloud resources. Tags: cost_visibility, AWS
- [Usage.ai](https://usage.ai) - Automates RI purchasing. Tags: automated_optimization, RIs
- [Vantage](https://vantage.sh) - Multi-cloud cost visibility and automated RI purchasing. Tags: cost_visibility, automated_optimization, multi_cloud, RIs
- [Xosphere](https://xosphere.io) - Based on an early version of AutoSpotting Community Edition (see OSS tools above), enhanced with tighter integration to Kubernetes. Tags: automated_optimization, AWS, ASG, Kubernetes, EKS
- [Zesty](https://zesty.io) - Automates RI purchasing and EBS Storage optimization. Tags: automated_optimization, RIs, EBS, storage

## Service providers

### Consultancies

- [Duckbill Group](https://www.duckbillgroup.com/) - mostly focused on Enterprise customers, based in the US.
- [TechNative](https://technative.eu) - mostly focused on Enterprise customers, based in the Netherlands.

### Freelancers

- [Cristian Magherusan-Stanciu / LeanerCloud](https://leanercloud.com) - Cloud Optimization Consultant, building tools including AutoSpotting, EBS Optimizer and Savings Estimator, ex-AWS Specialist Solutions Architect for Spot and Graviton, based in Germany. Tags: technical, tooling, open-source, cloud_strategy
- [Eli Mansoor / OskaQ Consulting]([https://www.oskaq-consulting.com/]) - Consultant focused on helping companies sign EDP contracts, cloud strategy, FinOps book author, ex-AWS Specialist for Graviton, based in Israel. Tags: cloud_strategy, contracts
- [Erik Norman / Caligo](https://caligo.cloud/) - FinOps consultant, based in Italy. Tags: technical, cloud_strategy
- [Jean Latiere / OptimNow](https://www.optimnow.io/) - ex-AWS Specialist for Spot and Graviton, based in France. Tags: cloud_strategy, greenops
- [Shahar Raz](https://razts.com) - Tech strategy consultant focused on AWS cost optimization, based in Israel. Tags: cloud_strategy
- [Srinivas Devaki / OptiOwl](https://optiowl.cloud/) - Cloud Optimization Consultant, based in India. Tags: technical, cloud_strategy

## FinOps Jobs

### Job Postings

- [FinOps Foundation Job Board](https://www.finops.org/jobs/)

### Recruiters

- [Lewis Cowell / OpzTalent](https://opztalent.com/) - Talent Agency dedicated to Cloud FinOps/Cost Optimization.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

