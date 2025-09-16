# Stellar Gasless SDK 🚀  

A lightweight SDK that enables **gasless transactions on Stellar**, letting users pay fees directly in **stablecoins** instead of XLM.  
Unlike other solutions that sponsor network fees, this SDK automatically swaps a small portion of the user’s stablecoin into XLM to cover the fee.
Gasolina SDK standardizes gasless payments across applications, removing friction and delivering a **fintech-like user experience**.  

---

## ✨ Features  
- **Gasless transactions** → users no longer need XLM for fees.  
- **Stablecoin-first UX** → pay fees in USD stablecoins. (Any token in the future)  
- **Plug & Play SDK** → easy integration for Stellar apps.  
- **Standardized** → consistent experience across the ecosystem.  
- **Relayer architecture** → fees are handled transparently with smart contracts.  

---

## 🎯 Why  
- On Stellar, users must hold XLM to pay fees, confusing and blocking the adoption.  
- Businesses and fintechs want payments in stablecoins only.  
- Over 80% of new crypto adoption starts with stablecoins, this SDK removes the main friction.  

👉 **With the Gasless SDK, Stellar apps feel like modern fintech apps — seamless and intuitive.**

---

## ⚙️ How It Works  

1. **SDK Integration**  
   - Import the SDK into your Stellar app.  
   - Wrap your transaction flow with the gasless transaction handler.  

2. **User Transaction**  
   - User signs in **stablecoin** only (no XLM required).  

3. **Relayer**  
   - The SDK routes the transaction through a relayer.  
   - Relayer swap the stablecoin to XLM and cover the fee on behalf of the user.  

4. **Execution**  
   - Transaction is submitted and confirmed on Stellar.  
   - User sees a **pure stablecoin payment experience**.

---
  
🤝 Contributing

Contributions are welcome! Please open issues or submit PRs to help improve the SDK.

---

📜 License

MIT License.

---

## 📦 Installation  

```bash
npm install stellar-gasless-sdk
