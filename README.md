# WpfD3D11Runtime Samples

[WpfD3D11Runtime](https://www.nuget.org/packages/WpfD3D11Runtime) 的使用示例。该包以一条 `PackageReference` 将 .NET 10 WPF 应用的渲染后端替换为 D3D11，并提供实验性彩色 Emoji（默认关闭）。它是 QuickerOrg 维护的第三方运行时，不是微软官方产品。

Samples for [WpfD3D11Runtime](https://www.nuget.org/packages/WpfD3D11Runtime), a third-party package that switches a .NET 10 WPF app's rendering backend to D3D11 with one `PackageReference`, plus experimental color Emoji (off by default). It is maintained by QuickerOrg and is not an official Microsoft product.

| 示例 / Sample | 内容 / What it shows |
| --- | --- |
| [WpfD3D11Demo](WpfD3D11Demo/README.md) | 渐变、旋转、阴影、半透明与模块诊断；`--emoji` 彩色 Emoji 页面；自动 selftest / Gradients, rotation, shadows, transparency, module diagnostics; `--emoji` color Emoji scene; automated selftest |

用 Visual Studio 打开 `WpfD3D11Runtime-Samples.slnx` 后直接运行，会出现主对话框，可从中打开各项测试；或在 `WpfD3D11Demo` 目录执行 `dotnet run -r win-x64`。

Open `WpfD3D11Runtime-Samples.slnx` in Visual Studio and run it to get the main dialog, or run `dotnet run -r win-x64` in `WpfD3D11Demo`.

运行时源码：[QuickerOrg/wpf](https://github.com/QuickerOrg/wpf) 分支 `quicker/d3d11-facade`。

Runtime source: [QuickerOrg/wpf](https://github.com/QuickerOrg/wpf), branch `quicker/d3d11-facade`.
