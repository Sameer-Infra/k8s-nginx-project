👨‍💻 Author

Sameer | DevOps Engineer (Aspiring)

GitHub: Sameer-Infra

Kubernetes Nginx Project 🚀

📌 Description

This project demonstrates deployment of an Nginx application using Kubernetes.

🛠️ Resources Used

- Namespace
- Deployment
- Service (ClusterIP)
- Job
- CronJob
- DaemonSet
- StatefulSet

📂 Files

- namespace.yaml
- deployment.yaml
- service.yaml
- job.yaml
- cronjob.yaml
- daemonset.yaml
- statefulset.yaml

⚙️ Steps to Run

kubectl apply -f namespace.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

📊 Verify

kubectl get pods -n nginx
kubectl get svc -n nginx

✅ Result

Nginx application successfully deployed and running in Kubernetes cluster.
