# 🌴 Seetha Kamare Outing — Expense Split & Settlement Dashboard

A clean, modern, zero-dependency web dashboard and one-page settlement statement for the **Seetha Kamare Outing**.

- **Total Outing Expense:** LKR 69,082.00
- **Participants:** Rashini, Piyumi, Bhagya, Dinesh, Tharusha
- **Net Status:** 100% Reconciled (LKR 0.00 discrepancy)

---

## ⚡ Direct Transfers (Who Pays Whom)

To settle all debts in the minimum number of transactions:

1. **Rashini** &rarr; pays **Bhagya**: `LKR 13,176.35`
2. **Dinesh** &rarr; pays **Bhagya**: `LKR 10,820.60`
3. **Piyumi** &rarr; pays **Bhagya**: `LKR 6,746.70`
4. **Piyumi** &rarr; pays **Tharusha**: `LKR 8,277.65`

---

## 📊 Summary Balance Sheet

| Participant | Total Paid | Actual Share | Net Balance | Status |
|:---|:---:|:---:|:---:|:---|
| **Bhagya** | LKR 45,768.00 | LKR 15,024.35 | **+LKR 30,743.65** | 🟢 Gets Reimbursed |
| **Tharusha** | LKR 14,770.00 | LKR 6,492.35 | **+LKR 8,277.65** | 🟢 Gets Reimbursed |
| **Rashini** | LKR 1,848.00 | LKR 15,024.35 | **-LKR 13,176.35** | 🔴 Needs to Pay |
| **Dinesh** | LKR 6,696.00 | LKR 17,516.60 | **-LKR 10,820.60** | 🔴 Needs to Pay |
| **Piyumi** | LKR 0.00 | LKR 15,024.35 | **-LKR 15,024.35** | 🔴 Needs to Pay |
| **Total** | **LKR 69,082.00** | **LKR 69,082.00** | **LKR 0.00** | **100% Balanced** |

---

## 🚀 Deploy to GitHub & Vercel

### Step 1: Push to GitHub
Create a new empty repository on [GitHub](https://github.com/new) (e.g. `seetha-kamare-budget`), then run:

```bash
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/seetha-kamare-budget.git
git branch -M main
git push -u origin main
```

### Step 2: Deploy on Vercel

#### Option A: Via Vercel Dashboard (Recommended)
1. Go to [vercel.com](https://vercel.com) and click **"Add New..." &rarr; "Project"**.
2. Select your `seetha-kamare-budget` GitHub repository.
3. Keep default settings (Framework: *Other*, Root Directory: `./`).
4. Click **Deploy**. Your site will be live instantly!

#### Option B: Via Vercel CLI
```bash
npx vercel
```
