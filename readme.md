```
[root@localhost1 goscp]# go build
[root@localhost1 goscp]# ./goscp -src /root/gitlab/goscp/go.mod -dst root@192.168.42.128:/root/123456.mod -p 123456
/root/123456.mod

[root@localhost1 goscp]# ./goscp -h
Usage of ./goscp:
  -P int
    	Port (default 22)
  -dst string
    	目的地址 (default "/root/test.txt")
  -p string
    	密码 (default "123456")
  -src string
    	源地址 (default "root@127.0.0.1:/root/test.txt")

```