#<p align="center"> Docker-Kubernetes-Container </p>

Kubernetes is made up many components that do not know are care about each other. The components all talk to each other through the API server. Each of these components operates its own function and then exposes metrics, that we can collect for monitoring later on. We can break down the components into three main parts.

The Control Plane - The Master.

Nodes - Where pods get scheduled.

Pods - Holds containers.
