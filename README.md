# appIntegration3

In this project, is built a scenario that makes use of messaging to support interaction
between one series director and a group of actors. In this scenario, there are three nodes
(director, system, and actor), which make use of the series database from the previous
assignment. The director and actor are standalone applications, whereas the system node
runs within the application server. Since one of the main goals is to learn the JMS API, all
communication between nodes will be supported by JMS, including the synchronous ones
(except when otherwise noted).
