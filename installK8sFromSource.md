# Part 1. Prerequisites

* In each servers (or machines, VMs, ...), configure `[IP address - hostname]` pair.

```# vim /etc/hosts```

```
192.168.254.101 my01
192.168.254.102 my02
192.168.254.103 my03
192.168.254.104 my04
```

* (Optional) Install some packages
  - Ubuntu: `# apt-get install vim build-essential htop aptitude -y`
  - CentOS: `# yum install vim htop -y`

# Part 2. Build from source

* It is possible to build once and make many master & worker nodes using built files.

# Part 3. Place binaries and config files

# Part 4. Create new cluster on k8s master node (candidate)

# Part 5. Join k8s worker node (candidate) to the cluster
