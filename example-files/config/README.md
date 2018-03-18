

Done:
* CloudFront logging must be enabled

* EBS Volumes must be encrypted

* IamPolicyNotActionRule
* IamPolicyNotResourceRule
* IamPolicyWildcardActionRule
* IamPolicyWildcardResourceRule

TODO
* CloudFront resource !Metadata['AWS::CloudFront::Authentication'].nil?  How to specify in Terraform?
* ELB must access logging should be enabled

* IamManagedPolicyNotActionRule  - How is this different than a plain IamPolicy?
* IamManagedPolicyNotResourceRule
* IamManagedPolicyWildcardActionRule
* IamManagedPolicyWildcardResourceRule

* IamRoleNotActionOnPermissionsPolicyRule
* IamRoleNotActionOnTrustPolicyRule
* IamRoleNotPrincipalOnTrustPolicyRule
* IamRoleNotResourceOnPermissionsPolicyRule
* IamRoleWildcardActionOnPermissionsPolicyRule
* IamRoleWildcardActionOnTrustPolicyRule
* IamRoleWildcardResourceOnPermissionsPolicyRule

* LambdaPermissionInvokeFunctionActionRule
* LambdaPermissionWildcardPrincipalRule

* ManagedPolicyOnUserRule
* PolicyOnUserRule

* S3BucketPolicyNotActionRule
* S3BucketPolicyNotPrincipalRule
* S3BucketPolicyWildcardActionRule
* S3BucketPolicyWildcardPrincipalRule
* S3BucketPublicReadAclRule
* S3BucketPublicReadWriteAclRule

* SecurityGroupEgressOpenToWorldRule
* SecurityGroupEgressPortRangeRule
* SecurityGroupIngressCidrNon32Rule
* SecurityGroupIngressOpenToWorldRule
* SecurityGroupIngressPortRangeRule
* SecurityGroupMissingEgressRule

* SnsTopicPolicyNotActionRule
* SnsTopicPolicyNotPrincipalRule
* SnsTopicPolicyWildcardPrincipalRule

* SqsQueuePolicyNotActionRule
* SqsQueuePolicyNotPrincipalRule
* SqsQueuePolicyWildcardActionRule
* SqsQueuePolicyWildcardPrincipalRule

* UserHasInlinePolicyRule
* UserMissingGroupRule

* WafWebAclDefaultActionRule