# Currency-Convertor

<div align="center">

# 💱 Currency Converter

A fast and simple **real-time currency converter** built with **HTML, CSS and vanilla JavaScript**, powered by a live exchange rate API.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Deployed%20on-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

### 🌐 [Try the Live Demo](https://currency-convertor-sneha.netlify.app)

[🐛 Report Bug](https://github.com/sneha-goyal7/Currency-Convertor/issues) · [✨ Request Feature](https://github.com/sneha-goyal7/Currency-Convertor/issues)

</div>

---

## 📖 About The Project

Currency Converter lets you instantly convert an amount from one currency to another using the **latest exchange rates**. Choose the **From** and **To** currencies from dropdowns (with country flags), enter an amount and click **Get Exchange Rate** to see the converted value.

This project was built to practise **API integration, async/await, fetch, dynamic DOM updates and event handling** in vanilla JavaScript.

---

## ✨ Features

- 💰 Convert between a wide range of world currencies
- ⚡ Live exchange rates fetched from a public currency API
- 🚩 Country flag updates automatically with the selected currency
- 🔽 Dropdowns generated dynamically from a country-code list
- 🔄 Default pair set to **USD → INR** on load
- 📝 Clear result message, e.g. `1 USD = 80 INR`
- 🎨 Clean, centered and responsive card-style UI
- 🪶 No frameworks or libraries: pure HTML, CSS and JS

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Page structure and form |
| **CSS3** | Styling and responsive layout |
| **JavaScript (ES6)** | Async API calls, DOM manipulation, event handling |
| **Currency API** | Real-time exchange rate data |
| **Netlify** | Hosting / deployment |

---

## 📂 Project Structure

```
Currency-Convertor/
│── index.html     # App layout
│── style.css      # Styling
│── codes.js       # Currency code → country code list (for flags)
│── app.js         # Main logic (API fetch, dropdowns, conversion)
└── README.md      # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
Ek modern web browser aur internet connection (live rates fetch karne ke liye). Koi installation ki zarurat nahi.

### Installation & Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/sneha-goyal7/Currency-Convertor.git
   ```
2. **Go to the project folder**
   ```bash
   cd Currency-Convertor
   ```
3. **Open the app**
   - Double-click `index.html`, **or**
   - Use the **Live Server** extension in VS Code (`Right click → Open with Live Server`)

---

## 🎮 How To Use

1. **Enter the amount** you want to convert (default is `1`).
2. Select the **From** currency (default: USD).
3. Select the **To** currency (default: INR).
4. Click **Get Exchange Rate**.
5. The converted result appears right below the dropdowns. 🎉

---

## 🧠 How It Works (Logic)

- `codes.js` stores a `countryList` object mapping currency codes (USD, INR, EUR...) to country codes.
- `app.js` loops over this list and fills both dropdowns with `<option>` elements dynamically.
- On change of a dropdown, `updateFlag()` swaps the flag image for the selected country.
- On clicking the button, `updateExchangeRate()` runs: it reads the amount, fetches the latest rate using `fetch()` with `async/await` and shows the final converted value in the message area.

---

## 🔮 Future Improvements

- [ ] 🔁 Swap button to interchange From and To currencies
- [ ] 📈 Historical rate chart
- [ ] ⚠️ Better error handling for offline / API failure
- [ ] 🌗 Dark / Light theme toggle
- [ ] 💾 Remember last selected currencies

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Sneha Goyal**
Final-year B.Tech CSE student | MERN Stack & Gen AI enthusiast

- GitHub: [@sneha-goyal7](https://github.com/sneha-goyal7)
- Email: snehagoyal4295@gmail.com

---

<div align="center">

⭐ **Agar project pasand aaya to repo ko star zaroor karein!** ⭐

</div>