# CanMV K230

## 测试环境

### 操作系统信息

- Canaan Kendryte K230 Official CanMV Debian SDK
  - 下载链接：https://kendryte-download.canaan-creative.com/developer/k230/canmv_debian_sdcard_sdk_1.3.img.gz
  - 参考安装文档：https://gitlab.inuyasha.love/weilinfox/plct-working/-/blob/master/Done/Month08/Week3/CanMV-K230_zh.md
- Canaan Kendryte K230 Official CanMV Ubuntu SDK
  - 下载链接：https://kendryte-download.canaan-creative.com/developer/k230/canmv_ubuntu_sdcard_1.3.img.gz
  - 参考安装文档：https://gitlab.inuyasha.love/weilinfox/plct-working/-/blob/master/Done/Month08/Week3/CanMV-K230_zh.md
- Fedora 38
  - 下载链接：https://github.com/ruyisdk/mkimg-k230-rv64ilp32/releases
  - 参考安装文档：https://developer.canaan-creative.com/k230/dev/zh/CanMV_K230_%E6%95%99%E7%A8%8B.html
- RT-Thread
  - 下载链接：https://github.com/kendryte/k230_sdk/releases/tag/v1.4
  - 参考安装文档：https://github.com/kendryte/k230_docs/blob/main/zh/01_software/board/K230_SDK_%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E_zh.md
- NuttX
  - 源码链接：https://github.com/apache/nuttx
  - 参考安装文档：https://nuttx.apache.org/docs/latest/platforms/risc-v/k230/boards/canmv230/index.html

### 硬件开发板信息

- Canaan Kendryte K230

## 测试结果

| 软件分类                 | 软件包名 | 测试结果（测试报告）           |
| ------------------------ | -------- | ------------------------------ |
| Debian 镜像启动          | N/A      | [成功][K230Debian]（厂商镜像） |
| Ubuntu 镜像启动          | N/A      | [成功][K230Ubuntu]（厂商镜像） |
| Fedora 镜像启动          | N/A      | [成功][Fedora]                 |
| RT-Thread 镜像构建及启动 | N/A      | [成功][RT-Thread]（厂商镜像）  |
| NuttX 镜像构建及启动     | N/A      | [成功][NuttX]                  |

[K230Debian]: ./Debian/README_zh.md
[K230Ubuntu]: ./Ubuntu/README_zh.md
[Fedora]: ./Fedora/README_zh.md
[RT-Thread]: ./RT-Thread/README_zh.md
[NuttX]: ./NuttX/README_zh.md