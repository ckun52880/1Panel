<p align="center"><a href="https://1panel.pro"><img src="https://resource.1panel.pro/img/1panel-logo.png" alt="1Panel" width="300" /></a></p>
<p align="center"><b>Top-Rated Web-based Linux Server Management Tool</b><br>Best VPS control panel<br>新一代的 Linux 服务器运维管理面板</p>
<p align="center">
  <a href="https://trendshift.io/repositories/2462" target="_blank"><img src="https://trendshift.io/api/badge/repositories/2462" alt="1Panel-dev%2F1Panel | Trendshift" style="width: 240px; height: auto;" /></a>
</p>
<p align="center">
  <a href="https://www.gnu.org/licenses/gpl-3.0.html"><img src="https://shields.io/github/license/1Panel-dev/1Panel?color=%231890FF" alt="License: GPL v3"></a>
  <a href="https://app.codacy.com/gh/1Panel-dev/1Panel?utm_source=github.com&utm_medium=referral&utm_content=1Panel-dev/1Panel&utm_campaign=Badge_Grade_Dashboard"><img src="https://app.codacy.com/project/badge/Grade/da67574fd82b473992781d1386b937ef" alt="Codacy"></a>
  <a href="https://discord.gg/bUpUqWqdRr" target="_blank">
        <img src="https://img.shields.io/discord/1318846410149335080?logo=discord&labelColor=%20%235462eb&logoColor=%20%23f5f5f5&color=%20%235462eb"
            alt="chat on Discord"></a>
  <a href="https://github.com/1Panel-dev/1Panel/releases"><img src="https://img.shields.io/github/v/release/1Panel-dev/1Panel" alt="GitHub release"></a>
  <a href="https://github.com/1Panel-dev/1Panel"><img src="https://img.shields.io/github/stars/1Panel-dev/1Panel?color=%231890FF&style=flat-square" alt="Stars"></a><br>
</p>
<p align="center">
  <a href="/README.md"><img alt="English" src="https://img.shields.io/badge/English-d9d9d9"></a>
  <a href="/docs/README.zh-Hans.md"><img alt="中文(简体)" src="https://img.shields.io/badge/中文(简体)-d9d9d9"></a>
  <a href="/docs/README.ja.md"><img alt="日本語" src="https://img.shields.io/badge/日本語-d9d9d9"></a>
  <a href="/docs/README.pt-br.md"><img alt="Português (Brasil)" src="https://img.shields.io/badge/Português (Brasil)-d9d9d9"></a>
  <a href="/docs/README.ar.md"><img alt="العربية" src="https://img.shields.io/badge/العربية-d9d9d9"></a>
  <a href="/docs/README.de.md"><img alt="Deutsch" src="https://img.shields.io/badge/Deutsch-d9d9d9"></a>
  <a href="/docs/README.es.md"><img alt="Español" src="https://img.shields.io/badge/Español-d9d9d9"></a><br>
  <a href="/docs/README.fr.md"><img alt="français" src="https://img.shields.io/badge/français-d9d9d9"></a>
  <a href="/docs/README.ko.md"><img alt="한국어" src="https://img.shields.io/badge/한국어-d9d9d9"></a>
  <a href="/docs/README.id.md"><img alt="Bahasa Indonesia" src="https://img.shields.io/badge/Bahasa Indonesia-d9d9d9"></a>
  <a href="/docs/README.zh-Hant.md"><img alt="中文(繁體)" src="https://img.shields.io/badge/中文(繁體)-d9d9d9"></a>
  <a href="/docs/README.tr.md"><img alt="Türkçe" src="https://img.shields.io/badge/Türkçe-d9d9d9"></a>
  <a href="/docs/README.ru.md"><img alt="Русский" src="https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-d9d9d9"></a>
  <a href="/docs/README.ms.md"><img alt="Bahasa Melayu" src="https://img.shields.io/badge/Bahasa Melayu-d9d9d9"></a>
</p>

------------------------------

1Panel is an open-source, modern web-based control panel for Linux server management.

- **Efficient Management**: Through a user-friendly web graphical interface, 1Panel enables users to effortlessly manage their Linux servers. Key features include host monitoring, file management, database administration, container management, LLMs management.
- **Rapid Website Deployment**: With deep integration of the popular open-source website building software WordPress, 1Panel streamlines the process of domain binding and SSL certificate configuration, all achievable with just one click.
- **Application Store**: 1Panel curates a wide range of high-quality open-source tools and applications, facilitating easy installation and updates for its users.
- **Security and Reliability**: By leveraging containerization and secure application deployment practices, 1Panel minimizes vulnerability exposure. It further enhances security through integrated firewall management and log auditing capabilities.
- **One-Click Backup & Restore**: Data protection is made simple with 1Panel's one-click backup and restore functionality, supporting various cloud storage solutions to ensure data integrity and availability.

