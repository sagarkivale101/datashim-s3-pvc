A Kubernetes Framework to provide easy access to S3 and NFS Datasets within pods. Orchestrates the provisioning of Persistent Volume Claims and ConfigMaps needed for each Dataset. 

https://github.com/datashim-io/datashim/tree/master

https://www.youtube.com/watch?v=gGT5-asERvc&t=144s

steps

---

kubectl create ns dlf

kubectl apply -f https://raw.githubusercontent.com/datashim-io/datashim/master/release-tools/manifests/dlf.yaml

kubectl apply nginx.yaml -n dlf


---

alternate solution

https://github.com/yandex-cloud/k8s-csi-s3