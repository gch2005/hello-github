# 我的第一个 GitHub 仓库

> 由 **gch2005** 创建于 2026-11-07，用来记录从零开始学 GitHub 的过程。

## 我挑的第一个项目：Filee

- **仓库**：https://github.com/KnifeLemon/Filee
- **是什么**：C# 写的离线文件格式转换器。按住 Ctrl 拖动文件，光标旁会弹出一个格式圆环，把文件放到目标格式上就完成转换。
- **能力**：支持 263 种格式，涵盖图片、PDF、Word / Excel / PowerPoint、HWP / HWPX、音视频、电子书、压缩包、CAD 等。
- **亮点**：全程不上传文件、不需要装 Office，Windows / Linux / macOS 都能用。
- **热度**（2026-11-07 查询）：23,124 star，1,374 fork，2026-09-29 建仓，一个多月就火了。
- **为什么挑它**：不用配环境、装上就能用，属于立刻能感受到开源好处的那一类项目。

## 今天学会的 Git 动作

| 命令 | 作用 |
| --- | --- |
| `git init -b main` | 把一个普通文件夹变成 Git 仓库 |
| `git status` | 查看当前有哪些改动 |
| `git add .` | 把改动放进暂存区 |
| `git commit -m "说明"` | 生成一次提交记录 |
| `git log` | 查看提交历史 |

## 关于本机网络

`git clone` / `git push` 到 GitHub 目前走不通（`github.com` 连接被中断），但 `codeload.github.com` 可用，且通过 GitHub 连接器读写仓库不受影响。所以线上部分由连接器代劳，本地 Git 动作照常练习。

## 接下来的路线

1. ~~读 README，挑一个感兴趣的项目~~ 已完成
2. ~~建第一个仓库，提交第一次 commit~~ 已完成
3. 装 akshare，拉取三只 ETF 的十年行情数据
4. 把三基金 10 日动量轮动写成完整回测
