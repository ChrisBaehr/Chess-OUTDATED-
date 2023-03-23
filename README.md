### Introduction

Hi, this is a very early version of my Chess App written in Python with TomSchimansky's CustomTkinter as the GUI foundation. The interface is kept straight forward and very intuitive. The raw code is divided into sections with various comments improving the readability.

⠀
### Playability

Chess games can already be played with only a few game interactions missing:

    • Stalemate / Draw
    • Checkmates depending on a piece being pinned to the king

Apart from that I've made sure to add every other rule I could think of, even the less common ones:
    
    • Pinned pieces
    • Castling king and queen side
    • Discovered checks
    • Forced king move
    • En passant

⠀
### Code Quality

As this literally is one of my first programming projects, don't expect overly fancy coding techniques. Most of the problem-solving was done with basic coding knowledge. When taking a look at the raw code, you will notice headings written in all caps to divide different parts of the code. Whilst trying not to overdo code commenting to keep it visually appealing and minimalistic, I added a comment where the purpose of the line might not be obvious right away. Every function has a short explanation of what it does at the top. Blocks of code that could look confusing have a brief summary of what they do above them.

⠀
### GUI Customization

As far as customization is concerned, you can set a color for everything visible to you on the game board itself. Take a look at the Wiki page for more details.

⠀
### Future Plans

Taking the elephant in the room aside, I plan to implement a sidebar with Chess notations showing the move history. While at it, being able to jump to a move in the past and look at the piece constellation then, would also be logical. Enabling dragging and dropping pieces as well as drawing arrows using the right mouse button are also part of my plans. Although still far ahead, playing against an AI is also an idea. Will probably have to use Stockfish with varying difficulty levels for that.
