---
title: 'github RPC failed; curl 56 OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 10054'
date: 2019-09-21 22:06:34
categories: github
---
出现此问题有可能是上传大小限制：
执行如下命令
``` bash
$ git config http.postBuffer 524288000
```
524288000算法：10241024500
出现如下错误：curl 56 OpenSSL SSL_read:SSL_ERROR_sysCALL
执行：
``` bash
$ git config http.sslVerify “false”
```