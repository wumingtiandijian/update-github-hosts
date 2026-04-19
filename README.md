# GitHub520 Hosts Updater v6.20

自动更新 GitHub520 hosts，带网络测试和回滚机制，广泛兼容主流 Linux 发行版。

## 快速使用

# 下载脚本
```bash
sudo curl -fsSL https://raw.githubusercontent.com/wumingtiandijian/update-github-hosts/main/update-github-hosts -o /usr/local/bin/update-github-hosts
```
# 赋予执行权限
```
sudo chmod +x /usr/local/bin/update-github-hosts
```
# 执行一次更新
```
sudo update-github-hosts
```
#定时更新（推荐）
```bash
sudo crontab -e
```
添加以下行（每周日凌晨 3 点自动更新）：
```
0 3 * * 0 /usr/local/bin/update-github-hosts
```
特性
✅ 原子更新，写入失败自动回滚

✅ 网络实测，无效 IP 立即回滚

✅ 多源下载，自动切换备用源

✅ 自动备份，保留最近 5 个备份

✅ 兼容 CentOS 6/7+、Ubuntu、Debian、Linux Mint、RHEL
