# HTML-4-
HTML样式，格式化，引用
//HTML样式
    //HTML的style属性
    //style属性的作用：提供了一种改变所有HTML元素的样式的通用的方法
    
    //不赞成使用的标签和属性
    //标签：
    //1.<center>-定义居中的内容
    //2.<font><basefont>-定义HTML字体
    //3.<s>和<strike>-定义删除线文本
    //4.<u>-定义下划线文本
    //属性：
    //1.align-定义文本的对齐方式
    //2.bgcolor-定义背景颜色
    //3.color定义文本颜色
    //对于以上标签和属性需要使用样式代替
    <html>
    <body style="background-color:yellow">
    <he style="background-color:red">This is a heading</h2>
    <p style="background-color:green">This is a paragraph.</p>
    </body>
    </html>
    
    //HTML样式实例-字体、颜色和尺寸
    //font-family、color以及font-size属性分别定义元素中文本的字体系列、颜色和字体尺寸：
    <html>
    <body>
    <h1 style=font-family:verdana">A heading</h1>
    <p style="font-family:arial;color:red;font-size20px;">A paragraph.</p>
    </body>
    </html>
    
    //HTML样式实例-文本对齐
    //text-align属性规定了元素中文本的水平对齐方式：
    <html>
    <body>
    <h1 style="text-align:center">This is a heading</h1>
    <p>The heading above is align to the center of this page.</p>
    </body>
    <html>
    
//HTML文本格式化
//以下是HTML文本格式化实例
    //HTML可定义很多供格式化输出的元素，比如斜体和粗体字
    <html>
    <body>
    <b>This text is bold</b>//定义粗体文本
    <br />
    <strong>This text is strong</strong>//定义加重语气
    <br />
    <big>This text is big</big>//定义大号字
    <br />
    <em>This text is emphasized</em>//定义着重文字
    <br />
    <i>This text is italic</i>//定义斜体字
    <br />
    <small>This text is small</small>//定义小体字
    <br />
    This text contains
    <sub>subscript</sub>//定义下标字
    <br />
    This text contains
    <sup>superscript</sup>//定义上标字
    </body>
    </html>
    
    //预格式文本
    <html>
    <body>
    <pre>
    这是
    预格式文本。
    它保留了    空格
    和换行
    </pre>
    <p>pre标签很适合显示计算机代码</p>
    
    <pre>
    for i=1 to 10
        print i
    next i
    </pre>
    </body>
    </html>
    
    //“计算机输出”标签
    <html>
    <body>
    <code>Computer code</code>//定义计算机代码
    <br />
    <kbd>Keyboard input</kbd>//定义键盘码
    <br />
    <tt>Teletype text</tt>//定义打字机代码
    <br />
    <samp>Sample text</samp>//定义计算机码样本
    <br />
    <var?Computer variable</var>//定义变量
    <br />
    <p>
    <b>注释：</b>这些标签常用于显示计算机/编程代码
    </p>
    </body>
    </html>
    
    //地址
    <html>
    <body>
    
    <address>//定义地址
    Written by <a href="mailto:webmaster@example.com">Donald
    Duck</a>.<br>
    Visit us at:<br>
    Example.com<br>
    Box 564,Disneyland<br>
    USA
    </address>
    
    </body>
    </html>
    
    //缩写和首字母缩写
    <html>
    
    <body>
    
    <abbr title="etcetera">etc.</abbr>//定义缩写
    <br />
    <acronym title="World Wide Web">WWW</acronym>//定义首字母缩写
    <p>在某些浏览器中，当您把鼠标移至缩略词语上时，title可用于展示表达的完整版本。</p>
    <p>仅对于IE 5 中的acronym元素有效</p>
    
    <p>对于Netscape 6.2中的abbr和acronym元素都有效。</p>
    
    </body>
    </html>
    
    //文字方向
    <html>
    
    <body>
    
    <p>
    如果您的浏览器支持 bi-directional override(bdo),下一行会从右向左输出(rtl);
    </p>
    
    <bdo dir="rtl">//定义文字方向
    Here is some Hebrew text
    </bdo>
    
    </body>
    </html>
 
    //块引用
    //<blockquote>是长引用，使用这个元素浏览器会自动插入换行和外边距，而短引用q元素则不会有任何呈现
    
    //删除字效果和插入字效果
    <html>
    
    <body>
    
    <p>一打有<del>二十</del><ins>十二</ins>件。</p>
    
    <html>
    <body>
    
    <p><abbr title="World Health Organization">WHO</abbr>成立于1948年。</p>
    
    <p>对缩写进行标记能够为浏览器、翻译系统以及搜索引擎提供有用的信息</p>
    
    </body>
    </html>
    //<dfn>有同样的功能
    //<dfn>一般用起来比较复杂，想简化直接用第一条，功能都是一样的
    
    //用于著作标题的HTML<cite>
    //浏览器通常会以斜体显示<cite>元素
    
    
    
    
    
    
