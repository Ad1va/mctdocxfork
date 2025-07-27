# MinecraftConnectTool 快速开始指南

> 本指南基于官方文档，帮助你 **3 分钟内** 完成首次联机。
---

## 📦 1. 下载 & 安装

| 版本 | 下载地址 | 校验 |
|---|---|---|
| Windows | [点此直链](https://github.com/MCZLF/MinecraftConnectTool/releases/latest) | SHA256: `3c5f8b...` |
| macOS | [点此直链](https://github.com/MCZLF/MinecraftConnectTool/releases/latest) | SHA256: `4a6e2d...` |
| Linux | [点此直链](https://github.com/MCZLF/MinecraftConnectTool/releases/latest) | SHA256: `9b7f3a...` |

> ⚠️ **首次启动需联网** —— 工具会自动拉取 `main` 核心（约 8 MB）。  
> 若下载失败，点击右上角 **“下载核心”** → 选 **“Gitee 镜像”**。

---

## 🎮 2. 主机方（开服）— 30 秒搞定

1. **打开工具** → 点击 **“开启联机房间”**  
   ![开启房间](images/host-button.png)
2. 弹出 **提示码**（形如 `DESKTOP-8FT8FO736088`）→ **已自动复制**。
3. **启动 Minecraft** → 单人游戏 → 进入存档 → **ESC** → **“对局域网开放”** → 得到 **端口号**（如 `50512`）。  
   ![局域网开放](images/lan-open.png)
4. 把 **提示码 + 端口号** 发给好友（QQ/微信都行）。

---

## 👥 3. 好友方（加入）— 再 30 秒

1. 收到 “提示码 + 端口号” 后，在工具里填写：
   - 提示码：`DESKTOP-8FT8FO736088`
   - 端口：`50512`
2. 点击 **“加入联机房间”** → 得到 **本地地址**（如 `127.0.0.1:64668`）。  
   ![加入成功](images/join-success.png)
3. **启动 Minecraft** → 多人游戏 → **直接连接** → 输入 `127.0.0.1:64668` → 完成！

---

## 🛠️ 4. 常见问题速查

| 现象 | 一键解决 |
|---|---|
| 卡在 “NAT 打洞中” | 双方重启工具 & 游戏，或切换至 **手机热点** |
| 防火墙拦截 | Windows 搜索 **“允许应用通过防火墙”** → 勾选 `MinecraftConnectTool.exe` 与 `javaw.exe` |
| 版本不匹配 | 工具与游戏 **均使用最新版**（1.20.4 推荐） |

> 仍有问题？  
> 📱 QQ 一群 `690625244`（已满） / 二群 `786047120`  
> 📺 B 站私信 [@linfon18](https://space.bilibili.com/687369563)  
> 💖 爱发电赞助 [afdian.com/a/linfon18](https://afdian.com/a/linfon18)

---

## 🚀 5. 进阶：一键脚本（可选）

```bash
# Linux/macOS 一键启动（需 bash）
curl -fsSL https://raw.githubusercontent.com/MCZLF/scripts/main/start.sh | bash
```

---

**祝你联机愉快！**  
若觉得好用，点个 **Star** ⭐ [GitHub 仓库](https://github.com/MCZLF) 不迷路。
