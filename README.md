# job-interview-skills

一套面试辅助 Skills，分两个使用场景：**面试前准备**，以及面试后的**录音整理 → 复盘**。

## 包含的 Skills

| 文件夹 | 用途 |
|---|---|
| `interview-transcript/` | 将面试录音原始转文字整理成结构化访谈记录，自动识别说话人、分段排版，生成面试摘要 |
| `interview-prep/` | 基于 JD（及可选的历史复盘、面经）生成完整的面试前准备策略文档，含自我介绍、高频题答法、项目深挖策略 |
| `interview-debrief/` | 基于面试文字记录生成结构化复盘文档，含逐题评估、面试官信号解读、改进建议和参考答案 |

每个文件夹下有一个 `SKILL.md`，包含完整的工作流说明和指令。

## 安装方法

克隆本仓库到本地：

```bash
git clone https://github.com/polaris-lo/job-interview-skills.git
```

然后将需要的 skill 文件夹（如 `interview-prep/`）按你所使用的 AI 工具的 skill 安装方式加载即可。

Skills 会根据你的个人经历（学历、实习、项目等）生成更具针对性的内容。首次使用时，你可以选择直接上传简历让 AI 自动提取，或手动提供相关信息——用于辅助生成更高质量的回答。

## 推荐工作流

```
面试前：      interview-prep
面试结束后：  interview-transcript  →  interview-debrief
```

## 适用范围

**适合**：以简历深挖、案例题、行为题为主的面试，常见于职能类 / 业务类岗位。
