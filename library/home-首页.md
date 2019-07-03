# api-wiki
### 1.	提交用户名称
```
xxx信息科技有限公司
```
### 2.	申请所需接口（* 代表所有接口）

| 模块     | 接口 | url                  |
| -------- | ---- | -------------------- |
| 设备管理 | 添加 | devicesmanage/create |
| 设备管理 | 删除 | devicesmanage/delete |
| 设备管理 | 查询 | devicesmanage/get    |

### 3.	获取用户key（代表用户）和token（代表用户权限）
```
key=a29193b764ce4f718789e43720336b3c
```
```
token=15e1598ef27d44fb99dc48b7de0ed9b0
```
### 4.	后续所有请求须携带用户key和token
```
devicesmanage/get?key=a29193b764ce4f718789e43720336b3c&token=15e1598ef27d44fb99dc48b7de0ed9b0
```


