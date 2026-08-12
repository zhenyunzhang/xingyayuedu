# 《送杜少府之任蜀州》儿童互动教材

面向 3—6 岁。含 AI 绘本**故事小课**（约 2 分半）、情感朗读、逐句配图与低难度互动。

## 目录

```text
song-du-shao-fu/
├── index.html
├── README.md
└── assets/
    ├── images/   # scene-01…10.png, video-poster.jpg
    ├── audio/    # poem.mp3, narration.mp3
    └── video/    # story.mp4
```

## 本地预览

```bash
cd output/song-du-shao-fu
python3 -m http.server 8765
```

访问 `http://localhost:8765/`，建议强制刷新。

## 诗文核验（大人用）

> 城阙辅三秦，风烟望五津。  
> 与君离别意，同是宦游人。  
> 海内存知己，天涯若比邻。  
> 无为在歧路，儿女共沾巾。

- 香港教育局课程发展处：https://resources.edcity.hk/resource_detail.php?rid=752415515  
- 香港教育局《积累与感兴》PDF：https://www.edb.gov.hk/attachment/tc/curriculum-development/kla/chi-edu/resources/primary/lang/jilei_shi_pdf/jilei_shi_014.pdf  
- 维基文库（含异文）：https://zh.wikisource.org/zh-hans/送杜少府之任蜀州  

访问日期：2026-08-11。儿童页面不展示本区块。

## 故事小课里讲了什么

旁白以儿童故事方式覆盖（均可核验的要点，非虚构史实对话）：

- 王勃送友人杜少府赴蜀地（今四川一带）上任，路途遥远  
- 「少府」儿童化解释为古时办事的小官  
- 诗一反常见送别的哭哭啼啼，强调真友情不怕远  
- 名句「海内存知己，天涯若比邻」的儿童释义  
- 拓展：今天朋友去了别的城市，也可以写信、打电话、画画寄过去  

## AI 生成声明

- 10 幅绘本插画由 AI 生成  
- 故事视频：插画推拉 + XiaoyiNeural 故事旁白 + 字幕 + 轻柔合成配乐  
- 整诗朗读：XiaoxiaoNeural 预生成音频  

## 交互说明

- 故事视频与整诗朗读互斥  
- 互动为「点一点」「排两句」  
- 无统计、登录与个人信息收集  
