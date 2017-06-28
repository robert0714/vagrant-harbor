# vagrant-harbor
Usage
========================

<br/>
ansible-playbook  /vagrant/ansible/harbot.yml  -i /vagrant/ansible/hosts/sit
<br/>

2016.12.21
====================
centos 7.2升級到7.3之後，既有的centos/7 box images synchronized folder 會失敗，改成bento/centos-7.2,擇發生public_network不能正常自動啟動，而要手動去 將/etc/sysconfig/network-scripts/ifcfg-eth1(ifcfg-enp0s8)給予啟動 （ ifup  eth1或是ifup  enp0s8 ）
