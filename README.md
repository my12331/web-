<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>摄影摄像技术课程</title>
    <style>
        /* 基础样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }
        
        body {
            background: url('https://images.unsplash.com/photo-1516035069371-29a1b244cc32?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            min-height: 100vh;
            position: relative;
        }
        
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: -1;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            text-align: center;
            padding: 2rem 0;
            margin-bottom: 2rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        h2 {
            font-size: 1.8rem;
            margin: 1.5rem 0;
            color: #f8f8f8;
            border-left: 4px solid #3498db;
            padding-left: 1rem;
        }
        
        /* 模块卡片样式 */
        .module {
            background: rgba(30, 30, 30, 0.8);
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(5px);
        }
        
        /* 响应式布局 */
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>摄影摄像技术课程</h1>
            <p>探索视觉艺术的无限可能</p>
        </header>
        
        <!-- 教师简介模块 -->
        <section class="module">
            <h2>教师简介</h2>
            <div class="content">
                <!-- 内容占位 -->
            </div>
        </section>
        
        <!-- 学生名单模块 -->
        <section class="module">
            <h2>学生名单</h2>
            <div class="content">
                <!-- 内容占位 -->
            </div>
        </section>
        
        <!-- 课堂作业模块 -->
        <section class="module">
            <h2>课堂作业</h2>
            <div class="content">
                <!-- 内容占位 -->
            </div>
        </section>
        
        <!-- 课后作业模块 -->
        <section class="module">
            <h2>课后作业</h2>
            <div class="content">
                <!-- 内容占位 -->
            </div>
        </section>
    </div>
</body>
</html>

