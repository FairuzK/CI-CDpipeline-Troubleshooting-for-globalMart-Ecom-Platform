# Implementing-CI-CD-pipeline-for-globalMart-Ecom-Platform
Resolved critical production deployment failures, restoring $25K/ hour revenue stream*

Situation 
Production deployment failures are causing site outages andan  estimated $25,000/hour revenue loss

Task 
Diagnose root cause, implement a permanent fix, and establish monitoring to prevent recurrence

Action
Systematically traced CI/CD execution using AWS CodePipeline and CloudWatch Logs to identify failure points
Rectified IAM Role misconfigurations for AWS CodeDeploy, lacking necessary S3 bucket permissions
Corrected ELB health check configurations (path and timeout settings), causing target group failures
Fixed security group rules preventing EC2 instances in Auto Scaling groups from communicating
Implemented automated rollback procedures and deployment validation checks

Result 
Restored full site functionality within 2 hours; establisheda  stable CI/CD pipeline with zero deployment failures post-implementation
