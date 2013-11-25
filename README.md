<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML标准控件</title>
  <style>
    .one-control{
      padding: 10px;
    }
  </style>
</head>
<body>
  <form action="">
    <div class="one-control">
      <label for="text">单行文本框:</label>
      <input id="text" name="text" type="text" placeholder="占位文字只在HTML5下有效" size="30">
    </div>
    <div class="one-control">
      <label for="password">密码输入:</label>
      <input id="password" name="password" type="password" size="30">
    </div>
    <div class="one-control">
      <label>多选框:</label>
      <input name="checkbox" type="checkbox" id="checkbox1"> <label for="checkbox1">美国</label>
      <input name="checkbox" type="checkbox" id="checkbox2"> <label for="checkbox2">中国</label>
    </div>
    <div class="one-control">
      <label>单选框:</label>
      <input name="radio" type="radio" id="radio1"> <label for="radio1">男</label>
      <input name="radio" type="radio" id="radio2"> <label for="radio2">女</label>
    </div>
    <div class="one-control">
      <label>单选下拉列表:</label>
      <select name="" id="">
        <option value="">武汉</option>
        <option value="">深圳</option>
      </select>
    </div>
    <div class="one-control">
      <label>多选下拉列表:</label>
      <select name="" id="" multiple="true">
        <option value="">武汉</option>
        <option value="">深圳</option>
      </select>
    </div>
    <div class="one-control">
      <label>文件:</label>
      <input name="file" type="file" id="file">
    </div>
    <div class="one-control">
      <label for="textarea">片段输入:</label>
      <textarea name="textarea" cols="30" rows="10">用于输入文字片段</textarea>
    </div>
    <div class="one-control">
      <label>提交按钮:</label>
      <input name="submit" type="submit" id="submit" value="提交">
    </div>
    <div class="one-control">
      <label>按钮:</label>
      <button>提交</button>
    </div>
  </form>
  <div class="one-control">
    <h1>H1</h1>
    <h2>H2</h2>
    <h3>H3</h3>
    <h4>H4</h4>
    <h5>H5</h5>
    <h6>H6</h6>
  </div>
  <div class="one-control">
    <h4>蛋炒饭需要的食材</h4>
    <ul>
      <li>鸡蛋</li>
      <li>油</li>
      <li>米</li>
    </ul>
  </div>
  <div class="one-control">
    <h4>成为一名程序大师所必须的步骤</h4>
    <ol>
      <li>打开电脑</li>
      <li>打开编辑器</li>
      <li>敲键盘</li>
      <li>编译运行</li>
      <li>发布到网站然后吹自己的代码是遵循了某种规范</li>
      <li>写一本书</li>
      <li>完成</li>
    </ol>
  </div>
  <div class="one-control">
    <a href="http://www.pathsource.com">这是一个标准的超链接</a>
  </div>
  <div class="one-control">
    <b>粗文本</b>
  </div>
  
  <div class="one-control">
    <blockquote>这是一段引用</blockquote>
  </div>
  <div class="one-control">
    好员工的标准是<del>每天打酱油</del>认真完成自己的工作
  </div>
  <div class="one-control">
    分割线
    <hr>
  </div>
  <div class="one-control">
    <i>斜体字</i>
  </div>
</body>
</html>
