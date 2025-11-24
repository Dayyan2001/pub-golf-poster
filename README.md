# pub-golf-poster
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pub Golf 2025</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: linear-gradient(135deg, #2e7d32 0%, #66bb6a 100%);
            font-family: 'Arial', sans-serif;
            padding: 20px;
        }
        
        .poster {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #1b5e20 0%, #388e3c 100%);
            color: #ffd700;
            text-align: center;
            padding: 30px 20px;
            border-bottom: 5px solid #ffd700;
        }
        
        .header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.3);
        }
        
        .header .date {
            font-size: 1.3em;
            margin-top: 10px;
            color: white;
        }
        
        .content {
            padding: 30px;
        }
        
        .section {
            margin-bottom: 25px;
            background: #f5f5f5;
            padding: 20px;
            border-radius: 10px;
            border-left: 5px solid #388e3c;
        }
        
        .section h2 {
            color: #1b5e20;
            font-size: 1.8em;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .two-column {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        
        .rule-item {
            background: white;
            padding: 12px;
            margin: 8px 0;
            border-radius: 8px;
            border-left: 4px solid #4caf50;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .penalty {
            border-left-color: #f44336;
        }
        
        .bonus {
            border-left-color: #ffd700;
        }
        
        .score {
            background: #4caf50;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.9em;
        }
        
        .score.penalty-score {
            background: #f44336;
        }
        
        .score.bonus-score {
            background: #ffd700;
            color: #1b5e20;
        }
        
        .mini-games {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }
        
        .game-card {
            background: linear-gradient(135deg, #388e3c 0%, #4caf50 100%);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        
        .game-card .game-name {
            font-size: 1.2em;
            margin-bottom: 10px;
            font-weight: bold;
        }
        
        .game-card .game-score {
            font-size: 2em;
            color: #ffd700;
        }
        
        .footer {
            background: #1b5e20;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 0.9em;
        }
        
        .highlight-box {
            background: #fff3cd;
            border: 3px dashed #ffc107;
            padding: 15px;
            border-radius: 10px;
            margin: 15px 0;
            text-align: center;
            font-weight: bold;
            font-size: 1.1em;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
        }
        
        table th {
            background: #388e3c;
            color: white;
            padding: 12px;
            text-align: left;
        }
        
        table td {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        
        table tr:hover {
            background: #f5f5f5;
        }
        
        @media print {
            body {
                background: white;
                padding: 0;
            }
            .poster {
                box-shadow: none;
            }
        }
    </style>
</head>
<body>
    <div class="poster">
        <!-- Header -->
        <div class="header">
            <h1>🍺⛳ PUB GOLF 🏌️‍♂️🍻</h1>
            <div class="date">
                <strong>[INSERT DATE HERE]</strong><br>
                TEE OFF: [INSERT TIME]<br>
                STARTING HOLE: [INSERT VENUE NAME & ADDRESS]
            </div>
        </div>

        <!-- Content -->
        <div class="content">
            
            <!-- Dress Code -->
            <div class="section">
                <h2>👔 DRESS CODE - MANDATORY!</h2>
                <div class="rule-item">
                    <span>❌ Not in golf attire</span>
                    <span class="score penalty-score">+3 per person</span>
                </div>
                <div class="rule-item bonus">
                    <span>🏆 Best dressed team</span>
                    <span class="score bonus-score">-3</span>
                </div>
                <div class="rule-item penalty">
                    <span>💩 Worst dressed team</span>
                    <span class="score penalty-score">+3</span>
                </div>
                <div class="rule-item bonus">
                    <span>⭐ Happy Gilmore costume</span>
                    <span class="score bonus-score">-5</span>
                </div>
            </div>

            <!-- How to Play -->
            <div class="section">
                <h2>⛳ HOW TO PLAY</h2>
                <div class="highlight-box">
                    Each Pub = 1 Hole | Each Sip = 1 Stroke<br>
                    LOWEST SCORE WINS! 🏆
                </div>
                <ul style="list-style: none; padding: 0;">
                    <li style="padding: 8px 0;">✓ Every hole has a <strong>PAR</strong> (max sips allowed)</li>
                    <li style="padding: 8px 0;">✓ <strong>3 players per team</strong> drink at each hole</li>
                    <li style="padding: 8px 0;">✓ Scores combine for team total</li>
                    <li style="padding: 8px 0;">✓ Under par = 🦅 | Over par = 📈</li>
                </ul>
                <div style="background: white; padding: 15px; border-radius: 8px; margin-top: 15px;">
                    <strong>Example:</strong><br>
                    Par 4 drink finished in 3 sips = <span style="color: green; font-weight: bold;">-1 (Birdie!)</span><br>
                    Par 4 drink finished in 6 sips = <span style="color: red; font-weight: bold;">+2 (Bogey!)</span>
                </div>
            </div>

            <!-- Two Column Section -->
            <div class="two-column">
                
                <!-- Penalties -->
                <div class="section">
                    <h2>⚠️ HAZARDS & PENALTIES</h2>
                    <table>
                        <thead>
                            <tr>
                                <th>Offense</th>
                                <th>Penalty</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Spilling drink</td>
                                <td><strong>+1</strong></td>
                            </tr>
                            <tr>
                                <td>💧 Water Hazard (toilet)</td>
                                <td><strong>+2</strong></td>
                            </tr>
                            <tr>
                                <td>Slipping/falling</td>
                                <td><strong>+3</strong></td>
                            </tr>
                            <tr>
                                <td>Incomplete drink</td>
                                <td><strong>+4 + shot</strong></td>
                            </tr>
                            <tr>
                                <td>Cheating</td>
                                <td><strong>+5</strong></td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <!-- Dayyan's Law -->
                <div class="section">
                    <h2>👨‍⚖️ DAYYAN'S LAW</h2>
                    <div class="rule-item penalty">
                        <span>🗣️ Arguing with ref</span>
                        <span class="score penalty-score">+3</span>
                    </div>
                    <div class="rule-item penalty">
                        <span>🟨 Yellow Card</span>
                        <span class="score penalty-score">+1 per member</span>
                    </div>
                    <div class="rule-item penalty">
                        <span>🟥 Red Card</span>
                        <span class="score penalty-score">+2 per member + shots</span>
                    </div>
                    <div style="background: white; padding: 15px; border-radius: 8px; margin-top: 15px; font-size: 0.9em;">
                        <strong>Example:</strong> Team of 4 gets red card = +8 strokes + 4 penalty shots
                    </div>
                </div>

            </div>

            <!-- Mini Games -->
            <div class="section">
                <h2>🎮 MINI GAMES - BONUS POINTS!</h2>
                <div class="mini-games">
                    <div class="game-card">
                        <div class="game-name">🎯 BINGO</div>
                        <div>First to complete</div>
                        <div class="game-score">-5</div>
                    </div>
                    <div class="game-card">
                        <div class="game-name">🎯 DARTS</div>
                        <div>Highest score</div>
                        <div class="game-score">-5</div>
                    </div>
                    <div class="game-card">
                        <div class="game-name">🎵 SONGS</div>
                        <div>Name artist first</div>
                        <div class="game-score">-2</div>
                    </div>
                </div>
                <div class="rule-item bonus" style="margin-top: 15px;">
                    <span>👀 Spotto (each win)</span>
                    <span class="score bonus-score">-1</span>
                </div>
                <div class="rule-item bonus">
                    <span>🥢 Sticks on Judge (first team)</span>
                    <span class="score bonus-score">-5</span>
                </div>
            </div>

            <!-- Special Play -->
            <div class="section" style="background: linear-gradient(135deg, #ffd700 0%, #ffeb3b 100%); border-left-color: #f57c00;">
                <h2 style="color: #1b5e20;">🤝 STRANGER DANGER BONUS</h2>
                <div style="text-align: center; font-size: 1.3em; padding: 10px;">
                    Convince a random stranger to finish your <strong>ENTIRE</strong> drink
                    <div style="font-size: 2em; color: #1b5e20; margin-top: 10px; font-weight: bold;">-5 STROKES! 🎉</div>
                </div>
            </div>

        </div>

        <!-- Footer -->
        <div class="footer">
            <p style="font-size: 1.2em; margin-bottom: 10px;">
                <strong>RSVP: [YOUR CONTACT INFO]</strong>
            </p>
            <p>
                🔞 21+ ONLY | DRINK RESPONSIBLY | ARRANGE SAFE TRANSPORT
            </p>
        </div>
    </div>
</body>
</html>
