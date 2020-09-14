# 如何安装开源协作机器人

本次特训营使用一个 GitHub 机器人进行各位的项目管理工作，安装该机器人可以帮助你进行项目的工作量统计、文件合规检查等。

## 安装机器人

本项目使用了 [oss-mentor-bot](https://github.com/apps/oss-mentor-bot) 机器人作为教学机器人，请参考[该图](https://frank-cdn.opensource-service.com/image/gif/install-robot.gif)安装机器人。

安装步骤为

- 打开[机器人主页](https://github.com/apps/oss-mentor-bot)
- 点击 `Configure` 按钮
- 选择要安装的账号或组织，即你的项目做在的账号或组织
- ***选择 `Only select repositories`，并在下拉菜单中选择要安装的项目，切记不要在所有项目上安装***
- 点击 `Install` 进行安装即可 

## 机器人配置

该机器人是通过每个项目自己仓库中的配置文件来定制配置内容的，请将本仓库中的[配置文件样例](https://github.com/kaiyuanshe/Open-source-training-camp/blob/master/.github/hypertrons.json) 中的内容放在你的项目中相同文件中，内容不变。

## 机器人校验

若安装成功，则该机器人每日北京时间 22 点会以 PR 形式向项目发送一个活跃度统计报告。

## 其他配置

另外安装机器人后可以通过一些 URL 获取项目中的文件合规情况。

以 [`hu-qi/30-days-of-react-native`](https://github.com/hu-qi/30-days-of-react-native) 项目为例，可以通过如下的 URL 获取到文件合规情况

![license](http://github.zhangqx.com/file-checker/github/hu-qi/30-days-of-react-native?path=LICENSE)
![readme](http://github.zhangqx.com/file-checker/github/hu-qi/30-days-of-react-native?path=README.md)
![contributing](http://github.zhangqx.com/file-checker/github/hu-qi/30-days-of-react-native?path=CONTRIBUTING.md)
![coc](http://github.zhangqx.com/file-checker/github/hu-qi/30-days-of-react-native?path=CODE_OF_CONDUCT.md)
![codestyle](http://github.zhangqx.com/file-checker/github/hu-qi/30-days-of-react-native?path=CODE_STYLE.md)
![pulltemplate](http://github.zhangqx.com/file-checker/github/hu-qi/30-days-of-react-native?path=.github/PULL_REQUEST_TEMPLATE.md)

将这些 badge 的 Markdown 文本拷贝到你自己的项目 README 中，并替换 URL 中的仓库名为自己的仓库名即可。
