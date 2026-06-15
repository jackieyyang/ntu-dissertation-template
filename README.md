# NTU 论文模板 - Agent is all you need

<p align="center">
  <img src="./assets/icon.png" alt="template" width="600" />
</p>

<p align="center">
  <a href="https://github.com/jackieyyang/ntu-dissertation-template/blob/main/LICENSE"><img src="https://img.shields.io/github/license/jackieyyang/ntu-dissertation-template?style=flat-square" alt="LICENSE" /></a>
  <a href="https://github.com/jackieyyang/ntu-dissertation-template/stargazers"><img src="https://img.shields.io/github/stars/jackieyyang/ntu-dissertation-template?style=flat-square" alt="Stars" /></a>
  <a href="https://github.com/jackieyyang/ntu-dissertation-template/network/members"><img src="https://img.shields.io/github/forks/jackieyyang/ntu-dissertation-template?style=flat-square" alt="Forks" /></a>
  <a href="https://github.com/jackieyyang/ntu-dissertation-template/issues"><img src="https://img.shields.io/github/issues/jackieyyang/ntu-dissertation-template?style=flat-square" alt="Issues" /></a>
</p>


<p align="center">
  <a href="./README.en.md">English</a> | 中文
</p>


**NTU 论文模板** 提供适用于 NTU EEE MSc Dissertation 的 `Word` 与 `LaTeX` 双模板，尽量贴合官方格式要求，帮助你更快开始写作、排版和提交论文。

**如果这个模板对你有帮助，欢迎点一个 Star 🌟**。

## 特点

- `Word` 与 `LaTeX` 双版本模板
- 覆盖标题页、声明页、摘要、正文、参考文献与附录
- 内置目录、图表编号、交叉引用与参考文献结构
- 附带模板截图与使用说明，便于快速上手
- 支持结合 AI Agent / AI Editor，通过 `skills` 辅助论文写作、润色与结构整理

## 官方资源

- 官方论文资料：[EEE Dissertation Share Documents](https://entuedu.sharepoint.com/sites/Student/cs/eee/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FStudent%2Fcs%2Feee%2FShared%20Documents%2FGraduate%2FM%2ESc%2E%20Programme%2FMaster%20of%20Science%20%28MSc%29%20Programme%2FImportant%20Links%2FDissertation)
- 官方论文模板说明：[EEE Dissertation Template](https://entuedu.sharepoint.com/sites/Student/cs/eee/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FStudent%2Fcs%2Feee%2FShared%20Documents%2FGraduate%2FM%2ESc%2E%20Programme%2FMaster%20of%20Science%20%28MSc%29%20Programme%2FImportant%20Links%2FDissertation%2FGuideline-MSc-Diss_v8%2Epdf&parent=%2Fsites%2FStudent%2Fcs%2Feee%2FShared%20Documents%2FGraduate%2FM%2ESc%2E%20Programme%2FMaster%20of%20Science%20%28MSc%29%20Programme%2FImportant%20Links%2FDissertation)
- 官方提交流程图：[EEE Dissertation Process Flow](https://entuedu.sharepoint.com/sites/Student/cs/eee/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FStudent%2Fcs%2Feee%2FShared%20Documents%2FGraduate%2FM%2ESc%2E%20Programme%2FMaster%20of%20Science%20%28MSc%29%20Programme%2FImportant%20Links%2FDissertation%2FMSc%20Dissertation%20Process%20Flow_updated%2Epdf&parent=%2Fsites%2FStudent%2Fcs%2Feee%2FShared%20Documents%2FGraduate%2FM%2ESc%2E%20Programme%2FMaster%20of%20Science%20%28MSc%29%20Programme%2FImportant%20Links%2FDissertation)


## 预览

![](./assets/template_1.png)
![](./assets/template_2.png)
![](./assets/template_3.png)
![](./assets/template_4.png)
![](./assets/template_5.png)
![](./assets/template_6.png)

## 快速开始

您可以参考以下任意一种方式使用本模板，如果您偏好传统写作流程，建议选择方式二，如果您接受通过自然语言对话的方式使用本模板，建议选择方式一。

### 方式一：Agent is all you need

如果你希望通过自然语言对话来完成论文模板使用，推荐使用 `skills` 搭配任意你喜欢的 Agent / AI Editor（如 Cursor、CodeBuddy）。

如果你希望**不配置本地环境**，可以直接使用 [OpenAI Prism](https://openai.com/prism)。

1. 下载 AI Editor
    - Cursor: [点击下载 Cursor](https://cursor.com/download)
    - Codebuddy: [点击下载 Codebuddy](https://www.codebuddy.cn/ide/?auto-download=1)
    - Trae: [点击下载 Trae](https://www.trae.ai/download)

2. 新建一个论文目录并打开

    ![skills 安装步骤 0](./assets/skills-download-0.png)

3. 打开终端安装 `skills`， 终端中安装 `skills` 的过程示意（按顺序）：

    ```bash
    npx skills add https://github.com/jackieyyang/skills --skill ntu-dissertation-expert
    ```

    ![skills 安装步骤 1](./assets/skills-download-1.png)
    ![skills 安装步骤 2](./assets/skills-download-2.png)
    ![skills 安装步骤 3](./assets/skills-download-3.png)
    ![skills 安装步骤 4](./assets/skills-download-4.png)

4. 在右侧自然语言聊天，验证是否安装成功

    ![skills 安装步骤 5](./assets/skills-download-5.png)

5. 在右侧，通过自然语言对话的方式，Agent 会自动完成模版拉取，编译，修改工作

    ![skills 安装步骤 6](./assets/skills-download-6.png)

6. 在插件市场下载 LaTeX Workshop，获取保存自动编译功能

    ![skills 安装步骤 7](./assets/skills-download-7.png)

7. 最终效果，开始自然语言交互吧

    ![skills 安装步骤 8](./assets/skills-final.png)

### 方式二：传统模版使用（Word / LaTeX）

如果你更希望自己手动编写内容，也可以直接使用 `Word` 或 `LaTeX` 模板。

#### Word 版本

- 模板下载：[下载 Word 版本](https://github.com/jackieyyang/ntu-dissertation-template/releases/download/v1.0.0/word-v1.0.0.zip)
- 使用 Microsoft Word 或 WPS Office 打开即可开始编辑
- 按需替换标题、姓名、学院、年份等占位内容
- 右键目录选择“更新字段”，或使用 F9 更新目录、图表和引用编号
- 压缩包内包含 Word 模板和 PDF 使用说明

#### LaTeX 版本

- 模版下载：[下载 LaTeX 版本](https://github.com/jackieyyang/ntu-dissertation-template/releases/download/v1.0.0/latex-v1.0.0.zip)
- 可导入 Overleaf，或在本地编译使用

## 关注记录

[![Star History Chart](https://api.star-history.com/svg?repos=jackieyyang/ntu-dissertation-template&type=date&legend=top-left)](https://www.star-history.com/#jackieyyang/ntu-dissertation-template&type=date&legend=top-left)

## 许可证

[MIT](./LICENSE)
