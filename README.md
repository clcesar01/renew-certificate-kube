# renew-certificate-kube

yum install -y git \
git clone https://github.com/yuyicai/update-kube-cert.git \
cd update-kube-cert/ \ 
chmod 755 update-kubeadm-cert.sh \ 
./update-kubeadm-cert.sh master \

kubeadm alpha certs check-expiration \

systemctl restart kubelet 




