# $\LaTeX$の導入 (Windows)

## 目次

- [$\\LaTeX$の導入 (Windows)](#latexの導入-windows)
  - [目次](#目次)
  - [$\\LaTeX$ とは](#latex-とは)
    - [動作環境](#動作環境)
  - [環境構築](#環境構築)
    - [$\\TeX$ Liveのインストール](#tex-liveのインストール)

## $\LaTeX$ とは

$\LaTeX$ とは, Leslie B. Lamport によって開発されたテキストベースの組版処理システムである. 電子組版ソフトウェア $\TeX$ にマクロパッケージを組み込むことによって構築されており, 単体の $\TeX$ に比べて, より手軽に組版を行うことができるようになっている.

### 動作環境

$\LaTeX$ ソフトウェアは, Latex Project Public License (LPPL) に規定されたライセンスで提供されたフリーソフトウェアである. 現在, macOSやSolarisなどのUNIX, LinuxやBSD系OS,  OpenSolarisなどのUNIX互換OS, Microsoft Windowsなどの多くのOS上で利用可能である.

## 環境構築

### $\TeX$ Liveのインストール

$\LaTeX$ の環境構築をするにあたり, $\TeX$ ディストリビューションの1つである $\TeX$ Live をインストールする. 以下のページからインスラー (install-tl-windows.exe) をダウンロードする. 

><a href="https://www.tug.org/texlive/acquire-netinstall.html" target="_blank">Installing TeX Live over the Internet</a>

なお, 本記事を執筆中 (2023/11) では $\TeX$ Live 2023が最新版である. 


:::note info
インフォメーション
infoは省略可能です。
:::

ダウンロードしてから実行する際に, Windows から警告が出るが, 無視して実行する. 

`Install` にチェックが入った状態で, `Next > ` して, `Install` する. 

これでインスラーのインストールが開始される. インスラーのインストールが完了すると, 

```c:demo.c
include <stdio.h>

int main(void){
    return 0;
}
```
