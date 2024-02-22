# DevOps Decision Record 

This is a DevOps Decision Record example. It can serve as a helpful starting point creating your own.

**Title**: Add DevOps tool to improve developers shipping to product

**Status**: request for comments | proposed | accepted | rejected | deprecated | superseded

**Updated on:** [Date]

**Updated by:** [Name/Role]

**Issue**: Describe the issue you want to address, and leave no questions about why.

* The DevOps team has identified the need to replace the existing CI/CD tool with a more scalable and feature-rich solution. The current tool lacks certain capabilities required for automated testing, deployment orchestration, and integration with other DevOps tools.

**Assumptions**: Describe any assumptions, premises, cross-project requirements, etc.
  
* **Integration**: The DevOps tools must work with our existing DevOps toolchain, including version control systems (e.g. Git), issue tracking systems (e.g. Jira), and container orchestration platforms (e.g. Kubernetes).

**Constraints**: Capture any constraints to the environment this decision might pose. 

* Depending on the specific features and integrations used, there may be a degree of vendor lock-in with [New CI/CD Tool]. It will be important to carefully evaluate and mitigate this risk by adopting open standards and best practices for interoperability.

**Positions**: List the potential candidate options as facts and data, not opinions.

* Tool 1: Supports parallel execution of builds, parallel deployments, distributed architectures, and can handle large codebases up to [size] efficiently. [Links to sources of information].

* Tool 2: Paid [New CI/CD Tool] has a community of users [size] and source code contributors [count], and provides access to specific plugins [x, y, z] that are relevant to us. Licensing cost is $x per year per developer. [Links to sources of information].

**Opinions**: List the perspectives of the team and stakeholders, and also third-party advisors and reviewers.

* Person 1 opinion: I used Tool 1 and Tool 2 at my previous job. I'm comfortable recommending Tool 1 for technical reasons [x, y, z]. However, I found the customer service of Tool 2 to be better. [More specifics].

* Person 2 opinion: I tried scaling Tool 1 and Tool 2 by doing [x, y, z]. Both tools reached level [x] of speed. In my opinion, Tool 2 has clearer semantics, and is more pleasant to use because [x, y, z].
  
**Selection**: Explain why you selected a position, with purpose and accountability.

* The team selected [x] because [y]. [More specifics]
  
**Implications**: state your decision’s implications, such as any need for changes.

* Implementing [New CI/CD Tool] will require a migration effort to transition existing pipelines, configurations, and workflows from the old tool to the new one. This may involve training sessions for team members and temporary disruptions to ongoing projects.
