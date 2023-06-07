# aws-s3static-cloudfront
Demo project for Maolte Technical Solutions Limited using Azure DevOps, along with AWS S3 and AWS Cloudfront to develop and deploy a client side website built solely with HTML5 and CSS. IaC will be used to develop the CICD pipeline in Azure DevOps deploying to the demo account of Maolte Technical Solutions in AWS. 

The deployments will include CloudFormation templates coded up to provision a S3 bucket and then a CloudFront instance with an OAI policy securing the S3 bucket. I did not purchase a custom domain for this demo project, so did not code up AWS Certification Manager SSL cert for inclusion. Nor did I enact Route 53 domain registration (yet) as you would do in a commerical project that would be more extensive then this bare bones iteration of it.

The sample site around life balance and vacations is coded at a basic level using HTML5 and CSS3 only. There is no inclusion of social media specific tags in the head tag, nor Javascript deployed to implement the likes of a sticky header. These finer touches were left out due to this project having an IaC focus, and a not front end software development focus. The content however is custom written so can be accessed via the AWS owned url from the CloudFront distribution, until such time as I destory the instance given the nature, and scope of the project.

# Maolte Technical Solutions Limited 
This repo is the 3rd in a series of demo deployments for the company I set up to pursue contracting. My intent for these repos is to demo my CICD skills mainly in infrastructure deployments over time and in segments. The idea is to show case reusable infrastructure as code (IaC) for cloud resources via ARM templating in Azure and CloudFormation templating in AWS. I will time permitting code up some fun apps for demo purposes and demo infrastructure as I go. 

Maolte Technical Solutions Limited was set up provide specialist services in the Cloud Infrastructre, DevOps and Writing. More at https://maolte.ie. Any queries, drop me a long at john@maolte.ie.

Best Regards
John

Founder | Engineer | Writer
Maolte Technical Solutions Limited