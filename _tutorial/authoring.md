---
id: authoring
title: 新手教程编辑流程
---
# 新手教程编辑流程

## 开工！
在`_tutorial`目录中创建一个新的`.md`文件，插入以下内容：
<pre>
---
id: &lt;这里插入与文件名一致的英文页面ID&gt;
title: &lt;这里插入标题&gt;
---
# 标题
正文部分
</pre>
然后，在目录文件（`_data/tutorials.yml`）中的合适位置加入这个页面:
<pre>
－ &lt;页面ID&gt;
</pre>
保存，在命令行键入`jekyll serve`，然后用浏览器访问[http://localhost:4000/tutorial](http://localhost:4000/tutorial)，新页面就出现在目录中了！

<div class="note">
当你编辑时请继续保持Jekyll运行，它会实时渲染你的修改，只需刷新浏览器即可看到效果。
</div>

