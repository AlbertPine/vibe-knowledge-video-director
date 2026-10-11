# Vibe 知识短片导演

一个用于制作中文情景驱动知识动画的 Codex Skill。

它把知识点改写成 2 至 3 分钟、无配音、以连续图形和角色动作为主的短片，并要求先核查事实、再写故事、最后完成真实渲染和画面验收。

## 适合的任务

- Vibe 知识大赏风格的知识短片
- 算法、网络、数学、公共系统和科学机制解释
- 从一个具体人物或事件切入的无配音动画
- 分析参考视频并改进现有影片

## 核心原则

- 一个小故事承载一个主要机制
- 动画展示因果，文字只补充必要条件
- 中文句子按语义完整出现
- 优先连续图形、二维或三维角色演示
- 不把未经证实的网络图解写成产品内部事实
- 交付可编辑工程与真实 MP4

## 安装

将整个 `vibe-knowledge-video-director` 文件夹复制到 Codex 的 skills 目录，然后重新载入技能列表。

```text
$CODEX_HOME/skills/vibe-knowledge-video-director
```

调用示例：

```text
使用 $vibe-knowledge-video-director，把“12306 候补成功以后发生了什么”制作成一条两分半钟的无配音知识动画。
```

## 仓库描述建议

> A Codex skill for researched, story-first Chinese knowledge videos with continuous motion graphics, semantic on-screen text, and render-level QA.
