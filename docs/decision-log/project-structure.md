## Context

The application that we are intending to build here consists of 2 different part, First is the frontend to serve our application and second is to a create node express server to connect to DB or to create a simple bff layer for data manipulation. 


## Decision

After analyis between  javascript monorepos structure such as yarn workspace, bazel, and [lerna](https://lerna.js.org/), Lerna seems to be one that most fitted our requirement. Lerna makes it easy to resolve the internal package dependencies and helps to maintain version dependencies between the pacakges. And it is recommened by yarn site to handle monorepos. 
