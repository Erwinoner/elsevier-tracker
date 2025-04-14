# Elsevier 论文投稿状态跟踪工具

[![简体中文](https://img.shields.io/badge/语言-简体中文-red)](README.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

一个简单易用的工具，帮助研究人员跟踪在Elsevier期刊投稿的论文审稿状态。无需安装任何软件，只需在浏览器中访问即可使用。

[立即使用此工具](https://你的用户名.github.io/elsevier-tracker/)

![工具截图](screenshot.png)

## 功能特点

- **实时追踪审稿状态**：获取论文的最新审阅进展
- **审稿人详情展示**：查看每位审稿人的邀请、接受和完成时间
- **时间计算**：自动计算审稿响应时间和审阅时间
- **无需安装**：纯网页应用，任何设备的浏览器都能访问
- **数据安全**：所有数据处理都在本地完成，不会保存到远程服务器
- **响应式设计**：适配电脑和移动设备屏幕

## 使用方法

1. 在Elsevier作者中心找到你的论文追踪链接，例如：
   ```
   https://track.authorhub.elsevier.com?uuid=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
   ```

2. 从链接中复制`uuid`参数的值

3. 打开[此工具](https://你的用户名.github.io/elsevier-tracker/)，粘贴UUID到输入框

4. 点击"获取状态"按钮查看详细审稿信息

## 详细功能说明

### 基本信息展示
- 论文标题
- 期刊名称
- 当前状态
- 提交日期
- 最新修订版本

### 审稿人信息追踪
- 审稿邀请、接受和完成的时间
- 审稿人响应时间计算
- 审稿完成时间计算
- 直观的状态指示（已邀请、审阅中、已完成）

### 数据保存
- 自动保存最近查询数据到浏览器本地存储
- 下次访问时自动恢复上次查看的结果
- 提供清除数据选项

## 工作原理

此工具通过Elsevier提供的API获取论文审稿状态数据，API请求基于论文的唯一标识符(UUID)。获取的数据在用户浏览器中处理和展示，不会传输到任何第三方服务器，确保用户数据安全。

## 隐私和安全

- 不收集任何个人信息
- 不会将数据发送到第三方服务器
- 所有处理都在用户自己的浏览器中完成
- 数据仅保存在用户浏览器的本地存储中

## 常见问题

**Q: 此工具是否会保存我的论文数据?**  
A: 此工具仅将数据保存在你自己的浏览器中，用于恢复上次的查询，不会上传到任何服务器。

**Q: 如何清除已保存的数据?**  
A: 点击工具界面上的"清除数据"按钮即可。

**Q: 工具显示"无法获取论文状态信息"怎么办?**  
A: 请检查UUID是否正确，或者API服务是否临时不可用。

**Q: 我可以在自己的服务器上部署这个工具吗?**  
A: 可以，只需下载`index.html`文件并放在任何Web服务器上即可。

## 贡献与反馈

如果你有任何问题、建议或者想要贡献代码，欢迎:
- 提交Issue
- 创建Pull Request
- 联系开发者

## 许可证

此项目采用MIT许可证 - 详见 [LICENSE](LICENSE) 文件。

---

# Elsevier Submission Tracker

[![English](https://img.shields.io/badge/Language-English-blue)](#elsevier-submission-tracker)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple tool to help researchers track the status of their paper submissions to Elsevier journals. No installation required, just access it through your browser.

[Use this tool now](https://your-username.github.io/elsevier-tracker/)

![Tool Screenshot](screenshot.png)

## Features

- **Real-time submission tracking**: Get the latest status of your paper
- **Reviewer details**: View invitation, acceptance, and completion dates for each reviewer
- **Time calculation**: Automatically calculate reviewer response and review times
- **No installation required**: Pure web application accessible from any device's browser
- **Data security**: All data processing happens locally, nothing is saved to remote servers
- **Responsive design**: Adapts to both desktop and mobile screens

## How to Use

1. Find your paper tracking link in Elsevier Author Hub, e.g.:
   ```
   https://track.authorhub.elsevier.com?uuid=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
   ```

2. Copy the value of the `uuid` parameter from the link

3. Open [this tool](https://your-username.github.io/elsevier-tracker/), paste the UUID into the input field

4. Click the "Get Status" button to view detailed review information

## Detailed Features

### Basic Information Display
- Manuscript title
- Journal name
- Current status
- Submission date
- Latest revision number

### Reviewer Tracking
- Reviewer invitation, acceptance, and completion times
- Response time calculation
- Review completion time calculation
- Intuitive status indicators (Invited, In Review, Completed)

### Data Saving
- Automatically saves most recent query data to browser local storage
- Automatically restores last viewed results on next visit
- Provides option to clear data

## How It Works

This tool retrieves paper review status data through an API provided by Elsevier, based on the paper's unique identifier (UUID). The retrieved data is processed and displayed in the user's browser without being transmitted to any third-party servers, ensuring data security.

## Privacy and Security

- Does not collect any personal information
- Does not send data to third-party servers
- All processing happens in the user's own browser
- Data is only saved in the user's browser local storage

## FAQ

**Q: Does this tool save my paper data?**  
A: This tool only saves data in your own browser for restoring your last query. It does not upload to any servers.

**Q: How do I clear saved data?**  
A: Click the "Clear Data" button in the tool interface.

**Q: What if the tool shows "Unable to retrieve submission status"?**  
A: Please check if your UUID is correct or if the API service is temporarily unavailable.

**Q: Can I deploy this tool on my own server?**  
A: Yes, just download the `index.html` file and place it on any web server.

## Contribution and Feedback

If you have any questions, suggestions, or want to contribute code, please:
- Submit an Issue
- Create a Pull Request
- Contact the developer

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 
