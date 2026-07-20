# Taste Skill Collection

基于 [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) 安装的设计品味规范。

## 已安装 Skill

| Skill | 用途 |
|-------|------|
| `design-taste-frontend` (v2) | 默认前端品味规范：Brief 推断 → 设计系统选择 → 排版/配色/布局约束 |
| `design-taste-frontend-v1` | v1 备份，v2 不兼容时回退使用 |
| `redesign-existing-projects` | 已有项目重设计审计清单 |

## 使用方式

每做一个工具 / 每改一次 UI，都应参照 `design-taste-frontend/SKILL.md` 的核心节奏：

1. **Read the brief** → 推断工具类型（landing / portfolio / tool / dashboard）
2. **Set the dials** → DESIGN_VARIANCE / MOTION_INTENSITY / VISUAL_DENSITY
3. **Pick the stack** → 单文件 HTML 用原生 CSS + OKLCH 主题系统
4. **Apply anti-slop rules** → 禁止 AI 默认审美（紫色渐变、3列卡片、Inter 字体等）
