
# zcasbin_mgo
> bearer 认证

## 获得 zcasbin_mgo
` go get -u github.com/zlyuancn/zcasbin_mgo `

## 导入 zcasbin_mgo
```go
import "github.com/zlyuancn/zcasbin_mgo"
```

## 示例

```go
    p := zcasbin_mgo.NewAdapter("127.0.0.1:27017")
    e, _ := casbin.NewEnforcer("examples/rbac_model.conf", p)
```
