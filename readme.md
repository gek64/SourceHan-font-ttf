# 思源字体 `TTF` 版本
- 方便`Kodi`等只支持`ttf`字体的软件使用
- 使用`github action`进行自动转换

## 思源字体包含
- [思源黑体](https://github.com/adobe-fonts/source-han-sans) SC
- [思源宋体](https://github.com/adobe-fonts/source-han-serif) SC
- 思源黑体 SC TTF
- 思源宋体 SC TTF

## 转换处理细节
- 仅转换SC版本 `SourceHanSansSC` `SourceHanSerifSC`, `SC`版本指的是简体中文版
- 使用[otf2ttf](https://github.com/awesometoolbox/otf2ttf) 进行转换
- 因为`otf2ttf`运行效率低下, 且无多线程, github actions 转换一个otf文件大概需要3-5分钟, 完成思源黑体+思源宋体两组14个字重的字体转换大概需要40分钟左右

## 开源协议
- 本项目采用[MIT协议](https://github.com/gek64/SourceHan-font-ttf/raw/main/LICENSE)
