botw_Translation是塞尔达旷野之息的中文汉化项目
我的网站:
http://chdong.top/
http://game.cgcss.com/

码云分发:
https://gitee.com/joyist2019/BOTW

export_txt目录——包含2个程序“export_txt.exe”和“export_init.exe”

   export_txt.exe ——程序功能：
	首先读取..\import_txt\zelda breath of the wild.xls 中的翻译，
	然后扫描export_txt\en文件中的msbt文件，最后生成export_txt\zelda breath of the wild.xls

   export_init.exe ——程序功能：
	扫描en和cn中的msbt，最后生成export_txt\zelda breath of the wild.xls

import_txt 目录——包含2个程序 “import_txt.exe”和“批量封包.bat"
首先解压缩xls_extract.7z到import_txt 目录，得到zelda breath of the wild.xls，才能正常工作。必须的步骤。

    import_txt.exe ——程序功能：
	首先读取..\import_txt\zelda breath of the wild.xls 中的翻译，
	然后在import_txt\cn文件夹中重新生成翻译过的msbt文件。import.bat是把错误日志记录到1.txt文本里


   Bulk_packet批量封包.bat ——脚本功能：
	自动打包msbt文件名字为cn.sarc。
