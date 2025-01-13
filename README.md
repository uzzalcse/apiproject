### Install the bee command 


```
go install github.com/beego/bee/v2@latest

```

### Add the directory to your path 
### For Mac/Linux

```
export PATH=$PATH:$HOME/go/bin

```
### For windows
```
$env:PATH += ";C:\Users\uzzal\go\bin"

```

### Create new Project

```
bee new myproject 

```
### Go project directory

```
cd myproject

```
### Download required dependencies
```
go mod tidy

```

### Run the project

```
bee run
```

### Install Swagger for Beego 

```
go get -u github.com/beego/beego/v2/server/web/swagger





```

#### install swagger cmd

```
go install github.com/swaggo/swag/cmd/swag@latest
```

### Beego docs 



https://www.koyeb.com/docs/deploy/beego

https://beego.w3engineers.com/beego.vip/docs/install/bee.html

https://beego.wiki/docs/mvc/controller/config/

