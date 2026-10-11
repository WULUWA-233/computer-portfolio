# 黎添宇 · 计算机项目作品集

从日常英文阅读、学习网页和科研工作中遇到的具体问题出发，开发浏览器工具与 Python 自动化脚本。项目使用 AI 辅助编码与调试，公开版补充了异常处理、回归测试和运行示例。

**每个项目都有独立仓库。点击名称查看代码和使用方法。**

| 项目 | 做了什么 | 技术 |
| --- | --- | --- |
| [DeepSeek 划词翻译](https://github.com/WULUWA-233/deepseek-selection-translator) | 选中文字，就地查看翻译；支持个人 API Key、目标语言与复制 | JavaScript · Chrome MV3 · DeepSeek API |
| [网页划词真人发音](https://github.com/WULUWA-233/human-pronunciation-userscript) | 选中英文单词，查找并播放公开词典中的真人录音 | JavaScript · Tampermonkey · MediaWiki · Audio |
| [词频与例句面板](https://github.com/WULUWA-233/word-frequency-examples) | 将学习网页已返回的词频、概率、词形与例句整理为独立面板 | JavaScript · fetch / XHR · DOM |
| [训练与损失曲线绘图](https://github.com/WULUWA-233/training-curve-plotter) | 解析训练日志或 CSV，按折导出损失与训练指标曲线 | Python · Matplotlib · 数据校验 |
| [论文图件修订与资料整理](https://github.com/WULUWA-233/paper-figure-document-tools) | 替换 Word 图件、处理 EMF、导出文献索引并校验交付文件 | Python · DOCX · Windows GDI · RIS · SHA-256 |

<table>
<tr><td width="50%"><a href="https://github.com/WULUWA-233/deepseek-selection-translator"><img src="https://raw.githubusercontent.com/WULUWA-233/deepseek-selection-translator/main/docs/preview.svg" alt="划词翻译界面示意" /></a></td><td width="50%"><a href="https://github.com/WULUWA-233/word-frequency-examples"><img src="https://raw.githubusercontent.com/WULUWA-233/word-frequency-examples/main/docs/preview.svg" alt="词频和例句界面示意" /></a></td></tr>
<tr><td width="50%"><a href="https://github.com/WULUWA-233/training-curve-plotter"><img src="https://raw.githubusercontent.com/WULUWA-233/training-curve-plotter/main/docs/fold_2_curves.png" alt="程序导出的合成训练曲线" /></a></td><td width="50%"><a href="https://github.com/WULUWA-233/paper-figure-document-tools"><img src="https://raw.githubusercontent.com/WULUWA-233/paper-figure-document-tools/main/docs/preview.svg" alt="论文资料处理流程示意" /></a></td></tr>
</table>

曲线图由程序实际导出；其余图片为界面或流程示意。示例与回归测试使用合成数据，真实 API 与第三方网站适配情况见各仓库说明。

这个仓库仅作为导航入口，不混放项目源码。
