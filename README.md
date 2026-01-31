# snwiki.dpdns.org
My personal blog
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>欢迎来到春屿</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f8f0;
            font-family: 'Microsoft YaHei', 'Segoe UI', sans-serif;
        }
        
        .container {
            text-align: center;
            padding: 40px;
            max-width: 800px;
            width: 100%;
        }
        
        .main-title {
            font-size: 4.5rem;
            font-weight: 700;
            color: #2c5530;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.1);
            letter-spacing: 2px;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .subtitle {
            font-size: 1.8rem;
            color: #5a9367;
            margin-top: 10px;
            font-weight: 300;
            letter-spacing: 1px;
        }
        
        .divider {
            height: 3px;
            width: 200px;
            background: linear-gradient(to right, transparent, #5a9367, transparent);
            margin: 30px auto;
        }
        
        .description {
            font-size: 1.2rem;
            color: #5a7c5a;
            line-height: 1.6;
            margin-top: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        
        /* 响应式调整 */
        @media (max-width: 768px) {
            .main-title {
                font-size: 3rem;
            }
            
            .subtitle {
                font-size: 1.4rem;
            }
            
            .description {
                font-size: 1.1rem;
                padding: 0 20px;
            }
        }
        
        @media (max-width: 480px) {
            .main-title {
                font-size: 2.5rem;
                letter-spacing: 1px;
            }
            
            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="main-title">欢迎来到春屿</h1>
        <p class="subtitle">春天的岛屿，心灵的栖息地</p>
        
        <div class="divider"></div>
        
        <p class="description">
            春屿是一个想象中的春日岛屿，这里四季如春，鲜花盛开，湖水清澈，鸟语花香。
            在这里，您可以暂时远离尘嚣，享受片刻的宁静与美好。
        </p>
    </div>
</body>
</html>
