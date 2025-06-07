👽 Alien Dictionary
This project solves the Alien Dictionary problem using a topological sort approach to determine the character order from a sorted list of alien language words. The interface is built with HTML, CSS, and JavaScript for an interactive browser experience.

🧠 Problem Description
You are given a list of words sorted according to the rules of an alien language. Your task is to determine the correct order of characters in that language.

✅ Features
📝 Accepts multiline word input via a textarea

🧭 Uses topological sorting (Kahn’s algorithm) to infer character order

⚠️ Detects and handles invalid orderings (cycles or prefix issues)

🚀 Instant results displayed in the browser

💡 Lightweight, client-side implementation

💻 Technologies Used
HTML5
CSS3
JavaScript (Vanilla)

🧪 Test Cases
✅ Valid Case
Input:
wrt
wrf
er
ett
rftt

Output:
🧠 Alien Order: wertf
❌ Invalid Case
Input:
abc
ab

Output:
❌ Invalid order (Cycle Detected)

