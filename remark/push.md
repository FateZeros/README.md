# PUSH

```bash
echo "# README.md" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/FateZeros/README.md.git
git push -u origin main
```

## github clone 443

1. 查看 github ip

[DNS](https://tool.chinaz.com/dns)

2. 修改 hosts 文件

3. 刷新 DNS

```bash
sudo killall -HUP mDNSResponder
```

## Streak Stats

[Streak Stats](https://github-readme-streak-stats.herokuapp.com/demo/)

## 修改 gitconfig

1. 修改当前 git 项目的 config

```bash
cd .git

git config user.name [name]
git config user.email [email]
```

2. 查看全局 git config

```bash
open ~/.gitconfig
```
