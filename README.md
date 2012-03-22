# VSPLF Semantic Web Framework for Java

https://github.com/vsplf/vsplf-sw4j/wiki

## Project Mission
* Create a common range of Java Model matching semantic web items
* Modular model systems and easy to extend

## How to develop


### Prepare your environment

Use [Apache Maven][maven] version 3.0.0 minimum. Version 3.0.3 and above is recommended.

[maven]: http://maven.apache.org "Apache Maven"

### Default Build

Use this command to build project:

<pre>
  mvn clean install
</pre>

### Violations Checking Build

To check any violations, use this command below:

<pre>
  git submodule init
  git submodule update
  mvn clean install -Dvsplf.violations.checking
</pre>

### Project resources

* Issues management: https://github.com/vsplf/vsplf-sw4j/issues
* Jenkins continuous integration build: https://vsplf.ci.cloudbees.com/job/vsplf-sw4j-master-ci/
* Artifact deployment:
  * release repository:  https://repository-vsplf.forge.cloudbees.com/release/
  * snapshot repository: http://repository-vsplf.forge.cloudbees.com/snapshot/


## How to use this framework
