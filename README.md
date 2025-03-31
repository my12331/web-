<!DOCTYPE html>
<html>
<head>
    <title>我的前端作品集</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            margin: 10px 0;
            transition: transform 0.3s;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>欢迎来到我的学习空间</h1>
        <p>Web前端开发课程作品展示</p>
    </header>
    
    <section class="projects">
        <div class="project-card">
            <h3>项目1：个人简历</h3>
            <p>使用HTML+CSS制作的响应式简历</p>
            <a href="#">查看项目</a>
        </div>
        <!-- 更多项目卡片... -->
    </section>
</body>
</html>
