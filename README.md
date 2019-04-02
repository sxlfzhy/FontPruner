# FontPruner

## use

1. 修改`input/Chinese.txt`文件中的内容为需要支持的中文字符，包括中文标点符号，数字等；
2. 修改`input/unchinese.txt`文件中的内容为需要支持的非中文字符；
3. 将源字体放置在当前目录中，如：HanziPen.ttf；
4. 执行命令：`python FontPruner.py --inputPath="input" --inputFont="HanziPen.ttf"`；
5. 在目录`tmp/output`目录中会有精简后的字体。
