[README.md](https://github.com/user-attachments/files/32933307/README.md)
# HOW TO EDIT YOUR WEBSITE

Only three places matter:
  content.js        all text, times, timeline, dress code, accommodation  (+ EDITABLE LINKS at the bottom)
  illustrations.js  the list of drawings
  assets/illustrations/*.svg   the drawings themselves

A. Change text ......... open content.js, edit the words between the quotation marks.
B. Change a time ....... content.js > timeline > items: change  time: "15:00"  to  "15h00".
                         (The opening-screen date lines are in  hero.dateLines.)
C. Change a drawing .... save your own SVG over the file in assets/illustrations/ (same name),
                         or point the entry in illustrations.js to another file.
D. Replace an image .... same as C. PNG / JPG / WEBP also work: put its path in illustrations.js.
E. Change a link ....... content.js > EDITABLE LINKS (bottom). Empty "" hides the button.
E2. Our Honeymoon ...... content.js > gift: wording + iban. Its drawing (a small vintage airplane) is assets/illustrations/honeymoon.svg.
F. Add / remove an event  content.js > timeline > items: copy or delete one { … } line.
                         Choose its drawing with illustration: "ceremony" | "cocktail" | "dinner" | "party" | "" (none).
G. Add / remove a stay .. content.js > stay > nearby: copy or delete one { … } block; for a new one
                         add a line  accommodation5: "https://…"  in EDITABLE LINKS and use "accommodation5" as its link.

FILE MAP
  ceremony.svg · cocktail.svg · dinner.svg · party-mirror-ball.svg   timeline (15:00 · 17:00 · 20:00 · 23:00)
  suit.svg · evening-dress.svg                            dress code
  chandelier.svg · dinner-table.svg · manor.png           opening screen (x2) and section 02
  honeymoon.svg                                            section 07, A Gift (the cluster of 8 passport stamps, no dates)
  gift-accent.svg                                          section 07, A Gift — the small sprig either side of the IBAN

HOSTING: upload the whole folder (index.html, content.js, illustrations.js, assets/, fonts/) to any web host
(Netlify, GitHub Pages, OVH…). To preview on your computer, run a tiny server in the folder
(e.g.  python3 -m http.server ) and open http://localhost:8000 — opening index.html by double-click also
works, but the drawings then appear without their draw-in animation.
