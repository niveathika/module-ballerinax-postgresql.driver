## Package overview

This Package bundles the latest PostgreSQL drivers so that the PostgreSQL connector can be used in ballerina projects easily.

## Compatibility

| |     Version      |
|:---|:----------------:|
|Ballerina Language |   **2201.3.0**   |
|PostgreSQL Driver |    **42.5.1**    |
|PostgreSQL DB Server| **8.2 or above** |

> The above PostgreSQL drivers are released under the [BSD 2-Clause](https://jdbc.postgresql.org/about/license.html).

## Usage

To add the PostgreSQL driver dependency the project, simply import the module as below,

```ballerina
import ballerina/sql;
import ballerinax/postgresql;
import ballerinax/postgresql.driver as _;
```
