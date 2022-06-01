<h1>E-commerce Backend Deployment on kubernetes</h1><br>

This project is about  kubernetes deployment for E-commerce backend.
The E-commerce backend project link (https://github.com/purbo75/E-Commerce-site-BackEnd-with-Node-js.git )
<br>
 
********
<h2>Tools</h2>
<ol>
	<li>Docker</li>
	<li>Kubernetes</li>
	<li>Minikube</li>
	
</ol><br>
*********
<p> To install minikube : </P><br>
	sudo apt-get update<br>
	curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 <br>
	sudo install minikube-linux-amd64 /usr/local/bin/minikube <br>
	minikube start
<br>
***********

	
The commands to run the deployment on Ubuntu - <br>

To start minikube: <br>
	minikube start<br>

To enable ingress-nginx:<br>
	kubectl addon enable ingress-inginx<br>
		
	kubectl apply -f FileName<br>

**********
kubectl command-<br>

To get the pods information<br>
	kubectl get pods<br>
To get the service information<br>
	kubectl get service<br>
To get the namespace information<br>
	kubectl get ns<br>
To get the pod's  log<br>
	kubectl logs pod_name<br>

