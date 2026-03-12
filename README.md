# -Dify-
A Dify-based weather assistant using Caiyun API (Coordinates required). Supports Outlook alerts with a touch of "Kagurazaka" style. ✨
2. 详细配置说明 (README.md - 完整中英对照)
你可以直接复制下面的 Markdown 内容：

⚠️ 重要提醒：
导入 DSL 文件后，请务必进入“发送消息”(Outlook) 节点，使用您自己的账号重新点击“授权”，否则工作流将无法发送邮件。
 After importing the DSL file, you must open the "Send Message" (Outlook) node and re-authorize it using your own account, or the workflow will fail to send emails.

Caiyun API: Requires Lat/Lon (City names won't work). See config below.
彩云 API：需要经纬度坐标（不支持城市名），配置见下文。

Email: If using Outlook, a backup email address is highly recommended.
邮件发送：建议准备一个 Outlook 备用邮箱。

Contributions: PRs and Issues are welcome!
欢迎提 PR 或 Issue。

🛠️ Configuration / 配置说明
Get Coordinates / 获取经纬度
Caiyun API requires specific Lat/Lon. Use AMap Picker to click and copy your location.
彩云 API 要求经纬度，请使用高德地图坐标拾取器获取。

API Key Setup / 配置 API Key

Register at Caiyun Weather Developer to get your token.
注册彩云天气开发者获取 token。

Create a .env file in the root directory:
在根目录创建 .env 文件。

Fallback Text / 备用文案
There is an else branch in the workflow. Default signature:
工作流内置 else 分支，默认落款：

“ だいすきっ！神楽坂ですよ♡” (Daisuki! It's Kagurazaka-desu♡)

🚀 How to Use / 如何使用
Clone Project / 下载项目
git clone <your-repo-url> or download the ZIP.

Install & Import / 安装与导入
For Dify users: Import the DSL file located in the workflows/ folder.
Dify 用户直接导入 workflows/ 文件夹下的 DSL 文件。

Update Config / 修改配置
Fill in your .env file as per the instructions above.
按配置说明填好 .env。

Run / 运行

Local Test: Run manually in Dify.
本地测试：手动点击运行。

Automation: Use "Schedule Trigger" in Dify Cloud (e.g., Daily at 08:00).
定时任务：Dify 云端开启 Schedule Trigger。

Support / 有问题
Open an issue. I'll reply when I see it (No guarantees on bug fixes, I'm still learning too! 😅).
提 issue，看到就回（但不保证能修好，我也在踩坑）。
