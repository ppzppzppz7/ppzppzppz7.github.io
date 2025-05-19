
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>彭培真 - 个人主页</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', sans-serif; line-height: 1.6; color: #333; background: #f5f5f5; }
        
        .container { max-width: 1000px; margin: 0 auto; padding: 20px; }
        
        header { 
            text-align: center; 
            padding: 40px 0; 
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        h1 { font-size: 2.5em; margin-bottom: 10px; }
        
        section { 
            background: white; 
            padding: 25px; 
            margin-bottom: 25px; 
            border-radius: 8px; 
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        h2 { 
            color: #3498db; 
            border-bottom: 2px solid #eee; 
            padding-bottom: 10px; 
            margin-bottom: 15px;
        }
        
        .timeline { margin-left: 20px; }
        .timeline-item { margin-bottom: 25px; }
        .timeline-date { color: #666; font-size: 0.9em; }
        
        ul { padding-left: 25px; }
        li { margin-bottom: 8px; }
        
        .skills { display: flex; gap: 15px; flex-wrap: wrap; }
        .skill-tag {
            background: #e8f4ff;
            padding: 6px 12px;
            border-radius: 15px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>彭培真</h1>
            <p>华中师范大学经济学专业本科生</p>
        </header>

        <section>
            <h2>教育背景</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-date">2022.09 - 至今</div>
                    <h3>华中师范大学 经济学专业</h3>
                    <p>主修课程：会计学、财政学、市场营销学、经济法、企业战略管理等</p>
                </div>
            </div>
        </section>

        <section>
            <h2>校园经历</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-date">2022.10 - 2024.06</div>
                    <h3>校学生会权益服务中心 工作人员</h3>
                    <ul>
                        <li>策划执行校园安全文化节（参与1800+人次）</li>
                        <li>组织校园调研大赛（收集1100+问卷，推动4项改进措施）</li>
                        <li>协调校领导午餐会，推动13项学生提案落实</li>
                    </ul>
                </div>
                <!-- 其他经历模块结构类似 -->
            </div>
        </section>

        <section>
            <h2>技能证书</h2>
            <div class="skills">
                <span class="skill-tag">CET-4</span>
                <span class="skill-tag">全国计算机二级</span>
                <span class="skill-tag">Office 办公软件</span>
                <span class="skill-tag">SPSS/Stata</span>
            </div>
        </section>
    </div>
</body>
