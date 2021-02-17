# How to create a static pod

1. Create a pod definition file and place that in in 
``/etc/kubernetes/manifests``
   
# Ways for check static pod configuration
1. look for kubelet service file configuration and check for `--config` option.
it can be using a specific directory path or will be using a config files where all static pod config file location might specified.
   

2. If the file is named as kubeconfig.yml, then look for `staticPodPath:` for Static pod configuration