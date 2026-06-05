# John Gaming Shop - Setup Instructions

ဤဝဘ်ဆိုဒ်သည် Supabase Backend ကို အသုံးပြုထားပြီး HTML/CSS/JS သီးသန့်ဖြင့် တည်ဆောက်ထားပါသည်။

## ၁။ Supabase Project တည်ဆောက်ခြင်း
1. [Supabase](https://supabase.com/) တွင် အကောင့်ဖွင့်ပြီး Project အသစ်တစ်ခု တည်ဆောက်ပါ။
2. **SQL Editor** သို့သွားပြီး ပေးထားသော `schema.sql` ထဲမှ ကုဒ်များကို Copy ကူးပြီး Run ပါ။
3. ထို့နောက် `rls-policies.sql` ထဲမှ ကုဒ်များကိုလည်း Run ပေးပါ။

## ၂။ Storage Bucket တည်ဆောက်ခြင်း
1. Supabase Dashboard ရှိ **Storage** သို့သွားပါ။
2. `payments` အမည်ဖြင့် Bucket အသစ်တစ်ခု တည်ဆောက်ပါ။
3. Bucket ကို **Public** ပေးထားရန် မမေ့ပါနှင့်။

## ၃။ Authentication သတ်မှတ်ခြင်း
1. **Authentication** > **Providers** တွင် Email Provider ကို Enable လုပ်ပါ။
2. 'Confirm Email' ကို ပိတ်ထားလိုပါက ပိတ်ထားနိုင်ပါသည်။

## ၄။ Admin အကောင့် သတ်မှတ်ခြင်း
1. အကောင့်တစ်ခုကို Signup ပြုလုပ်ပါ။
2. **Table Editor** ရှိ `users` table ထဲတွင် ထိုအကောင့်၏ `role` ကို `admin` ဟု ပြောင်းလဲပေးပါ။
   - (သတိပြုရန် - `playeraung449@gmail.com` ကို admin အဖြစ် သတ်မှတ်ရန် ညွှန်ကြားထားပါသည်)

## ၅။ ဝဘ်ဆိုဒ်ကို လွှင့်တင်ခြင်း (Hosting)
- ဤဖိုင်များအားလုံးကို Netlify, Vercel သို့မဟုတ် GitHub Pages တို့တွင် အခမဲ့ လွှင့်တင်နိုင်ပါသည်။

## ၆။ Telegram Bot သတ်မှတ်ခြင်း
- Telegram Bot Token နှင့် Admin Chat ID တို့ကို ဖိုင်များထဲတွင် ထည့်သွင်းပေးထားပြီး ဖြစ်ပါသည်။

---
**John Gaming Shop** - ၂၀၂၅ ခုနှစ်၏ ခေတ်မီ ဂိမ်းဝန်ဆောင်မှု ဝဘ်ဆိုဒ်။
