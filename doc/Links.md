## Doc Links

#### [Return to Main Readme](https://github.com/virtmerlin/mglab-share-eks#links)

#### (1) Introduction to Devops

- Waterfall vs Agile (3rd Party Blog):
  https://www.seguetech.com/waterfall-vs-agile-methodology/
- What is Scrum (3rd Party Blog):
  https://www.scrum.org/resources/what-is-scrum
- Monolithic & Microservices Patterns
  https://microservices.io/patterns/monolithic.html
  https://microservices.io/patterns/microservices.html
- DevOps Team Topologies
  https://web.devopstopologies.com/

#### (2/3) Infrastructure Automation & CLI Tools:

- AWS CloudFormation (CFN) References:
  https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html
  https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html
- AWS CloudFormation (CFN) References Templates & QuickStarts:
  https://github.com/awslabs/aws-cloudformation-templates
  https://aws.amazon.com/quickstart/
  https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-sample-templates.html
- AWS CDK (Drive CLoudFormation via Code)
  https://aws.amazon.com/cdk/
- AWS SAM (Drive Serverless Application dev & deployment via CloudFormation)
  https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html
- AWS SDKs
  https://aws.amazon.com/tools/
- AWS CLI Control Output
  https://docs.aws.amazon.com/cli/latest/userguide/cli-usage-output.html
  https://jmespath.org/

#### (4) AWS CI/CD Tools:

- GIT Management Models (Flow vs. Trunk) (3rd party Blogs)
  https://nvie.com/posts/a-successful-git-branching-model/
  https://www.toptal.com/software/trunk-based-development-git-flow
- GIT Duet
  https://github.com/git-duet/git-duet
- CodeCommit
  https://aws.amazon.com/codecommit/
- CodeBuild & Code Deploy
  https://aws.amazon.com/codebuild/
  https://aws.amazon.com/codedeploy/
  https://aws.amazon.com/blogs/devops/setting-up-a-ci-cd-pipeline-by-integrating-jenkins-with-aws-codebuild-and-aws-codedeploy/
  https://www.jenkins.io/doc/pipeline/steps/codedeploy
  https://plugins.jenkins.io/codedeploy/
  https://plugins.jenkins.io/ec2-fleet/
  https://aws.amazon.com/blogs/compute/cost-optimize-your-jenkins-ci-cd-pipelines-using-ec2-spot-instances/

#### (5/6) MicroServices & Containers:

- Should we make a MicroService (3rd Party Blog):
  https://tanzu.vmware.com/content/blog/should-that-be-a-microservice-keep-these-six-factors-in-mind
- ECR Security Best practices:
  https://d2908q01vomqb2.cloudfront.net/fe2ef495a1152561572949784c16bf23abb28057/2020/08/21/C3-ECR-Security-Best-Practices_072020_v3-no-notes.pdf
- ECS vs EKS:
  https://aws.amazon.com/blogs/containers/amazon-ecs-vs-amazon-eks-making-sense-of-aws-container-services/
- ECS Task Placement
  https://aws.amazon.com/blogs/compute/amazon-ecs-task-placement/

  EKS:

  - Public EKS Customers
    https://aws.amazon.com/eks/customers/
  - Public EKS Roadmap
    https://github.com/aws/containers-roadmap
  - 3rd party Blog: KOPS versus EKS
    https://www.bluematador.com/blog/kubernetes-on-aws-eks-vs-kops
  - 3rd party Blog: Install EKS Terraform
    https://medium.com/dev-genius/create-an-amazon-eks-cluster-with-managed-node-group-using-terraform-a3b50d276b13
  - 3rd part BLog: 10 Essential EKS capabilities
    https://logz.io/blog/aws-eks-features/
  - EKSCTL reference
    https://eksctl.io/usage/creating-and-managing-clusters/
  - Exposing K8s services publicly with EKS
    https://aws.amazon.com/premiumsupport/knowledge-center/eks-kubernetes-services-cluster/
  - Using K8s Persistant Storage in EKS
    https://aws.amazon.com/premiumsupport/knowledge-center/eks-persistent-storage/
  - AWS IAM Authenticator Project
    https://github.com/kubernetes-sigs/aws-iam-authenticator
  - Generating Kubeconfig
    https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html
  - AWS Cluster Autoscaler on EKS
    https://docs.aws.amazon.com/eks/latest/userguide/cluster-autoscaler.html
  - K8s (HPA) Horizontal Pod Autoscaler on EKS
    https://docs.aws.amazon.com/eks/latest/userguide/horizontal-pod-autoscaler.html
  - K8s (VPA) Vertical Pod Autoscaler on EKS
    https://docs.aws.amazon.com/eks/latest/userguide/vertical-pod-autoscaler.html

