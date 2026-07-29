# 📚 Vocabulary Learning Prompt | پرامپت یادگیری واژگان انگلیسی

A ready-to-use ChatGPT/Claude prompt that turns any AI chat into a personalized English
vocabulary tutor — built for non-native speakers who want to improve **reading and
comprehension** skills.

یک پرامپت آماده برای ChatGPT/Claude که چت هوش مصنوعی رو تبدیل می‌کنه به یک معلم شخصی‌سازی‌شده‌ی
واژگان انگلیسی — مخصوص افرادی که زبان مادری‌شون انگلیسی نیست و می‌خوان مهارت **خواندن و درک مطلب**‌شون
رو تقویت کنن.

---

## 🚀 How to use / نحوه‌ی استفاده

**English:**
1. Copy the full prompt from [`Vocabulary.md`](./Prompts/Vocabulary/Vocabulary.md)
2. Paste it as the first message in a new ChatGPT or Claude conversation
3. Fill in the three settings at the top (see below) — or leave them blank to use defaults
4. Send any English word(s), separated by commas or dashes — e.g. `resilient, override, cat`
5. Get back a structured flashcard for each word
   
<br/>

**فارسی:**
1. کل پرامپت رو از فایل [`Vocabulary.md`](./Prompts/Vocabulary/Vocabulary.md) کپی کن
2. به‌عنوان اولین پیام در یک چت جدید (ChatGPT یا Claude) پیست کن
3. سه تنظیم بالای پرامپت رو پر کن (توضیح کامل در پایین) — یا خالی بذار تا پیش‌فرض استفاده بشه
4. هر تعداد کلمه‌ی انگلیسی رو با کاما یا خط تیره جدا کن و بفرست
5. برای هر کلمه یک کارت آموزشی ساختاریافته دریافت می‌کنی

---

## ⚙️ User Settings explained / توضیح بخش تنظیمات کاربر

At the top of the prompt, there are three settings to fill in **once**, before you start
sending words:

بالای پرامپت، سه تنظیم وجود داره که باید **یک‌بار** قبل از فرستادن کلمات پر کنی:

### 1. Native language / زبان مادری
```
My native language: Persian
```
**EN:** Used only for the *Memory card* section of each flashcard — a short conceptual
summary written in your native language (not a literal translation). Every other part
of the card stays in English on purpose, so you keep practicing reading comprehension.
If left blank, everything defaults to English.

**FA:** این فقط برای بخش *Memory card* هر کارت استفاده می‌شه — یک خلاصه‌ی مفهومی کوتاه به
زبان مادری‌ت (نه ترجمه‌ی تحت‌اللفظی). بقیه‌ی بخش‌های کارت عمداً انگلیسی می‌مونن تا مهارت
خواندن و درک مطلبت تمرین بشه. اگه خالی بذاریش، همه‌چیز پیش‌فرض انگلیسی می‌مونه.

### 2. English level (CEFR) / سطح انگلیسی
```
My English level: B1
```
**EN:** One of `A1 / A2 / B1 / B2 / C1 / C2`. Controls the difficulty of definitions,
examples, and explanations using the "i+1" principle — mostly at your level, with a
slight stretch above it. If left blank, a general moderately simple level is used.

**FA:** یکی از `A1 / A2 / B1 / B2 / C1 / C2`. سطح دشواری تعاریف، مثال‌ها و توضیحات رو
با اصل "i+1" کنترل می‌کنه — عمدتاً هم‌سطح خودت، با کمی چالش بالاتر. اگه خالی بذاری، یک
سطح متوسط و ساده به‌طور پیش‌فرض استفاده می‌شه.

### 3. Personal context/interests (optional) / زمینه یا علایق شخصی (اختیاری)
```
My context: I'm a programmer
```
**EN:** Completely optional. If filled in, example sentences will naturally draw from
your world (e.g., a programmer might see examples about code, a football coach might
see examples about training). If left blank, general-purpose examples are used —
the assistant will never assume a profession or domain on its own.

**FA:** کاملاً اختیاریه. اگه پر بشه، مثال‌ها تا حد امکان از دنیای تو میان (مثلاً برای
یک برنامه‌نویس، مثال‌ها حول کد می‌چرخن؛ برای یک مربی فوتبال، حول تمرین). اگه خالی بمونه،
مثال‌های عمومی استفاده می‌شن — دستیار هیچ‌وقت خودش حدس نمی‌زنه که شغل یا زمینه‌ت چیه.

---

## 🃏 What each flashcard includes / محتوای هر کارت آموزشی

| Section | English | فارسی |
|---|---|---|
| Part of speech | Grammatical role of the word | نقش دستوری کلمه |
| Concept definition | Simple English definition, matched to your level | تعریف ساده‌ی انگلیسی، متناسب با سطح تو |
| Examples | 3-4 natural example sentences | ۳ تا ۴ جمله‌ی مثال طبیعی |
| Collocations *(if relevant)* | Common word pairings (e.g. "make a decision") | ترکیب‌های رایج کلمه (مثل «make a decision») |
| Word family *(if relevant)* | Related word forms (e.g. create/creator/creative) | اشکال مرتبط کلمه (مثل create/creator/creative) |
| Mental image | A visual analogy to help you remember | یک تصویر ذهنی برای کمک به یادسپاری |
| Memory card | Short summary in your native language | خلاصه‌ی کوتاه به زبان مادری |
| Usage frequency | Score (0-100) showing how common the word is | امتیاز (۰ تا ۱۰۰) نشان‌دهنده‌ی رواج کلمه |

*Collocations and Word family only appear when they genuinely apply to the word —
they're skipped rather than filled with weak/forced content.*

*بخش‌های Collocations و Word family فقط وقتی ظاهر می‌شن که واقعاً برای اون کلمه معنی داشته
باشن — در غیر این صورت، به‌جای پر شدن با محتوای ضعیف، کلاً حذف می‌شن.*

---

## 📝 Notes / نکات

- Works with **any English word or phrasal verb** — not limited to a specific topic,
  unless you set a personal context.
  با **هر کلمه یا phrasal verb انگلیسی** کار می‌کنه — محدود به یک موضوع خاص نیست، مگر اینکه
  زمینه‌ی شخصی تعیین کرده باشی.
- You can send multiple words at once, separated by commas or dashes.
  می‌تونی چند کلمه رو هم‌زمان بفرستی، با کاما یا خط تیره جدا شده.
- Designed to keep you reading and thinking in English — the native language only
  appears as a small safety net at the end of each card.
  طراحی‌شده تا تو رو در حالت خواندن و فکر کردن به انگلیسی نگه داره — زبان مادری فقط به‌عنوان
  یک تور ایمنی کوچک در پایان هر کارت ظاهر می‌شه.
