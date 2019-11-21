[![pipeline status](https://api.travis-ci.org/bityuan/bityuan.svg?branch=master)](https://travis-ci.org/bityuan/bityuan/)
[![Go Report Card](https://goreportcard.com/badge/github.com/bityuan/bityuan)](https://goreportcard.com/report/github.com/bityuan/bityuan)

# 基于 chain33 区块链开发 框架 开发的 CIC公有链系统

#### 编译

```
git clone https://github.com/cichain-vip/cichian.git $GOPATH/src/github.com/cichain-vip/cichian
cd $GOPATH/src/github.com/cichain-vip/cichian
go build -i -o cic
go build -i -o cic-cli github.com/cichain-vip/cichian/cli
```

#### 运行

拷贝编译好的cic, cic-cli, cichain.toml这三个文件置于同一个文件夹下，执行：

```
./cic -f cichain.toml
```


