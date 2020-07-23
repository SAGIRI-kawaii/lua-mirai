# 好友对象 (MiraiFriend)

## 属性

| 属性名 | 类型     | 描述         |
| ------ | -------- | ------------ |
| id     | Integer  | 好友的qq号码 |
| bot    | MiraiBot | bot对象      |

## 方法

### getNick (获取昵称)

#### 返回值：

| 类型   | 描述 |
| ------ | ---- |
| String | 昵称 |


### sendMsg (发送消息)

#### 参数列表：

| 参数 | 类型     | 描述     |
| ---- | -------- | -------- |
| msg  | MiraiMsg | 消息对象 |


### getAvatarUrl (获取头像地址)

#### 返回值：

| 类型   | 描述             |
| ------ | ---------------- |
| String | 获取到的头像地址 |


### isActive (是否在线)

#### 返回值：

| 类型    | 描述     |
| ------- | -------- |
| Boolean | 是否在线 |


# 