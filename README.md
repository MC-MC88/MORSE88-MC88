<div align="center">

# 🎯 MORSE88

**Bridging Arabic and Morse code — with a system that never existed before.**

</div>

---

<details>
<summary><b>🌍 Language / اللغة — English / العربية</b></summary>

- [🇬🇧 English Version](#-english-version)
- [🇲🇷 النسخة العربية](#-النسخة-العربية)

</details>

---

# 🇬🇧 English Version

## 👋 Welcome

Morse code has a standard. It's been standardized since 1865. Every letter in the Latin alphabet has an agreed pattern of dots and dashes — `S` is `...`, `O` is `---`, `E` is just a single dot. Everyone who learns Morse learns the same thing.

But Arabic never had one. Not officially. Different sources, different tables, different traditions — but no single agreed-upon Arabic Morse standard that everyone could point to and say *"this is the one."* When I searched for it, I found scattered references, half-finished tables, and conflicting opinions. Nothing authoritative.

So I built one myself.

**MORSE88** is a translator that handles both worlds: standard English Morse as it's been used for over a century, and a custom Arabic Morse mapping designed by **Mohamed Cheikh (MC88)** — built from the ground up around one guiding rule: **the more frequent the letter, the shorter its code.** Just like Morse was originally designed.

That makes MORSE88 more than a translator. It's the first clean, self-consistent, ready-to-use Arabic Morse system — and it's free to use, with one condition: the origin is acknowledged.

Open it, and you'll see: a translator, an English dictionary, an Arabic dictionary, and a copy-ready prompt for any AI. Four things, and that's the whole tool.

---

## 📸 Look Inside

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/MORSE88-MC88/raw/main/images/preview-1.png" alt="The MORSE88 translator" width="100%" />
  <br />
  <sub><b>① The translator</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/MORSE88-MC88/raw/main/images/preview-2.png" alt="The custom Arabic dictionary" width="100%" />
  <br />
  <sub><b>② The custom Arabic dictionary</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/MORSE88-MC88/raw/main/images/preview-3.png" alt="The AI prompt generator" width="100%" />
  <br />
  <sub><b>③ The AI prompt generator</b></sub>
</div>

---

## ✨ What you'll find

**Two dictionaries, one translator.**  
The tool handles standard English Morse (letters, digits, punctuation) and the custom Arabic Morse system designed by MC88. You switch between them, or let the tool detect the input automatically and choose the right one for you.

**Custom Arabic Morse — built around one rule.**  
The system follows the same principle that made Morse work in the first place: **frequency drives length.** The most-used Arabic letters get the shortest codes. `ا` (Alif) is a single dot. `ل` (Lam) is a single dash. Rare letters get longer, more complex patterns. This isn't arbitrary — it's a design.

**Automatic mode.**  
Type anything into the input field. If it's Arabic text, MORSE88 converts it to Arabic Morse. If it's English text, it uses standard Morse. If it's already Morse code, it tries to decode it back to text. No mode-switching required if you don't want it.

**Manual mode — when you need to be sure.**  
Three buttons at the top: **Auto**, **English**, **Arabic**. Lock the mode when you're working with mixed content and want predictable results.

**A complete dictionary, visible to you.**  
The Guide button opens a modal with the full tables — every English letter, every Arabic letter, every code. No black box. You can read the entire mapping yourself.

**A ready-to-copy AI prompt.**  
The **Prompt** button generates a complete instruction set you can paste into any AI model — ChatGPT, Claude, Gemini, anything. It tells the AI exactly which dictionary to use, how to handle spaces, and how to format the output. The prompt includes the full MC88 Arabic dictionary, so the AI will translate correctly even without this tool.

**Swap, copy, download, clear.**  
A round swap button in the middle flips the input and output. Copy puts the output on your clipboard. Download saves it as a text file. Clear resets both panels. Standard controls, placed where you'd expect them.

**Light and dark themes.**  
Two modes, both clean. The light theme is paper-white with bold black borders. The dark theme is matte charcoal with the same bold black-and-white contrast flipped. One button. Your choice is remembered.

**Works entirely in your browser.**  
No backend, no server, no tracking, no analytics. Everything happens locally. The translation logic, the dictionaries, the AI prompt — all of it is in the page. You can turn off the internet and MORSE88 will keep working.

---

## 🧭 How it works

**1. Open it.**  
One HTML file. No install, no dependencies, no build step. Double-click and it runs.

**2. Choose your mode.**  
Auto, English, or Arabic. The default is Auto, which handles most cases correctly.

**3. Type in the input panel.**  
Arabic text, English text, or Morse code. The output appears as you type, with a small delay to let you finish.

**4. Or paste Morse code.**  
The tool recognizes Morse input (`...` `---` `/`) and decodes it back to text.

**5. Swap if you need to.**  
The round button in the middle flips the two panels. Useful when you want to work backward from a result.

**6. Copy or download.**  
Standard controls at the bottom: **Copy Output**, **Download Text**, **Clear All**.

**7. Read the dictionary whenever.**  
Tap **Guide** in the header to see the full tables side by side.

**8. Get the AI prompt.**  
Tap **Prompt** in the header, copy the instruction set, and paste it into any AI model. It will now translate Arabic Morse using the MC88 system.

That's the whole tool. Nothing hidden.

---

## ⚖️ Copyright & Original Work

This section matters. Please read it.

**The custom Arabic Morse code system in MORSE88 was invented by Mohamed Cheikh (MC88).**

Before MORSE88, there was no single agreed-upon Arabic Morse standard. Different sources existed, but none were universal or authoritative. Searching for one resulted in conflicting tables, unfinished references, and contradictory traditions.

So I designed a new one from the ground up. The mapping in this tool is **my original work**, built around one deliberate principle: **more frequent letters receive shorter codes**, mirroring how Samuel Morse originally designed the Latin system in the 1830s.

**What you can do:**
- Use the tool freely, for personal or commercial purposes.
- Learn from the dictionary, study it, discuss it.
- Share the tool with others, link to it, recommend it.

**What requires acknowledgment:**
- If you use the MC88 Arabic Morse dictionary in your own project, you must credit **Mohamed Cheikh (MC88)** as its author.
- If you redistribute or republish the dictionary, keep this attribution visible.
- If you build a derivative system on top of it, mention the original source.

**What is not permitted:**
- Claiming the MC88 Arabic Morse system as your own work.
- Removing the copyright notice from the code.
- Publishing a modified version without noting the original.

This is not about restricting access. The tool is free, and it will stay free. It's about making sure the origin is honest — because building a new Arabic Morse standard from scratch is not a small thing, and it deserves to be recognized.

---

## 🛠️ A few small helps

**"Why isn't there an official Arabic Morse standard?"**  
Because Morse was designed for the Latin alphabet and the telegraph networks of Europe and North America in the 1800s. Arabic was never part of that original design. Some regional adaptations existed, but no single organization ever ratified a global Arabic Morse table. MORSE88 fills that gap with a coherent, documented, ready-to-use system.

**"How did you decide which Arabic letters get which codes?"**  
The rule was frequency. Letters that appear most often in everyday Arabic — `ا` (Alif), `ل` (Lam), `م` (Meem), `و` (Waw), `ن` (Noon) — received the shortest codes: one or two symbols. Letters that appear less often — `ظ` (Dhaa), `ذ` (Dhaal), `غ` (Ghayn) — received longer codes. This is the same principle Morse used for English, and it's the only principle that makes practical sense for a system built to be typed quickly.

**"Why does Auto mode assume Morse input means Arabic?"**  
Because if someone is entering raw Morse code without context, and they found their way to MORSE88, they're probably working with the Arabic system. If you want to decode Morse as English, switch to **English** mode manually and paste the same input.

**"Can I use this with an AI model?"**  
Yes — that's exactly what the **Prompt** button is for. It generates a complete instruction set including the full MC88 dictionary, ready to paste into ChatGPT, Claude, Gemini, or any other model. The AI will then be able to translate Arabic text and Morse in both directions using the same system.

**"Does this work offline?"**  
Completely. Open the HTML file, and everything runs in your browser. No internet required after the initial page load. The only thing that needs a connection is if you want to send the AI prompt somewhere.

**"Is anything sent to a server?"**  
No. Every translation happens locally. Every dictionary entry is stored in the page itself. Nothing leaves your device. No tracking, no analytics, no telemetry.

**"Can I add more letters or symbols?"**  
Yes. The two dictionaries at the top of the script (`customArabicMorseMap` and `standardEnglishMorseMap`) are plain JavaScript objects. Add an entry, and it works instantly. But if you're extending the **Arabic** dictionary, please be transparent about the fact that you're modifying the MC88 system — the point is that the original is credited.

**"What if my Arabic text has diacritics (tashkeel)?"**  
They're ignored by design. The translator works on the base letter. `م` and `مْ` produce the same Morse output. If you need diacritics encoded separately, that would be a different system, and MORSE88 doesn't try to do it.

---

## 📞 A question, an idea, a bug?

[![Email](https://img.shields.io/badge/Email-mohamed005cheikh@gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamed005cheikh@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+222_30_73_64_75-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/22230736475)
[![GitHub](https://img.shields.io/badge/GitHub-mohamed005cheikh--rgb-181717?style=flat-square&logo=github)](https://github.com/mohamed005cheikh-rgb)

<br />

*The first clean Arabic Morse standard — designed, not inherited.*

<sub>© 2026 Mohamed Cheikh — MC88</sub>

<br />
<br />

    ███    ███    ████████    ████████    ████████
    ████  ████   ███    ███  ███    ███  ███    ███
    ██ ████ ██   ███         ███    ███  ███    ███
    ██  ██  ██   ███          ████████    ████████
    ██      ██   ███         ███    ███  ███    ███
    ██      ██   ███    ███  ███    ███  ███    ███
    ██      ██    ████████    ████████    ████████

---

# 🇲🇷 النسخة العربية

<div dir="rtl">

## 👋 مرحبًا

شيفرة مورس لها معيار واحد. معتمدة رسميًا منذ العام 1865. كل حرف لاتيني له نمط متفق عليه من النقاط والشرطات — `S` هو `...`، و `O` هو `---`، و `E` هو نقطة واحدة فقط. كل من يتعلم مورس يتعلم الشيء نفسه.

لكن العربية لم يحدث لها ذلك. لم يكن هناك نظام رسمي معتمد. مصادر مختلفة، جداول متفرقة، تقاليد متضاربة — لكن لا يوجد مرجع موحّد يمكن الإشارة إليه والقول *"هذا هو المعيار."* عندما بحثت عنه، وجدت مراجع متناثرة، وجداول غير مكتملة، وآراء متعارضة. لا شيء موثوق.

فبنيتُ واحدًا بنفسي.

**MORSE88** هو أداة ترجمة تتعامل مع العالمين معًا: مورس الإنجليزي القياسي كما استُخدم لأكثر من قرن، ومورس عربي مخصّص من تصميم **محمد الشيخ (MC88)** — مبني من الصفر حول قاعدة واحدة موجّهة: **كلما زاد تكرار الحرف، قصر رمزه.** تمامًا كما صُمِّم مورس الأصلي.

وهذا يجعل MORSE88 أكثر من مجرّد مترجم. إنه **أول نظام مورس عربي نظيف ومتماسك وجاهز للاستخدام** — ومتاح للجميع مجانًا، بشرط واحد: الاعتراف بالأصل.

افتحه، وسوف ترى: مترجم، وقاموس إنجليزي، وقاموس عربي، ونص جاهز لنسخه إلى أي ذكاء اصطناعي. أربعة أشياء، وهذه هي الأداة كلها.

---

## 📸 نظرة من الداخل

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/MORSE88-MC88/raw/main/images/preview-1.png" alt="واجهة المترجم" width="100%" />
  <br />
  <sub><b>① المترجم</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/MORSE88-MC88/raw/main/images/preview-2.png" alt="القاموس العربي المخصّص" width="100%" />
  <br />
  <sub><b>② القاموس العربي المخصّص</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/MORSE88-MC88/raw/main/images/preview-3.png" alt="مولّد نص الذكاء الاصطناعي" width="100%" />
  <br />
  <sub><b>③ مولّد نص الذكاء الاصطناعي</b></sub>
</div>

---

## ✨ ما ستجده

**قاموسان، ومترجم واحد.**  
الأداة تتعامل مع مورس الإنجليزي القياسي (حروف، أرقام، علامات ترقيم) ومع نظام المورس العربي المخصّص من تصميم MC88. تستطيع التبديل بينهما، أو ترك الأداة تكتشف المدخل تلقائيًا وتختار النظام المناسب.

**مورس عربي مخصّص — مبني حول قاعدة واحدة.**  
النظام يتبع المبدأ نفسه الذي جعل مورس ينجح من الأساس: **التكرار يحدّد الطول.** الحروف العربية الأكثر استخدامًا تحصل على رموز أقصر. `ا` (ألف) نقطة واحدة. `ل` (لام) شرطة واحدة. الحروف النادرة تحصل على أنماط أطول وأكثر تعقيدًا. هذا ليس عشوائيًا — إنه تصميم واعٍ.

**الوضع التلقائي.**  
اكتب أي شيء في خانة الإدخال. إن كان النص عربيًا، يحوّله MORSE88 إلى مورس عربي. إن كان إنجليزيًا، يستخدم مورس القياسي. إن كان مورسًا بالفعل، يحاول فكّه إلى نص. لا حاجة للتبديل اليدوي إن لم ترغب.

**الوضع اليدوي — حين تحتاج اليقين.**  
ثلاثة أزرار في الأعلى: **تلقائي**، **إنجليزي**، **عربي**. ثبّت الوضع حين تعمل بنصوص مختلطة وتريد نتائج متوقعة.

**قاموس كامل، مرئي لك.**  
زر الدليل يفتح نافذة تحتوي الجدولين كاملين — كل حرف إنجليزي، وكل حرف عربي، وكل رمز. لا صندوق أسود. تستطيع قراءة الخريطة كاملة بنفسك.

**نص جاهز للنسخ إلى الذكاء الاصطناعي.**  
زر **Prompt** يولّد مجموعة تعليمات كاملة يمكنك لصقها في أي نموذج ذكاء اصطناعي — ChatGPT، Claude، Gemini، أي شيء. يخبر النموذج بالقاموس الذي يجب استخدامه، وكيفية التعامل مع المسافات، وكيفية تنسيق المخرجات. النص يتضمن قاموس MC88 العربي الكامل، فيترجم الذكاء الاصطناعي بدقة حتى بدون هذه الأداة.

**تبديل، نسخ، تنزيل، مسح.**  
زر دائري في المنتصف يعكس الإدخال والإخراج. زر النسخ يضع المخرَج في الحافظة. زر التنزيل يحفظه كملف نصي. زر المسح يعيد ضبط اللوحتين. أدوات قياسية، في أماكنها المتوقعة.

**نمطان بصريان: فاتح وداكن.**  
الوضع الفاتح ورقي بأبيض، بحدود سوداء سميكة. الوضع الداكن فحمي مطفيّ بنفس التباين معكوسًا. زرّ واحد. واختيارك محفوظ.

**يعمل بالكامل في متصفحك.**  
لا خادم، لا تتبّع، لا إحصاءات. كل شيء يجري محليًا. منطق الترجمة، والقاموسان، ونص الذكاء الاصطناعي — كلها داخل الصفحة. يمكنك قطع الإنترنت وسيستمر MORSE88 في العمل.

---

## 🧭 كيف يعمل

**١. افتحه.**  
ملف HTML واحد. لا تثبيت، لا اعتماديات، لا خطوة بناء. نقر مزدوج ويشتغل.

**٢. اختر وضعك.**  
تلقائي، إنجليزي، أو عربي. الافتراضي تلقائي، وهو يتعامل مع معظم الحالات بشكل صحيح.

**٣. اكتب في لوحة الإدخال.**  
نص عربي، أو نص إنجليزي، أو شيفرة مورس. المخرَج يظهر أثناء الكتابة، بتأخير صغير ليتيح لك إكمال ما تكتب.

**٤. أو الصق شيفرة مورس.**  
الأداة تتعرف على مدخلات مورس (`. . .` `---` `/`) وتفكّها إلى نص.

**٥. بدّل إن احتجت.**  
الزر الدائري في المنتصف يعكس اللوحتين. مفيد حين تريد العمل بالعكس من نتيجة وصلت إليها.

**٦. انسخ أو نزّل.**  
أدوات قياسية في الأسفل: **نسخ المخرَج**، **تنزيل نص**، **مسح الكل**.

**٧. اقرأ القاموس متى أردت.**  
اضغط **الدليل** في الترويسة لترى الجدولين جنبًا إلى جنب.

**٨. احصل على نص الذكاء الاصطناعي.**  
اضغط **Prompt** في الترويسة، انسخ مجموعة التعليمات، والصقها في أي نموذج ذكاء اصطناعي. سيكون الآن قادرًا على ترجمة المورس العربي بنظام MC88.

هذه هي الأداة كلها. لا شيء مخفي.

---

## ⚖️ الحقوق والعمل الأصلي

هذا القسم مهم. يُرجى قراءته.

**نظام المورس العربي المخصّص في MORSE88 من اختراع محمد الشيخ (MC88).**

قبل MORSE88، لم يكن هناك معيار مورس عربي موحّد ومتفق عليه. وُجدت مصادر مختلفة، لكن لا شيء منها كان شاملًا أو موثوقًا. البحث عنه كان يقود إلى جداول متضاربة، ومراجع غير مكتملة، وتقاليد متناقضة.

لذلك صمّمتُ نظامًا جديدًا من الصفر. الخريطة في هذه الأداة هي **عملي الأصلي**، مبنية حول مبدأ متعمّد واحد: **الحروف الأكثر تكرارًا تأخذ رموزًا أقصر**، على غرار الطريقة التي صمّم بها صامويل مورس النظام اللاتيني في ثلاثينيات القرن التاسع عشر.

**ما تستطيع فعله:**
- استخدام الأداة بحرية، للأغراض الشخصية أو التجارية.
- التعلم من القاموس، دراسته، مناقشته.
- مشاركة الأداة مع الآخرين، والربط بها، والتوصية بها.

**ما يتطلّب الإشارة إلى الأصل:**
- إن استخدمت قاموس MC88 العربي في مشروعك، يجب أن تنسبه إلى **محمد الشيخ (MC88)** كمؤلف له.
- إن أعدت نشر القاموس أو توزيعه، أبقِ هذه الإشارة ظاهرة.
- إن بنيت نظامًا مشتقًا منه، فاذكر المصدر الأصلي.

**ما لا يُسمح به:**
- ادّعاء أن نظام MC88 العربي المورس من عملك.
- إزالة إشعار الحقوق من الكود.
- نشر نسخة معدّلة دون الإشارة إلى الأصل.

الأمر ليس تقييدًا للوصول. الأداة مجانية، وستبقى مجانية. الأمر يتعلق بالأمانة حول الأصل — لأن بناء معيار مورس عربي جديد من الصفر ليس بالأمر الصغير، ويستحق أن يُعترف به.

---

## 🛠️ مساعدات صغيرة

**"لماذا لا يوجد معيار مورس عربي رسمي؟"**  
لأن مورس صُمِّم للأبجدية اللاتينية ولشبكات التلغراف في أوروبا وأمريكا الشمالية في القرن التاسع عشر. العربية لم تكن جزءًا من ذلك التصميم الأصلي. وُجدت بعض التعديلات الإقليمية، لكن لم تصادق أي جهة عالمية على جدول مورس عربي واحد. MORSE88 يسدّ هذه الفجوة بنظام متماسك، موثّق، وجاهز للاستخدام.

**"كيف قرّرت أي حرف عربي يأخذ أي رمز؟"**  
القاعدة كانت التكرار. الحروف التي تظهر أكثر في العربية اليومية — `ا`، `ل`، `م`، `و`، `ن` — نالت رموزًا أقصر: رمزًا أو رمزين. الحروف الأقل ظهورًا — `ظ`، `ذ`، `غ` — نالت رموزًا أطول. هذا هو المبدأ نفسه الذي استخدمه مورس للإنجليزية، وهو المبدأ العملي الوحيد لنظام صُمِّم ليُكتب بسرعة.

**"لماذا يفترض الوضع التلقائي أن المورس المُدخَل عربي؟"**  
لأن من يُدخل مورسًا خامًا بلا سياق، وقد وصل إلى MORSE88، فالأرجح أنه يعمل بالنظام العربي. إن أردت فكّ المورس كإنجليزي، بدّل يدويًا إلى وضع **إنجليزي** والصق المدخل نفسه.

**"هل أستطيع استخدامه مع الذكاء الاصطناعي؟"**  
نعم — وهذا بالضبط ما زرّ **Prompt** من أجله. يولّد مجموعة تعليمات كاملة تتضمن قاموس MC88 العربي الكامل، جاهزة للصق في ChatGPT أو Claude أو Gemini أو أي نموذج آخر. سيتمكن الذكاء الاصطناعي حينها من ترجمة النص العربي والمورس في الاتجاهين بالنظام نفسه.

**"هل يعمل دون إنترنت؟"**  
تمامًا. افتح ملف HTML، وكل شيء يعمل في متصفحك. لا حاجة للإنترنت بعد تحميل الصفحة الأولى. الشيء الوحيد الذي يحتاج اتصالًا هو إن أردت إرسال نص الذكاء الاصطناعي إلى مكان ما.

**"هل يُرسَل شيء إلى خادم؟"**  
لا. كل ترجمة تحدث محليًا. كل مدخل في القاموس مخزّن في الصفحة نفسها. لا شيء يغادر جهازك. لا تتبّع، لا إحصاءات، لا قياسات.

**"هل أستطيع إضافة حروف أو رموز أخرى؟"**  
نعم. القاموسان في أعلى السكربت (`customArabicMorseMap` و `standardEnglishMorseMap`) كائنا JavaScript عاديان. أضف مدخلًا، وسيعمل فورًا. لكن إن كنت تُوسّع القاموس **العربي**، فيرجى أن تكون شفافًا حول أنك تُعدّل نظام MC88 — الفكرة كلها أن الأصل يُنسب إليه.

**"ماذا لو كان نصّي العربي يحتوي على تشكيل؟"**  
يُتجاهل بالتصميم. يعمل المترجم على الحرف الأساسي. `م` و `مْ` يُنتجان المخرَج نفسه. لو احتجت ترميز التشكيل بشكل منفصل، فسيكون ذلك نظامًا آخر، وMORSE88 لا يحاول القيام بذلك.

---

## 📞 سؤال، فكرة، خطأ؟

[![Email](https://img.shields.io/badge/Email-mohamed005cheikh@gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamed005cheikh@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+222_30_73_64_75-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/22230736475)
[![GitHub](https://img.shields.io/badge/GitHub-mohamed005cheikh--rgb-181717?style=flat-square&logo=github)](https://github.com/mohamed005cheikh-rgb)

<br />

*أول معيار مورس عربي نظيف — مصمَّم، لا موروث.*

<sub>© 2026 محمد الشيخ — MC88</sub>

</div>

<br />
<br />

<div align="center" dir="ltr" style="direction:ltr;text-align:center">

    ███    ███    ████████    ████████    ████████
    ████  ████   ███    ███  ███    ███  ███    ███
    ██ ████ ██   ███         ███    ███  ███    ███
    ██  ██  ██   ███          ████████    ████████
    ██      ██   ███         ███    ███  ███    ███
    ██      ██   ███    ███  ███    ███  ███    ███
    ██      ██    ████████    ████████    ████████

</div>
