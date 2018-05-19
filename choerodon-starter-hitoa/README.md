# Hitoa Toolkit

The hitoa toolkit is used to collect the information of jvm while the microservice program is running.
## Feature

Add richer thread group monitoring capabilities to future plans.
## Requirements

References in `pom.xml` of microservices. 

```xml
<dependency>
    <groupId>io.choerodon</groupId>
    <artifactId>choerodon-starter-hitoa</artifactId>
     <version>0.5.0.RELEASE</version>
</dependency>
```

To start up the monitoring of prometheus.

## To get the code

```shell
git clone https://github.com/choerodon/choerodon-starters.git
cd choerodon-starter-hitoa
```
## Installation and Getting Started

Microservices can be monitored after being referenced.
## Documentation

1. Use the toolkit ofio.micrometer version 1.0.2 for the  collection of jvm information.
2. By using spring.factories, the file is injected and the citation takes effect.
3. View the returned data information on the /prometheus endpoint of the program monitoring port that references the package.
4. Later iterations of the version may require changes to the version.

## Dependencies

- io.micrometer 1.0.2

## Reporting Issues

If you find any shortcomings or bugs, please describe them in the Issue.
    
## How to Contribute
Pull requests are welcome! Follow this link for more information on how to contribute.

