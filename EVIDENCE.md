# Lab 5 Evidence

## GitHub Actions

Successful GitHub Actions workflow run:

![Successful GitHub Actions Run](evidence/github-actions-success.png)

## Docker Hub Multi-Architecture Image

Docker Hub image showing support for both `linux/amd64` and `linux/arm64`:

![Docker Hub Multi-Architecture Image](evidence/dockerhub-multiarch.png)

## Kubernetes Resources

Output of `kubectl get all,pvc` showing the database pod, two web pods, services, deployments, and bound persistent volume claim:

![kubectl get all,pvc](evidence/kubectl-get-all-pvc.png)

## Experiment 2 - Data Persistence

The note remained in the database after the database pod was deleted and recreated:

![Experiment 2 Data Persistence](evidence/experiment2-data-persistence.png)

## Experiment 3 - Load Balancing

Requests were served by multiple web pods, as shown by the different `served_by` values:

![Experiment 3 Load Balancing](evidence/experiment3-load-balancing.png)

## Rolling Update

Output of `kubectl rollout history deployment/web` after performing the rolling update:

![Rollout History](evidence/rollout-history.png)