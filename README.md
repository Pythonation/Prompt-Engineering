
Prompt Engineering Cours in Arabic
# Prompt Engineering (Arabic)
<h1 align="right">هندسة التلقين (بالعربي)</h1>
<h2 align="right">الجزء الثاني من سلسلة الخوارزميات :البارادايم</h2>



<a href="https://www.youtube.com/channel/UC9ocsRoOwj9tkAQNfUt8ZJg?sub_confirmation=1"><img src="https://github.com/Pythonation/Prompt-Engineering/blob/main/Prompt%20engineering%20YouTube%20video.png"></a>


[![مجتع بايثون العربي](https://images.milled.com/2019-12-19/3pGli9s5cCGeONOJ/uM1ZG0_8Y8E8.gif)](https://www.youtube.com/channel/UC9ocsRoOwj9tkAQNfUt8ZJg?sub_confirmation=1)

<h3 style="direction: rtl; text-align: right;">العنصر الأول : المُهمّة الـTask</h3>
<p style="direction: rtl; text-align: right;">وهو التحديد الواضح للوظيفة أو الهدف الذي يجب أن يركز عليه النموذج ، وتعيين المهام في التلقينات أمر أساسي لا أعتقد أن أحداً منكم يجهله ، إلا أن الخطأ الذي سقط فيه الجميع هو ضيق الأفق ، الناس يستخدمون نوع محدود جدا من المهام مثل :</p>
<ul style="text-align: right;">
<li style="direction: rtl;">أكتب لي ..</li>
<li style="direction: rtl;">لخص لي ..</li>
<li style="direction: rtl;">أعد الصياغة ..</li>
</ul>
<p style="direction: rtl; text-align: right;">الخبر الجميل أن نماذج الذكاء الإصطناعي قادرة على تنفيذ آلاف المهام الأخرى ، دعنا نطرح على الشات جي بي تي السؤال التالي :</p>
<p>ما هي 100 مهمة أو فعل يمكن أن تقوم به كنموذج لغوي؟</p>
<p style="direction: rtl; text-align: right;">، وهنا في نفس الوقت سأعطيك درس في مسألة التحديد الواضح للمهمة ، دعنا نغير التلقينة إلى التالي :</p>
<ul style="text-align: right;">
<li style="direction: rtl;">ما هو 100 فعل أو أمر مباشر يمكن أن تقوم بها كنموذج لغوي يا شات جي بي تي؟</li>
</ul>
<p style="direction: rtl; text-align: right;">إلا أن ما يهمني هو أن أختار لك منها 3 مهام رائعة جدا يمكنك الإستفادة منها بشكل يومي .</p>
<p style="direction: rtl; text-align: right;">المهِمة الأولى : الفرز</p>
<p style="direction: rtl; text-align: right;">النماذج اللغوية قوية جدا في ترتيب الأشياء ، لن نستخدمها لترتيب الأشياء أبجديا سيكون ذلك إهانة لقوتها ، دعنا نجرب مثال بسيط، بما أننا جميعا نحب الأكل :</p>
<p style="direction: rtl; text-align: right;">" رتب لي هذه الأطباق من الأفضل صحيا إلى الأقل&nbsp; :</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">إليك مثال آخر :</p>
<p style="direction: rtl; text-align: right;">"</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">الآن ستكون فهمت فكرة الفرز ، ويمكنك مثلا استخدامها كذلك لترتيب لغات البرمجة من الأسهل إلى الأصعب أو حسب الوقت المطلوب لتعلمها ، ويمكن ترتيب الكواكب حسب وزنها أو دنوها من الأرض إلى غير هذا أمور الفرز التي لا يستطيع الإكسل القيام بها .</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">المهمة الثانية : الفلترة</p>
<p style="direction: rtl; text-align: right;">الفلترة أو التصفية لا تتطلب دائما معايير واضحة كفلترة مجموعة من البيانات التي تحتوي حرف أو رقم معين ، في المثال التالي لدي جدول إكسل يحتوي الكثير من الأسماء، بعض هذه الأسماء لأشخاص أجانب أريد استخراجها ،هل علي المرور على كل الأسماء ونسخها يدويا لأنه لا توجد معايير واضحة للفلترة . طبعا لا .</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">"</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">هذا مثال آخر للفلترة يقوم على استخراج وتنقيب البيانات :</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
