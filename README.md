# Awesome FinOps

> A curated list of awesome FinOps resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**FinOps, also called Cloud Financial Management, is a set of principles, practices and tools to increase an organization's ability to understand cloud costs, make business tradeoffs, and ultimately get the most value out of their cloud spending.**

## Contents

- [Awesome FinOps](#awesome-finops)
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

### Blogs and Newsletters

- [Corey Quinn / Last Week In AWS](https://www.lastweekinaws.com/newsletter/)
- [Cristian Magherusan-Stanciu / LeanerCloud](https://leanercloud.beehiiv.com)
- [Jean Latiere / OptimNow](https://www.optimnow.io/en/blog)
- [Bastien Martins Da Torre / Cloud FinOps](https://cloud-finops.io/FinOpsTools.html)

### Podcasts

- [Corey Quinn / Screaming in the Cloud](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/) - interviews people in the cloud space.
- [Cristian Magherusan-Stanciu / LeanerCloud](https://podcasters.spotify.com/pod/show/leanercloud) - technical deep-dives on cloud optimization topics.
- [Jon Myer](https://jonmyer.com/) - FinOps insights, interviews with FinOps people and tooling vendors.
- [Keys to AWS Optimization Podcast](https://podcasters.spotify.com/pod/show/keys-to-aws-optimization) - Podcast from the AWS Twitch Channel with SME's on cost optimization.
- [Keys to AWS Optimization Youtube](https://www.youtube.com/c/thekeystoawsoptimization) - Videos from the AWS Twitch Channel with SME's on cost optimization.

### Books

- [Cloud FinOps - J.R. Storment, Mike Fuller](https://www.oreilly.com/library/view/cloud-finops/9781492054610/) - Seminal book by founders of the FinOps Foundation.
- [Mastering AWS Cost Optimization - Eli Mansoor](https://www.amazon.de/-/en/Eli-Mansoor/dp/B087HDKMKH) - Book focused on cost optimization techniques for AWS.

### Online Courses

- [edX - Introduction to FinOps](https://courses.edx.org/courses/course-v1:LinuxFoundationX+LFS175x+2T2020/course/) - Self-paced, 1-2 hour introduction.
- [Well Architected Cost Labs](https://wellarchitectedlabs.com/cost/) - The Cost Optimization section of the Well-Architected Labs.

### Certifications

- [FinOps Certified Practitioner](https://www.finops.org/certification/) - Two-day training course and certification by the FinOps Foundation.

### KPIs

- [finopsfoundation/kpis](finopsfoundation/kpis) - List of common KPIs by the FinOps Foundation.

## Tools

### Open Source Tools

- [AutoSpotting Community Edition](https://github.com/LeanerCloud/AutoSpotting) - Converts ASGs to Spot with automated failover to on-demand and no configuration changes. Tags: automated_optimization, AWS, ASG, Kubernetes, EKS, ECS, Spot
- [Cloud Custodian](https://cloudcustodian.io/) - Stateless rules engine for cloud policy definition and enforcement. Tags: cost_visibility, automated_optimization, multi_cloud
- [ec2instances.info](https://github.com/vantage-sh/ec2instances.info) - Information about AWS infrastructure, like EC2 and RDS instance types. Tags: cost_visibility, AWS, EC2, RDS
- [EBS Optimizer Community Edition](https://github.com/LeanerCloud/EBS-Optimizer) - Converts AWS EBS volumes to GP3 without configuration changes. Tags: automated_optimization, AWS, EBS
- [InfraCost](https://github.com/infracost/infracost) - Displays cost of Terraform code changes. Tags: cost_visibility, Terraform
- [Karpenter](https://karpenter.sh) - Just-in-time capacity provisioner for Kubernetes. Tags: automated_optimization, Kubernetes, AWS, Spot, EKS
- [OptScale](https://github.com/hystax/optscale) - FinOps and cloud cost optimization with ML/AI developer tools. Tags: cost_visibility, multi_cloud, ML
- [Savings Estimator](https://github.com/LeanerCloud/savings-estimator) - GUI for estimating Spot savings in ASGs. Tags: cost_visibility, AWS, Spot

### Commercial Tools

- [AutoSpotting](https://autospotting.io) - Commercial version of AutoSpotting Community Edition with some enhancements. Tags: automated_optimization, AWS, ASG, Kubernetes, EKS, ECS
- [BlueArch](https://www.bluearch.io/) - Automated tagging and cost optimization recommendations. Tags: cost_visibility, recommendations
- [Cast.ai](https://cast.ai) - Automated cost optimization for Kubernetes. Tags: automated_optimization, multi_cloud, Kubernetes, EKS, Spot
- [Cloudability](https://www.cloudability.com/) - Cloud cost management and visibility. Tags: cost_visibility, multi_cloud
- [CloudCheckr](https://www.cloudcheckr.com/) - Cloud management platform for cost, security, and compliance. Tags: cost_visibility, multi_cloud
- [CloudHealth](https://cloudhealth.vmware.com/) - Cloud cost visibility and automated optimizations. Tags: cost_visibility, multi_cloud
- [CloudPouch](https://cloudpouch.dev/) - A unique desktop application that works with any AWS account, uses AWS CLI proviles. Cloud cost visibility and optimizations. Tags: cost_visibility, automated_optimization, AWS, EBS
- [CloudThread](https://www.cloudthread.io/) - Cloud cost tracking and waste identification, part of FinOut since April 2nd 2024 ([announcement](https://www.finout.io/blog/cloudthread_finout)). Tags: cost_visibility, multi_cloud 
- [CloudZero](https://www.cloudzero.com/) - Cloud cost intelligence platform. Tags: cost_visibility, multi_cloud
- [DigiUsher](https://www.digiusher.com/) - Cloud cost visibility platform. Tags: cost_visibility, multi_cloud, Kubernetes, EKS, AWS, GCP, Azure
- [Densify](https://www.densify.com/) - Automated rightsizing for Kubernetes and Compute Instances. Tags: cost_visibility, automated_optimization, Kubernetes, EKS, EC2
- [EBS Optimizer](https://leanercloud.com/ebs-optimizer) - Commercial version of EBS Optimizer Community Edition. Tags: automated_optimization, AWS, EBS
- [Finout](https://www.finout.io/) - FinOps all-in-one solution. Tags: Virtual Tagging, costs optimization, comprehensive cost governance suite, AWS, GCP, Azure, Kubernetes, AI/ML
- [Hystax](https://hystax.com/) - FinOps and MLOps platform. Tags: cost_visibility, recommendations, ML, multi_cloud
- [InfraCost](https://www.infracost.io/) - Commercial version of Infracost. Tags: cost_visibility, Terraform, multi_cloud
- [KubeCost](https://kubecost.com) - Rightsizing recommendations for Kubernetes. Tags: cost_visibility, multi_cloud, Kubernetes, EKS, rightsizing
- [MemVerge](https://memverge.com/) - Optimizes cost and performance for data-intensive workloads. Tags: automated_optimization, Spot, rightsizing
- [nOps](https://nops.io) - Comprehensive AWS FinOps platform. Tags: automated_optimization, AWS, Spot, Kubernetes, EBS, RDS, RIs
- [Pepperdata](https://www.pepperdata.com/) - Real-time, automated cost optimization for Amazon EMR and Amazon EKS. Tags: automated_optimization, EKS, EMR, Kubernetes, multi_cloud
- [ProsperOps](https://www.prosperops.com/) - Automates RI and savings plans purchasing. Tags: automated_optimization, AWS, RIs
- [Pump](https://pump.co/) - Cost optimization through group buying, AI and automated RI purchasing. Tags: automated_optimization, AWS, RIs, AI/ML
- [ScaleOps](https://scaleops.com/) - Automated rightsizing for Kubernetes pods. Tags: automated_optimization, multi_cloud, Kubernetes, rightsizing
- [Spot.io](https://spot.io) -  Visibility, infrastructure automation and optimization for Spot and RIs. Tags: automated_optimization, multi_cloud, Spot, Kubernetes, RIs
- [Stacklet](https://stacklet.io/) - Enterprise version of Cloud Custodian. Tags: cost_visibility, automated_optimization, multi_cloud
- [Unusd](https://unusd.cloud/) - Detects unused cloud resources. Tags: cost_visibility, AWS
- [Usage.ai](https://usage.ai) - Automates RI purchasing. Tags: automated_optimization, RIs
- [Vantage](https://vantage.sh) - Multi-cloud cost visibility with automated RI purchasing. Tags: cost_visibility, automated_optimization, RIs, multi_cloud
- [Xosphere](https://xosphere.io) - Commercial version of AutoSpotting Community Edition with some enhancements. Tags: automated_optimization, AWS, ASG, Kubernetes, EKS
- [Zesty](https://zesty.io) - Automates RI purchasing and EBS optimization. Tags: automated_optimization, AWS, RIs, EBS

## Service providers

### Consultancies

- [Duckbill Group](https://www.duckbillgroup.com/) - mostly focused on Enterprise customers, based in the US.
- [TechNative](https://technative.eu) - mostly focused on Enterprise customers, based in the Netherlands.

### Freelancers

- [Cristian Magherusan-Stanciu / LeanerCloud](https://leanercloud.com) - Cloud Optimization Consultant, building OSS and commercial tools like AutoSpotting, EBS Optimizer and Savings Estimator, ex-AWS Specialist Solutions Architect for Spot and Graviton, based in Germany. Tags: technical, tooling, open_source, cloud_strategy
- [Eli Mansoor / OskaQ Consulting](https://www.oskaq-consulting.com/) - Consultant focused on helping companies and public sector organizations define cloud strategy and negotiate EDP contracts, FinOps book author, ex-AWS Specialist for Graviton, based in Israel. Tags: cloud_strategy, contracts, public_sector
- [Bastien Martins Da Torre / Cloud FinOps](https://cloud-finops.io)- Pragmatic FinOps consultant, ex-ServiceNow, based in France. Tags: finops_tooling, cloud_strategy, finops 
- [Erik Norman / Caligo](https://caligo.cloud/) - FinOps consultant, based in Italy. Tags: technical, cloud_strategy
- [Jean Latiere / OptimNow](https://www.optimnow.io/) -  FinOps consultant focused on Green Computing, ex-AWS Specialist for Spot and Graviton, based in France. Tags: cloud_strategy, greenops
- [Shahar Raz](https://razts.com) - Tech strategy consultant focused on AWS cost optimization, based in Israel. Tags: cloud_strategy
- [Srinivas Devaki / OptiOwl](https://optiowl.cloud/) - Technical Cloud Optimization Consultant, based in India. Tags: technical, cloud_strategy

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