## Quick Start

Execute the script below and follow the prompts to install 1Panel:

```bash
curl -sSL https://resource.1panel.pro/quick_start.sh -o quick_start.sh && bash quick_start.sh
```

Please refer to our [documentation](https://docs.1panel.pro/quick_start/) for more details.

中国用户请使用这个 [安装脚本](https://1panel.cn/docs/installation/online_installation/)，其应用数量比国际版本更丰富。

## 在线安装

> 安装前请确保您的系统符合安装条件：
> - 操作系统：支持主流 Linux 发行版本（基于 Debian / RedHat，包括国产操作系统）
> - 服务器架构：x86_64、aarch64、armv7l、ppc64le、s390x、riscv64
> - 内存要求：建议可用内存在 1GB 以上
> - 浏览器要求：请使用 Chrome、FireFox、IE10+、Edge 等现代浏览器
> - 可访问互联网
> - 如果是内网环境，推荐实现 [离线安装包](https://1panel.cn/docs/v2/installation/package_installation/) 方式进行部署

> GitHub release 链接: https://github.com/1Panel-dev/1Panel/releases

> 执行以下安装脚本，根据命令行提示完成安装。
> ```bash
> bash -c "$(curl -sSL https://resource.fit2cloud.com/1panel/package/v2/quick_start.sh)"
> ```

> 如果遇到 Docker 安装失败等问题，可以尝试运行以下脚本：
> ```bash
> bash <(curl -sSL https://linuxmirrors.cn/docker.sh)
> ```
> 了解更多信息，请访问官方网站：https://linuxmirrors.cn

> 安装成功后，控制台会打印面板访问信息，可通过浏览器访问 1Panel：
> ```bash
> http://目标服务器 IP 地址:目标端口/安全入口
> ```
> - 如果使用的是云服务器，请在安全组中开放对应的目标端口
> - ssh 登录 1Panel 服务器后，执行 1pctl user-info 命令可获取安全入口（entrance）

> 安装成功后，可使用 1pctl 命令行工具来维护 1Panel
## 离线版

> 请下载最新的 1Panel 离线包，上传至服务器 /tmp 目录，并以 root 用户 执行以下命令进行安装准备：
> ```bash
> cd /tmp
> # 解压离线包（请将示例文件名替换为实际名称）
> tar zxvf 1panel-v2.0.11-offline-linux-amd64.tar.gz
> ```

> 执行安装脚本
> ```bash
> # 进入解压目录（请根据实际目录名替换）
> cd 1panel-v2.0.11-offline-linux-amd64
> 
> # 执行安装脚本
> /bin/bash install.sh
> ```

> 升级版本：解压离线包
> 
> 请下载最新的 1Panel 离线包，上传至服务器 /tmp 目录，并以 root 用户 执行以下命令进行升级准备：
> ```bash
> cd /tmp
> # 解压离线包（请将示例文件名替换为实际名称）
> tar zxvf 1panel-v2.0.12-offline-linux-amd64.tar.gz
> ```

> 执行升级脚本
> ```bash
> # 进入解压目录（请根据实际目录名替换）
> cd 1panel-v2.0.12-offline-linux-amd64
> 
> # 执行升级脚本
> /bin/bash upgrade.sh
> ```

> 登录访问
> 安装成功后，控制台会打印面板访问信息，可通过浏览器访问 1Panel：
> ```bash
> http://目标服务器 IP 地址:目标端口/安全入口
> ```
> - 如果使用的是云服务器，请在安全组中开放对应的目标端口
> - ssh 登录 1Panel 服务器后，执行 1pctl user-info 命令可获取安全入口（entrance）

> 安装成功后，可使用 1pctl 命令行工具来维护 1Panel

## Screenshot

![UI Display](https://resource.1panel.pro/img/1panel.png)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=1Panel-dev/1Panel&type=Date)](https://star-history.com/#1Panel-dev/1Panel&Date)

## Pro Edition

Compared to the OSS Edition, 1Panel Pro Edition provides users with a wealth of enhanced features and technical support services. Enhanced features include WAF enhancement, website tamper protection, website monitoring, GPU monitoring, custom logo and theme color, etc. [Click to view the detailed introduction of the Pro Edition](https://1panel.pro/pricing).

## Security Information

If you discover any security issues, please refer to [SECURITY.md](/SECURITY.md).

## License

Licensed under The GNU General Public License version 3 (GPLv3)  (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

<https://www.gnu.org/licenses/gpl-3.0.html>

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
