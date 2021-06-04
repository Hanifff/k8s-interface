# k8s-interface


This repository contains a Golang interface that anyone can integrate into any k8s cluster version v.1.17.x.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## About the project

The Kube was a part of my project for a bachelor's thesis, where I integrated a k8s go interface to an application that the university use to auto-grade students' assignments.<br>
The k8s interface runs each instance of applications as single [k8s job objects](https://kubernetes.io/docs/concepts/workloads/controllers/job/).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Run The Application
In order to run the application you need to have at least one k8s cluster connected to the k8s [client-go](https://github.com/kubernetes/client-go) up & running.

