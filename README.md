# 电影视觉风格图鉴

两套独立的中文静态图鉴，用于非盈利学习分享。

| 在线站点 | 源码目录 |
| --- | --- |
| [奥斯卡最佳摄影视觉风格图鉴](https://oscar-cinematography-atlas.vercel.app/) | `sites/oscar-cinematography/` |
| [伪纪录恐怖画质风格图鉴](https://found-footage-horror-atlas.vercel.app/) | `sites/found-footage-horror/` |

保留风格检索、分类索引、详情弹窗、提示词复制及伪纪录画质对比功能。两站均为独立 HTML，无后端、构建、环境变量或依赖安装；图片内嵌，Google Fonts 为可选网络字体。

## 本地运行

在仓库根目录运行 `python3 -m http.server 8765 --bind 127.0.0.1`，访问对应 `sites/` 路径；也可在支持本地文件的浏览器中打开各站 `index.html`。

## 部署

两个 Vercel 静态项目分别以对应源码目录为 Root Directory，Framework 选 Other，安装和构建命令留空，输出目录为当前目录。无需购买域名或配置密钥。

## 许可与来源

代码采用 [MIT](LICENSE)。第三方图片、字体、研究文字及提示词配方不自动适用 MIT，详见 [授权范围说明](NOTICE.md)。用户已确认取得图片公开使用许可；原有来源与权利归属说明继续保留。

《边陲》《咒》的图片来源页仍有疑问，已在详情中标记“来源待核”，未猜测替换。更多修正见 [变更记录](docs/CHANGES.md)。

原始备份、内部核验材料及凭据不纳入仓库。外部资料的时效与准确性以对应原始来源为准。
