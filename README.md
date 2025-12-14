# ClassIsland 2 插件模板

这是用于快速创建 ClassIsland 插件的模板，适用于 .NET CLI 和 JetBrains Rider 等支持的开发工具。在使用之前，请先根据文档[设置开发环境](https://docs.classisland.tech/dev/get-started/development-plugins.html)，并仔细阅读[关于插件开发的文档](https://docs.classisland.tech/dev/)。

ClassIsland 插件功能目前仍在不断更新中，请记得更新模板。

## 前置条件

- 已按照[文档设置开发环境](https://docs.classisland.tech/dev/get-started/development-plugins.html)

## 安装

1. 运行以下命令安装模板包
    ``` bash
    dotnet new install ClassIsland.PluginTemplate.Packaging
    ```
2. 大功告成！您现在可以在 .NET CLI 中通过以下命令行创建项目，或者在 JetBrains Rider 中选择此模板创建项目了！
    ``` bash
    # MyPlugin 是您的插件项目名称
    mkdir MyPlugin
    cd MyPlugin
    dotnet new cipx-template -n MyPlugin
    ```

接下来您可以继续阅读[开发文档](https://docs.classisland.tech/dev/)，了解插件开发的更多细节。

## 许可证

本项目基于 [MIT License](LICENSE) 获得许可。
