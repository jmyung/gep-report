# gep-cnct-report

## GEP Intro
- Writer : Jesang Myung
- Term : 2018.6.10 ~ 9.1
- Office : Seattle CNCT

## JOB
- Participating in Workshop
  - term : 18.6.25 ~ 18.7.6
  - task : Interview with CMP team from Korea
  - result : Understood about epic and acceptance criteria
- Working on project in CMS (Cluster Manager Service)
  - Role : Cluster Provisioning on AWS
    - Discovery of AWS Provisioner using Cloudformation
    - Create resources (VPC, Subnet, EC2, master/worker tagging) stack on AWS
    - Bring up K8s Cluster on AWS resources using ssh-provisioner and make instruction
  - Task
    - CMS-212 : Discovery of AWS Provisioner using Cloudformation
      - result : investigated Provisioning K8s cluster services in AWS (Managed and 3rd Party services)
    - CMS-290 : Create some nodes that are pre-configured with public IP and SSH       
      - result : created Cloudformation template modified from Heptio's one
    - CMS-306 : Integrate Cloud formation template in cluster repo
      - result : modified template to work with Joe's template
    - CMS-304 : Create and deploy to minikube and test
      - result : Brought up a cluster to MaaS with SSH Provisioner
    - CMS-315 : Document (and CI?) how to standup pacific for the first time
      - result
        - found how to bring up cluster in AWS with Joe's script
        - modified Cloudformation in order to work well with SSH provisioner
        - wrote instuction on pacific repo

## Learn From CNCT
- Agile
  - experienced agile method in CNCT
    - standup
    - chatops with Slack
  - learn how to use Jira
    - 1) Create Epic
    - 2) Review with team to have understanding of requirement and acceptance criteria ... Assign engineer
    - 3) Create design doc
    - 4) Socialize with team
    - 5) Breakdown
  - documentation on Confluence : https://samsung-cnct.atlassian.net/wiki/spaces/AG/pages/233406484/Discovery+of+AWS+Provisioner+using+CloudFormation
- Git
  - learn how to contribute on report
  - PR (Pull Request) Process
    - 1. Fork the repo
    - 2. git clone your repo
    - 3. create a branch, add your changes
    - 4. push to your fork
    - 5. create a pull request in github from your fork to the samsung-cnct repo
