This Project
#####

This project is focused on AWS services to deploy a static website using Azure DevOps. Its IaC focus makes it a DevOps project developing a static website in HTML5/CSS3 only, which will act as an app payload. The CloudFormation template is customised for this project to firstly provision an s3 bucket, and then an AWS CLoudFront instance. Once done, the S3 bucket is bound via OAI policy to the CloudFront instance completing the templates automated provisioning of service infrastructure. The 2nd stage of the pipeline will deploy the app payload to the s3 bucket for rendering onto the cloudfront distribution. No custom domain was included in this project nor associated securing of its routing via TLS encryption over SSL.

Maolte Technical Solutions Limited
#####

This repo is the 3rd in a series of demo deployments for the company I set up to pursue contracting. My intent for these repos is to demo my CICD skills mainly in infrastructure deployments over time and in segments. The idea is to show case reusable infrastructure as code (IaC) for cloud resources via Azure Devops and CloudFormation templating in AWS. I will time permitting code up some fun apps for demo purposes and demo infrastructure as I go.

Maolte Technical Solutions Limited was set up provide specialist services in the Cloud Infrastructre, DevOps and Writing. More at https://maolte.ie. Any queries, drop me a long at john@maolte.ie.

Best Regards 
John

Founder | Engineer | Writer 
Maolte Technical Solutions Limited