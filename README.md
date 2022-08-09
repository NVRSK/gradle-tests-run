# gradle-tests-run

CI status: [![CI (all tests - unit, integrated, performance)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/gradle.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/gradle.yml)

CI, only unit tests status: [![CI (only unit tests)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/unitTestsRunner.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/unitTestsRunner.yml)

CI, only integrated tests status: [![CI (only integrated tests)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/integratedTestsRunner.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/integratedTestsRunner.yml)

CI, only performance tests status: [![CI (only performance tests)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/performanceTestsRunner.yml/badge.svg)](https://github.com/NVRSK/gradle-tests-run/actions/workflows/performanceTestsRunner.yml)


## How to run tests via gradle
- To build the project, all the tests: unit, integrated, performance, will be run:
> *gradle  integrationTest performanceTest build --continue* 
- To build the project, only unit tests will be run:
> *gradle  build*
- To build the project without any tests:
> *gradle  build -x test*
- To start only unit tests:
> *gradle test*
- To start only integrated tests:
> *gradle integrationTest*
- To start only performance tests:
> *gradle performanceTest*
- To start unit and performance tests:
> *gradle test performanceTest --continue*
> 
_--continue_ flag - '_performanceTest_' task will be executed even if '_test_' task fails
- To start unit, integrated and performance tests without building the project:
> *gradle test integrationTest performanceTest --continue*

### Notes
Some tests are failing just only for demo
