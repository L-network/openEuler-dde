# 标题：控制中心不支持修改非自身帐户的自动登录状态
* 优先级：3
# 前置条件：系统中存在非root帐户TEST、openeuler
| 编号 | 步骤                                | 预期                                                         |
| ---- | :---------------------------------- | ------------------------------------------------------------ |
| 1    | root帐户图形化界面登入系统，并打开“控制中心-帐户”下openeuler帐户三级菜单 | 成功打开 |
| 2    | 单击“自动登录”button | “自动登录”button质灰，单击无任何反应 |
| 3    | TEST帐户图形化界面登入系统，并打开“控制中心-帐户”下openeuler帐户三级菜单 | 成功打开 |
| 4    | 单击“自动登录”button | “自动登录”button质灰，单击无任何反应 |

