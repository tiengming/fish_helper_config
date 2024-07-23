## 闲鱼猪手配置
- 本仓库存储原作者在停止使用前的最后一次提交
- 不欢迎任何倒卖、滥用、滥改
- 转载、Fork 请不要去除原作者信息（包括模块本体作者和我），即使修改了也不要直接 PR 到原仓库，球球了
![image.png](https://s2.loli.net/2023/04/18/63ayU8Tz2HvGs5V.png)

## 适配版本
- 7.1.30 ~ 7.8.80

## Config 解密方法

- https://www.cnblogs.com/azwhikaru/p/17045056.html

## 如何定制
- fork 本仓库
- 下载 [1.3.9_sub.apk](https://github.com/azwhikaru/fish_helper_config/blob/main/1.3.9_sub.apk)
- 使用任意反编译工具打开，例如 [MT管理器](https://www.coolapk.com/apk/21048)
- 编辑 classes.dex，全局搜索 `REPLACE_ME_TO_YOUR_REPO` 
- 将 `REPLACE_ME_TO_YOUR_REPO` 部分替换为~~你的仓库地址~~ jsDelivr 地址
- 回编译并签名

## 使用 jsDelivr
- Release 版本已使用 jsd.cdn.zzko.cn 镜像，第三方镜像不保证稳定性，如有必要还请 Fork 后使用自己的地址
- 示例：
  - https://cdn.jsdelivr.net/gh/用户名/仓库名@分支/文件名
  - https://gitee.com/tpnet/fish-helper-data/raw/master/config-a40.json -> https://raw.githubusercontent.com/azwhikaru/fish_helper_config/main/config-a40.json ->
  - https://cdn.jsdelivr.net/gh/azwhikaru/fish_helper_config@main/config-a40.json √

## 懒人
- 如果不想自己改，可以去 Release 找我改好的
