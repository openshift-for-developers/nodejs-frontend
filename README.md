# The Noted Application
This is a sample application for the book, Getting Started with OpenShift.

It's a web app that allows users to `list, add, and delete` posts with content.

The Noted Application that is composed of:
- [a quarkus backend](https://github.com/openshift-for-developers/quarkus-backend)
- [a nodejs react frontend](https://github.com/openshift-for-developers/nodejs-frontend)
- an optionally deployed database

## Application Topology
![Application topology](topology.png "Application Topology")

## Deployment
It is expected for readers of the book to follow the steps outlined in each chapter.  However we provide minimal quickstart instructions below.

### Local Deployment
You are able to run the quarkus application locally using the command:
`npm install && npm run devmode`

### OpenShift Deployment
You can find minimal [quickstart instructions at openshift-for-developers/noted](https://github.com/openshift-for-developers/noted).

> *Note: this example app is derived from the [example at redhat-developer-demos/quarkus-reactjs-postit-app](https://github.com/redhat-developer-demos/quarkus-reactjs-postit-app).*
