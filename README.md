# opensvip-plugin-vpr-build-release
仓库 [TwoCreepers/opensvip-plugin-vpr](https://github.com/TwoCreepers/opensvip-plugin-vpr) 的二进制构建文件存放点，同时用于推送更新

## 仓库结构

- `market/`: 存放用于推送更新的 `toml` 文件（`plugin-vpr.toml`）
- `README.md`: 仓库说明文件。
- `LICENSE`: 仓库许可证文件。

## 自动构建

该仓库由 [opensvip-plugin-vpr](https://github.com/TwoCreepers/opensvip-plugin-vpr) 的 Github Actions 于有符合条件的Tag时自动测试并构建并推送到该仓库。  
该仓库基本不会有任何来自手动构建的二进制文件，手动构建的二进制文件应发布在[原仓库](https://github.com/TwoCreepers/opensvip-plugin-vpr)的发行版中。~~虽然原仓库大概没有发行版，作者真的很懒欸~~  

## issue与pr

不要在该仓库提issue与pr，请在[原仓库](https://github.com/TwoCreepers/opensvip-plugin-vpr)中提issue与pr，该仓库不接受任何issue与pr。
