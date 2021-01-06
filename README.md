# Go-Cms

### 基于Beego实现CMS

## 功能列表

### 前台功能

- 个人信息展示
  - 昵称展示
  - 签名展示
  - 个人头像展示
- 最新随笔
  - 展示近期发布的10篇文章
- 最新分类
  - 根据文章标签分类
- 友情链接
- 阅读排行榜
  - 展示阅读量排名前10的文章
- 文章列表(服务端分页)
- 正在开发中......
### 后台功能

- 文章标签模块
  - 添加标签
  - 编辑标签
  - 冻结/解冻标签
  - 标签内文章量统计

- 文章模块
  - 添加文章
  - 编辑文章
  - 冻结/解冻文章

- 管理员模块
  - 添加管理员
  - 超级/普通管理员
  - 密码修改
  - 冻结/解冻管理员

- 其它
  - 个人简介模块
    - 添加个人简介
    - 编辑个人简介
    - 解冻/冻结个人简介

  - 友情链接模块
    - 添加友情链接
    - 编辑友情链接
    - 冻结/解冻友情链接
    
- 正在开发中......
## Install

1. 把项目拉到本地   

   `git clone https://github.com/Echo-Mr-Pengw/Go-Cms.git`
   
2. 导入数据库 `go_cms.sql`
  
3. 进入`Go-Cms`目录，运行`bee run`   
   ```
   cd Go-Cms
   bee run
   ```

4. 前台访问地址

   `http://localhost:8181/home`

5. 后台访问地址

   `http://localhost:8181`， 后台初始化账户：admin，密码：123456
   
## End
  欢迎👏提出问题和建议，本项目是基于在学习Go后的实践。如果客官你有什么开源项目需要志同道合者一起加入，我有意愿一起加入。我的微信：Weipeng_dream，加好友时，请备注：github
