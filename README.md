<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人网站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        header {
            text-align: center;
            padding: 50px 0;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 5px solid white;
        }
        section {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        .projects {
            display: grid;
            grid-gap: 20px;
        }
        .project-card {
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            color: #666;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <img src="your-avatar.jpg" alt="头像" class="avatar">
        <h1>刘锦林的个人网站</h1>
        <p>Web开发者 | 技术不爱好者</p>
    </header>

    <section id="about">
        <h2>关于我</h2>
        <p>我是刘锦林，一个人。
    </section>

    <section id="projects">
        <h2>我的项目</h2>
        <div class="projects">
            <div class="project-card">
                <h3>项目一</h3>
                <p>这是一个使用Vue.js构建的电子商务平台</p>
                <a href="#">查看项目</a>
            </div>
            <div class="project-card">
                <h3>项目二</h3>
                <p>基于Python的博客系统</p>
                <a href="#">查看项目</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>联系我</h2>
        <ul>
            <li>GitHub:2024303120063 <a href="https://github.com/yourusername">@yourusername</a></li>
            <li>Email: 1992662529@qq.com<a href="mailto:your.email@example.com">your.email@example.com</a></li>
           
        </ul>
    </section>

    <footer>
        <p>© 2024303120063 刘锦林 保留所有权利</p>
    </footer>
</body>
</html>
