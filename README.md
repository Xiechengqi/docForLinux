# docForLinux
A terminal doc command for linux, it can easily collect yourself commands notes

## Install

```shell
$ wget https://github.com/Xiechengqi/docForLinux/archive/latest.tar.gz -O /tmp/doc.tar.gz
$ mkdir -p /opt/doc
$ tar zxvf /tmp/doc.tar.gz -C /opt --strip-components=1
$ sudo bash /opt/doc/install
```

## Usage

![doc](https://user-images.githubusercontent.com/26536442/97070860-3802e880-160e-11eb-8cd5-67bd3b5fd423.png)

```shell
$ doc ansible
```

![doc-ansible](https://user-images.githubusercontent.com/26536442/97070832-0c7ffe00-160e-11eb-9b67-3e65755611a1.png)

```
$ doc ansible mvn [...]
```

![](https://user-images.githubusercontent.com/26536442/97070700-0f2e2380-160d-11eb-9367-c3ab85e01515.png)

```
# add new doc file
$ vidoc docker
```

![doc-add](https://user-images.githubusercontent.com/26536442/97070989-69c87f00-160f-11eb-866d-860c43292453.png)

