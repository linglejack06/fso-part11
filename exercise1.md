# Part 11 Exercise 1 questions

### What are the specific tools for taking care of integration / deployment steps in Java?

Regarding linting within a Java development pipeline, I would use either Checkstyle or a combination of prettier-java and error-prone to hit code styling and static analysis. Since a multitude of developers will be writing, deploying, and testing the code, Selenium seems like a perfect choice for a testing framework, it's disregard to specific platforms allows easy setup no matter the device. Upon research on Google, the most popular choice for building the application tends to be Maven, as it is consistenly used alongside Java Spring Boot.

### What alternatives are there to setup the CI besides Jenkins and GIthub Actions?

Following along with git, I would choose the Gitlab deployment pipeline, as it is similar to github actions while having the option of running on local servers or the cloud.

### Would this setup be better in a self-hosted or a cloud-based environment?

Without knowing about the further intricacies of this project, cloud-based pipelines would be the better choice. This is due to the relative ease-of-use and cheaper costs.
