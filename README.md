# openshift-mapit-spring

openshift-mapit-spring is a geo-spatial Spring Boot app which shows the location of AirPorts on the Map using Leaflet. This app is a
port of a [python app](https://github.com/thesteve0/awsdemo) originally created by [Steven Pousty](https://github.com/thesteve0).


# Deploy Guide

You can deploy openshift-mapit-spring on OpenShift using the provided template:
```
oc new-app -f https://raw.githubusercontent.com/siamaksade/openshift-mapit-spring-spring/master/openshift-mapit-spring-template.yaml
```

