# Cvendr - Airdrop Mining App

**Cvendr** एक Web3 आधारित एप्प है जो यूज़र्स को एयरड्रॉप क्लेम करने और टोकन कमाने की सुविधा देता है। यह ऐप "CVDR" (Cvendr Token) पर आधारित है।

---

## फीचर्स (Features)

- ERC-20 आधारित CVDR टोकन
- स्मार्ट कॉन्ट्रैक्ट से Airdrop क्लेमिंग
- MetaMask वॉलेट कनेक्शन
- MongoDB बैकएंड के साथ यूज़र डेटा स्टोर
- रेफरल सिस्टम (बाद में जोड़ा जा सकता है)
- React + Node.js बेस्ड फ्रंटएंड और बैकएंड

---

## कैसे इस्तेमाल करें (How to Use)

### 1. स्मार्ट कॉन्ट्रैक्ट डिप्लॉय करें
- Remix IDE में `CvendrToken.sol` और `CvendrAirdrop.sol` डिप्लॉय करें
- `CvendrAirdrop.sol` में `cvdrToken` के लिए `CvendrToken` का कॉन्ट्रैक्ट एड्रेस डालें

### 2. बैकएंड चलाएं

```bash
cd backend
npm install
node server.js
