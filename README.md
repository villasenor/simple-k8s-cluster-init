[![Travis Build Image]][Travis Build Status]

# simple-k8s-cluster-init

Quick and simple Ansible playbook to
initialize fresh Linux machines
and get them ready for Kubernetes.

Once this playbook has run, you're
ready for `kubeadm init`

**Assumptions:**

- The host is running Ubuntu 18.04+
- SSH is already enabled
- You have a user account on the machine
- Python is available on the target machine

Inspired by [The Myth of the Genius Programmer][Genius Programmer Book], I've started open sourcing things instead of waiting for perfection, and I encourage you to do so as well!

[Travis Build Status]: https://travis-ci.org/villasenor/simple-k8s-cluster-init
[Travis Build Image]: https://travis-ci.org/villasenor/simple-k8s-cluster-init.svg?branch=master
[Genius Programmer Book]: https://www.oreilly.com/library/view/team-geek/9781449329839/ch01.html