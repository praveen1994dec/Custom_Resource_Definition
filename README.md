# Custom_Resource_Definition
Go to this URL: https://github.com/praveen1994dec/Custom_Resource_Definition.git

kubectl apply -f ./crd.yaml

Once the CRD is registered, verify that by running the kubectl get crds command. Or we could use kubectl api-resources | grep myplatform instead.

Creating the custom resource
kubectl apply -f ./cr.yaml

kubectl get myp
