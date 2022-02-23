# AppXLauncher

[ysc3839 commented on Jul 18, 2021](https://github.com/ysc3839/FontMod/issues/70#issuecomment-882069692)

> 如果你在使用微软商店的 Telegram ([链接](https://www.microsoft.com/store/productId/9NZTWSQNTD0S))，可以试试我的项目 [AppXLauncher](https://github.com/ysc3839/AppXLauncher)。
> 在[这里](https://github.com/ysc3839/AppXLauncher/actions/runs/1042583200)下载 exe，把 `FontMod64.dll` 放在 exe 同目录下，然后创建 `AppXLauncher.json` 文件并写入以下内容：
> 
> ``` json
> {
>     "PackageFamilyName": "TelegramMessengerLLP.TelegramDesktop_t4vj0pshhgkwm",
>     "AppId": "Telegram.TelegramDesktop.Store",
>     "InjectDll": "FontMod64.dll",
>     "Persistent": true,
>     "KillRunning": false
> }
> ```
> 
> 当 `Persistent` 开启时，在首次运行 `AppXLauncher.exe` 之后，你可以直接在开始菜单中打开 Telegram，不需要再打开 `AppXLauncher.exe`。
> 注意上述文件不能移动或删除。如果你移动了之后打不开 Telegram，或者想卸载，把 `Persistent` 改为 `false` 后运行一次 `AppXLauncher.exe` 即可。
