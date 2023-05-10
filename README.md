# kubernetes-troubleshoot

  # not pulled image kubernetes in kubeadm init
  ---
  https://computingforgeeks.com/manually-pull-container-images-used-by-kubernetes-kubeadm/
  sudo kubeadm config images list
  sudo kubeadm config images list --image-repository docker.io
  sudo kubeadm config images list --kubernetes-version latest
  sudo kubeadm config images pull
  sudo kubeadm config images pull --image-repository docker.io
  sudo docker login
  ---
  
  
