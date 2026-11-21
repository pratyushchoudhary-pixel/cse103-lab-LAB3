# Heading 1 (largest)
## Heading 2
### Heading 3

**Bold text** *Italic text* ~~Strikethrough~~

Unordered list:
- Item A
- Item B
  - Nested item B1 (indent with 2 spaces)

Ordered list:
1. First step
2. Second step

Inline code: `print("Hello")`

Fenced code block (use language name for syntax highlighting):
```python
def greet(name):
    return f"Hello, {name}!"
Hyperlink: GitHub

Table:

Column 1	Column 2	Column 3
Left	Centre	Right
### **2. `README.md` banao**
Ab `YOUR_GITHUB_USERNAME` ki jagah apna actual GitHub username daal kar yeh poora block paste karo aur **Enter** dabao[cite: 2, 3]:

<pre>
cat << 'EOF' > README.md
# CSE103 Lab — LAB 3: GitHub Collaboration & API Interaction

![Last Commit](https://img.shields.io/github/last-commit/YOUR_GITHUB_USERNAME/cse103-lab-LAB3)
![Language](https://img.shields.io/badge/language-Python-blue)
![Status](https://img.shields.io/badge/status-active-brightgreen)

## Overview
This repository contains lab work for **LAB 3** of the **Computer Fundamentals & Career Pathways (CSE103)** course at **K.R. Mangalam University**, Gurugram.

## Repository Structure
text
cse103-lab-LAB3/
+-- README.md      # Project documentation (this file)
+-- CHANGELOG.md   # Version history
+-- main.py        # Primary Python script
+-- .gitignore     # Files excluded from Git tracking
git clone https://github.com/pratyushchoudhary-pixel/cse103-lab-LAB3.git
cd cse103-lab-LAB3
python3 main.py
git add README.md MARKDOWN_GUIDE.md && git commit -m "docs: create comprehensive README and Markdown guide" && git push
