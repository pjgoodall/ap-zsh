# ap-zsh
ansible-pull repository for install and configure of zsh with utilities

## to execute

```
sudo ansible-pull \
    -U https://github.com/pjgoodall/ap-zsh.git \
    -C origin/main
```
## the plan

Instead of repeatedly, partially configuring cli environments for working in containers and virtual machines, create an ansible-pull repository on github to allow basic, comfortable zsh cli environments for establishing development.

## commentary

## references

1. [Configuring Zsh Without Dependencies](https://thevaluable.dev/zsh-install-configure-mouseless/)
2. [ansible-pull official documentation](https://docs.ansible.com/ansible/latest/cli/ansible-pull.html#ansible-pull)

## log
## pre ansible-pull
1. update `.autoenv.zsh` to reflect lxc project specific defaults. 
2. create container and make snapshot `zero`
3. establish ssh shell connection using `ssh-agent` authority

## install zsh package and basic configuration:w
