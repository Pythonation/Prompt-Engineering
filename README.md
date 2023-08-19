
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
<ul style="text-align: right; list-style-type: disc;">
<li style="direction: rtl; text-align: right;">
<blockquote><span style="color: #33cccc;"><em><strong>"ما هي 100 مهمة أو فعل يمكن أن تقوم به كنموذج لغوي؟"</strong></em></span></blockquote>
</li>
</ul>
<p style="direction: rtl; text-align: right;">، وهنا في نفس الوقت سأعطيك درس في مسألة التحديد الواضح للمهمة ، دعنا نغير التلقينة إلى التالي :</p>
<ul style="text-align: right;">
<li style="direction: rtl;">
<blockquote><strong>"ما هو 100 فعل أو أمر مباشر يمكن أن تقوم بها كنموذج لغوي يا شات جي بي تي؟"</strong></blockquote>
</li>
</ul>
<p style="direction: rtl; text-align: right;">إلا أن ما يهمني هو أن أختار لك منها 3 مهام رائعة جدا يمكنك الإستفادة منها بشكل يومي .</p>
<h2 style="direction: rtl; text-align: right;">المهِمة الأولى : الفرز</h2>
<p style="direction: rtl; text-align: right;">النماذج اللغوية قوية جدا في ترتيب الأشياء ، لن نستخدمها لترتيب الأشياء أبجديا سيكون ذلك إهانة لقوتها ، دعنا نجرب مثال بسيط، بما أننا جميعا نحب الأكل :</p>
<blockquote>
<p style="direction: rtl; text-align: right;"><em><strong>" رتب لي هذه الأطباق من الأفضل صحيا إلى الأقل&nbsp; :&nbsp;</strong></em></p>
<p style="direction: rtl; text-align: right;"><em><strong>Italian pizza, الكباب التركي, American hamburger, الفلافل ,أسلاك النحاس; كسكس ; فول مدمس ; crepe; Nutella; سم الفئران "</strong></em></p>
</blockquote>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<blockquote>
<p style="direction: rtl; text-align: right;"><em>إليك مثال آخر :</em></p>
<p style="direction: rtl; text-align: right;"><em><strong>" رتب من الأكثر لؤما الى الأقل مع ذكر السبب :</strong></em></p>
<p style="direction: rtl; text-align: right;"><em><strong>الجوكر باربي سبونج بوب كابتن ماجد هيفاء وهبي المحقق كونان&nbsp; بهجت الأباصيرى محمد رمضان"</strong></em></p>
</blockquote>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">الآن ستكون فهمت فكرة الفرز ، ويمكنك مثلا استخدامها كذلك لترتيب لغات البرمجة من الأسهل إلى الأصعب أو حسب الوقت المطلوب لتعلمها ، ويمكن ترتيب الكواكب حسب وزنها أو دنوها من الأرض إلى غير هذا أمور الفرز التي لا يستطيع الإكسل القيام بها .</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<h2 style="direction: rtl; text-align: right;">المهمة الثانية : الفلترة</h2>
<p style="direction: rtl; text-align: right;">الفلترة أو التصفية لا تتطلب دائما معايير واضحة كفلترة مجموعة من البيانات التي تحتوي حرف أو رقم معين ، في المثال التالي لدي جدول إكسل يحتوي الكثير من الأسماء، بعض هذه الأسماء لأشخاص أجانب أريد استخراجها ،هل علي المرور على كل الأسماء ونسخها يدويا لأنه لا توجد معايير واضحة للفلترة . طبعا لا .</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl;">يمكننا ببساطة نسخ كل الأسماء وأن نطلب من النموذج اللغوي القيام بالعمل :</p>
<blockquote>
<p style="direction: rtl;">" قم بفلترة الأشخاص الذين ليسو من أصل عربي :</p>
<table style="width: 544.4px;">
<tbody>
<tr>
<td style="width: 535.4px;">Aiden Moonstone</td>
</tr>
<tr>
<td style="width: 535.4px;">Amira Talib</td>
</tr>
<tr>
<td style="width: 535.4px;">Ammarah Nabil</td>
</tr>
<tr>
<td style="width: 535.4px;">Asher Stormrider</td>
</tr>
<tr>
<td style="width: 535.4px;">Aurora Starling</td>
</tr>
<tr>
<td style="width: 535.4px;">Celeste Emberglow</td>
</tr>
<tr>
<td style="width: 535.4px;">Dalia Tahir</td>
</tr>
<tr>
<td style="width: 535.4px;">Farisah Adnan</td>
</tr>
<tr>
<td style="width: 535.4px;">Hamidah Layla</td>
</tr>
<tr>
<td style="width: 535.4px;">Iman Rami</td>
</tr>
<tr>
<td style="width: 535.4px;">Iris Skylark</td>
</tr>
<tr>
<td style="width: 535.4px;">Isabella Moonlight</td>
</tr>
<tr>
<td style="width: 535.4px;">Jasper Evergreen</td>
</tr>
<tr>
<td style="width: 535.4px;">Karimah Nassir</td>
</tr>
<tr>
<td style="width: 535.4px;">Khaled Aziz</td>
</tr>
<tr>
<td style="width: 535.4px;">Layla Samir</td>
</tr>
<tr>
<td style="width: 535.4px;">Luna Silverbrook</td>
</tr>
<tr>
<td style="width: 535.4px;">Maximilian Frost</td>
</tr>
<tr>
<td style="width: 535.4px;">Orion Nightshade</td>
</tr>
<tr>
<td style="width: 535.4px;">Phoenix Blackwood</td>
</tr>
<tr>
<td style="width: 535.4px;">Rafiqah Hani</td>
</tr>
<tr>
<td style="width: 535.4px;">Rayan Nour</td>
</tr>
<tr>
<td style="width: 535.4px;">Samiha Zaid</td>
</tr>
<tr>
<td style="width: 535.4px;">Seraphina Duskwood</td>
</tr>
<tr>
<td style="width: 535.4px;">Tariq Sana</td>
</tr>
<tr>
<td style="width: 535.4px;">Tristan Wintersong</td>
</tr>
<tr>
<td style="direction: rtl; text-align: right; width: 535.4px;">Violet Summerfield</td>
</tr>
</tbody>
</table>
<p style="direction: rtl;">"</p>
<p style="direction: rtl;">&nbsp;</p>
</blockquote>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">هذا مثال آخر للفلترة يقوم على استخراج وتنقيب البيانات :</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">لدينا مستند يحتوي على بعض المحادثات العشوائية ونريد أن نستخرج منه الإيميلات وأرقام الهاتف، أيضا نقوم بنسخ المحتوى ونطلب من النموذج التالي :</p>
<blockquote>
<p style="direction: rtl; text-align: right;"><em><strong>" استخرج معلومات الإتصال من هذا النص :</strong></em></p>
<p><em><strong>&nbsp;</strong></em></p>
<p style="text-align: right;"><em><strong>محادثة 1:</strong></em></p>
<p style="text-align: right;"><em><strong>Emma: Yes, I did. It's about the upcoming project, right?</strong></em></p>
<p style="text-align: right;"><em><strong>+44 (789) 987-6543</strong></em></p>
<p style="text-align: right;"><em><strong>&nbsp;</strong></em></p>
<p style="text-align: right;"><em><strong>محادثة 2:</strong></em></p>
<p style="text-align: right;"><em><strong>John: Have you seen the latest updates on the website?</strong></em></p>
<p style="text-align: right;"><em><strong>Sarah: Reach out to the IT department, they can help you with that.</strong></em></p>
<p style="text-align: right;"><em><strong><a href="mailto:john.doe@example.com">john.doe@example.com</a></strong></em><br /><em><strong>..</strong></em></p>
<p style="direction: rtl; text-align: right;"><em><strong>"</strong></em></p>
<p style="direction: rtl; text-align: right;"><em><strong>&nbsp;</strong></em></p>
</blockquote>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<h2 style="direction: rtl; text-align: right;">المهمة الثالثة : الإستنباط</h2>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">هذه الوظيفة قوية جداً وتهُم الباحثين ومحللي الظواهر ، مثلا لدينا هذا الملف فيه معلومات عن أيام الأسبوع وعدد المثلجات التي تم بيعها في شاطيء ما وعدد حالات الغرق</p>
<p style="direction: rtl;">&nbsp;&nbsp;</p>
<p style="direction: rtl;"><strong>" استنبط سبب منطقي لنتيجة الحدث:</strong></p>
<p style="direction: rtl;"><strong>مكان الحدث : الشاطيء</strong></p>
<p style="direction: rtl;"><strong>البيانات: ... ........."</strong></p>
<p>&nbsp;</p>
<p style="direction: rtl;">نقوم بلصق البيانات ، لا تقلق النماذج اللغوية يمكنها أن تتخيل التنسيق.</p>
<p style="direction: rtl;">أليس هذا رائعا لقد استنبط النموذج أن العلاقة بين ارتفاع عدد حالات الغرق وعدد قطع الايس المباعة بسبب أن استهلاك الآيس كريم أعلى في الأيام الحارة وبالتالي فإن أعداد الناس في الشاطيء تزيد بسبب الحرارة ، مما يعني أن عدد الغرقى يرتفع بارتفاع عدد المصطفين وليس له علاقة باستهلاك الآيس كريم . جميل !</p>
<p>&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">يمكن استخدام نفس المهمة لتحليل البيانات لن نطيل أكثر . إلى الآن ستكون قد استوعبت أن مهام النماذج اللغوية ليست محدودة كما كنت تعتقد ، وأن هذه النماذج تفهم اكثر من اللغة &nbsp;، وأنها تفهم كذلك البيانات الفوضوية التي ننسخها اليها من الاكسل والمستندات .</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">مازلنا في العنصر الأول من عناصر التلقينة الجيدة ، الآن سننتقل إلى العنصر الثاني .</p>
<p style="direction: rtl;">&nbsp;</p>
<p>&nbsp;</p>
<h1 style="direction: rtl;"><span style="font-size: 14px;">العنصر الثاني : السياق الـ Context</span></h1>
<p style="direction: rtl; text-align: right;">رأينا في الفصل الماضي كيف يمكننا تزويد النماذج اللغوية بكل تلك المهام الرائعة، لكنّ المهام لتُنتج نتائج أكثر دقة فهي بحاجة إلى سياق ، لنفترض أنني شخص مبتدئ يتعلم لغة بايثون الآن ، سنذهب إلى&nbsp;</p>
<p style="direction: rtl;">bard ونكتب :</p>
<blockquote>
<p style="direction: rtl;"><em><strong>"تمارين لغة بايثون"</strong></em></p>
</blockquote>
<p style="direction: rtl;">النتيجة ليست جيدة</p>
<p style="direction: rtl;">لنُجرب الأمر في شات جي بي تي:</p>
<blockquote>
<p style="text-align: right;"><em><strong>"تمارين لغة بايثون"</strong></em></p>
</blockquote>
<p>&nbsp;</p>
<p style="direction: rtl;">أفضل لكن إذا كان الشخص مبتديء سيضيع هنا لنعد إلى bard ، الآن سنُضيف السياق أولا :</p>
<p style="direction: rtl;"><span style="font-size: 14px;"><em><strong>"أنا مبتديء في لغة بايثون وأجد صعوبة في فهم الحلقات التكرارية ،اكتب لي تمارين من الأسهل الى الأصعب مع شرح كل جزء من الكود"</strong></em></span></p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">كما أن السياق مهم بشكل حاسم حين يتعلق الأمر بوظائف التسويق الالكتروني ، إليك مثال آخر :</p>
<blockquote>
<p style="direction: rtl;"><span style="font-size: 14px;">"</span><strong style="font-size: 14px;">كيف يمكنني تسويق منتجي؟"</strong></p>
</blockquote>
<h2>&nbsp;</h2>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">التوجيهات التي يقدمها لنا النموذج عامة ، ما رأيك أن نضيف السياق ؟ حسنا سنعيد كتابة التلقينة بالشكل التالي :</p>
<blockquote>
<p style="direction: rtl; text-align: right;"><em><strong>"أنا أملك مشروعا صغيرا لطباعة القمصان وبيعها للشباب، تصميماتي جريئة ومبتكرة، لكنني لا أعرف كيف أسوقها خاصة على الأنترنت، أريد خطوات"</strong></em></p>
</blockquote>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">هل رأيت كيف تغيرت النتيجة إلى الأفضل ، هناك أمر يجبُ تعيه كذلك : معظم النماذج لديها ذاكرة قصيرة خلال المحادثة ،هذا لا يعني أنه لا يمكنها تذكر السياق طيلة المحادثة ، من الأفضل إذا أردت أن تغيير السياق أن تنشيء محادثة جديدة أو أن تطلب من النموذج أن ينسى كل شيء ، نعم ذك ممكن .</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;الآن لننتقل إلى العنصر الثالث .</p>
<p>&nbsp;</p>
<p style="direction: rtl;"><span style="font-size: 14px;">العنصر الثالث : الأدوار</span></p>
<p style="direction: rtl;">لكي يعمل النموذج اللغوي بأفضل ما لديه يجب أولاً أن يعرف أي عباءة يجب أن يرتدي، فحين تقوم بطرح سؤال ما أحيانا يختلف الرد حسب نوع الخبير، وأنت لن تريد ترك ذلك للصدفة. فعلى سبيل المثال عند سؤال النموذج :</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">حسب نوع الخبير، وأنت لن تريد ترك ذلك للصدفة. فعلى سبيل المثال عند سؤال النموذج :</p>
<blockquote>
<p style="direction: rtl; text-align: right;"><strong><em>"ما هو البحر ؟"</em></strong></p>
</blockquote>
<p style="direction: rtl; text-align: right;">سيخبرك أنه كتلة من المياه إلى آخره ، إذا أضفنا الدور في البداية وجعلناه على الشكل التالي :</p>
<blockquote>
<p style="direction: rtl; text-align: right;"><em><strong>"انت بروفيسور في الأدب العربي، ما هو البحر ؟"</strong></em></p>
</blockquote>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">&nbsp;إتقان الأدوار إذا كان تخصصك يعتمد على الكتابة أو صناعة المحتوى أمر مهم ويؤثر على جودة وقوة النتائج ، لنجرب مثلاً هذا :</p>
<p style="direction: rtl;">"أكتب لي فقرة عن أهمية البيانات"</p>
<p style="direction: rtl;">&nbsp;طبعا ستكون الإجابة مختلفة والنوذج سيتحدقث عن البحور الشعرية،</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl;">إتقان الأدوار إذا كان تخصصك يعتمد على الكتابة أو صناعة المحتوى أمر مهم ويؤثر على جودة وقوة النتائج ، لنجرب مثلاً هذا :</p>
<p style="direction: rtl;"><em><strong>"أكتب لي فقرة عن أهمية البيانات"</strong></em></p>
<p style="direction: rtl;">النتيجة كانت عبارة عن فقرة إنشائية مبتذلة ، الآن سنضيف الدور :</p>
<p>&nbsp;</p>
<blockquote>
<p style="text-align: right;"><em><strong>"أنت مدون تقني محترف مع خبرة كبيرة في علم البيانات وتجيد الكتابة الابداعية، أكتب لي فقرة عن أهمية البيانات"</strong></em></p>
</blockquote>
<p style="text-align: right;">&nbsp;هل رأيت كيف استجاب النموذج بشكل مختلف وقدم لنا فقرة جيدة ومثيرة للإهتمام ،بنفس الطريقة يمكنك كتابة مقالات ، فيديوهات ،أو حتى كتب ، إذا أضفت السياق مع الأدوار فأنت سترفع اللعبة إلى مستوى آخر خاصة في المهام المتعلقة بالتسويق والتخطيط الإستراتيجي ,.</p>
<p style="text-align: right;">إذن ما يجب فعله هو تحديد الدور في بداية التلقينة ولكي لا نكون غافلين أو نضيق علي الناس فالأدوار كثيرة وغير محدودة ، هذه قائمة بأشهرها ، لكنني أريدك أن تُشغّل دماغك وتبدع الدور الذي تحتاجه تلقينتك لأنني سبق وشرحت لك أن نماذج LLM هي نماذج دلالية وتنظر الى الكلمات عبر معانيها ، لا داعي لحفظ هذه الأشياء فهي ليست أوامر .</p>
<p style="text-align: right;">&nbsp;</p>
<p style="text-align: right;">&nbsp;</p>
<p>&nbsp;</p>
