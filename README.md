# 🔒 Password Strength Checker

A real-time password strength checker built with vanilla **HTML, CSS, and JavaScript** — no frameworks, no dependencies, no data leaves the browser.

**[Live Demo →](https://Cr-haze.github.io/password-strength-checker/)**  <!-- update this link after enabling GitHub Pages -->

![Password Strength Checker preview](preview.png) <!-- optional: add a screenshot here -->

## Features

- ✅ Real-time strength meter (Very Weak → Very Strong)
- ✅ Checks length, uppercase, lowercase, numbers, special characters, and repeated characters
- ✅ Entropy (bits) calculation based on character pool size
- ✅ Estimated crack time
- ✅ Common/leaked password detection
- ✅ Actionable suggestions to improve weak passwords
- ✅ Show/hide password toggle
- ✅ 100% client-side — nothing is stored or transmitted

## How it works

1. User types a password into the input field
2. JavaScript analyzes it against multiple criteria (length, character variety, patterns)
3. An entropy score and strength level are calculated live
4. The strength meter and suggestions update instantly as the user types

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)

## Getting started

Clone the repo and open `index.html` in your browser — that's it, no build step required.

```bash
git clone https://github.com/Cr-haze/password-strength-checker.git
cd password-strength-checker
open index.html   # or just double-click the file
```

## What I learned

- String handling and regular expressions in JavaScript
- Basic password security best practices (entropy, common password lists, crack-time estimation)
- Building real-time, reactive UI without a framework

## License

MIT — free to use, modify, and share.
