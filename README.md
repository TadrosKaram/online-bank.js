
A minimalist banking demo that showcases DOM-heavy JavaScript: login, balance and movements, transfers, loan request, account closure, and sorting.

## ✨ Features
- User login with demo credentials
- Display of balance, income, outcome, and interest
- Movements list with dates and formatted currency
- Transfer between accounts (validation included)
- Loan request based on simple rule
- Close account flow
- Sort movements asc/desc
- Session timeout (optional if implemented)

## 🗂️ Tech
- Vanilla JS (ES6+)
- No frameworks, no build step

## 🚀 Live preview at

https://tadroskaram.me/online-bank.js/


## 🔑 Demo Accounts
(test the app by yourself)

## 🧪 What to Try
- Login, review movements, toggle sort
- Make a transfer to another demo user
- Request a loan and observe UI update
- Close the account and test error paths

## 🧠 Key Learnings
- Array methods: \`map\`, \`filter\`, \`reduce\`, \`find\`, \`some\`, \`every\`, \`flatMap\`, \`sort\`

## 🧹 Notes
- No backend or persistence (refresh resets state)
- For production, add linting and tests


`;

fs.writeFileSync("README.md", md);
console.log("README.md created");
