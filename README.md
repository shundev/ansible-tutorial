# Ansible tutorial

Basic on this article (Japanese)

<https://qiita.com/t_nakayama0714/items/fe55ee56d6446f67113c>

## Getting started

On Host

```
git clone <this_repo>
vagrant ssh controller
```

On controller VM

```
su # password is "vagrant"
yum localinstall http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm
yum install ansible
```

