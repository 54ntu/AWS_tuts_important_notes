# AWS- Amazon Web Services
<h2>Important key points of AWS::::::</h2>
<ul>

<li>Lambda ::::function -- this is also used in serverless  </li>
<li>EC2--> Elastic compute cloud which provides secure,resizable compute capacity in the cloud.....  </li>
<li>S3 :: simple storage services</li>
<li>IAM is for permissions </li>
<li>Amazon simple Email service </li>
<li>Elasctic Container Service </li>
<li>API Gateway --->> it is actually used in serverless </li>

</ul>


# S3 services and its structure
<img src="amazonwebs3.png" alt="s3 structure"/>
<p>one amazon account has 100 bucket limit with unlimited storage inside it</p>
<p>one bucket is used to store the data of one project</p>



# presigned url

<p>when we declare the bucket as a private one..then when we add any images or file then it can not be accessed publicly.....we can access through the help of presigned url.....</p>




# AWS tutorial

# AWS  --- "IAM"

There is two user for the AWS account console. ROOT user is used by the admin of the account to login into the account.

IAM user account is used by the other sub users created by the root user with different roles and permissions.


NOTE: To perform critical works like deployment we must use IAM user account. ROOT account must be used for handling the account.


We can add permissions to the particular directly but there is limitation for that. Only 10 permissions can be add directly. Therefore it is recommended to use groups options so that we can give multiple permissions and later on we can add user on that group.


