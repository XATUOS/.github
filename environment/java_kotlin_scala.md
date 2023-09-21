# 搭建 Java / Kotlin / Scala 开发环境

## 一、下载并安装 JDK

1. 打开 [Microsoft OpenJDK 的构建页面](https://www.microsoft.com/openjdk)
2. 点击页面上的 `Download（下载）`
3. 选择 `OpenJDK 17`
4. 下载对应你 CPU 架构和操作系统的构建
   > 通常情况下 Windows 系统应下载 `Windows` `x64` `msi`
5. 打开下载的文件，点击 `下一步`
6. 勾选 `我接受许可协议中的条款`，点击 `下一步`
7. 选择你要安装的位置，点击 `下一步`
8. 点击 `安装`
9. 点击 `完成`
10. 按下 `Win` + `R` 键，输入 `cmd` ，按下回车
11. 输入 `java -version` ，若屏幕上打印出 Java 版本即为安装成功

## 二、下载并安装 IntelliJ IDEA

1. 打开 [JetBrains IntelliJ IDEA 页面](https://www.jetbrains.com/idea/)
2. 点击页面上的 `Download（下载）`
3. 选择你的操作系统并点击 `Download（下载）`
4. 打开下载的文件，点击 `Next >（下一步）`
5. 选择安装目录，点击 `Next >（下一步）`
6. 勾选全部选项，点击 `Next >（下一步）`
7. 不作任何修改，点击 `Next >（下一步）`
8. 点击 `Install（安装）` ，耐心等待安装完成
9. 点击 `Finish（完成）` ，结束安装

## 三、登录 JetBrains 账号

1. 打开安装好的 `IntelliJ IDEA`
2. 勾选弹出页面中的选项并点击 `Continue（继续）`
3. 点击 `Don't Send（不要发送）`
4. 点击 `Log In to JetBrains Account（登录 JetBrains 账号）`
5. 在浏览器中登录
6. 点击 `Activate（触发）`
7. 点击 `Continue（继续）`

## 四、安装 IntelliJ IDEA 插件（建议）

1. 打开安装好的 `IntelliJ IDEA`
2. 点击 `Plugins（插件）`
3. 在 `Marketplace（市场）` 中搜索 `Chinese`
4. 选中 `Chinese ​(Simplified)​ Language Pack / 中文语言包` ，点击 `Install（安装）`
5. 耐心等待安装完成，然后点击 `Restart IDE（重新启动IDE）` ， 点击 `Restart（重新启动）`
6. 完成

## 五，新建项目

1. 打开安装好的 `IntelliJ IDEA`
2. 点击 `新建项目`
3. 选择 `新建项目`
4. 填写项目名称，项目位置
5. 勾选 `创建 Git 仓库`
6. 语言选择 `Java / Kotlin / Scala`
7. 构建系统选择 `Gradle`
8. Gradle DSL 选择 `Groovy`
9. JDK 选择步骤一中安装的 JDK
10. 勾选添加示例代码
11. 打开高级设置，将组ID设置为 `io.github.yourusername（例如：io.github.gugle）`，工件ID与项目名称相同
12. 点击 `创建`
13. 等待右下角项目加载完毕，点击顶部的 ![Run Icon](./images/run.png) 图标