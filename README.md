Ballerina Snowflake Connector
===================

[![Build](https://github.com/ballerina-platform/module-ballerinax-snowflake/workflows/CI/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-snowflake/actions?query=workflow%3ACI)
[![Trivy](https://github.com/ballerina-platform/module-ballerinax-snowflake/actions/workflows/trivy-scan.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-snowflake/actions/workflows/trivy-scan.yml)
[![codecov](https://codecov.io/gh/ballerina-platform/module-ballerinax-snowflake/branch/main/graph/badge.svg)](https://codecov.io/gh/ballerina-platform/module-ballerinax-snowflake)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerinax-snowflake.svg)](https://github.com/ballerina-platform/module-ballerinax-snowflake/commits/main)
[![GraalVM Check](https://github.com/ballerina-platform/module-ballerinax-snowflake/actions/workflows/build-with-bal-test-native.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-snowflake/actions/workflows/build-with-bal-test-native.yml)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The Snowflake [Ballerina](https://ballerina.io/) connector allows you to programmatically access all of the Snowflake applications, databases, APIs, services via the Java Database Connectivity (JDBC) API using [Ballerina](https://ballerina.io/).
It provides operations to execute a wide range of standard DDL Commands, SQL Commands, and SQL Functions for querying data sources. 
You can find reference information for all the Snowflake SQL commands (DDL, DML, and query syntax) [here](https://docs.snowflake.com/en/sql-reference-commands.html).

For more information, go to the module(s).
- [snowflake](Module.md)

## Building from the source

### Setting up the prerequisites

1. Download and install Java SE Development Kit (JDK) version 17. You can install either [OpenJDK](https://adoptopenjdk.net/) or [Oracle](https://www.oracle.com/java/technologies/downloads/).

    > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.

2. Download and install [Ballerina Swan Lake](https://ballerina.io/). 

### Building the source

Execute the commands below to build from the source.

- To build the library:
    ```shell
    ./gradlew clean build
    ```
- To run the integration tests: 
    ```shell
    ./gradlew clean test
    ```

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of conduct

All the contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful links

* Discuss the code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Discord server](https://discord.gg/ballerinalang).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
