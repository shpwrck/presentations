# Title 

Three ways to turn your mess of clusters into a mesh of clusters.

# Description

Many organizations running Kubernetes today are running it at scales much larger than in years past. Running multiple clusters is extremely helpful at decreasing blast radius, improving availability, enabling granular chargeback, and estabilishing security boundaries. While this usually comes with added cost and complexity, that is not always true. The following presentation outlines the current state of multi-cluster meshes, based on three prototypical models. Using any one of these techniques will generally enhance the benefits of a multi-cluster approach, while reducing some of the inherent costs. 

# Outline

* Intro
  * Bio: Describe why I'm qualified to give the talk.
  * Prerequisites: Describe what terms/concepts will be required to consider this talk useful.
  * Motivation
    * Case 1: Elasticity
    * Case 2: Resiliency requirements
    * Case 3: Resource constraints
  * Impediments: Warn the audience that "there be dragons".
* Ways to implement this solution
  * Beneath the CNI 
    * Sample Implementation: Wireguard
    * Demonstration
    * Further Reading
  * Within the CNI
    * Sample Implementation: Cilium
    * Demonstration
    * Further Reading
  * Above the CNI
    * Sample Implementation: Istio
    * Demonstration
    * Further Reading
