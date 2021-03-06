# Step 3: Enable AWS Config<a name="enable-config"></a>

Enable AWS Config for each member account in your AWS organization\. For more information, see [Getting Started with AWS Config](https://docs.aws.amazon.com/config/latest/developerguide/getting-started.html)\.

You must enable AWS Config for each AWS Region that contains the resources that you want to protect\. You can enable AWS Config manually, or you can use the AWS CloudFormation template "Enable AWS Config" at [AWS CloudFormation StackSets Sample Templates](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/stacksets-sampletemplates.html)\.

You must, at a minimum, specify the following resource types that you want to protect with AWS Firewall Manager: Application Load Balancers, CloudFront distributions, or both\.

You can now configure AWS Firewall Manager to begin protecting your resources\. For more information, see [Getting Started with AWS Firewall Manager](getting-started-fms.md) \.