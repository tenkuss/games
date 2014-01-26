games
=====
{
    "splash":   "arcadeArt/background.jpg",
    "titleArt": "arcadeArt/gameTitle.png",
 
    "id":       "breakout",
    "name":     "Super Breakout",
    "gameClass": "Breakout.js",
 
    "modes": [
        {"id":"cavity", "label":"Cavity Mode",
            "src":"arcadeArt/sp-mode-01.jpg"},
        {"id":"progressive", "label":"Progressive Mode",
            "src":"arcadeArt/sp-mode-02.jpg"},
        {"id":"double", "label":"Double Mode",
            "src":"arcadeArt/sp-mode-03.jpg"}
    ],
 
    "dependencies":   [
        "scripts/Ball.js",
        "scripts/Brick.js",
        "scripts/Level.js",
        "scripts/Player.js",
        "scripts/Paddle.js",
        "scripts/LevelManager.js",
        "scripts/LevelSelector.js",
        "scripts/Breakout.js",
        "scripts/ScoreBoard.js"
    ],
 
    "deployDependencies": [
        "scripts/breakout-min.js"
    ],
 
    "assets": [
        {"id":"json","src":"data/data.json"},
        {"id":"bricks","src":"data/bricks.json"},
        {"id":"lives","src":"data/lives.json"},
        "img/lives.png",
        {"id":"paddleData","src":"data/paddle.json"},
        "img/paddle.png",
        {"id:":"brickImage", "src":"img/bricks.png"},
        {"id":"background", "src":"img/background.png"},
        {"id":"scanlines", "src":"img/ui-scanlines.png"},
 
        {"id":"wall", "src":"sounds/Wall_Hit_02.mp3", "data":2},
        {"id":"brick1", "src":"sounds/Brick_Hit_01_Final.mp3"}
        // altri file audio
    ]
}
