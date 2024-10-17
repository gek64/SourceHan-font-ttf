# 思源字体 `TTF` 版本
- 方便`Kodi`等只支持`ttf`字体的软件使用
- 使用`github action`进行自动转换

## 思源字体包含
- [思源黑体](https://github.com/adobe-fonts/source-han-sans) SC TC OTF
- [思源宋体](https://github.com/adobe-fonts/source-han-serif) SC TC OTF
- 思源黑体 SC TC TTF
- 思源宋体 SC TC TTF

## 转换处理细节
- 仅转换 `SourceHanSansSC` `SourceHanSansTC` `SourceHanSerifSC` `SourceHanSerifTC`, `SC` 指的是简体中文版, `TC` 指的是繁体中文版
- 使用[otf2ttf](https://github.com/awesometoolbox/otf2ttf) 进行转换
- 请注意! 因为 `otf2ttf` 转换较为缓慢, github actions 转换一个 otf 文件大概需要 3-5 分钟, 完成思源黑体+思源宋体 4 组 28 个字重的字体转换需要比较长的时间, 可能会触发 github 免费版账户 github actions 使用时间限制

## 开源协议
- 本项目采用[MIT协议](https://github.com/gek64/SourceHan-font-ttf/raw/main/LICENSE)
