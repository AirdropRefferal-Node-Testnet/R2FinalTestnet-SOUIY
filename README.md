# R2 Auto Bot - Panduan Instalasi dan Penggunaan

---

## R2 Final Testnet Live

➡️ Faucet USDC : [DISCORD](https://discord.gg/r2yield)

➡️ Faucet Testnet : [Faucet 1](https://www.alchemy.com/faucets/ethereum-sepolia) | [Faucet 2](https://t.me/cloudfaucetbot)

👉 Link : [R2.MONEY](https://r2.money?code=LXTNZ)

➖ Connect Wallet Same Season 0

➖ Claim Faucet on DC

➖ Claim R2 Token

➖ Try Swap Buy/Sell

➖ Try Add Lp, Stake, Unstake

➖ Try All Network

➖ Done

---

## 📝 Deskripsi
Bot otomatis untuk melakukan berbagai transaksi di jaringan Sepolia dan Sepolia R2, termasuk:
- Swap token (USDC, R2USD, R2)
- Staking
- Menambahkan likuiditas ke pool
- Claim faucet

## 🛠️ Persyaratan Sistem
- Node.js (versi 16 atau lebih baru)
- NPM/Yarn
- Git

## 📥 Instalasi

### 1. Clone Repository
```bash
git clone https://github.com/AirdropRefferal-Node-Testnet/R2FinalTestnet-SOUIY.git
cd R2FinalTestnet-SOUIY
```

### 2. Install Dependencies
```bash
npm install
# atau
yarn install
```

### 3. Buat File .env
Buat file `.env` di root direktori dengan konten berikut:
```env
nano .env
```
```env
PRIVATE_KEY=YourPrivateKey
DISCORD_TOKEN=YourDiscordToken
RPC_URL=https://ethereum-sepolia-rpc.publicnode.com/
USDC_ADDRESS=0xef84994eF411c4981328fFcE5Fda41cD3803faE4
R2USD_ADDRESS=0x20c54C5F742F123Abb49a982BFe0af47edb38756
sR2USD_ADDRESS=0xBD6b25c4132F09369C354beE0f7be777D7d434fa
R2_ADDRESS=0xb816bB88f836EA75Ca4071B46FF285f690C43bb7
R2_USDC_ADDRESS=0x8BEbFCBe5468F146533C182dF3DFbF5ff9BE00E2
R2_R2USD_ADDRESS=0x9e8FF356D35a2Da385C546d6Bf1D77ff85133365
```

### 4. Jalankan Bot
```bash
node index.js
```

## 🎛️ Fitur Utama

### Menu Utama
- **Sepolia Network**: Akses fitur untuk jaringan Sepolia
- **Sepolia R2 Network**: Akses fitur untuk jaringan Sepolia R2
- **Claim Faucet**: Klaim faucet otomatis
- **Antrian Transaksi**: Lihat daftar transaksi dalam antrian
- **Clear Transaction Logs**: Bersihkan log transaksi
- **Refresh**: Perbarui data
- **Exit**: Keluar dari aplikasi

### Fitur Sepolia Network
- Auto Swap R2USD & USDC
- Auto Stake R2USD & sR2USD
- Auto Add LP (Liquidity Pool)
- Manual Swap
- Ubah jumlah random untuk transaksi

### Fitur Sepolia R2 Network
- Auto Swap R2 & USDC
- Auto Swap R2 & R2USD
- Auto Add LP (Liquidity Pool)
- Manual Swap
- Ubah jumlah random untuk transaksi

### Fitur Claim Faucet
- Klaim faucet manual
- Auto klaim harian
- Hentikan auto klaim

## 🖥️ Tampilan Antarmuka
Bot menggunakan antarmuka terminal dengan:
- Panel informasi wallet
- Log transaksi
- Menu interaktif
- Prompt input

## ⚠️ Catatan Penting
1. Pastikan Anda memiliki saldo cukup untuk gas fee
2. Bot ini untuk tujuan airdrop dan pengujian
3. Gunakan dengan risiko sendiri
4. Jangan gunakan private key utama Anda

## ❓ Bantuan
Jika mengalami masalah, buka issue di repository GitHub atau hubungi developer.


---

**FOLLOW TIKTOK**: [AirdropRefferal (@Souiy1)](https://www.tiktok.com/@souiy1)  
**DONASI**: [Bantu Palestina](https://digital.dompetdhuafa.org/donasi/jagapalestina)