#### (7) Serverless (Lambda):

- Lambda Scalability
  https://aws.amazon.com/blogs/compute/new-for-aws-lambda-predictable-start-up-times-with-provisioned-concurrency/
- Top 5 Concepts in Serverless (3rd party Blog)
  https://thenewstack.io/5-things-to-know-about-serverless-in-2020/

#### (8) Deployment Strategies:

- CodeDeploy Deployment Configurations
  https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-configurations.html
- ECS Blue Green
  https://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-blue-green.html
- K8s Blog on Blue/Green with Jenkins
  https://kubernetes.io/blog/2018/04/30/zero-downtime-deployment-kubernetes-jenkins/
- K8s Weaveworks project (same folks who do flux) to transition blue greens in K8s
  https://github.com/weaveworks/flagger

#### (9) Automated Testing:

- Whats the diff between Unit & Integration testing? (3rd Party Blog):
  https://www.softwaretestingclass.com/what-is-difference-between-unit-testing-and-integration-testing/
- GO TDD testing with Ginko:
  https://onsi.github.io/ginkgo/
- Python TDD testing with pytest:
  https://www.thedigitalcatonline.com/blog/2020/09/10/tdd-in-python-with-pytest-part-1/
- JavaScript TDD testing with Mocha:
  https://mochajs.org/
- CodePipeline with GhostScript:
  https://ghostinspector.com/docs/integration/aws-codepipeline/
- Chaos Engineering Workshop:
  https://gremlin.awsworkshop.io/50_automating_experiments.html

#### (10) DevSecOps:

- AWS CodePipeline Best Practices:
  https://docs.aws.amazon.com/codepipeline/latest/userguide/best-practices.html
  https://docs.aws.amazon.com/codepipeline/latest/userguide/security-best-practices.html
- AWS Systems Manager how Security Patches are seleted:
  https://docs.aws.amazon.com/systems-manager/latest/userguide/patch-manager-how-it-works-selection.html
- AWS Systems Manager Parameter Store vs. AWS Secrets Manager:
  https://www.1strategy.com/blog/2019/02/28/aws-parameter-store-vs-aws-secrets-manager/
- AWS SecurityWorkshops:
  https://awssecworkshops.com/
  https://snyk.awsworkshop.io/
  https://security-hub-workshop.awssecworkshops.com/
  https://devops.awssecworkshops.com/

#### (10) Config Management:

- AWS Management Workshops:
  https://workshop.aws-management.tools/
- Golden AMIs:
  https://aws.amazon.com/blogs/mt/creating-packer-images-using-system-manager-automation/
  https://aws.amazon.com/blogs/awsmarketplace/announcing-the-golden-ami-pipeline/
- AWS Systems Manager Patching:
  https://docs.aws.amazon.com/systems-manager/latest/userguide/service-pack-patch-walkthrough.html

#### (10) Observability:

- AWS Observability Workshops
  https://observability.workshop.aws/en/
- AWS Observability PodCast
  https://d1le29qyzha1u4.cloudfront.net/AWS_Podcast_Episode_357.mp3
