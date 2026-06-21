# assets/fonts — Source Han Sans SC（思源黑体 简体）

PingFang SC（苹方）的**可商用、可嵌入**替代字体系统。苹方是 Apple 专有字体、不可单独分发；本目录改用 Adobe 思源黑体（Source Han Sans），观感接近、授权干净。

## 字体信息

| 项 | 内容 |
|---|---|
| 名称 | Source Han Sans SC（思源黑体 简体中文） |
| 出品 | Adobe（与 Google Noto Sans CJK SC 为同一字体） |
| 版本 | 2.004R |
| 授权 | **SIL Open Font License 1.1**（免费商用、可嵌入网页/应用，见 [LICENSE.txt](LICENSE.txt)） |
| 来源 | https://github.com/adobe-fonts/source-han-sans/releases/tag/2.004R |
| 格式 | OTF（简体子集） |

## 字重（7 档，覆盖全字重系统）

| 文件 | 字重 | 推荐 CSS `font-weight` |
|---|---|---|
| SourceHanSansSC-ExtraLight.otf | 极细 | 200 |
| SourceHanSansSC-Light.otf | 细 | 300 |
| SourceHanSansSC-Normal.otf | 常规（偏细） | 350 |
| SourceHanSansSC-Regular.otf | 常规 | 400 |
| SourceHanSansSC-Medium.otf | 中 | 500 |
| SourceHanSansSC-Bold.otf | 粗 | 700 |
| SourceHanSansSC-Heavy.otf | 特粗 | 900 |

## 用法

**本机安装：** 双击任一 `.otf` → 安装，即可在设计软件里选用 "Source Han Sans SC"。

**网页 @font-face（原型/产品 UI）：**
```css
@font-face {
  font-family: "Source Han Sans SC";
  src: url("./SourceHanSansSC-Regular.otf") format("opentype");
  font-weight: 400;
  font-display: swap;
}
body { font-family: "Source Han Sans SC", "PingFang SC", sans-serif; }
```
> 网页发布建议先转 **WOFF2**（体积约为 OTF 的 1/4、加载更快）。需要的话我可以帮你批量转换并入库。

## Git 说明

`.otf` 字体二进制（共约 110MB）**不入库**（见根 `.gitignore`），因其体积大且可从官方复现。本目录只版本化 README 与 LICENSE。

**复现下载：**
```bash
cd assets/fonts
curl -L -o SourceHanSansSC.zip \
  https://github.com/adobe-fonts/source-han-sans/releases/download/2.004R/SourceHanSansSC.zip
unzip SourceHanSansSC.zip && mv OTF/SimplifiedChinese/*.otf . && rm -rf OTF SourceHanSansSC.zip
```
