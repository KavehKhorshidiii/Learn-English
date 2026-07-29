<h1 align="center">Learn English</h1>
<p align="center">

Ready-to-use prompts that turn any AI chat into a personalized English tutor —
built for non-native speakers who want to improve their **vocabulary, reading
comprehension, and speaking** skills.

پرامپت‌های آماده که چت هوش مصنوعی رو تبدیل می‌کنن به یک معلم شخصی‌سازی‌شده‌ی
زبان انگلیسی — مخصوص افرادی که زبان مادری‌شون انگلیسی نیست و می‌خوان **واژگان، درک مطلب و مهارت مکالمه**‌شون
رو تقویت کنن.

</p>

<br/>
<br/>

## prompt | پرامپت
<h3 align="left">

→ [Click here | برای پرامپت واژگان اینجا کلیک کنید](./Prompts/Vocabulary/Vocabulary.md)

→ [Click here | برای پرامپت صحبت کردن اینجا کلیک کنید](./Prompts/Speaking/Speaking.md)

</h3>

<br/>
<br/>

## Screenshots

##### Vocabulary
![Screenshot](./screenshot/Vocabulary/Vocabulary.png)

##### Speaking
![Screenshot](./screenshot/Speaking/Speaking.png)

<br/>
<br/>

## How to use | نحوه‌ی استفاده

##### Vocabulary

###### English
1. Copy the full prompt from [`here`](./Prompts/Vocabulary/Vocabulary.md)
2. Paste it as the first message in a new ChatGPT or Claude conversation
3. Fill in the three settings at the top (see below) — or leave them blank to use defaults
4. Send any English word(s), separated by commas or dashes — e.g. `apple, car`
5. Get back a structured flashcard for each word

###### فارسی
1. کل پرامپت رو از فایل [`اینجا`](./Prompts/Vocabulary/Vocabulary.md) کپی کن
2. به‌عنوان اولین پیام در یک چت جدید (ChatGPT یا Claude) پیست کن
3. سه تنظیم بالای پرامپت رو پر کن (توضیح کامل در پایین) — یا خالی بذار تا پیش‌فرض استفاده بشه
4. هر تعداد کلمه‌ی انگلیسی رو با کاما یا خط تیره جدا کن و بفرست — مثلاً: `apple, car`
5. برای هر کلمه یک کارت آموزشی ساختاریافته دریافت می‌کنی

<br/>

##### Speaking

###### English
1. Copy the full prompt from [`here`](./Prompts/Speaking/Speaking.md)
2. Paste it as the first message in a new ChatGPT or Claude conversation
3. Fill in the settings at the top (see below) — or leave them blank to use defaults
4. Start chatting in English as if you were speaking to a real person
5. Get a natural conversational reply, plus optional gentle feedback and vocabulary tips
6. If you don't understand a message, just say "I didn't understand" (in English or your
   native language) and the AI will explain it and give you example answers

###### فارسی
1. کل پرامپت رو از فایل [`اینجا`](./Prompts/Speaking/Speaking.md) کپی کن
2. به‌عنوان اولین پیام در یک چت جدید (ChatGPT یا Claude) پیست کن
3. تنظیمات بالای پرامپت رو پر کن (توضیح کامل در پایین) — یا خالی بذار تا پیش‌فرض استفاده بشه
4. به انگلیسی شروع به چت کن، انگار داری با یک آدم واقعی صحبت می‌کنی
5. یک پاسخ طبیعی مکالمه‌ای همراه با فیدبک ملایم و نکات واژگانی (در صورت نیاز) دریافت می‌کنی
6. اگه یه پیام رو متوجه نشدی، کافیه بگی "نفهمیدم" (به انگلیسی یا زبان مادری‌ت) و هوش مصنوعی
   اون رو برات توضیح می‌ده و چند نمونه جواب هم بهت پیشنهاد می‌ده

<br/>
<br/>

## User Settings explained | توضیح بخش تنظیمات کاربر

##### Vocabulary

At the top of the prompt, there are three settings to fill in **once**, before you start
sending words:

بالای پرامپت، سه تنظیم وجود داره که باید **یک‌بار** قبل از فرستادن کلمات پر کنی:

**1. Native language | زبان مادری**
```
My native language: Persian
```
**EN:** Used only for the *Memory card* section of each flashcard — a short conceptual
summary written in your native language (not a literal translation). Every other part
of the card stays in English on purpose, so you keep practicing reading comprehension.
If left blank, everything defaults to English.

**2. English level (CEFR) | سطح انگلیسی**
```
My English level: B1
```
**EN:** One of `A1 / A2 / B1 / B2 / C1 / C2`. Controls the difficulty of definitions,
examples, and explanations using the "i+1" principle — mostly at your level, with a
slight stretch above it. If left blank, a general moderately simple level is used.

**3. Personal context/interests (optional) | زمینه یا علایق شخصی (اختیاری)**
```
My context: I'm a programmer
```
**EN:** Completely optional. If filled in, example sentences will naturally draw from
your world (e.g., a programmer might see examples about code, a football coach might
see examples about training). If left blank, general-purpose examples are used —
the assistant will never assume a profession or domain on its own.

