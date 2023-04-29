# kubernetes_lab5
RBAC
User smoke should be allowed to create and delete Pods, Deployments and StatefulSets in Namespace applications.
![Screenshot (1225)](https://user-images.githubusercontent.com/93229250/235270868-444354fc-8b39-43f5-a1d4-8d5918d77068.png)
![Screenshot (1226)](https://user-images.githubusercontent.com/93229250/235270884-5e054218-8b66-48de-ba11-ee08de99f969.png)
![Screenshot (1227)](https://user-images.githubusercontent.com/93229250/235270892-07c8153f-a8a5-461e-ba34-1a0297ab1cb7.png)

User smoke should have view permissions (like the permissions of the default ClusterRole named view ) in all Namespaces but not in kube-system .
Verify everything using kubectl auth can-i .
![Screenshot (1230)](https://user-images.githubusercontent.com/93229250/235271660-709cfd9d-62b1-48fa-9461-9b0e2d07b31b.png)
![Screenshot (1231)](https://user-images.githubusercontent.com/93229250/235271665-3975c2eb-d4c0-497e-bb54-92c404c9c10f.png)

HELM
Using helm install apache chart on your system
![Screenshot (1234)](https://user-images.githubusercontent.com/93229250/235276855-09da92f5-3f57-4751-ac81-c7732dd47204.png)
![Screenshot (1235)](https://user-images.githubusercontent.com/93229250/235276858-4ecffce7-13bc-44c8-93bc-b1dfa50da21c.png)
