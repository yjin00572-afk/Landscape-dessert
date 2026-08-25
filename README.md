# Dessert Cutout From Image

一个为 Codex 设计的图像生成 skill，用来分析用户上传的图片，提取其中的核心视觉元素与主色块，并将其重新转译为一款甜点。

## 安装方式

1、可以将 GitHub 仓库链接直接发给支持安装 Skill 的 Agent：

```text
请为我安装这个 Skill，链接是：https://github.com/yjin00572-afk/Landscape-dessert.git
```

2、你也可以下载仓库 ZIP，解压后将完整的 `neo-chinoiserie-stamp` 文件夹放入 `$CODEX_HOME/skills/` 或 `~/.codex/skills/`。

安装后，Skill 通常位于 Agent 的 `skills` 文件夹中。例如 Codex 的默认路径：

```text
C:\Users\LENOVO\.codex\skills\neo-chinoiserie-stamp\
```


## 使用方式

### 1. 直接调用 skill

```text
使用 $dessert-cutout-from-image 将我上传的图片重新设计成一款高级创意甜品。
```

### 2. 先分析，再生成

```text
Use $dessert-cutout-from-image 先分析原图，再生成。
```

### 3. 只要 prompt，不要直接生成

```text
Use $dessert-cutout-from-image 给我最终 prompt，不要直接生成。
```

### 4. 直接应用到图片

```text
Use $dessert-cutout-from-image 直接根据这张图生成高端甜点图。
```

## 适合的图像类型

这个 skill 更适合以下类型的输入图：

- 具有明确主体、结构层次或纹理特征的图片
- 有明显主色块或大面积背景色的图片
- 含有可转译为甜点造型的物体、轮廓、图案或材质
- 适合被抽象成高级甜点摆盘语言的视觉素材

如果原图缺少可识别形态、颜色过于杂乱，或者没有清晰的主色区域，最终结果通常会更依赖模型推断。

## 常见失败情况

如果结果出现以下问题，通常说明提示词需要进一步收紧：

- 只提取了 1-2 个元素，没有完成至少 4 个元素映射
- 背景不是来自原图最大色块
- 甜点仍然像普通蛋糕照，而不是高端 fine-dining cutout 产品图
- 画面中加入了盘子、桌面、道具或复杂环境
- 光影太弱，导致主体像悬浮贴图
- 材质映射不清晰，看不出 glaze、mousse、crisp 或 chocolate decor 的层次



## GitHub 仓库结构

当前 skill 包建议保留以下结构：

```text
dessert-cutout-from-image/
├─ SKILL.md
├─ README.md
├─ LICENSE
├─ NOTICE
└─ agents/
   └─ openai.yaml
```

主要文件说明：

- `SKILL.md`：skill 主规则与默认执行协议
- `README.md`：GitHub 展示与使用说明
- `LICENSE`：MIT License
- `NOTICE`：第三方资产、参考图片权利与艺术家名称引用声明
- `agents/openai.yaml`：Codex UI 元数据

## 版权与授权

当前仓库默认采用 MIT License。

- 许可证文件：`LICENSE`
- 权利与声明文件：`NOTICE`

目前该 skill 包本身不附带第三方参考图片或第三方素材；若后续加入外部资产，应同步在 `NOTICE` 中补充来源、版权归属和再分发状态。
- 感谢您的观看，这是我制作的skill，有任何意见和问题欢迎抖音@Breathe ，也欢迎您来玩这个skill发抖音可以@Breathe ，让我欣赏您的作品。
