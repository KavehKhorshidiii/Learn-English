<h1 align="center">Learn English</h1>
<p align="center">

A ready-to-use ChatGPT/Claude prompt that turns any AI chat into a personalized English
vocabulary tutor — built for non-native speakers who want to improve **reading and
comprehension** skills.

یک پرامپت آماده  که چت هوش مصنوعی رو تبدیل می‌کنه به یک معلم شخصی‌سازی‌شده‌ی
واژگان انگلیسی — مخصوص افرادی که زبان مادری‌شون انگلیسی نیست و می‌خوان مهارت **خواندن و درک مطلب**‌شون
رو تقویت کنن.

</p>


<br/>
<br/>


## How to use | نحوه‌ی استفاده

###### English
1. Copy the full prompt from [`here`](./Prompts/Vocabulary/Vocabulary.md)
2. Paste it as the first message in a new ChatGPT or Claude conversation
3. Fill in the three settings at the top (see below) — or leave them blank to use defaults
4. Send any English word(s), separated by commas or dashes — e.g. `apple, car`
5. Get back a structured flashcard for each word

<br/>

###### فارسی
1. کل پرامپت رو از فایل [`here`](./Prompts/Vocabulary/Vocabulary.md) کپی کن
2. به‌عنوان اولین پیام در یک چت جدید (ChatGPT یا Claude) پیست کن
3. سه تنظیم بالای پرامپت رو پر کن (توضیح کامل در پایین) — یا خالی بذار تا پیش‌فرض استفاده بشه
4. هر تعداد کلمه‌ی انگلیسی رو با کاما یا خط تیره جدا کن و بفرست — مثلاً: `apple, car`
5. برای هر کلمه یک کارت آموزشی ساختاریافته دریافت می‌کنی


<br/>
<br/>


## User Settings explained | توضیح بخش تنظیمات کاربر

At the top of the prompt, there are three settings to fill in **once**, before you start
sending words:

بالای پرامپت، سه تنظیم وجود داره که باید **یک‌بار** قبل از فرستادن کلمات پر کنی:

### 1. Native language | زبان مادری
```
My native language: Persian
```
**EN:** Used only for the *Memory card* section of each flashcard — a short conceptual
summary written in your native language (not a literal translation). Every other part
of the card stays in English on purpose, so you keep practicing reading comprehension.
If left blank, everything defaults to English.

### 2. English level (CEFR) | سطح انگلیسی
```
My English level: B1
```
**EN:** One of `A1 / A2 / B1 / B2 / C1 / C2`. Controls the difficulty of definitions,
examples, and explanations using the "i+1" principle — mostly at your level, with a
slight stretch above it. If left blank, a general moderately simple level is used.


### 3. Personal context/interests (optional) | زمینه یا علایق شخصی (اختیاری)
```
My context: I'm a programmer
```
**EN:** Completely optional. If filled in, example sentences will naturally draw from
your world (e.g., a programmer might see examples about code, a football coach might
see examples about training). If left blank, general-purpose examples are used —
the assistant will never assume a profession or domain on its own.


<br/>
<br/>


## What each flashcard includes | محتوای هر کارت آموزشی

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

---