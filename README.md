# IAM policies for configuration of read-only AWS user
When attached to an AWS user, the four policies provide read-only access to resources in the AWS account. 

How to configure a read-only AWS user:
1. In the AWS console, create four new IAM policies using the content of the provided four JSON files
2. Create a new AWS user, for example, "cloudxray_read_only"
3. Attach the four previously confiured IAM policies to the new AWS user
4. For the user, create API access credentials. The access key ID and secret access key can be used to configure a new AWS integration in your CloudXray account.