<br/>

##### Speaking

At the top of the prompt, there are four settings to fill in **once**, before you start
chatting:

بالای پرامپت، چهار تنظیم وجود داره که باید **یک‌بار** قبل از شروع چت پر کنی:

**1. Native language | زبان مادری**
```
My native language: Persian
```
**EN:** Used only as a backup — for short clarifications when you say you didn't
understand something. It is never used as the default language of the conversation.
If left blank, clarifications are given in simple English instead.

**2. English level (CEFR) | سطح انگلیسی**
```
My English level: B1
```
**EN:** One of `A1 / A2 / B1 / B2 / C1 / C2`. Controls the difficulty of the AI's
replies, corrections, and vocabulary using the "i+1" principle. If left blank, the AI
starts at a general moderate level and adjusts as it learns your level from your messages.

**3. Today's topic (optional) | موضوع امروز (اختیاری)**
```
Today's topic: my job interview
```
**EN:** Completely optional. If filled in, the conversation will focus on that topic.
If left blank, the AI starts with light small talk and lets the topic evolve naturally.

**4. Personal context/interests (optional) | زمینه یا علایق شخصی (اختیاری)**
```
My context: I'm a programmer
```
**EN:** Completely optional. Used to make conversation topics and examples feel more
relevant and personal to you. If left blank, general-purpose topics are used.

<br/>
<br/>

## What each response includes | محتوای هر پاسخ

##### Vocabulary

| Section | English | فارسی |
|---|---|---|
| Part of speech | Grammatical role of the word | نقش دستوری کلمه |
| Concept definition | Simple English definition, matched to your level | تعریف ساده‌ی انگلیسی، متناسب با سطح تو |
| Examples | 3-4 natural example sentences | جمله‌ی مثال طبیعی |
| Collocations *(if relevant)* | Common word pairings (e.g. "make a decision") | ترکیب‌های رایج کلمه |
| Word family *(if relevant)* | Related word forms (e.g. create/creator/creative) | اشکال مرتبط کلمه |
| Mental image | A visual analogy to help you remember | یک تصویر ذهنی برای کمک به یادسپاری |
| Memory card | Short summary in your native language | خلاصه‌ی کوتاه به زبان مادری |
| Usage frequency | Score (0-100) showing how common the word is | امتیاز (0 تا 100) نشان‌دهنده‌ی رواج کلمه |

<br/>

##### Speaking

| Section | English | فارسی |
|---|---|---|
| 💬 Reply | A natural conversational response with a follow-up question | پاسخ طبیعی مکالمه‌ای همراه با یک سوال ادامه‌دار |
| 📝 Feedback *(if needed)* | Gentle correction of a meaningful mistake | اصلاح ملایم یک اشتباه مهم |
| 🌟 More natural way to say it *(if relevant)* | A more native-like way to phrase what you said | یک روش طبیعی‌تر برای بیان همون جمله |
| 🔑 Useful word/phrase *(if relevant)* | One relevant new word or expression | یک کلمه یا عبارت مفید و مرتبط |
| 🔍 "I didn't understand" mode *(on demand)* | Explains the previous message + gives example answers | توضیح پیام قبلی + چند نمونه جواب |

<br/>
<br/>

## Why use these prompts? | چرا از این پرامپت‌ها استفاده کنیم؟

##### Vocabulary

Learning English vocabulary is not just about memorizing translations.
This prompt helps you understand words through context, examples, and memory techniques —
so you can recognize and use new vocabulary more naturally while reading English.

یادگیری واژگان فقط حفظ کردن ترجمه نیست.
این پرامپت کمک می‌کند کلمات را با مفهوم، مثال و تصویر ذهنی یاد بگیرید؛
تا هنگام خواندن متن‌های انگلیسی، کلمات جدید را بهتر درک و به خاطر بسپارید.

<br/>

##### Speaking

Speaking fluently isn't just about knowing grammar rules — it's about practicing real,
live conversation without fear of making mistakes. This prompt gives you a patient
conversation partner who keeps the chat natural and engaging, while quietly helping
you sound more fluent over time.

مهارت مکالمه فقط دونستن قواعد گرامری نیست — تمرین یک گفتگوی واقعی و زنده، بدون ترس از
اشتباه کردنه. این پرامپت یک همراه صبور برای مکالمه بهت می‌ده که گفتگو رو طبیعی و جذاب
نگه می‌داره، و در همون حین به آرومی کمکت می‌کنه با گذر زمان روون‌تر صحبت کنی.

<br/>
<br/>

## A list of other learning resources

<h3 align="left">

→ [Language learning resources](https://kavehkhorshidiii.notion.site/Language-learning-resources-3ac62d44ff8380eea592cea27b0acb85?source=copy_link)

</h3>

<br/>
<br/>

## Author

**Kaveh Khorshidi**

[![GitHub](https://img.shields.io/badge/GitHub-kavehkhorshidiii-181717?logo=github)](https://github.com/KavehKhorshidiii)

[![Email](https://img.shields.io/badge/Email-kavehkhorshidiii%40gmail.com-181717?logo=gmail&logoColor=white)](mailto:kavehkhorshidiii@gmail.com)