## <a name="troubleshoot"></a>疑难解答

### <a name="cookies-and-site-data"></a>Cookie 和网站数据

Cookie 和站点数据可能会在应用更新中保留，并干扰测试和故障排除。 在更改应用代码、使用提供程序更改用户帐户或提供程序应用配置更改时清除以下内容：

* 用户登录 Cookie
* 应用 Cookie
* 缓存和存储的站点数据

防止挥之不去的 Cookie 和站点数据干扰测试和故障排除的一种方法是：

* 使用浏览器进行测试，您可以配置该浏览器可在每次关闭浏览器时删除所有 Cookie 和站点数据。
* 关闭对应用、测试用户或提供程序配置的任何更改之间的浏览器。

### <a name="run-the-server-app"></a>运行服务器应用

测试和排除托管 Blazor 应用时，请确保从 **"服务器"** 项目运行该应用。 例如，在 Visual Studio 中，在使用以下任一方法启动应用之前，请确认服务器项目在**解决方案资源管理器**中突出显示：

* 选择“运行”按钮。****
* 使用**从** > 菜单**中调试开始调试**。
* 按 <kbd>F5</kbd>。
