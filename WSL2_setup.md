# WSL2 set on Windows Desktop PC
This script is MEMO of installing and setup for WSL2.

## Reference
- [wsl2をインストールしてwindows上でlinuxを使いこなそう](https://www.geekfeed.co.jp/geekblog/wsl2-with-windows10-insider-preview-build)

## Requirement
- Windows10 Home (version ≧ 2004)
- Linux distribution  (Ubuntu, CentOS, ...)

## setup process
1. Utilize WSL on windows system
1. Windows update (version ≧ 2004)
1. Install several distribution (Ubuntu, CentOS, ...)
1. Valid virtualize function (on powershell)
1. reboot
1. call command (on powershell)
1. check a version of the distributions & change version

## Note
- error1

```
PS C:\WINDOWS\system32> wsl --set-version CentOS7 2
変換中です。この処理には数分かかることがあります...
WSL 2 との主な違いについては、https://aka.ms/wsl2 を参照してください
WSL 2 を実行するには、カーネル コンポーネントの更新が必要です。詳細については https://aka.ms/wsl2kernel を参照してください     
```

[最新の WSL2 Linux カーネル更新プログラム パッケージをダウンロードすれば解決する。](https://docs.microsoft.com/ja-jp/windows/wsl/wsl2-kernel)

- 
- 
