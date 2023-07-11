<div align="center">
<h1 align="center">Welcome to Amplify Platform : Agents Helm-Chart Repo</h1>
<h4 align="center">You can find sample helm-charts to deploy respective Amplify Agents to integrate with Amplify Platform</h4>
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/somdutt-sharma-76965118/">
  <img  src="./resources/grid-snake.svg"
       alt="snake" /></a>
</div>

## Getting Started
Apigee : https://github.com/Axway/agents-apigee#setup-agent-environment-variables
Apigee-Discovery : https://github.com/Axway/agents-apigee/blob/main/discovery/README.md
Apigee-Traceability : https://github.com/Axway/agents-apigee/blob/main/traceability/README.md#traceability-agent-variables


### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Adding new chart or versioning

* update chart version in chart.yaml 
* helm package apigee-discovery
* helm lint apigee-discovery-<version>.tgz
* move the chart apigee-discovery-<version>.tgz to ./chart folder and verify the permisions
* helm repo index --url https://apievangelistsom.github.io/amplify-agents-helm/charts --merge index.yaml .
* commit and push


### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info : [@apievangelistsom]

## Version History

* 0.2
    * Various bug fixes and optimizations
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## RoadMap
- [x] Apigee-discovery-agent
- [x] Apigee-traceability-agent

- [ ] To-Do list
    - [ ] ABC agent
    - [ ] another agent
