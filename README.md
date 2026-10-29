\# Jenkins Shared Library



A simple Jenkins Shared Library demonstrating a reusable pipeline step.



\## Repository Structure



```text

jenkins-shared-library/

├── vars/

│   └── helloWorld.groovy

├── resources/

├── src/

└── README.md

```



\## Available Steps



\### `helloWorld()`



Prints a greeting in the Jenkins build console:



```groovy

helloWorld()

```



\## Usage



Configure this repository as a Global Pipeline Library in Jenkins, then call `helloWorld()` from a pipeline.



\## Purpose



This project demonstrates how to create and use reusable Jenkins Pipeline code.

