

DevSecOps

1. ci/cd - continous integration/continous delivery/continous deployment - Monolithic Approach
    
    Integration (Automation - Continous)

    Code management (Development Code) (Raw code - Java)
    Unit testing (Junit) (whitebox testing)
    Source code analysis (SAST Tools) (Sonarqube/Snyk SCA)
    Build Code (Convert this code - Class file) (Maven)
    Output - WAR/JAR file 

    Artifactory - JFrog
    
    Delivery ( Continous Delivery)
    Webserver - (testing environment) (sessions)
                - One code - At a time multiple users
    (blackbox testing) - Functional testing 
                            DAST Tools (OWASP 10)

    Deployment( Continous Deployment)
     Webserver - (Production environment) (sessions) (Cloud)
                - One code - At a time multiple users

2. ci/cd - Microservices Approach

        Docker
            Libraries - Container Security
        Kubernetes


3. Infrastructure as a code (Terraform)
        IAC Testing (DevSecOps)

4. Configuration Management (Ansible)


5. DevSecOps