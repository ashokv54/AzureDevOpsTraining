# AzureDevOpsTraining

## Syllabus

### Section 1

- DevOps Intoruduction
- Devops Tools
- Different practices of Devops - Agile, Scrum etc.
- Azure devops URL walkthourgh , user creation
- Azure Boards overview
- Work item types  - different use case scenario
- Queries in work items
  
  > **Task 1:** Create a agile Project , write a query to retrieve bugs
  
  > **Task 2:** integrate github with Azure boards, fix an issue from commit
  
- Integrate a repository with Azure Boards
- Integrate Azure Pipelines and GitHub Actions with work item tracking tools
- Identify appropriate metrics related to flow of work, such as cycle times, time to recovery, and lead time
- Document a project by using tools, such as wikis and process diagrams
- Custom dashboards in Azure Boards

    
  > **Task 3:** Configure dashboard and add all chart type

  > **Task 4:** Assign work items in sprint and capacity planning

### Section 2

- Azure repos overview , git basics
- Branching strategies for the source code - feature, relaese, trunk . 
- Pull request workflow by using branch policies and branch protections
- Different merging strategies in Azure Repos
- Branch merging restrictions by using branch policies and branch protections
- Configure permissions in the source control repository

### Section 3

- Azure Pipelines overview
- Configure agents in pipelines, Microsoft-hosted , Self-hosted .
- Classic pipeline creation for application Build
- Yaml based pipeline creation for application Build
- Integrate pipelines with external tools, including dependency scanning, security scanning, and code coverage
- Implement quality and release gates, including security and governance
- Integration of automated tests into pipelines
- Azure Pipeline Environments , Deployment groups
- Container based job configuration in pipeline
- Deployment jobs in Azure pipelines, Runonce, Rolling, canary strategies
- Azure Pipeline advanced configuration  - branch filter , scheduled builds 
- Reduce build time in azure pipelines
- Configure permissions for users in Pipelines, Service Connections.
- Azure pipelines troubleshooting with debug
- Reusable pipeline elements, including YAML templates, task groups, variables, and variable groups
- Monitor pipeline health, including failure rate, duration, and flaky tests
- Build and release pipelines in Github Actions
- Secret management in Pipelines and github actions

### Section 4

- Azure Artifacts overview
- package management implementation that uses Azure Artifacts, GitHub Packages, NuGet, and npm
- Implement a versioning strategy for pipeline artifacts
- Azure Testplans overview - manual testing addon example
- Infrastructure as a code overview
- ARM, BICEP , TERRAFORM introduction
- IaC strategy, including source control and automation of testing and deployment
- Automate security and compliance scanning 
- Automate analysis of source code by using GitHub code scanning, GitHub secrets scanning, pipeline-based scans, and SonarQube
- Automate analysis of licensing, vulnerabilities, and versioning of open-source components by using Mend Bolt and GitHub Dependency Scanning

### Section 5

- Docker introduction , VM vs Containers
- Creation of docker images : core build block
- Manage data and working with volumes in Docker
- Container network communication basics
- Kubernetes introduction
- Kubernetes pods, replicaset, deployments, services creation using imperative and declarative way
- Integration of Azure kubernetes with Azure files, storage disks for persistent storage
- Kubernetes cordon, taints, node affinity , corndon etc.
- Kubernetes ingress basics
- Working with ChatGPT for code creation for dockerfile, Kubernetes yaml files
