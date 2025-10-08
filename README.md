<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayesha System</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            color: white;
            margin-bottom: 30px;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .app-frame {
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .app-frame iframe {
            width: 100%;
            height: 70vh;
            border: none;
        }
        
        .footer {
            text-align: center;
            color: white;
            margin-top: 20px;
            opacity: 0.8;
        }
        
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .app-frame iframe {
                height: 80vh;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Ayesha System</h1>
            <p>आपका विश्वसनीय डेटा प्रोसेसिंग सिस्टम</p>
        </div>
        
        <div class="app-frame">
            <iframe src="YOUR_APPS_SCRIPT_URL_HERE" 
                    title="Ayesha System Application"
                    allow="autoplay; encrypted-media">
            </iframe>
        </div>
        
        <div class="footer">
            <p>© 2024 Ayesha System. All rights reserved.</p>
        </div>
    </div>
</body>
</html>
