# ChesSkelet
A port of World's smallest chess program to JavaScript

# A motivation behind the project
Original program is not about playing strength, it's
about squeezing every single byte possible to come up
with the smallest binary executable that can play chess.
I recommend looking at initial 268 bytes source code written in Z80 assembly
to get an idea what a masterpiece this program is.
When I saw the code I instantly fell in love with piece
encoding because this is something unique that has never
been done in such an elegant way before. Since not many
people, including myself, are familiar with Z80 good enough
to write some programs in it I thought it would be a good
idea to port the program into a somewhat high-level language.
Since the program does not rely on recursion execution speed
is not a problem, so I decided to choose javascript for the
biggest coverage. You may enjoy the program just right in your
browser.

# Original project (Guinness world record holder)
http://borialabs.free.nf/chesskelet/<br>
Special thanks to Alex Garcia for helping me with this port!

# How to play
Enter moves from keyboard, e.g. "e2e4"<br>
User input exactly mimics original program.

# Try it now!
https://maksimkorzh.github.io/chesskelet-js/chesskelet.html

# Known issues
Most quirks come with so called 1.5 ply search,
it would move a pawn away if under attack even
if exposing king to check. It may leave king in
check due to the same reason.
