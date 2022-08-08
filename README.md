# gradle-tests-run

CI status: [![CI (all tests - unit, integrated, performance)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/gradle.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/gradle.yml)

CI, only unit tests status: [![CI (only unit tests)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/unitTestsRunner.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/unitTestsRunner.yml)

CI, only integrated tests status: [![CI (only integrated tests)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/integratedTestsRunner.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/integratedTestsRunner.yml)

CI, only performance tests status: [![CI (only performance tests)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/performanceTestsRunner.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/performanceTestsRunner.yml)


## How to run tests via gradle
- To build the project, all the tests: unit, integrated, performance, will be run:
> *gradle --continue build* 
- To start only unit tests:
> *gradle test*
- To start only integrated tests:
> *gradle integrationTest*
- To start only performance tests:
> *gradle performanceTest*

### Notes
Some tests are failing just only for demo
