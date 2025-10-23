Kubernetes Handy Commands
1. Login to k8s Mirantis Framework cluster and download the env file for your profile.
2. Source the env file to add the env variables
3. kubectl config get-contexts  --> displays the available contexts
4. kubectl config use-context <context_name> --> Use the current context
5. kubectl config set-context --current --namespace=<namespace_name> --> switch to working namespace
6. kubectl describe pod <podname>
7. kubectl log --since-time='2025-10-23 15:00:00Z' <podname> > /logfilename
8. kubectl get pods/svc/deployment
9. kubectl scale <dpl_name> --replicaset=0
10. 
