#Learing Go

### 要注意GOPATH的环境变量的设置

### go install 感觉可以解决pkg编译，main主函数入口

### go test -v可以输出详细的单元测试信息。像t.Log这些函数会被输出。

### 在目录下创建一个test目录，用于编写测试用例，这样目录看起来会更合理，有条理。这里说的目录是指src/下的各个子目录。

### 压力测试的方法论已经有很多了，所以这里先不关注Go自带的压力（性能）测试。

### 交叉编译, 设置以下3个环境变量
	CGO_ENABLED=0
	GOOS_=linux
	GOARCH=amd64

