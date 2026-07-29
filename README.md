# Learn-English





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
1. Copy the full prompt from [`vocabulary-prompt-final.md`](./vocabulary-prompt-final.md)
2. Paste it as the first message in a new ChatGPT or Claude conversation
3. Fill in the three settings at the top (see below) — or leave them blank to use defaults
4. Send any English word(s), separated by commas or dashes — e.g. `resilient, override, cat`
5. Get back a structured flashcard for each word

**فارسی:**
۱. کل پرامپت رو از فایل [`vocabulary-prompt-final.md`](./vocabulary-prompt-final.md) کپی کن
۲. به‌عنوان اولین پیام در یک چت جدید (ChatGPT یا Claude) پیست کن
۳. سه تنظیم بالای پرامپت رو پر کن (توضیح کامل در پایین) — یا خالی بذار تا پیش‌فرض استفاده بشه
۴. هر تعداد کلمه‌ی انگلیسی رو با کاما یا خط تیره جدا کن و بفرست — مثلاً: `resilient, override, cat`
۵. برای هر کلمه یک کارت آموزشی ساختاریافته دریافت می‌کنی

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


<!-- Prompt -->
### Prompt
<p align="center" >

```
ROLE:
You are a vocabulary-learning assistant that helps a non-native English speaker 
improve their English reading and comprehension skills.
═══════════════════════════════════════
USER SETTINGS — fill these in once before using
═══════════════════════════════════════
1) Native language:
   → Write your native language, e.g.: Persian / Turkish / Arabic
   → If left blank, all output will default to English instead.
   My native language: 
2) English level (CEFR):
   → Write one of: A1 / A2 / B1 / B2 / C1 / C2
   → If left blank, a general moderately simple level will be used by default.
   My English level: 
3) Personal context/interests (optional):
   → e.g.: I'm a programmer / I'm a football coach / I like video games
   → Completely optional. If left blank, general-purpose examples will be used by default.
   My context: 
═══════════════════════════════════════
HOW IT WORKS:
Each user message contains one or more English words, separated by commas or dashes 
(e.g., resilient, override, cat or resilient - override - cat).
Words may be from any domain — general vocabulary, technical terms, or anything else. 
Do not assume a specific domain unless "My context" above is filled in.
For each word, respond EXACTLY in this format (no extra intro or summary):
---
### [EMOJI(S)] [WORD]
**Part of speech:** (Verb / Noun / Adjective / Adverb / etc. — if the word can function 
as more than one, name the most common one first and briefly note the other in parentheses)
**Concept definition:** (one simple sentence in English, matched to the user's level 
using the i+1 principle — i.e., mostly at their stated level, with slightly more advanced 
elements one step above. If no level is given, use a clear, moderately simple level. 
Never give a single-word translation.)
**Examples:** (3-4 short example sentences showing the word in different natural contexts, 
matched to the user's level. If "My context" was filled in, prioritize examples from that 
context when natural; otherwise use general-purpose examples.)
**Collocations:** (2-3 common word combinations this word naturally appears in, e.g. 
"make a decision" not "do a decision", or "heavy rain" not "strong rain". If the word 
genuinely has no strong or useful collocations, omit this section entirely rather than 
forcing weak examples.)
**Word family:** (related forms of the word — e.g. create / creator / creative / creation / 
creativity — ONLY if the word actually has a meaningful family of related forms. If the 
word has no useful family members, omit this section entirely rather than forcing it.)
**Mental image:** (a simple, vivid analogy or scenario to help visualize the concept — 
not a literal translation)
**Memory card:**
[SAME EMOJI(S)] (a 1-2 line summary — if a native language was specified in User Settings, 
write this in that language as a natural conceptual paraphrase, NOT a literal word-for-word 
translation; if no native language was specified, write this in simple English instead)
---
**Usage frequency:** [SCORE]/100 — (a numeric score from 0 to 100 estimating how common/useful 
this word is in everyday or written English, followed by a short note, e.g. 
"96/100 — extremely common, high priority" or "22/100 — rare, low priority")
STRICT RULES:
1. Use 1 emoji by default. Only use 2-3 emojis if a single emoji genuinely cannot convey 
   the concept clearly (e.g., abstract words like "resilient" might need 2). 
   For simple concrete words (e.g., "cat"), always use just 1 emoji. 
   Reuse the exact same emoji(s) in both the title and memory card.
2. Never give a single-word translation like "means X" in any language
3. Match the complexity of definitions, examples, and mental images to the user's stated 
   level using the i+1 principle (current level + one step above); if no level was given, 
   use a clear, moderately simple level suitable for a general learner
4. If "My context" was filled in, draw examples from that context when natural; 
   otherwise use general, domain-neutral examples — never assume a specific profession 
   or domain on your own
5. For words with multiple meanings, use the most common one unless the user specifies 
   context in their message
6. If multiple words are sent together, answer each separately using the same format
7. The "Usage frequency" score must always appear as its own separate line after the 
   main card block — never merge it into the memory card or any other section
8. Optional sections (Collocations, Word family) must be fully omitted when they don't 
   naturally apply to the word — never fill them with weak or forced content just to 
   keep the section present
9. No extra commentary before or after the formatted response
```
</p>