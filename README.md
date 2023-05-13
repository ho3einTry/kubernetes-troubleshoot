# kubernetes-troubleshoot

  ## not pulled image kubernetes in kubeadm init 
 [manually-pull-container-images-used-by-kubernetes-kubeadm](https://computingforgeeks.com/manually-pull-container-images-used-by-kubernetes-kubeadm) </br>
 ---
    sudo kubeadm config images list
    sudo kubeadm config images list --image-repository docker.io
    sudo kubeadm config images list --kubernetes-version latest
    sudo kubeadm config images pull
    sudo kubeadm config images pull --image-repository docker.io
    sudo docker login
  ---

  
  ## kube-fledged
    [kube-fledged](https://github.com/senthilrch/kube-fledged)</br>
---
    A kubernetes operator for creating and managing a cache of container images directly on the cluster worker nodes,
    so  application pods start almost instantly
---
