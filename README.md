# DO101-apps

Apps for the DO101 course.

Disclaimer: Everything written below this line has been added by me and might not make sense at all.

## OpenShift

* Each unit in OpenShift is named a "pod".
* You can make use of Webhooks in OpenShift to automatically trigger fields.

## OpenShift CLI

```bash
oc login - Self explanatory.

oc project <project name> - Change the current project.

oc new-app - Create a new app on the current project. This will not create a route by default.

oc expose svc/<app> - Create a route for a new app.

oc get svc - Get services running in the current project.
oc get routes - Get routes in the current project.
oc get pods - Get pods in current project.
oc logs -f <pod> - Interactively show logs of the given pod.
```

### OpenShift vs. Kubernetes


