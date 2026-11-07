<h1 align="center">Hi, I'm Moca 👋</h1>

<p align="center">
Web developer (frontend / CMS) who builds small tools for everyday life —<br/>
Windows widgets, a self-hosted household app on a Raspberry Pi, and image-classification tools.
</p>

---

### 🧑‍💻 About me

- 🌐 仕事では Web フロントエンド（HTML / CSS / JavaScript）と CMS（Movable Type）を中心に開発・ドキュメント整備をしています
- 🏠 個人では「自分と家族が毎日使うもの」を作るのが好きです。Raspberry Pi 5 の自宅サーバーで家計簿アプリを運用中
- 🪟 Windows 11 のウィジェットや Rainmeter で、デスクトップを自分好みにするツールも作っています
- 🗣️ 日本語 / English

### 🛠️ Tech stack

**Languages**<br/>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?logo=lua&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)

**Frameworks / Libraries**<br/>
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Movable Type](https://img.shields.io/badge/Movable_Type-CMS-1a1a1a)

**Infra / Tools**<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?logo=raspberrypi&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?logo=tailscale&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)

---

### 📌 Featured projects

#### 🏠 Self-hosted

| Project | What it is | Stack |
| --- | --- | --- |
| [**Sub-Tracker**](https://github.com/Moca-Piplup/Sub-Tracker) | 2人で使う家計簿 PWA。サブスク管理・3段階承認の折半家計簿・レシートOCR・買い物リスト。本番/Debug の2環境をタグ push で自動デプロイ | Node.js · Express · SQLite · FastAPI · RapidOCR · Docker · Tailscale |

#### 🪟 Windows desktop

| Project | What it is | Stack |
| --- | --- | --- |
| [**DeskPanel**](https://github.com/Moca-Piplup/DeskPanel) | 自作ウィジェットの情報をタブで切り替えて表示する Rainmeter パネル。常駐エージェント＋設定だけでタブ追加 | C# · .NET 9 · Rainmeter · Lua |
| [**BluetoothBatteryWidget**](https://github.com/Moca-Piplup/BluetoothBatteryWidget) | Bluetooth 機器の残量と充電状態（BLE GATT＋推定）を表示する Windows 11 ウィジェット | C# · Windows App SDK · Adaptive Cards |
| [**RaspberryPiMonitor**](https://github.com/Moca-Piplup/RaspberryPiMonitor) | Raspberry Pi のストレージ・メモリを SSH で取得する Windows 11 ウィジェット。CI と署名済み MSIX リリース | C# · .NET 9 · SSH.NET · xUnit |
| [**FavoriteImageWidget**](https://github.com/Moca-Piplup/FavoriteImageWidget) | 右クリックで登録したお気に入り画像をスライド表示する Windows 11 ウィジェット | C# · Windows App SDK |

#### 🖼️ Image / ML

| Project | What it is | Stack |
| --- | --- | --- |
| [**ImageTools**](https://github.com/Moca-Piplup/ImageTools) | キャラクター画像分類モデルの学習・評価と、画像のタグ付け・整理・重複検出・閲覧を行うツール群 | Python · PyTorch · YOLO · pytest · Sphinx |

---

### 🍓 Home lab

```
Raspberry Pi 5 (8GB) ── Ubuntu Server 24.04
 ├─ Docker Compose
 │   ├─ Sub-Tracker (prod / debug)
 │   ├─ Samba + File Browser (NAS)
 │   └─ Tailscale (VPN + HTTPS)
 └─ deployed by GitHub Actions over Tailscale SSH
```

<!--
### 📊 Stats
公開リポジトリが増えたら、github-readme-stats などのカードをここに追加すると見栄えが良くなります。
-->
