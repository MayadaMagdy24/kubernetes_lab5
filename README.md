# kubernetes_lab5
RBAC
User smoke should be allowed to create and delete Pods, Deployments and StatefulSets in Namespace applications.
User smoke should have view permissions (like the permissions of the default ClusterRole named view ) in all Namespaces but not in kube-system .
Verify everything using kubectl auth can-i .


HELM
Using helm install apache chart on your system
