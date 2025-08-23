<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README Generator</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;500;600;700&family=Inter:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
        }
        
        .code-block {
            background: #1e293b;
            border: 1px solid #334155;
            font-family: 'JetBrains Mono', monospace;
        }
        
        .copy-btn {
            transition: all 0.2s ease;
        }
        
        .copy-btn:hover {
            background: #3b82f6;
            transform: translateY(-1px);
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #3b82f6, #8b5cf6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
    </style>
</head>
<body class="min-h-screen text-white">
    <div class="max-w-4xl mx-auto px-6 py-12">
        <!-- Header -->
        <div class="text-center mb-12">
            <h1 class="text-4xl font-bold gradient-text mb-4">GitHub README Generator</h1>
            <p class="text-gray-300 text-lg">Professional Markdown README for your GitHub profile</p>
        </div>

        <!-- Instructions -->
        <div class="bg-slate-800 rounded-lg p-6 mb-8 border border-slate-600">
            <h2 class="text-xl font-semibold mb-4 flex items-center gap-2">
                <span class="text-2xl">📋</span>
                How to use this README
            </h2>
            <div class="space-y-3 text-gray-300">
                <p><strong>1.</strong> Copy the markdown code below</p>
                <p><strong>2.</strong> Go to your GitHub repository</p>
                <p><strong>3.</strong> Create a new file called <code class="bg-slate-700 px-2 py-1 rounded text-blue-400">README.md</code></p>
                <p><strong>4.</strong> Paste the code and commit</p>
                <p><strong>5.</strong> Your professional README is ready! 🎉</p>
            </div>
        </div>

        <!-- Generated README -->
        <div class="bg-slate-800 rounded-lg border border-slate-600 overflow-hidden">
            <div class="flex items-center justify-between bg-slate-700 px-4 py-3 border-b border-slate-600">
                <span class="text-sm font-medium">README.md</span>
                <button onclick="copyToClipboard()" class="copy-btn bg-blue-600 hover:bg-blue-500 px-3 py-1 rounded text-sm font-medium">
                    Copy Code
                </button>
            </div>
            <div class="code-block p-6 overflow-x-auto">
                <pre id="readme-code" class="text-sm text-gray-300 whitespace-pre-wrap"># Hi there, I'm Harshit Sharma 👋

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Frontend+Developer+%F0%9F%92%BB;UI%2FUX+Enthusiast+%F0%9F%8E%A8;React+Developer+%E2%9A%9B%EF%B8%8F;Problem+Solver+%F0%9F%A7%A9" alt="Typing SVG" />
</div>

<div align="center">
  
  [![GitHub followers](https://img.shields.io/github/followers/HarshitOnLoop?style=for-the-badge&color=58A6FF&labelColor=1C2128)](https://github.com/HarshitOnLoop)
  [![GitHub stars](https://img.shields.io/github/stars/HarshitOnLoop?style=for-the-badge&color=FFA500&labelColor=1C2128)](https://github.com/HarshitOnLoop)
  [![Profile views](https://komarev.com/ghpvc/?username=HarshitOnLoop&style=for-the-badge&color=brightgreen&labelColor=1C2128)](https://github.com/HarshitOnLoop)
  
</div>

## 🚀 About Me

<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'973c44ee212ab232',t:'MTc1NTk2OTUwOC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script>
