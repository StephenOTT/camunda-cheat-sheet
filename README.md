# Camunda Cheet Sheet

A list of commonly used links and commands for Camunda BPM

Links are as of version 7.6.x

WIP


# Links

1. API: https://docs.camunda.org/manual/7.6/reference/rest/
1. JavaDoc: https://docs.camunda.org/javadoc/camunda-bpm-platform/7.6/


# Common Commands

Variables:

1. getVariable
1. setVariable


# Process Engine Services:

https://docs.camunda.org/javadoc/camunda-bpm-platform/7.6/org/camunda/bpm/engine/ProcessEngineServices.html

Engine service gives you access to the various APIs through the `execution.getProcessEngineServices()`

# Camunda Public API (Java)

https://docs.camunda.org/javadoc/camunda-bpm-platform/7.6/org/camunda/bpm/engine/package-summary.html


# Execution

One of the most commonly called delegates, typically used in scripts and expressions.
https://docs.camunda.org/javadoc/camunda-bpm-platform/7.6/org/camunda/bpm/engine/delegate/DelegateExecution.html

# SPIN

Working with JSON
https://docs.camunda.org/manual/7.6/reference/spin/json/



# Script Logging to Camunda Console

Javascript
```
var system = java.lang.System
system.out.println("System out println");
```

