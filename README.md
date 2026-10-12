# minigame 2
## Devlog
1. When I uncommented the if statement Unity showed this error and wouldnt run my game. Something like expected c# needs parentheses. I ended up changing the timeLeft from if _timeLeft <= 0.0 to if (_timeLeft <= 0.0f) and that seemed to fix it. I looked up the error online and was able to find the answer. 
2. I would assume it changes the color of the spriteRenderer. The period connects the two together, so spriteRenderer is connected to the color by the period. The numbers probably represent the value of the colors.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
