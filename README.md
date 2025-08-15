# my-website
# 我的个人网站
欢迎来到我的网站！

## 关于我
我是 Rose Li，喜欢数据可视化和前端开发。

## 联系方式
- 邮箱：xxx@example.com
- GitHub：[RoseLi](https://github.com/你的用户名)

<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>我的 Tableau 图表</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }
    h1 {
      padding: 20px;
      color: #333;
    }
    .tableauPlaceholder {
      margin: auto;
      max-width: 1200px;
    }
  </style>
</head>
<body>
  <h1>我的 Tableau 图表</h1>

  <div class='tableauPlaceholder' id='tableauViz' style='position: relative'>
    <noscript>
      <a href='#'>
        <img alt='工作表 2' 
             src='https://public.tableau.com/static/images/_1/_17552694587720/2/1.png' 
             style='border: none' />
      </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='_17552694587720/2' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https://public.tableau.com/static/images/_1/_17552694587720/2/1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='zh-CN' />
    </object>
  </div>

  <script type='text/javascript'>
    var divElement = document.getElementById('tableauViz');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
  </script>

</body>
</html>
