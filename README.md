# Vibe 知识短片导演

一个用于制作中文情景驱动知识动画的 Codex Skill。

它把任何领域的知识主题改写成默认 2 至 3 分钟、无配音、以连续图形和角色动作为主的短片，并要求先核查事实、再写故事、最后完成真实渲染和画面验收。

## 适合的任务

- Vibe 知识大赏风格的知识短片
- 自然科学、数学、历史、地理、工程与产品原理
- 商业、经济、社会机制、文化现象与生活知识
- 从一个具体人物或事件切入的无配音动画
- 分析参考视频并改进现有影片

## 核心原则

- 一个小故事承载一条主要因果链
- 动画展示因果，文字只补充必要条件
- 中文句子按语义完整出现
- 优先连续图形、二维或三维角色演示
- 不把未经证实的网络图解、传闻或视觉比喻写成事实
- 视觉与叙事从当前主题生长，不套用固定的应用、订单、队列或算法模板
- 交付可编辑工程与真实 MP4

## 安装

将整个 `vibe-knowledge-video-director` 文件夹复制到 Codex 的 skills 目录，然后重新载入技能列表。

```text
$CODEX_HOME/skills/vibe-knowledge-video-director
```

调用示例：

```text
使用 $vibe-knowledge-video-director，把“一个谣言如何在六个人之间变形”制作成一条两分半钟的无配音知识动画。
```

也可以处理完全不同的主题，例如“海浪为什么会在岸边弯曲”“一座古城为什么沿河生长”“稳定匹配为何让先开口的一方更占优势”。

## 仓库描述建议

> A Codex skill for researched, story-first Chinese knowledge videos with continuous motion graphics, semantic on-screen text, and render-level QA.
