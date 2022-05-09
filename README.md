# workshop-eks

## AWS Reference Architecture

EKS Workshop介绍在AWS EKS上的最佳实践，包括安装和配置AWS EKS Cluster，部署常用Kubernetes插件，如负载均衡的插件-AWS Load Balancer Controller、监控插件-Prometheus和Grafana、日志插件-FluentBit、弹性扩展插件Cluster Autoscaler等。EKS Workshop采用[Cloudformation模版](Cloudformation_Template.yml)进行初始化配置，一键式创建VPC、Subnet、Nat Gateway、堡垒机、Role、Security Group、EKS Cluster等资源。

Kubernetes常用了WEB应用，下图是基于AWS EKS的参考架构。
![AWS Reference Architecture](AWSReferenceArchitecture.png)

下面是workshop的实验步骤。
## 1. [Login to AWS Console](01.login-to-aws-console.md)

## 2. [Install tools for EKS](02.install-tools-for-eks.md)

## 3. [Create EKS nodegroup](03.create-eks-nodegroup.md)

## 4. [Docker Image Build](04.docker-image-build.md)

## 5. [Deploy K8S APP Deployment and Service](05.deploy-k8s-app-service.md)

## 6. [AWS load balancer controller](06.create-aws-load-balancer-controller.md)

## 7. [Prometheus and Grafana Monitoring EKS](07.monitor-eks-with-prometheus-grafana.md)

## 8. [Create service account for pod](08.create-service-account-for-pod.md)

## 9. [Fluentbit Logs](09.fluent-bit-logs.md)

## 10. [Scale pod and node](10.scale-pod-and-node.md)

