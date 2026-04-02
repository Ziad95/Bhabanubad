# ভাবানুবাদক — Contextual Bangla-English Translation

বাংলা থেকে ইংরেজি এবং ইংরেজি থেকে বাংলা **ভাবানুবাদ** — পত্রিকামানের অনুবাদ।
BCS ও চাকরি পরীক্ষার প্রস্তুতির জন্য তৈরি।

Made by **Ziad Bin Hashem**

---

## ৫ মিনিটে Website Live করুন — সম্পূর্ণ ফ্রি

### ধাপ ১: Gemini API Key নিন (ফ্রি)

1. যান: https://aistudio.google.com/apikey
2. Google account দিয়ে sign in করুন
3. **"Create API Key"** বাটনে ক্লিক করুন
4. API key টি কপি করে রাখুন

### ধাপ ২: GitHub-এ কোড আপলোড করুন

1. https://github.com এ যান (account না থাকলে ফ্রি তে খুলুন)
2. **"New Repository"** ক্লিক করুন
3. নাম দিন: `bhabanubad`
4. এই পুরো ফোল্ডারের সব ফাইল আপলোড করুন

### ধাপ ৩: Vercel-এ Deploy করুন (ফ্রি)

1. যান: https://vercel.com
2. **"Sign up with GitHub"** দিয়ে account করুন
3. **"Add New Project"** → আপনার `bhabanubad` repo সিলেক্ট করুন
4. **Environment Variables** সেকশনে যান:
   - Name: `GEMINI_API_KEY`
   - Value: ধাপ ১ এ পাওয়া API key পেস্ট করুন
5. **"Deploy"** বাটনে ক্লিক করুন

### ব্যস! ✅

আপনার সাইট live হয়ে যাবে: `https://bhabanubad.vercel.app`

---

## Custom Domain (ঐচ্ছিক)

`bhabanubad.com` বা `bhabanubad.com.bd` কিনতে চাইলে:
- Namecheap বা Hostever থেকে domain কিনুন
- Vercel Dashboard → Settings → Domains → domain যুক্ত করুন

## Tech Stack

- **Frontend**: Next.js 14 (React)
- **AI**: Google Gemini 2.0 Flash (Free Tier)
- **Hosting**: Vercel (Free Tier)
- **Cost**: ০ টাকা/মাস
