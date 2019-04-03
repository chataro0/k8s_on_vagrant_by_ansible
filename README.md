# Kubernetes Setup Using Ansible and Vagrant

## ソース

[Kubernetes Setup Using Ansible and Vagrant](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

## 変更点

- 端末がWindowsマシンだったので、provisionerをansible_localに変更
- eth1のIPがInternal IPとして表示されるように/etc/default/kubeletに設定追加
- calicoの追加コマンドを変更