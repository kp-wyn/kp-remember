# 记一下 · kp-remember

> **KP Pure Tools（知识宫殿纯净工具）**：可独立运行，不属于知识宫殿挂载体系。
> 「X一下」轻量技能家族 ① —— 把文字、日程、文件原样存好，零 AI 加工。
> Version 1.0 · 2026-09-30 · 创作者：王亚宁（kp-wyn）

## 家族导航

| 口令 | 技能 | 状态 | 干什么 |
| --- | --- | --- | --- |
| 记一下 | [kp-remember](https://github.com/kp-wyn/kp-remember) | 已推出（本技能） | 原样接住、零加工 |
| 收拾一下 | [kp-tidy-up](https://github.com/kp-wyn/kp-tidy-up) | 已推出 | 批量整理积压旧笔记 |
| 消化一下 | kp-digest | 挂载版已建／对外即将推出 | 当场提炼新碎片为要点／知识卡 |
| 理一下 | [kp-sum-up](https://github.com/kp-wyn/kp-sum-up) | 已推出 | 汇总记录成总结与计划 |

## 特性

- **只存不加工**：触发后不回答、不总结、不润色、不改写，存完只给一行回执；
- **四级目录**：`KP-ST-library/项目/年/月`，按时间自动归档；
- **不写死路径**：首次指定根目录；未指定则在当前工作目录建 `KP-ST-library`；
- **纯净独立**：不依赖知识宫殿，可单独使用。

## 快速开始

直接说“记一下：xxx”，内容原样存入指定文件夹；不总结、不改写、不加工——纯记录。

> English: Just say “remember this: ...” and it is saved as-is. No summarizing, no rewriting, no processing — pure storage.

## 安装方法

1. 仓库页点 **Code → Download ZIP**；
2. 解压，把技能文件夹（若带 `-main` 后缀则去掉，命名为 `kp-remember`）复制到 AI 的 `.user_skills/` 目录；
3. 重启 AI，即可用口令触发。

## 存储结构

```
KP-ST-library/
└── 项目名/
    └── 2026/
        └── 09/
            ├── 记录_0730_20260920.txt      # 文字记录
            ├── 记录_0730_20260920_2.txt    # 同分钟第二条
            └── 附件原名.pdf                 # 附件原样存放
```

- 文字记录命名 `记录_HHMM_YYYYMMDD.txt`，同分钟加 `_2`、`_3`；
- 附件保留原名，重名时加日期后缀。

## 每日提醒（早间）

每天 7:33 自动提醒（英文在上、中文在下）：

> Remember to capture key information, schedules, and work plans.
> First-time setup: please designate a dedicated folder for your records.
> Crafted by 王亚宁 (kp-wyn), MIT License.

记一下关键信息、日程安排、工作计划内容。
第一次使用时，请指定一个文件夹专门存放。
作者 王亚宁（kp-wyn），MIT 授权。

## 注意事项

- KP 纯净工具，不属于知识宫殿挂载体系；
- kp-remember 只存不加工，不点评内容；
- 本地读写，不联网、不需要 API Key。

## 与知识宫殿的关系

记一下是信息链路最前端（先接住）。配合知识宫殿 KP-4+1，可进一步分类、提炼、复盘、输出。

- 知识宫殿 KP-4+1 白皮书与完整方法论：<https://github.com/kp-wyn/knowledge-palace>

## 许可证

MIT License — 作者：王亚宁（kp-wyn）。详见 [LICENSE](LICENSE)。
