<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌌 Echoes of the Loom | Cosmic Puzzle Adventure</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0a0a1a 0%, #1a1a2e 50%, #16213e 100%);
            color: #e6e6ff;
            line-height: 1.6;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(15, 15, 30, 0.9);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(100, 100, 255, 0.1);
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 30px;
            border-bottom: 2px solid rgba(100, 149, 237, 0.3);
        }
        
        .title {
            font-size: 3.5rem;
            background: linear-gradient(90deg, #6495ed, #9370db, #ba55d3);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 10px;
            text-shadow: 0 0 20px rgba(100, 149, 237, 0.5);
        }
        
        .tagline {
            font-size: 1.4rem;
            color: #b0b0ff;
            margin-bottom: 20px;
        }
        
        .quote {
            font-style: italic;
            color: #87ceeb;
            border-left: 3px solid #6495ed;
            padding-left: 20px;
            margin: 25px 0;
            font-size: 1.2rem;
        }
        
        h2 {
            color: #6495ed;
            margin: 30px 0 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid rgba(100, 149, 237, 0.2);
            font-size: 2rem;
        }
        
        h3 {
            color: #9370db;
            margin: 20px 0 10px;
            font-size: 1.4rem;
        }
        
        .section {
            background: rgba(25, 25, 50, 0.5);
            padding: 25px;
            border-radius: 15px;
            margin: 20px 0;
            border: 1px solid rgba(100, 149, 237, 0.1);
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .feature-card {
            background: rgba(30, 30, 60, 0.7);
            padding: 20px;
            border-radius: 12px;
            border-left: 4px solid #6495ed;
            transition: transform 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            border-left-color: #9370db;
        }
        
        .vision-modes {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 15px 0;
        }
        
        .vision-mode {
            flex: 1;
            min-width: 200px;
            padding: 15px;
            background: rgba(100, 149, 237, 0.1);
            border-radius: 10px;
            border: 1px solid rgba(100, 149, 237, 0.3);
        }
        
        .memory { border-top: 3px solid #4169e1; }
        .time { border-top: 3px solid #ffd700; }
        .matter { border-top: 3px solid #dc143c; }
        
        .gameplay-loop {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin: 20px 0;
        }
        
        .step {
            display: flex;
            align-items: center;
            gap: 15px;
            padding: 15px;
            background: rgba(147, 112, 219, 0.1);
            border-radius: 10px;
        }
        
        .step-number {
            background: #6495ed;
            color: white;
            width: 35px;
            height: 35px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
        }
        
        .controls-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }
        
        .control-item {
            background: rgba(30, 30, 60, 0.7);
            padding: 15px;
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .button {
            display: inline-block;
            background: linear-gradient(90deg, #6495ed, #9370db);
            color: white;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            margin: 10px 5px;
        }
        
        .button:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(100, 149, 237, 0.4);
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid rgba(100, 149, 237, 0.2);
            color: #b0b0ff;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            .title {
                font-size: 2.5rem;
            }
            
            .vision-modes {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1 class="title">🌌 Echoes of the Loom</h1>
            <p class="tagline">A cosmic narrative puzzle adventure where reality is woven from threads of memory, time, and matter.</p>
            <p class="quote">"Every thread pulled affects the whole tapestry. Choose your mends wisely."</p>
        </header>

        <div class="section">
            <h2>🎮 Game Concept</h2>
            <p>You are a <strong>Weaver</strong>, one of the last artisans capable of mending the broken cosmic <strong>Loom</strong>. Reality itself is fraying at the edges, with timelines splicing together, memories overwriting physics, and parallel worlds bleeding into one another. Your task: repair the fractures before everything unravels completely.</p>
        </div>

        <h2>✨ Key Features</h2>
        <div class="features-grid">
            <div class="feature-card">
                <h3>🧵 Thread-Seeing Vision</h3>
                <p>Switch between three vision modes to perceive different aspects of reality:</p>
                <div class="vision-modes">
                    <div class="vision-mode memory">
                        <strong>Memory Threads (Blue)</strong>
                        <p>See emotional and historical imprints</p>
                    </div>
                    <div class="vision-mode time">
                        <strong>Time Threads (Gold)</strong>
                        <p>Visualize temporal pathways and paradoxes</p>
                    </div>
                    <div class="vision-mode matter">
                        <strong>Matter Threads (Crimson)</strong>
                        <p>Perceive fundamental structure of reality</p>
                    </div>
                </div>
            </div>

            <div class="feature-card">
                <h3>🪡 Weaving Mechanics</h3>
                <p>Manipulate reality through creative thread weaving:</p>
                <ul style="margin-left: 20px; margin-top: 10px;">
                    <li>Grab, splice, and weave loose threads</li>
                    <li>Combine threads in unexpected ways</li>
                    <li>Mend broken structures with memories</li>
                    <li>Create time-loops and paradoxes</li>
                </ul>
            </div>

            <div class="feature-card">
                <h3>🕸️ Consequence Tapestry</h3>
                <p>Every action creates ripple effects:</p>
                <ul style="margin-left: 20px; margin-top: 10px;">
                    <li>Dynamic world states</li>
                    <li>Non-linear narrative branching</li>
                    <li>Visible tapestry of your choices</li>
                    <li>Butterfly effect gameplay</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>🕹️ Core Gameplay Loop</h2>
            <div class="gameplay-loop">
                <div class="step">
                    <div class="step-number">1</div>
                    <div><strong>Explore</strong> fractured reality zones</div>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <div><strong>Analyze</strong> using Thread-Seeing Vision</div>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <div><strong>Identify</strong> frayed threads and connections</div>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <div><strong>Weave</strong> solutions through manipulation</div>
                </div>
                <div class="step">
                    <div class="step-number">5</div>
                    <div><strong>Observe</strong> consequences ripple through world</div>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>🎮 Controls</h2>
            <div class="controls-grid">
                <div class="control-item">
                    <span>WASD / Left Stick</span>
                    <span>Move</span>
                </div>
                <div class="control-item">
                    <span>Mouse / Right Stick</span>
                    <span>Look Around</span>
                </div>
                <div class="control-item">
                    <span>Q/E / LB/RB</span>
                    <span>Cycle Vision Modes</span>
                </div>
                <div class="control-item">
                    <span>Left Click / RT</span>
                    <span>Grab Thread</span>
                </div>
                <div class="control-item">
                    <span>Right Click / LT</span>
                    <span>Release Thread</span>
                </div>
                <div class="control-item">
                    <span>Tab / View Button</span>
                    <span>Open Tapestry View</span>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>🎯 Development Status</h2>
            <p><strong>Current Phase:</strong> Pre-Production / Concept Development</p>
            <p><strong>Engine:</strong> Unity HDRP / Unreal Engine 5 (Evaluation)</p>
            <p><strong>Timeline:</strong> Target Release 2025</p>
            
            <h3 style="margin-top: 20px;">🤝 Looking For Team Members</h3>
            <p>Unity/Unreal Developers • Puzzle Designers • 3D Artists • Narrative Designers • Sound Designers</p>
            <a href="mailto:threadweaverstudio@protonmail.com" class="button">Contact Us</a>
        </div>

        <footer>
            <p>© 2024 Threadweaver Studio | Echoes of the Loom Concept</p>
            <p style="margin-top: 10px; font-size: 0.9em; color: #87ceeb;">
                "Some see the world as it is. You see it as it could be—and as it was—and as it never should have been. Pull the threads carefully, Weaver."
            </p>
        </footer>
    </div>

    <script>
        // Simple animation for step numbers
        document.addEventListener('DOMContentLoaded', function() {
            const steps = document.querySelectorAll('.step');
            steps.forEach((step, index) => {
                step.style.animationDelay = `${index * 0.1}s`;
            });
            
            // Add hover effect to feature cards
            const cards = document.querySelectorAll('.feature-card');
            cards.forEach(card => {
                card.addEventListener('mouseenter', function() {
                    this.style.boxShadow = '0 10px 20px rgba(100, 149, 237, 0.3)';
                });
                card.addEventListener('mouseleave', function() {
                    this.style.boxShadow = 'none';
                });
            });
        });
    </script>
</body>
</html>
