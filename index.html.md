<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>EasyLife | Daily Solutions</title>  
    <style>  
        :root {  
            --primary: #2563eb;  
            --bg: #f8fafc;  
            --card-bg: #ffffff;  
            --text: #1e293b;  
        }  
  
        body {  
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
            background-color: var(--bg);  
            color: var(--text);  
            margin: 0;  
            padding: 0;  
        }  
  
        header {  
            background: linear-gradient(135deg, #1e3a8a, #2563eb);  
            color: white;  
            padding: 2rem 1rem;  
            text-align: center;  
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);  
        }  
  
        .container {  
            max-width: 1200px;  
            margin: 2rem auto;  
            padding: 0 1rem;  
        }  
  
        .hero-text {  
            margin-bottom: 2rem;  
        }  
  
        /* Search Bar */  
        .search-box {  
            width: 100%;  
            max-width: 600px;  
            padding: 1rem;  
            border-radius: 50px;  
            border: 1px solid #ddd;  
            display: block;  
            margin: -30px auto 2rem;  
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);  
            font-size: 1rem;  
        }  
  
        /* Solution Grid */  
        .grid {  
            display: grid;  
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));  
            gap: 1.5rem;  
        }  
  
        .card {  
            background: var(--card-bg);  
            padding: 1.5rem;  
            border-radius: 15px;  
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);  
            transition: transform 0.2s, box-shadow 0.2s;  
            cursor: pointer;  
            border: 1px solid #e2e8f0;  
        }  
  
        .card:hover {  
            transform: translateY(-5px);  
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);  
        }  
  
        .icon {  
            font-size: 2rem;  
            margin-bottom: 1rem;  
        }  
  
        .card h3 {  
            margin: 0 0 0.5rem 0;  
            color: var(--primary);  
        }  
  
        .card p {  
            font-size: 0.9rem;  
            line-height: 1.5;  
            color: #64748b;  
        }  
  
        footer {  
            text-align: center;  
            padding: 3rem;  
            color: #94a3b8;  
        }  
    </style>  
</head>  
<body>  
  
<header>  
    <h1>EasyLife Solutions</h1>  
    <p>Making your daily routine effortless.</p>  
</header>  
  
<input type="text" class="search-box" placeholder="What can we solve for you today?">  
  
<div class="container">  
    <div class="grid">  
        <div class="card">  
            <div class="icon">📅</div>  
            <h3>Smart Meal Planner</h3>  
            <p>Generate a healthy weekly meal plan based on your diet in seconds.</p>  
        </div>  
  
        <div class="card">  
            <div class="icon">💰</div>  
            <h3>Expense Tracker</h3>  
            <p>Snap a photo of your bills and let AI organize your monthly spending.</p>  
        </div>  
  
        <div class="card">  
            <div class="icon">🧘</div>  
            <h3>1-Min Wellness</h3>  
            <p>Quick guided breathing and eye-rest exercises for busy workers.</p>  
        </div>  
  
        <div class="card">  
            <div class="icon">⚡</div>  
            <h3>Task Automator</h3>  
            <p>Connect your apps to handle repetitive emails and schedules.</p>  
        </div>  
  
        <div class="card">  
            <div class="icon">🛠️</div>  
            <h3>Unit Converter</h3>  
            <p>Instantly convert weight, length, or currency for travel and work.</p>  
        </div>  
  
        <div class="card">  
            <div class="icon">✍️</div>  
            <h3>AI Summary</h3>  
            <p>Paste long articles and get the key points in 3 bullet points.</p>  
        </div>  
    </div>  
</div>  
  
<footer>  
    <p>&copy; 2026 EasyLife Hub. Designed for Efficiency.</p>  
</footer>  
  
</body>  
</html>  
