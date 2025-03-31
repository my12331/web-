<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web课程框架</title>
    <style>
        /* 基础样式重置 */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: Arial, sans-serif; line-height: 1.6; }
        
        /* 布局容器 */
        .container { max-width: 1200px; margin: 0 auto; padding: 20px; }
        
        /* 头部样式 */
        header { 
            background: #2c3e50; 
            color: white;
            padding: 1.5rem 0;
            text-align: center;
            margin-bottom: 20px;
        }
        
        /* 内容区块通用样式 */
        .section {
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 30px;
        }
        
        /* 教师简介区域 */
        .teacher-profile {
            display: flex;
            gap: 20px;
        }
        .teacher-photo { width: 150px; height: 150px; background: #eee; }
        .teacher-info { flex: 1; }
        
        /* 响应式调整 */
        @media (max-width: 768px) {
            .teacher-profile { flex-direction: column; }
            .teacher-photo { width: 100%; height: 200px; }
        }
    </style>
</head>
<body>
    <!-- 头部区域 -->
    <header>
        <div class="container">
            <h1>课程标题</h1>
            <p>课程副标题或学期信息</p>
        </div>
    </header>
    
    <!-- 主内容区 -->
    <div class="container">
        <!-- 1. 教师简介模块 -->
        <section class="section teacher-section">
            <h2>教师简介</h2>
            <div class="teacher-profile">
                <div class="teacher-photo"><!-- 照片占位 --></div>
                <div class="teacher-info">
                    <!-- 教师信息内容 -->
                </div>
            </div>
        </section>
        
        <!-- 2. 课堂作业模块 -->
        <section class="section assignments-section">
            <h2>课堂作业</h2>
            <div class="assignments-container">
                <!-- 作业列表内容 -->
            </div>
        </section>
        
        <!-- 3. 学生名单模块 -->
        <section class="section students-section">
            <h2>学生名单</h2>
            <div class="student-list">
                <!-- 学生名单内容 -->
            </div>
        </section>
        
        <!-- 4. 课后作业哲学选项 -->
        <section class="section philosophy-section">
            <h2>课后作业哲学</h2>
            <div class="philosophy-options">
                <!-- 单选选项内容 -->
            </div>
        </section>
    </div>
    
    <!-- 页脚 -->
    <footer class="section">
        <div class="container">
            <!-- 页脚内容 -->
        </div>
    </footer>
</body>
</html>
