<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dalí Interactive Lessons</title>
    <style>
        body {
            font-family: 'Signika', 'DIN 2014', Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #231f20 0%, #565759 100%);
            min-height: 100vh;
            color: white;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }
        
        h1 {
            color: #cd234c;
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 10px;
            font-family: 'DIN 2014', Arial, sans-serif;
        }
        
        .subtitle {
            text-align: center;
            color: #eab06b;
            font-size: 1.2em;
            margin-bottom: 40px;
            font-style: italic;
            font-family: 'Baskerville', Georgia, serif;
        }
        
        .lesson-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .lesson-card {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
            color: #231f20;
        }
        
        .lesson-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.3);
        }
        
        .lesson-card h3 {
            color: #cd234c;
            margin-bottom: 15px;
            font-size: 1.4em;
            font-family: 'DIN 2014', Arial, sans-serif;
        }
        
        .lesson-card p {
            color: #565759;
            margin-bottom: 15px;
        }
        
        .features {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            margin: 15px 0;
            border-left: 4px solid #7ba550;
        }
        
        .features strong {
            color: #231f20;
            font-family: 'DIN 2014', Arial, sans-serif;
        }
        
        .lesson-link {
            display: inline-block;
            background: linear-gradient(45deg, #cd234c, #233e99);
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 25px;
            font-weight: bold;
            transition: all 0.3s ease;
            font-family: 'DIN 2014', Arial, sans-serif;
            text-transform: uppercase;
            font-size: 0.9em;
            letter-spacing: 1px;
        }
        
        .lesson-link:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(205, 35, 76, 0.4);
        }
        
        .intro {
            background: rgba(255, 255, 255, 0.1);
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 30px;
            border-left: 4px solid #53c8e9;
        }
        
        .artwork-preview {
            text-align: center;
            margin: 30px 0;
        }
        
        .artwork-preview img {
            max-width: 400px;
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
        }
        
        .canvas-tip {
            background: rgba(234, 176, 107, 0.2);
            border: 2px solid #eab06b;
            border-radius: 10px;
            padding: 20px;
            margin-top: 30px;
        }
        
        .canvas-tip h4 {
            color: #eab06b;
            margin-bottom: 10px;
            font-family: 'DIN 2014', Arial, sans-serif;
        }
        
        code {
            background: rgba(0,0,0,0.2);
            padding: 2px 6px;
            border-radius: 4px;
            font-family: 'Courier New', monospace;
            color: #53c8e9;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Dalí Interactive Lessons</h1>
        <p class="subtitle">Exploring "The Persistence of Memory" through Interactive Learning</p>
        
        <div class="intro">
            <p>Three different interactive approaches to Salvador Dalí's most famous masterpiece. Each lesson uses the same educational framework but offers different levels of interactivity and engagement.</p>
        </div>
        
        <div class="artwork-preview">
            <img src="https://upload.wikimedia.org/wikipedia/en/d/dd/The_Persistence_of_Memory.jpg" 
                 alt="The Persistence of Memory by Salvador Dalí (1931)">
            <p style="margin-top: 10px; font-style: italic; opacity: 0.8;">
                "The Persistence of Memory" (1931) - Oil on canvas, 24 × 33 cm
            </p>
        </div>
        
        <div class="lesson-grid">
            <div class="lesson-card">
                <h3>Simple Page Version</h3>
                <p>Clean, accessible design perfect for Canvas LMS integration. Features tab-based navigation with consistent branding.</p>
                
                <div class="features">
                    <strong>Best for:</strong> Canvas embedding, accessibility compliance<br>
                    <strong>Features:</strong> Tab navigation, mobile-responsive, screen reader friendly
                </div>
                
                <a href="simple_page_dali.html" class="lesson-link">Start Learning</a>
            </div>
            
            <div class="lesson-card">
                <h3>Split-Screen Storytelling</h3>
                <p>Immersive experience with the artwork on one side and progressive content revelation on the other.</p>
                
                <div class="features">
                    <strong>Best for:</strong> Storytelling, guided discovery<br>
                    <strong>Features:</strong> Synchronized highlighting, smooth transitions, navigation dots
                </div>
                
                <a href="split_screen_dali.html" class="lesson-link">Explore Story</a>
            </div>
            
            <div class="lesson-card">
                <h3>Layered Discovery</h3>
                <p>Interactive hotspot exploration where learners discover information by clicking on different areas of the painting.</p>
                
                <div class="features">
                    <strong>Best for:</strong> Self-paced exploration, gamified learning<br>
                    <strong>Features:</strong> Clickable hotspots, progress tracking, layered content
                </div>
                
                <a href="layered_discovery_dali.html" class="lesson-link">Discover Art</a>
            </div>
        </div>
        
        <div class="canvas-tip">
            <h4>🎯 For Canvas Users</h4>
            <p>Embed the Simple Page Version using this iframe code:</p>
            <code>&lt;iframe src="https://kkelley-collab.github.io/-dali-interactive-lessons/simple_page_dali.html" width="100%" height="800px" frameborder="0"&gt;&lt;/iframe&gt;</code>
        </div>
    </div>
</body>
</html>
