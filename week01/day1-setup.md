# 第一次提交：把环境跑通

按顺序做，每步都要看到结果再往下。

## 1. 检查 Python

```powershell
python --version
```

看到 `Python 3.12.x` 就对了。没有就去装：https://www.python.org/downloads/ ，**安装时勾上 Add python.exe to PATH**。

## 2. 装 VS Code 和 Jupyter 插件

1. 装 VS Code：https://code.visualstudio.com/
2. 打开 VS Code → 左侧扩展图标 → 搜 `Python`（Microsoft 官方）→ Install
3. 再搜 `Jupyter`（Microsoft 官方）→ Install

## 3. 配 git

```powershell
git config --global user.name "你的GitHub用户名"
git config --global user.email "你的注册邮箱"
git config --global init.defaultBranch main
```

验证：

```powershell
git config --global --list
```

## 4. 把仓库拉到本地

```powershell
cd D:\ai-work
git clone https://github.com/你的用户名/ds-journey.git
cd ds-journey
```

## 5. 改一个字，提交，推上去

```powershell
# 随便改 README.md 里的一句话，保存
git add .
git commit -m "init: 第一次提交"
git push
```

第一次 push 会弹窗要求认证：
- 用 **Personal Access Token** 当密码（不是账号密码）
- 或者装 GitHub Desktop，图形界面点 Push

## 6. 验收

打开 `https://github.com/你的用户名/ds-journey`，能看到刚才的改动，就说明环境全通了。

---

**跑通了才可以开始学 Python。**没跑通之前不要往下翻课程视频。
