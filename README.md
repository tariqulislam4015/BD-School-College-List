# 🎓🕌 শিক্ষা অ্যাটলাস বাংলাদেশ (EduAtlas Bangladesh)

বাংলাদেশের শিক্ষাপ্রতিষ্ঠান ও মসজিদ এক মানচিত্রে। দুটি আলাদা অংশ: **🎓 শিক্ষাপ্রতিষ্ঠান**: শিশু নিকেতন, ক্যাডেট, প্রাথমিক, উচ্চ বিদ্যালয়, কলেজ, মাদরাসা, কারিগরি ও বিশ্ববিদ্যালয়; **🕌 মসজিদ**: জামে মসজিদ, ওয়াক্তিয়া/পাঞ্জেগানা মসজিদ, ঈদগাহ ময়দান, মারকাজ/কেন্দ্রীয় মসজিদ। বিভাগ → জেলা → উপজেলা → ইউনিয়ন → ওয়ার্ড, সিটি কর্পোরেশন, শহর/পৌরসভা ও ডাকঘর (পোস্টকোড) ধরে খোঁজা যায়।

**🌐 লাইভ:** https://tariqulislam4015.github.io/BD-School-College-List/

## ✨ বৈশিষ্ট্য

- **প্রশাসনিক এলাকা:** ৮ বিভাগ, ৬৪ জেলা, সব উপজেলা, ইউনিয়ন, ১২টি সিটি কর্পোরেশন ও ওয়ার্ড, শহর/পৌরসভা, ডাকঘর ও পোস্টকোড
- **EIIN-সহ তথ্য (BANBEIS):** EIIN, প্রতিষ্ঠানের নাম, সরকারি/বেসরকারি, MPO, শিক্ষার স্তর, ঠিকানা, মৌজা, ডাকঘর, মোবাইল নম্বর
- **মানচিত্র:** OpenStreetMap ও স্যাটেলাইট ভিউ; প্রতিটি প্রতিষ্ঠানে **Google Maps** লোকেশন ও দিকনির্দেশনার বোতাম
- **নিজে যোগ করা:** যে প্রতিষ্ঠান নেই, তা ম্যাপে ক্লিক করে বা GPS দিয়ে যোগ, সম্পাদনা ও মুছে ফেলা যায়
- **স্বয়ংক্রিয় ডাটাবেস:** অনলাইনে যা পাওয়া যায় তা ব্রাউজারে (IndexedDB) স্থায়ীভাবে জমা হয় এবং ইন্টারনেট ছাড়াও দেখা যায়
- **মসজিদ অংশ (আলাদা পার্টিশন):** নিজস্ব ম্যাপ, তালিকা, পরিসংখ্যান, ডাটাবেস ও যোগ করার ফর্ম; সরাসরি লিংক `#mosque`
- **পুরো দেশ এক ক্লিকে:** ৬৪ জেলার সব তথ্য একবারে সংরক্ষণ
- **Export / Import:** JSON ও CSV (Excel-এ খোলা যায়)
- নাম বা EIIN দিয়ে খোঁজা, ধরন অনুযায়ী ফিল্টার, দূরত্ব অনুযায়ী সাজানো
- মোবাইল, ট্যাবলেট ও ডেস্কটপ, সব স্ক্রিনে মানানসই

## 📚 তথ্যসূত্র

| তথ্য | উৎস |
|---|---|
| বিভাগ, জেলা, উপজেলা, ইউনিয়ন, সিটি কর্পোরেশন, পোস্টকোড | [nuhil/bangladesh-geocode](https://github.com/nuhil/bangladesh-geocode) |
| EIIN-সহ প্রতিষ্ঠানের তালিকা (BANBEIS) | [Institutional Information of Bangladesh](https://huggingface.co/datasets/Mahadih534/Institutional-Information-of-Bangladesh) (Hugging Face) |
| প্রতিষ্ঠান ও মসজিদের অবস্থান (ম্যাপ) | [OpenStreetMap](https://www.openstreetmap.org/copyright) / Overpass API |

> ⚠️ ম্যাপে যেসব প্রতিষ্ঠানের সঠিক অবস্থান নেই, সেগুলো ইউনিয়ন বা উপজেলা কেন্দ্রে **আনুমানিক অবস্থানে** দেখানো হয় এবং আলাদাভাবে চিহ্নিত থাকে। সরকারি প্রাথমিক বিদ্যালয় BANBEIS-এর EIIN তালিকায় থাকে না; সেগুলো OpenStreetMap থেকে আসে।

## 📱 মোবাইল অ্যাপ

- **Android (APK):** [⬇ EduAtlas-Bangladesh.apk ডাউনলোড](https://github.com/tariqulislam4015/BD-School-College-List/releases/latest/download/EduAtlas-Bangladesh.apk). প্রতিবার `main`-এ push করলে GitHub Actions নিজে থেকেই নতুন APK বানিয়ে [Releases](https://github.com/tariqulislam4015/BD-School-College-List/releases)-এ দেয়। প্রথম ইনস্টলে ফোনে “Install unknown apps” অনুমতি দিতে হতে পারে।
- **যেকোনো ফোন (Android / iPhone):** ওয়েবসাইট খুলে “📲 ফোনে ইনস্টল করুন” চাপুন, অথবা ব্রাউজার মেনু থেকে *Add to Home Screen* করুন।

## 🚀 চালানোর নিয়ম

কোনো সার্ভার লাগে না। মূল অ্যাপ একটিমাত্র ফাইল `index.html`; `android/` ফোল্ডারে APK-এর সোর্স, `.github/workflows/` এ APK বানানোর স্বয়ংক্রিয় ব্যবস্থা।

- **অনলাইনে:** GitHub Pages লিংকে যান
- **নিজের কম্পিউটারে:** `index.html` ফাইলটি Chrome / Edge / Firefox-এ খুলুন (ইন্টারনেট সংযোগ লাগবে)

## 👨‍💻 নির্মাতা

**তারিকুল ইসলাম (সুমন)** · MSc Mathematics

- ▶️ YouTube: [TIS Academy](https://www.youtube.com/@tis.academy24)
- 📘 Facebook: [tariqul.islam.422531](https://www.facebook.com/tariqul.islam.422531/)
- 💬 WhatsApp: [01755-489719](https://wa.me/8801755489719)
- 🐙 GitHub: [tariqulislam4015](https://github.com/tariqulislam4015)
