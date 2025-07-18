<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rust Code Typing Effect - No JS</title>
    <style>
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            font-family: 'Fira Code', 'Consolas', monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        
        .code-container {
            background-color: #161b22;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            width: 80%;
            max-width: 600px;
            border: 1px solid #30363d;
        }
        
        .code-header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid #30363d;
        }
        
        .dot {
            height: 12px;
            width: 12px;
            border-radius: 50%;
            margin-right: 6px;
        }
        
        .red { background-color: #ff5f56; }
        .yellow { background-color: #ffbd2e; }
        .green { background-color: #27c93f; }
        
        .filename {
            margin-left: 10px;
            color: #7d8590;
            font-size: 14px;
        }
        
        .code-content {
            font-size: 16px;
            line-height: 1.5;
        }
        
        .line {
            margin: 0;
            padding: 0;
            white-space: pre;
            overflow: hidden;
            animation: typing 2s steps(30, end), blink 0.5s step-end infinite alternate;
            width: 0;
        }
        
        .line:nth-child(1) { animation-delay: 0.5s, 0.5s; animation-fill-mode: forwards; }
        .line:nth-child(2) { animation-delay: 1.5s, 1.5s; animation-fill-mode: forwards; }
        .line:nth-child(3) { animation-delay: 2.5s, 2.5s; animation-fill-mode: forwards; }
        .line:nth-child(4) { animation-delay: 3.5s, 3.5s; animation-fill-mode: forwards; }
        
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        
        @keyframes blink {
            50% { border-color: transparent; }
        }
        
        .keyword { color: #ff7b72; }
        .function { color: #d2a8ff; }
        .macro { color: #ffab70; }
        .string { color: #a5d6ff; }
        .comment { color: #8b949e; }
        .punctuation { color: #c9d1d9; }
    </style>
</head>
<body>
    <div class="code-container">
        <div class="code-header">
            <div class="dot red"></div>
            <div class="dot yellow"></div>
            <div class="dot green"></div>
            <div class="filename">main.rs</div>
        </div>
        <div class="code-content">
            <p class="line"><span class="keyword">fn</span> <span class="function">main</span><span class="punctuation">()</span> <span class="punctuation">{</span></p>
            <p class="line">    <span class="macro">println!</span><span class="punctuation">(</span><span class="string">"Hello, world!"</span><span class="punctuation">);</span></p>
            <p class="line"><span class="punctuation">}</span></p>
            <p class="line"><span class="comment">// Rust code successfully executed!</span></p>
        </div>
    </div>
</body>
<div align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Ubuntu&size=30&duration=2000&pause=500&center=true&width=435&lines=Hi%EF%BC%81I%60m+lhyz1024.;Nice+to+meet+you!" alt="Typing SVG" /></a>
</div>

<h4>编程语言：</h4>
<p align="left">
  <img src="https://ziadoua.github.io/m3-Markdown-Badges/badges/Rust/rust3.svg" alt="Rust" width="80" height="80" title="Rust">
  <img src="https://ziadoua.github.io/m3-Markdown-Badges/badges/Python/python3.svg" alt="Python" width="100" height="100" title="Python">
  <img src="https://ziadoua.github.io/m3-Markdown-Badges/badges/HTML/html3.svg" alt="HTML" width="100" height="100" title="HTML5">
  <img src="https://ziadoua.github.io/m3-Markdown-Badges/badges/Javascript/javascript3.svg" alt="JavaScript" width="120" height="120" title="JavaScript">
</p>
<h4>常用工具：</h4>
<p align="left">
  <img alt="Justfile" src="https://img.shields.io/badge/-Justfile-000000?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/TOML-F05032?style=flat-square&logo=TOML&logoColor=white" alt="TOML" >
  <img src="https://img.shields.io/badge/Nix%20Flakes-5277C3?style=flat-square&logo=nixos&logoColor=white" alt="Nix Flakes" >
  <img alt="Git" src="https://ziadoua.github.io/m3-Markdown-Badges/badges/Git/git1.svg" height="25" />
</p>
<h4>环境：</h4>
<p align="left">
  <img alt="Linux" src="https://ziadoua.github.io/m3-Markdown-Badges/badges/Linux/linux3.svg" height="25" />
  <img alt="NixOS" src="https://img.shields.io/badge/-NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white">
</p>
<div align="left">
<span>&emsp;&emsp;</span>
<img height="170px" src="https://github-readme-stats.vercel.app/api?username=lhyz1024" /><img height="170px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lhyz1024&layout=compact&langs_count=8" />
<span>&emsp;&emsp;</span>
</div>
