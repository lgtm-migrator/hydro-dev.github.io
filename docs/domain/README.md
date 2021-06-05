# 域管理员文档

## 简介

域，可以理解为 OJ 中的 OJ。  
用户有权限为自己创建多个域。（取决于用户组设定，需要 PRIV_CREATE_DOMAIN 权限）。
同一 Hydro 实例上的多个域间完全独立，仅用户信息相通（您在一个 Hydro 实例上注册账户后，在该实例的所有域中均有效）。  

## 创建域

登录账号后，在“我的”选项卡中找到“我的域”，并点击“创建域”，填入以下信息：

- ID： 每个域有一个唯一的 ID，将会在域 URL 中体现。**创建后无法修改。**
- 名称： 域的名字，创建后可以更改。
- 公告： 域主页上显示的公告，创建后可以更改。
- avatar： 域头像，与用户头像同理，可以使用 `gravatar:email` 或 `qq:id` 或 `github:name` 的格式添加。将会在“我的域”界面内显示。

创建域后，您将在此域中拥有管理员权限，可以在域内进行添加题目/创建比赛等操作。

## 访问控制

**未登录用户将默认使用 `guest` 权限，登录用户将默认使用 `default` 权限。**  
所以将一个用户的权限设为 `default` 和将用户移出该域是等价的。

## 创建比赛

若您想要创建比赛，您可以在“比赛”选项卡中点击“创建一个比赛”按钮，并填写：

- 规则；
- 标题；
- 开始日期，时间；
- 持续时间；
- 题目： 此比赛包含的题目的 **ID**，若有多个则用逗号分隔；
- 内容： 该比赛的详细介绍；
- 是否 Rated： 该比赛是否会改变参加选手的 RP。

设置完后可点击“创建”按钮创建比赛。

## 创建作业

若您想要创建作业，您可以在“作业”选项卡中点击“创建作业”按钮，并填写：

- 标题；
- 开始日期、时间；
- 结束日期、时间；
- 最长延期；
- 延期递交扣分规则；
- 题目：此作业包含的题目的 **ID**，若有多个则用逗号分隔；
- 内容：该作业的详细介绍。

之后点击“创建”按钮进行创建。

## 初始化讨论节点

您可以在“管理域”选项卡中点击“初始化讨论节点”按钮初始化讨论节点。