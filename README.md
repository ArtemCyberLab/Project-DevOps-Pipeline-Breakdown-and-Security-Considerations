I have developed a project that provides a detailed overview of the DevOps pipeline, outlining its key stages and the tools used at each phase. In this project, I explored how the final product is deployed across different environments, from development to production. I analyzed version control systems, identifying GitHub as the largest Git provider and GitLab as a popular self-hosted Git solution. I also highlighted GittyLeaks as a tool used to scan repositories for sensitive information.

I examined dependency management, distinguishing between internal dependencies (created by our organization) and external ones (such as jQuery). I also mentioned PyPi as the public repository for Python dependencies and discussed the critical Log4j vulnerability that made headlines in 2021.

In the section on automated testing, I explained how SAST and DAST tools are used to identify vulnerabilities in code and noted that they cannot replace full penetration testing. I then covered CI/CD, explaining the meanings of Continuous Integration and Continuous Delivery while defining the roles of build orchestrators and build agents within the infrastructure.

I provided an in-depth look at deployment environments, noting that the DEV environment has the weakest security configuration, UAT is used for testing, and PrePROD serves as a final verification stage before deployment to production. Additionally, I pointed out that a common class of vulnerabilities found in PROD is developer bypasses inherited from DEV.

The final step of the project involved completing a pipeline diagram and answering related questions about its functionality.
