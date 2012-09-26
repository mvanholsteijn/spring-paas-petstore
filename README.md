spring-paas-petstore
====================

A git copy of the subversion  from https://src.springframework.org/svn/spring-samples/petclinic/trunk/ for PaaS demonstration purposes

To use:
- mvn install tomcat:run
- go to http://localhost:8080/org.springframework.samples.petclinic/

To deploy to Openshift:
git push <OPENSHIFT-GITHUB-LOCATION> openshift:master
where OPENSHIFT-GITHUB-LOCATION can be replaced by the address of the openshift github account, or an alias in the .git/config
