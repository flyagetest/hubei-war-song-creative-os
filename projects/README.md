# 项目索引

> 本文件是“湖北战歌宇宙 Creative OS”的总项目目录。  
> 所有新任务开始前，先确认项目是否已有 `brief.yaml`；存在时必须以 brief 为准。

## 当前项目

| 项目目录 | 项目名称 | 状态 | 核心用途 | 主要资料 |
|---|---|---:|---|---|
| `enshi/` | 恩施阿尼白虎 | 进行中 | 楚超赛事、远征、角色 IP、战歌、主视觉 | `enshi/brief.yaml` |
| `yichang/` | 宜昌开闸 / 开扎 | 进行中 | 山歌摇滚城市战歌、三峡水势视觉 | `yichang/brief.yaml` |
| `xiangyang/` | 襄阳《铁打的城》 | 进行中 | 古城、汉江、史诗体育战歌 | `xiangyang/brief.yaml` |
| `churenbufuzhou/` | 楚人不服周 | 进行中 | 宇宙级主视觉、楚文化、绿茵古战场 | `churenbufuzhou/brief.yaml` |
| `world-cup/` | 《大力神杯的年轮》 | 进行中 | 世界杯主题歌曲、全球足球视觉 | `world-cup/brief.yaml` |
| `_template/` | 新项目模板 | 模板 | 新城市、新歌曲、新赛事的标准起点 | `_template/brief.yaml` |

## 项目状态定义

- **进行中**：已有明确设定，可继续生产海报、歌词、分镜和宣发物。
- **待补全**：已有方向，但事实、角色、赛程或口号仍需确认。
- **归档**：不再继续扩展，保留作为历史参考。
- **模板**：不可直接当成正式项目，需要复制后改名。

## 新项目创建规则

1. 复制 `projects/_template/`。
2. 目录名使用小写英文或拼音短名，例如 `wuhan/`、`jingzhou/`。
3. 填写 `brief.yaml` 中的身份、事实、创意和约束。
4. 把不确定信息放入 `pending_confirmation`，不得编造。
5. 在本文件新增一行项目索引。

## 项目交付建议

每个正式项目建议逐步具备以下目录：

```text
projects/<项目名>/
├─ brief.yaml            # 唯一事实与创意总表
├─ lyrics/               # 歌词版本
├─ posters/              # 海报方案与提示词
├─ storyboard/           # MV、短视频分镜
├─ social/               # 平台文案
├─ references/           # 图片、资料、调研
└─ outputs/              # 最终交付物
```
