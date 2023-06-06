## Lab Environment Setup
* Ensure you have an AWS account with the necessary permissions to create and manage CodeBuild resources.
* Create an IAM role for CodeBuild with the required permissions.
   * Open the IAM service in the AWS Management Console.
   * Navigate to "Roles" and click "Create role".
   * Give it a permission "AWSCodeBuildAdminAccess" role
   * Select the CodeBuild use case and proceed with the role creation wizard.
* Set up the necessary IAM policies for the CodeBuild IAM role.
    * Attach the policy for the "AWSCodeBuildAdminAccess" permission to the role
    * Add a Tag with the key as "Tool" and Values as "BuildCode" to the role and click on create role