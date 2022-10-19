```
 1989  kubectl  get pods -n kube-system -o wide
 1990  systemctl status kubelet
 1991  cd /etc/kubernetes/manifests/
 1992  ls
 1993  vim kube-apiserver.yaml
 1994  ls
 1995  cd
 1996  kubectl  get pods
 1997  exit
 1998  kubectl config view
 1999  cat /etc/kubernetes/admin.conf
 2000  kubectl cluster-info
 2001  kubectl version
 2002  kubectl api-versions
 2003  kubectl api-resources
 2004  ls
 2005  cd docker-k8s-ericsson-17-Oct-2022/
 2006  ls
 2007  cd 02-K8s/
 2008  ls
 2009  cd 01-FirstApp/
 2010  ls
 2011  cat nginx.yaml
 2012  kubectl  get api-versions
 2013  kubectl   api-versions
 2014  cat nginx.yaml
 2015  ls
 2016  curl -k https://172.31.0.100:6443
 2017  kubectl  get pods
 2018  kubectl proxy --address='172.31.0.100' --port=8080 --accept-hosts='.' --accept-paths='.' &
 2019  kubectl  get pods
 2020  kubectl  get pods -o wide
 2021  cat /root/.kube/config
 2022  kubectl  get proxy
 2023  ps -ef | grep -i proxy
 2024  kill -9 18717
 2025  ps -ef | grep -i proxy
```
