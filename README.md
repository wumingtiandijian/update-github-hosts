# update-github-hosts
自动更新 GitHub520 hosts，带网络测试和回滚机制（广泛兼容版 v6.20）

# GitHub520 Hosts Updater v6.20

自动更新 GitHub520 hosts，带网络测试和回滚机制，广泛兼容主流 Linux 发行版。

## 快速使用

```bash
# 下载脚本
sudo curl -fsSL https://raw.githubusercontent.com/wumingtiandijian/update-github-hosts/main/update-github-hosts -o /usr/local/bin/update-github-hosts

# 赋予执行权限
sudo chmod +x /usr/local/bin/update-github-hosts

# 执行一次更新
sudo update-github-hosts
