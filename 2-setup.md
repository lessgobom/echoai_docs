# Quick Setup Guide ⚙️

### **Step 1: Acquire $EchoAI Tokens**
1. Purchase $EchoAI tokens from supported exchanges. 🔄
2. Add $EchoAI to your wallet. Ensure you have enough balance for transactions. 💼

### **Step 2: Generate API Key 🔑**
- Connect your wallet to the EchoAI API service. (No dashboard required).
- Approve the transaction to generate a **unique API key** tied to your wallet address. 🔐

### **Step 3: Install SDK**
```bash
npm install @echoai/sdk
```

### Step 4: Basic Integration Example 🛠️ **
```
import EchoAI from '@echoai/sdk';

const client = new EchoAI('YOUR_API_KEY');
const result = await client.verifyVoice(sampleAudio);
console.log(result);
```




