# Wordpress .xml转换为PDF&DOC

## Info 
有的时候可能会导致找不到博客文章，虽然在有备份意识的情况下概率极小，但这个工具给了一种快速从Wordpress xml内容备份文件恢复文章的方法。
使用前请关闭或停止杀毒软件。

使用教程
准备：在下载前请 关闭or停止WindowsDefender 或其它杀毒软件，然后从Github下载原版软件，同时你需要准备好要转换的Wordpress .xml 文件。

开始：

打开 Wordpress2Doc 应用主程序。
点击 Load Wordpress export xml 按钮后，Open想要转换的.xml文件
此时会进入Choose articles选项卡，页面已经列出该文件下所有文章，可以勾选或取消勾选文章名前选框以选择想转换的文章，若单机文章名可以html或text在右侧预览。
选择完成后单击 Convert and export 选项卡。
在Convert and export选项卡页，可通过相应格式开关选择导出格式，也可选择是否将所有文章导出至一个文档。
准备完成后单击 Convert Choose articles 按钮并选择导出位置，等待软件提示 “Sir I'm done” 即表示完成。



Wordpress2Doc is a small tool which helps to convert Wordpress articles/blog-posts to .docx and/or .pdf files.
It's more a proof of concept, than the perfect solution, but it finally works.

Feel free to grab-up/fork the project and make it better!

For more information visit:

(german) => http://code-bude.net/2013/08/31/wordpress2doc-wordpress-artikel-in-word-und-pdf-dokumente-konvertieren/

(english) => http://en.code-bude.net/2013/08/31/wordpress2doc-how-to-convert-wordpress-articles-into-word-and-pdf-documents/



## Legal information and credits

Wordpress2Doc is project by [Raffael Herrmann](http://raffaelherrmann.de) and was first released 
in 08/2013.

### Special thanks

#### Technology

Michael Bielski -> Information about .docx-processing
http://www.codeproject.com/Articles/91894/HTML-as-a-Source-for-a-DOCX-File

gmanny -> Pechkin (.NET Wrapper for WkHtmlToPdf - used before)
https://github.com/gmanny/Pechkin

tuespetre -> TuesPechkin (.NET Wrapper for WkHtmlToX)
https://github.com/tuespetre/TuesPechkin

Andre Loker -> How to load fonts in memory
http://blog.andreloker.de/post/2008/07/03/Load-a-font-from-disk-stream-or-byte-array.aspx


#### Graphics & Design

Sven Walter (viperneo) -> MetroFramework
https://github.com/viperneo/winforms-modernui

thielj -> Fork and additions to the MetroFramework
https://github.com/thielj/MetroFramework

Oliver Scholtz (and others) -> For the Wordpress2Doc app icon
http://schollidesign.deviantart.com/art/Human-O2-Iconset-105344123

#### Pictograms & Arrows
http://modernuiicons.com
http://zwibbler.com

#### Fonts
"FG Virgil" by http://fontgarden.com
