# X Entropy Project 
By BONHOMME Mailis and GELEBART Lauriane (IMAC-ESIEE Paris Engineering Students)  
Under the supervision of ROBILLARD Gaetan (Research Professor at Université Gustave Eiffel)

![A4 - 1 (2)](https://github.com/user-attachments/assets/f6f48844-d5d2-4b44-9331-f0e21766af40)

A data visualization project analyzing climate change skepticism on X (formerly Twitter) through the lens of information entropy and textual analysis.

![preview](https://github.com/user-attachments/assets/3a77b865-07f6-46a0-81da-006e19a07445)

## 🔍 About
X_Entropy examines how climate change skepticism and misinformation spread on X by analyzing tweet data from the [Critical Climate Machine project](https://robillardstudio.github.io/ccm.html). The visualization combines entropy measurements with temporal analysis to reveal patterns in climate skepticism discourse.

The project's presentation adopts the scrollable format inspired by [.able journal](https://able.am/), creating an engaging and intuitive user experience that mirrors modern digital content consumption patterns.

## 🛠️ Technical Details
The visualization displays entropy values vertically over time, with horizontal bars representing entropy levels. Each bar is color-coded based on tweet categorization, combining:
- Tweet timestamp
- Topic classification
- Entropy measurement

The entropy calculation follows Claude Shannon's formula:
```
H(X) = -Σp(x)log2p(x)
```
where p(x) represents the probability of occurrence for each symbol in the text.

## 💻 Source Code & Implementation
### P5.js Editors:
- [Graphic Visualization](https://editor.p5js.org/LaurianeGelebart/sketches/wikrbcMd3)
- [Word Analysis](https://editor.p5js.org/LaurianeGelebart/sketches/mxrZQLfvQ)

## 📊 Dataset and Analysis Resources
- [Project Dataset](https://docs.google.com/spreadsheets/d/1LHxUb5HsSh6nsJ6soozipbB6o2Xl67AaBT7IsRkfGeE/edit?gid=708961411#gid=708961411)
- [Climate Public GitHub](https://github.com/robillardstudio/climate-public)
- [Nature Article on Climate Change Claims Classification](https://www.nature.com/articles/s41598-021-01714)

## 🎨 Design Elements
The project's visual identity incorporates X's rebranded design language while maintaining clarity in data presentation:

###Color Palette

Primary: #000000, #ffffff (X's official colors)
Data Categories: #4f7918, #a0421c, #198ba3, #7b108b, #aea02a

### Typography
The project uses Verdana, a sans-serif typeface chosen for its similarity to X's Chirp font family.
