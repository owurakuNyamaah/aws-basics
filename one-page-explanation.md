# How EC2 + S3 Work Together

    User
     │
   Internet
     │
   EC2 (Apache)
     │
     └── Fetches static files
          from S3 bucket


## Explanation

EC2 is a virtual server that runs application logic. S3 stores static assets such as HTML, CSS, and images. The EC2 server fetches content from S3 to serve users, while IAM ensures secure access and the VPC isolates network traffic. This separation of compute and storage allows scalable, secure, and cost-efficient applications.  

In real-world DevOps setups, this design improves reliability, simplifies scaling, and reduces costs by offloading static content to S3 while dynamic processes run on EC2.
