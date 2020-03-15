<h2>Project Introduction</h2>

As your final project, you'll be faced with a real scenario.

Creating this project will give you the hands-on experience you need to confidently talk about infrastructure as code. So, for that reason, we have chosen a realistic scenario where you deploy an application (Apache Web Server) and you also pick up code (JavaScript and HTML) from S3 Storage and deploy it in the appropriate folder on the web server.

There will be two parts to this project:

You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation script.
The second part is to interpret the instructions as well as your own diagram and create a matching CloudFormation script.

<h2>Problem</h2>
Your company is creating an Instagram clone called Udagram. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket.

You have been tasked with deploying the application, along with the necessary supporting software into its matching infrastructure.

This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

<h2>Run Scripts</h2>
<p>Before running the scripts, you have to create IAM role first, role name is <b>UdacityS3ReadOnlyEC2</b>
</p>
> sudo ./create.sh udacity-project2-network  network.yml network-parameters.json
</br>
> sudo ./create.sh udacity-project2-servers servers.yml servers-parameters.json

<h2>URL</h2>
Load Balancer URL: <a target="_blank" href='http://proj2-webap-y4sv7cfl0fq1-1956458692.us-west-2.elb.amazonaws.com/'>http://proj2-webap-y4sv7cfl0fq1-1956458692.us-west-2.elb.amazonaws.com/</a>