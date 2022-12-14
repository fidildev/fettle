# 13. Bounded Contexts

Date: 2022-12-02

## Status

Accepted

## Context

We use domain driven design (DDD) to help organize the application. The application design is split into [Bounded Contexts](https://martinfowler.com/bliki/BoundedContext.html). Each bounded contexts uses the same [Ubiquitous Language](https://martinfowler.com/bliki/UbiquitousLanguage.html).

## Decision

There are four bounded contexts:

1. Organization Management
1. Repository Analysis
1. Subscription Management
1. Communications

![contexts](../diagrams/contexts.png)

## Consequences

Services will be developed within the Bounded Contexts and will speak a ubiquitous language.

Contexts will be scoped to specific capabilities to be orchestrated.
