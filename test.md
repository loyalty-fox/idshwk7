1.test.bmp为载体图片，1.txt中为待隐藏信息，test.bmp.hide.bmp为嵌入后图片，from bmp.txt为提取信息
2.将1.txt文本隐藏进test.bmp，读取载体图片大小(宽高和比特数)，判断文本是否过长，嵌入待隐藏信息，生成test.bmp.hide.bmp,调用showtxtFile函数提取隐藏信息写入from bmp.txt
