# 国乐体验室 Guoyue Lab

网页版虚拟国乐乐器，让没有接触过中国传统乐器的学生，打开浏览器就能亲手体验古筝、古琴、琵琶、二胡、笛子、唢呐和锣鼓的声音与演奏方式。不用下载、不用安装，电脑、平板、手机都能用。

A browser-based set of virtual Chinese traditional instruments for language and culture classes (built for AP Chinese Language and Culture). No download or install; works on desktop, tablet and phone.

## 乐器与玩法 Instruments

| 乐器 | 演奏方式 | 可以体验 |
|---|---|---|
| 古筝 guzheng | 弹 | 21 根弦、刮奏（手指滑过琴弦）、《茉莉花》示范 |
| 古琴 guqin | 弹 | 散音 / 泛音对比、13 个徽 |
| 琵琶 pipa | 弹 | 单音、轮指 |
| 二胡 erhu | 拉 | 按住拉弓、左右滑动 = 滑音 |
| 笛子 dizi | 吹 | 按住吹、笛膜开关对比 |
| 唢呐 suona | 吹 | 按住吹、音头上滑 |
| 锣鼓 luogu | 敲 | 大鼓、小鼓、小锣、大锣、钹、木鱼、舞狮锣鼓节奏 |

- 所有音都标有简谱（1 = D）和五声音阶名称（宫商角徵羽）
- 电脑键盘 `A S D F G H J K L ;` 可以演奏
- 介面可切换 简体 / 繁體

## 使用方式 Usage

直接打开 `index.html`，或启用 GitHub Pages 后用网址打开。第一次需要点一下乐器才会出声（浏览器的自动播放规定）。

Open `index.html` directly, or enable GitHub Pages and share the URL. Browsers require one tap/click before any sound plays.

## 技术说明 How it works

单一 HTML 文件，不依赖任何外部程序库。声音全部由 Web Audio API 即时合成：弹拨乐器使用 Karplus-Strong 弦振动模型，二胡、笛子、唢呐使用振荡器加滤波器，锣鼓使用非谐波合成与噪音。声音是模拟的，和真实乐器不完全相同，请搭配真实演奏录音使用。

Single self-contained HTML file with no external libraries. All sounds are synthesized live with the Web Audio API (Karplus-Strong plucked strings; oscillator + filter models for bowed and wind instruments; inharmonic and noise synthesis for percussion). Sounds are approximations of the real instruments.

## 延伸资源 More

- [在线古筝 onlineguzheng.com](https://onlineguzheng.com/zh)：用真实古筝录音做的网页古筝
- [空音 Kong Audio](http://www.kongaudio.com/Qin_Engine/dl_main.htm)：专业中国乐器音色库（需下载）

## 授权 License

本项目采用 MIT 授权，欢迎其他老师自由使用、修改和分享，详见 [LICENSE](LICENSE)。

Released under the MIT License. Teachers are welcome to use, adapt and share it. See [LICENSE](LICENSE).
