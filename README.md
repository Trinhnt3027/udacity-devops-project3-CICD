We are archiving this repository because we do not want learners to push personal development to the current repository. If you have any issues or suggestions to make, feel free to:
- Utilize the https://knowledge.udacity.com/ forum to seek help on content-specific issues.
- [Submit a support ticket](https://udacity.zendesk.com/hc/en-us/requests/new) along with the link to your forked repository. 
- If you are an enterprise learner, please [Submit a support ticket here](https://udacityenterprise.zendesk.com/hc/en-us/requests/new?ticket_form_id=360000279131)

## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)



### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01](https://github.com/Trinhnt3027/udacity-devops-project3-CICD)
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02](http://udapeople-ff7544b.s3.amazonaws.com/index.html)
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03](http://d2e4p47n71t7nd.cloudfront.net/)
  1. Public URLs to deployed application back-end in EC2 [URL04](http://ec2-52-3-235-133.compute-1.amazonaws.com:3030)
  1. Public URL to your Prometheus Server [URL05](http://ec2-3-83-120-13.compute-1.amazonaws.com:9090/targets)
- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01](screenshots/SCR01_build_backend_failed.JPG)
  1. Job failed because of unit tests. [SCREENSHOT02](screenshots/SCR02_test_backend_failed.JPG)
  1. Job that failed because of vulnerable packages. [SCREENSHOT03](screenshots/SCR03_scan_backend_failed.JPG)
  1. An alert from one of your failed builds. [SCREENSHOT04](screenshots/SCR04_failed_alert.png)
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05](screenshots/SCR05_deploy_backend_fail.JPG)
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06](screenshots/SCR06_smock_test_front_fail.JPG)
  1. Successful rollback after a failed smoke test. [SCREENSHOT07](screenshots/SCR07_rollback_success.JPG)
  1. Successful promotion job. [SCREENSHOT08](screenshots/SCR08_update_clountfront.JPG)
  1. Successful cleanup job. [SCREENSHOT09](screenshots/SCR09_cleanup_success.JPG)
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10](screenshots/SCR10_build_dev-branch.JPG)
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11](screenshots/SCR11_prometheus_graph.png)
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12](screenshots/SCR12_alert_email.JPG)

- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder. 

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
