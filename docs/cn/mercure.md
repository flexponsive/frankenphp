# 实时

FrankenPHP 带有一个内置的 Mercure 集线器！
Mercure 允许将事件实时推送到所有连接的设备：它们将立即收到 JavaScript 事件。

无需JS库或SDK！

![Mercure](https://mercure.rocks/static/main.png)

要启用 Mercure 中心，请按照 [Mercure 网站](https://mercure.rocks/docs/hub/config)中的说明更新`Caddyfile`。

要从您的代码中推送 Mercure 更新，我们推荐 [Symfony Mercure Component](https://symfony.com/components/Mercure)(您不需要 Symfony 全栈框架来使用它)。
