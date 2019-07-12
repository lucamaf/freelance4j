
# Business Use Case

You are a consultant assigned to Freelance4J Inc.. They are developing an application platform, branded freelance4j, a new online marketplace for freelancers. The online marketplace allows clients to post projects. Freelancers can then search for projects that match their skillset. Freelancers can bid on projects, and clients can accept the freelancer with the best bid.

Freelance4J Inc. is adopting a new microservices architecture and wishes to make their platform APIs available as REST APIs. They have asked you to lead a proof-of-concept (POC) using Red Hat OpenShift Application Runtimes. The purpose of the POC is to demonstrate the use of Red Hat OpenShift Application Runtimes for development of REST APIs on the OpenShift Container Platform.

In this version, you will not implement the full functionality. You will focus on creating a subset of the backend REST APIs.

# REST Services and Architecture

Freelance4J Inc. management requires that you implement the following services in your project.
freelance4j Microservices 	Function in freelance4j Application

API Gateway
	

Entry-point for web-based and mobile clients of the application

Project Service
	

Provides information about the projects—including project owner, description and status

Freelancer Service
	

Provides information about the freelancers—including their name, email address and list of skills.