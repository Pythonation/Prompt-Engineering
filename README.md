[![ReadMeSupportPalestine](https://raw.githubusercontent.com/Safouene1/support-palestine-banner/master/banner-support.svg)](https://techforpalestine.org/learn-more)
Prompt Engineering Cours in Arabic
# Prompt Engineering (Arabic)
<h1 align="right">هندسة التلقين (بالعربي)</h1>
<h2 align="right">الجزء الثاني من سلسلة الخوارزميات :البارادايم</h2>



<a href="https://youtu.be/gZv5hFW3OF8"><img src="https://github.com/Pythonation/Prompt-Engineering/blob/main/Prompt%20engineering%20YouTube%20video.png"></a>


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
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">العنصر الرابع : مؤشر المخرجات Output Indicator</p>
<p style="text-align: right;">&nbsp;</p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">تحديد صيغة المخرجات هو من الأمور الرائعة التي يستمر 99% من المستخدمين في تجاهلها دائما ، ميزة قوية مثل هذه من العار أن لا تستفيد منها أياً كان عملك أو تخصصك ، لندخل في صلب الموضوع وسنستثمر كل العناصر التي تعلمناها سابقا في تلقينة واحدة ..</p>
<p style="direction: rtl; text-align: right;">لنبدأ بالدور :</p>
<p style="direction: rtl; text-align: right;"><em><strong>" أنت بروفيسور في علوم الحاسب ولديك آلاف الطلبة تعلمهم البرمجة ،"</strong></em></p>
<p style="direction: rtl; text-align: right;">الآن نضيف السياق:</p>
<p style="direction: rtl; text-align: right;"><em><strong>" أنا طالب مبتدئ يريد أن يتعلم البرمجة ذاتيا،"</strong></em></p>
<p style="direction: rtl; text-align: right;">ثم نضيف المُهمّة بالتفصيل :</p>
<p style="direction: rtl; text-align: right;"><strong>"من فضلك أخبرني بأكثر 10 لغات البرمجة طلبا ودرجة صعوبة كل لغة (من 1 إلى 10) والوقت المطلوب بالأسابيع لتعلم كل لغة. <br />النتيجة عبارة عن جدول "</strong></p>
<p style="text-align: right;">&nbsp;</p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">كما ترى المخرجات جاءت عبارة عن جدول ، بالمناسبة هذه الجداول يمكن نسخها لبرنامج الإكسل كما يمكننا أيضا تغيير صيغة المخرجات هكذا إلى CSV ثم نسخهاا ووضعها في ملف نصي وحفظه بصيغة CSV وهكذا سيتحول الى spreadsheet تلقائيا، من اليوم توقف عن النسخ سطرا بسطر واختصر الوقت عبر توليد جداول كاملة .</p>
<p style="direction: rtl; text-align: right;">هل تعلم كذلك أن تشات جي بي تي يمكنها القيام ببعض الرسوم البيانية ؟ لكنها غبية في ذلك لن نتطرق لهذا الأمر حاليا، في المقابل دعنا نتعرف على نوع مخرجات قوي جدا للطلبة والعلماء ، سنكتب التلقينة التالية</p>
<p style="text-align: right;">&nbsp;</p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;"><strong>"أنت أستاذ إحصاء ،</strong></p>
<p style="direction: rtl; text-align: right;"><strong>سنة 2022 كان عدد المتابعين: 176000،</strong></p>
<p style="direction: rtl; text-align: right;"><strong>سنة 2021 كان عدد المتابعين:148172،</strong></p>
<p style="direction: rtl; text-align: right;"><strong>سنة 2020 كان عدد المتابعين:56199.</strong></p>
<p style="text-align: right;">&nbsp;</p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;"><strong>أحسب توقعات الثلاث سنوات القادمة باستخدم latex</strong></p>
<p style="direction: rtl; text-align: right;"><strong>مع النتائج "</strong></p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">في هذا المثال بغض النظر عن دقة النتائج ذلك لا يهمنا ، ما أريدك أن تلاحظ وتفهم هو أن الشات جي بي تي يستطيع تنفيذ تنسيق لاتيكس لكتابة المعادلات وكل تلك الأشياء التي نحتاجها في الأوراق العلمية أو التمارين المدرسية ، والخبر السعيد بالنسبة للدكاترة هو أن هذا النموذج يمكنه توليد كودات لاتيكس كذلك ، يمكن نسخها لمحررات الـ markdown ,.</p>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">النماذج اللغوية معظمها قادر على توليد أي نوع من الأكواد البرمجية ، لا أظن أننا بحاجة لمثال على ذلك ، الميزة التي أفادتني بشكل كبير في مشاريع الويب هي ملفات json حيث أننا أحيانا نحتاج لقواعد بيانات صغيرة للإعدادات البسيطة ، على سبيل المثال إذا كان عندي موقع حيث يدخل المستخدم اسم دولته ويتم اختيار رمز الهاتف ورمز اللغة تلقائيا ، سأذهب هذه المرة إلى Bard وأطلب منه أن ينشيء لي ملف json بتلك المعلومات هكذا :</p>
<blockquote>
<p style="direction: rtl;"><em><strong>" أسماء الدول ورمزها الهاتفي ورمز لغتها وكلمة مرحبا بلغتها</strong></em></p>
<p>&nbsp;</p>
<p style="direction: rtl; text-align: right;"><em><strong>المخرجات :json "</strong></em></p>
</blockquote>
<p style="text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl; text-align: right;">هذا جيد ، يجب أن تعرف كذلك أن هذه النماذج قوية جدا في تحويل صياغ البيانات وعادة أستخدمها لتحويل جداول البيانات الى ملف json أو xml أو لتحويل كود لغة برمجة معينة الى لغة برمجة أخرى . سنكتشف ذلك في العنصر التالي من عناصر التلقينة الجيدة ، أما الآن فأريد أن أريك صيغة أخرى من صيغ المخرجات قد تهم مصمم الجرافيكس ،</p>
<p style="direction: rtl; text-align: right;">هل تعلم أنه بإمكاننا استخدام الشات جي بي تي للرسم ؟</p>
<blockquote>
<p style="text-align: right;"><br /><em><strong>" أرسم لي وجه حزين بألوان زاهية، باستخدام svg"</strong></em></p>
</blockquote>
<p style="text-align: right;">هذا كود فيكتور يمكننا استخدامه مع الاتش تي إم إل أو يمكننا نسخه وحفظ الملف بصيغة SVG ، إذا فتحناه مع المتصفح سنرى التصميم ، طبعاً ستكون واهما إذا كنت تعتقد أنه يمكنك تصميم أشياء متقدمة بهذه الطريقة فهذا نموذج لغوي فقط ولم يتم تدريبه على الرسم نهائيا فهذا الشيء تعلمه النموذج صدفة ! هناك نماذج توليدية للرسوم والصور مثل stable diffusion، ربما نخصص له حلقة إن أردتم .</p>
<p style="text-align: right;">لحظة تذكرت أن هناك نوع آخر من المخرجات قد يفيد الطلبة كثيرا ، هو المخططات الشجرية ، على سبيل المثال :<br /><em><strong>"مخطط متعدد المستويات (شجرة) لعلم الذكاء الاصطناعي"</strong></em></p>
<p style="direction: rtl;">هذا يمكن أن يكون مفيدا ، وهذا مثال مفيد أكثر من الأول :</p>
<p><em><strong>" Multilevel diagram (tree) for ANN types in artificial intelligence"</strong></em><br />بالنسبة لي هذا النوع من الخطاطات يسمح لي بفهم الأشياء بشكل فعال ، لا أدري عنكم</p>
<p>&nbsp;</p>
<p style="text-align: right;">أصدقائي هذه لائحة بأنواع المخرجات التي تستطيع تحديدها للنماذج ، ومع هذا أظن أنكم تنظرون إلى قمة</p>
<p style="text-align: right;">الجبل الجليدي فقط ن هناك أشياء أخرى تننتظر من يكتشفها ,</p>
<div>
<blockquote>
<p>Checklists<br /> الخطاطات<br />Vector <br /> JSON<br /> Graphs<br /> Extensible Markup Language (XML)<br />النصوص المنسقة<br />الشيفرات البرمجية<br />الجداول<br /> CSV<br />تنسيق الأوراق العلمية LaTeX<br />تنسيق Markdown</p>
</blockquote>
</div>
<p style="text-align: right;">&nbsp;</p>
<h1 style="direction: rtl;">العنصر الخامس : المدخلات Input Data</h1>
<p style="direction: rtl;">هذا العنصر يبقى شيء إضافي إلا في بعض الحالات ، المدخلات هي بيانات نضيفها مع التلقينة لكي نسمح للنموذج اللغوي بالتعلم منها أو أخذها كمثال ، على سبيل المثال هناك حركة قوية يستخدمها المسوقون ، حين تطلب من الشات جي بي تي على سبيل المثال أن يُصمم لك خطة تسويقية أو ينظم لك مشروعك أجد أنه من المفيد أن تطلب من الشركة أن تقدم لك معلومات عن الرؤية Vision وتعريف مفصل عن خدماتها ونقاط قوتها ولِمَ لا بعض أرقامها في الأشهر الأخيرة ، هذه المعلومات نضيفها في آخر التلقينات.</p>
<p>&nbsp;</p>
<p style="direction: rtl;">&nbsp;</p>
<p style="direction: rtl;">سنكتب مثالا صغيرا وسنوظف فيه كل عناصر التلقينة الجيدة بالإضافة إلى هذا العنصر الأخير :</p>
<p style="direction: rtl;"><em><strong>" أنت خبير تسويق إلكتروني، نحن متجر صغير للنظارات الطبية نحاول اكتساب زبائن جدد، صمم لنا استراتيجية تسويقية على شكل تاكتيكات ابداعية بصيغة قابلة للتنفيذ ومقسمة على أسابيع ."</strong></em></p>
<p style="text-align: right;">ثم بعد هذا نضيف كل المعلومات الموجودة لدينا بعد كتابة "معلومات إضافية عنا" ، عليك أن تضع كل هذه المعلومات بين علامتي اقتباس، ومن تم إضف كل شيء تعرفه عن الشركة والمشروع ، أنا سأضيف كذلك بعض المعلومات الأخرى عن التسويق.</p>
<p style="direction: rtl;">هذه الأمور ساعدت على توليد استراتيجية جيدة وأكثر تفصيلا ومراعاةً لرؤية المشروع ، أحيانا المدخلات الإضافية في مهام الكتابة ربما تكون مقال نعطيه للنموذج ونطلب منه أن يكتب لنا مقال بنفس جودته أو أسلوبه.</p>
<p style="direction: rtl;">يجب الإنتباه أن شات جي بي تي تسمح فقط بحوالي 16 ألف حرف في التلقينة ، بينما bard يسمح بأقل من نصف هذا العدد.</p>
<p style="text-align: right;">كانت هذه العناصر الخمسة حسب تقييمنا أهم عناصر التلقينة الجيدة هذا لا يعني أنه لا توجد عناصر أخرى في انتظارك لإكتشافها يا حبيب، ربما كان يجب أن أذكرك قبل بداية الجزء بأن كل هذه التلقينات التي استخدمناها سأشاركها معك على شكل ملف نصي يمكنك النسخ منه وتجربتها بنفسك . ستجده في صندق الوصف .</p>
<p style="text-align: right;">الآن سننتقل إلى التقنيات وهو موضوع مثير جدا للإهتمام وضروري لكل مهندس تلقين ، رجاء إذا كنت تسمعني الآن وقطعت معي هذا الشوط الطويل قم بتسجيل الإشتراك إنن لم تفعل بعد ولا تنسى زر الإعجاب .</p>
<p style="direction: rtl; text-align: right;">تقنيات التلقين Prompting Techniques :</p>
<p style="direction: rtl; text-align: right;">هناك الكثير من تقنيات التلقين ويمكن للموضوع أن يتشعب ، لكن هناك 4 تقنيات يتفقُ علماء البيانات أنها الأساس والعمود الفقري لكل التقنيات الأخرى. إذا كنت تود أن تصبح مهندس تلقين فمن الواجب أن تعرفها لأنك ستسمع هذه المصطلحات باستمرار .</p>
<p style="direction: rtl; text-align: right;">التقنية الأولى : Zero-Shot Prompting</p>
<p style="direction: rtl; text-align: right;">هي التقنية الأصلية التي نشأت نماذج معالجة اللغات الطبيعية من أجلها أساسا، ففي ستينيات القرن الماضي قام الدكتور "فايزنباوم" بابتكار ELIZA - أول شات بوت في التاريخ وقد تم استخدامه آنذاك في جلسات العلاج النفسي !</p>
<p style="direction: rtl; text-align: right;">كانت الإمكانيات واعدة جداً ولكن الفكرة فشلت، إنها سابقة لأوانها ! ولكن من حسن حظ من يقرؤون التاريخ ويتعمقون في دقائق التقنيات أنهم جيدون في اقتناص الفرص ، خلاف الأشخاص الذين يبحثون دائما عن سطحيات التقنية .</p>
<p style="direction: rtl; text-align: right;">فما إن حقق الذكاء الإصطناعي صحوته حتى عاد الناس لإستغلاله في كل شيء وفي تنفيذ كل فكرة كانت صعبة التطبيق أو مستحيلةَ في الماضي . هذا ما فعله "ألتمان"ورفاقه ، وهكذا أصبح لإليزا أحفاد وأهمهم اليوم تشات جي بي تي !</p>
<p style="direction: rtl;">ما أحاول قوله أن فكرة نماذج اللغات الكبيرة نشأت كفكرة شات بوت ، وهذا هو معنى كلمة chat الموجودة في إسم chatgpt ، وبالتالي فإن فكرة التواصل مع الشات بوت بكفاءة قائمة على التلقين الصفري Zero-Shot Prompting</p>
<p style="direction: rtl;">وهذا الأخير فضلت أن أطيل في شرح ظروفه التاريخية لأن شرح مفهومه بسيط جدا :</p>
<p style="direction: rtl;">Zero-Shot Prompting هو كتابة تلقينة مباشرة وعامة بدون سياقٍ ولا أي مثال ، والنموذجُ سيكون قادراً على تزويدك بإجابات عن أسئلة لم يتم تدريبه بالضرورة للإجابة عنها بشكل مباشر .</p>
<p style="direction: rtl;">تماما مثل ما يفعل غالبية الناس مع نماذج اللغات الآن ، الأسئلة المباشرة أو الطلبات القصيرة ، من أمثلتها :</p>
<p style="direction: rtl;">&bull; ما هي عاصمة فرنسا ؟</p>
<p style="direction: rtl;">&bull; لخص النص التالي: ...</p>
<p style="direction: rtl;">&bull; ترجم الجملة التالية ..</p>
<p style="direction: rtl;">باختصار التعامل مع النموذج اللغوي على أساس أنه شات بوت ، طبعاً هذا مؤسف لأن هذه النماذج أصبحت شيء أكبر .</p>
<p style="direction: rtl;">عموما تقنية الـZero-Shot رغم أن نتائجها قد لا تكون أفضل شيء في بعض السيناريوهات، إلا أنها سريعة وأقل تعقيدا وضرورية للاستخدامات اليومية ، بالإضافة إلى أنها أرخص بكثير وأقل كلفة لمطوري تطبيقات الويب لأن الـ API الخاصة بهذه النماذج تدفع فيها مقابل عدد الكلمات وهذا أمر مهم جدا للمبرمجين .</p>
<p style="direction: rtl; text-align: right;">&nbsp;</p>
<p style="direction: rtl;">التقنية الثانية : Few-Shot Prompting</p>
<p style="direction: rtl;">من التقنيات الأصلية التي تستَخدم حتى في عملية تدريب نماذج الـ LLM ، نعم هندسة التلقين تسستخدم حتى في تدريب االنماذج ،والشركات الكبرى توظف الكثير من مهندسي التلقين لهذا الغرض .</p>
<p style="direction: rtl;">يُمكِّن الـ Few-Shot Prompting النماذج اللغوية من آداء المهام الأكثر تعقيدا بشكل أفضل ، وذلك عبر تقديم مجموعة من العروض التوضيحية لهذه النماذج، ذلك هو ما فعلناه بالضبط في أمثلة التلقينة الجيدة ، لتتضح الفكرة فإن تقنية zero-shot السابقة هي أشبه ما تكون بالأوامر ، بينما تقنية الـ Few-shots هي أشبه ما تكون بالتلقين ، إليك مثال بسيط :</p>
<p style="direction: rtl;">"</p>
<p style="direction: rtl;">&bull; س:المغرب</p>
<p style="direction: rtl;">&bull; ج:الرباط</p>
<p style="direction: rtl;">&bull; س: السودان</p>
<p style="direction: rtl;">&bull; ج: ..</p>
<p style="direction: rtl;">"</p>
<p style="direction: rtl;">النموذج رد علينا بـ "الخرطوم" ، دون أن تتضمن التلقينة أي إشارةٍ واضحة أو مباشرة أن المطلوب هو عاصمة السودان، لكننا وضحنا للنموذج المطلوب منه عبر المثال ، البعض سينظر لهذا الأمر وكأنه شيء غبي أو بديهي !</p>
<p style="direction: rtl;">صدقني إذا فكرت قليلاً في ما حصل الآن بالضبط من جانبه التقني المحض فنحن أمام معجزة . دعنا نستكشف طريقة أخرى لاستخدام هذه التقنية .</p>
<p style="direction: rtl;">أولا سنقوم باختراع كلمة عشوائية لا توجد في اللغة العربية ، على سبيل المثال كلمة "جمودار" .</p>
<p style="direction: rtl;">دعنا نتأكد إذا كان النموذج اللغوي يعرف أي شيء عنها ؟ واضح أنه لا يعرف معناها</p>
<p style="direction: rtl;">الآن لنكتب التلقينة التالية :</p>
<p style="direction: rtl;">"كان جمال يتجمودر عن الرياح في سيارته وكانت جمودارا منيعا .</p>
<p style="direction: rtl;">أعطني 5 جمل تتضمن كلمة جمودار &ldquo;</p>
<p style="direction: rtl;">أرأيت ، إنه تعلم كلمةُ جديدة وفهم معناها من السياق ، بل ها هو أعطانا 5 جمل تتضمنها بأسلوب متين جدا .</p>
<p style="direction: rtl;">إتقان هذه التقنية يسمح لنا بدفع النماذج إلى حافة قوتها عبر إعادة تدريبها ،إنها تتعلم بكفاءة مرعبة ، تخيل معايا أنها تتعلم شيء جديد بالكامل من مثال واحد ! هذه القوة يجب أن تستغلها لتقود الـ chatgpt وأشباهها إلى النتيجة التي تطمح إليها .</p>
<p style="direction: rtl; text-align: right;">ملاحظة يجب الإنتباه إليها ، المثالين السابقين هناك من يُطلق عليهما one-shot prompting لأننا استخدمنا مثال واحد ، هذا يجعلك تتسآل كيف ستصبح قوة هذه النماذج إذا استخدمت أمثلة متعددة ووفرت سياق كامل أثناء التلقين ؟!</p>
<p style="direction: rtl; text-align: right;">سنرى مثال آخر للتصنيف ، بما أن هذه التقنية جيدة في التصنيف لنفترض أنني صاحب متجر ويأتي أشخاص بعضهم نصاب وبعضهم صادق، ولأنني ذكي ماشاء الله حفظت كل ما قالوا لي ووضعتها على الشكل التالي مع النتيجة التي حصلت عليها:</p>
<p style="direction: rtl;">"<em><strong>بع لي وسأدفع لك لاحقا لأنني نسيت المال" / نصاب</strong></em></p>
<p style="direction: rtl;"><em><strong>"سأشتري واحدة وسأدفع لك الآن" / ليس نصاب</strong></em></p>
<p style="direction: rtl;"><em><strong>"هل تقبل الدفع بالبيتكوين" / نصاب</strong></em></p>
<p style="direction: rtl;"><em><strong>"جارك لديه أثمنة أفضل منك" / نصاب</strong></em></p>
<p style="direction: rtl;"><em><strong>"سآخذ 10 لكن أريد تخفيض" / ليس نصاب</strong></em></p>
<p style="direction: rtl;"><em><strong>بعد ذلك سنضيف الجملة الجديدة التي لا نعرف نتيجتها وهي:</strong></em></p>
<p style="direction: rtl;"><em><strong>"أعطني 2 وسأعود للدفع لاحقا" / ..</strong></em></p>
<p style="direction: rtl;">النموذج رد علينا وهو جاهز لتحليل احتمالية النصب مستقبلاً ، إنه نموذج إحصائي جاهز للتنبؤ بل هو أفضل حتى لأن النماذج الإحصائية تحتاج بيانات ضخمة ومعادلات ، السؤال : هل يمكنني استخدام هذه التقنية في حياتي العملية لحساب احتمالية حدوث شيء ما ، على سبيل المثال فقدان عميل أو مدى جدية صفقةٍ ما .</p>
<p style="direction: rtl;">الجواب نعم وبقوة ، ولكن يجب أن تجمع بيانات كافية عن تجاربك السابقة لكي تستطيع تقديمها على شكل shots للنموذج .</p>
<p style="direction: rtl;">التقنية الثالثة : Chain-of-Thought Prompting</p>
<p style="direction: rtl;">هل سبق وطلبت من الشات جي بي تي القيام بعملية حسابية منطقية بسيطة جداً ولكنه فشل في ذلك ؟ هل نمت مطمئناً تلك الليلة لأن الذكاء الاصطناعي مازال غبيا وأنك تفوقت عليه ؟</p>
<p style="direction: rtl;">دعني أخيّب ظنك ، إن ما حصل فقط هو أنك لا تعرف كيف تتعامل مع هذه النماذج، ولم تسمع قط بتقنية COT التي سنطلق عليها بالعربي التلقين باستخدام تسلسل الفكرة .</p>
<p style="direction: rtl;">هذه التقنية ظهرت لأول مرةِ العام الماضي في ورقة علمية من تأليف " جايسون وي" ورفاقه حيث أثبتوا بما لا يقبل الشك أن سلسلة من خطوات التفكير الوسيطة &ndash; يمكنها أن تحسن بشكل كبير من قدرة النماذج اللغوية الكبيرة على أداء المهام المنطقية المعقدة.</p>
<p style="direction: rtl; text-align: right;">دعنا نكتشف ذلك عبر المثال التالي :</p>
<p style="direction: rtl;"><em><strong>"أحمد لديه قلمين واشترى 3 علب أقلام كل واحدة سعتها 10 اقلام لكن احداها فيها النصف فقط</strong></em></p>
<p style="direction: rtl;"><em><strong>. كم قلم لدى أحمد ؟</strong></em></p>
<p style="direction: rtl;"><em><strong>."</strong></em></p>
<p style="direction: rtl;">تعالى نتفرج في الأجوبة في شات جي بي تي وbard ، أيهما أعطانا الجواب الصحيح ؟</p>
<p style="direction: rtl;">الجواب ولا واحد منهما ، لأن أحمد لديه 27 قلم وهذه مسألة من كتاب المدرسة الابتدائية !</p>
<p style="direction: rtl;">هنا تأتي أهمية التلقين بتسلسل الفكرة Chain-of-Thought Prompting، ما سنفعله هو دمج الـ Few-shots معه .</p>
<p style="direction: rtl;">أولاً لنقم بإضافة مسألة شبيهة سهلة في بداية التلقينة :</p>
<p style="direction: rtl;"><em><strong>"السؤال :مريم إشترت قطعة شوكولاته، ثم اشترت علبتي شوكلاته سعة كل واحدة 4 قطع ، إلا أن أحدى هذه العلب تحتوي على النصف فقط ، كم قطعة شوكلاته لدى مريم ؟</strong></em></p>
<p style="direction: rtl;"><em><strong>الجواب: 2 قطع التي كانت لديها + العلبة الأولى 4 قطع + العلبة الثانية 2 قطع لأنه فيها النصف فقط= 8 . "</strong></em></p>
<p style="direction: rtl;"><em><strong>السؤال : أحمد لديه قلمين واشترى 3 علب أقلام كل واحدة سعتها 10 اقلام لكن احداها فيها النصف فقط.</strong></em></p>
<p style="direction: rtl;"><em><strong>كم قلم لدى أحمد ؟</strong></em>"</p>
<p style="direction: rtl; text-align: right;">الآن هل رأيت كيف أصبح الرد أفضل بكثير ، بنفس الطريقة يمكن مساعدة النماذج اللغوية على حل أعقد وأصعب المسائل المنطقية ، لكن لا تخلط بين Few-shots و COT ، فالمقصود بتسلسل الأفكار في المثال السابق هو طريقة إجابتنا على المسألة الأولى ، دعني اُريك حتى تفهم .</p>
<p style="direction: rtl; text-align: right;">سنمسح تسلسل الحل في الجواب ونضع النتيجة فقط ، هل رأيت ماذا حصل ؟ لقد عاد النموذج إلى ضلاله القديم ، يعني القضية كلها حول تسلسل الحل ، والمثير للإهتمام كيف بإمكاننا أحيانا إعطاء أمثلة صغيرة للنموذج بحيث يساعدنا في حل مسائل أكثر تعقيدا ، سأضع لكم رابط الورقة العلمية لمراجعتها والاستفادة أكثر مما تتضمنه من أمثلة وأفكار .</p>
<h2 style="direction: rtl; text-align: right;">التقنية الرابعة :الإتساق الذاتي Self-Consistency Prompting</h2>
<p style="direction: rtl;">في سيناريوهات الحياة الواقعية ، عند مواجهة مشكلة ما ، غالبًا ما نستكشف كبشر مسارات تفكير مختلفة أو نستشير مصادر متعددة للوصول إلى قرار مستنير. وبالمثل ، يهدف الاتساق الذاتي إلى محاكاة هذه العملية من خلال تزويد النموذج اللغوي بوجهات نظر متنوعة وتشجيعه على تقييم منطقه بشكل نقدي. من خلال القيام بذلك ، فإنه يزيد من احتمال توليد استجابة دقيقة وغير متحيزة.</p>
<p style="direction: rtl;">قبل كل شيء أريدك أن تعرف أن الإتساق الذاتي يُبنى على التقنية الثالثة COT كما أن الـتقنية الثالثة تُبنى على التتقنية التي قبلها ، تقنية الـ few-Shots . ترتيبنا ليس عشوائي .</p>
<p style="direction: rtl;">نحن الآن في تقنية الإتساق الذاتي ويرمز لها بـ SC ، دعنا نختبر مثال جديد :</p>
<p style="direction: rtl;"><em><strong>" عندما كنت في السادسة من عمري ، كانت أختي في نصف عمري. عمري 70 سنة ، كم عمر أختي؟ "</strong></em></p>
<p style="direction: rtl;">كما ترى الجواب غبي مرة أخرى .</p>
<p style="direction: rtl; text-align: right;">إذن كيف يمكننا تصويب الأمر من خلال الإتساق الذاتي ؟ الأمر بسيط ولكن مُتعِب لأغلبكم، يجب أن نقدم للنموذج مجموعة من الأمثلة المنطقية المتنوعة ومن الأفضل تقديم الأمثلة من داخل شركتك أو مجال عملك ولكن على كل حال يمكن تقديم مسائل مختلفة كما سأفعل الآن ، سأسرع الفيديو ، سأسرعه أكثر ، الآن انتهيت من كتابة المسائل وسأضيف سؤالنا في الأخير :</p>
<blockquote>
<p style="text-align: right;">س: لدى يوسف 20 حلوى على شكل عصا. أعطى زيد بعض الحلوى. الآن لديه يوسف 12 حلوى على شكل عصا. كم حلوى أعطى يوسف لزيد؟ ج: لدى يوسف 20 حلوى على شكل عصا. نظرًا لأنه لديه فقط 12 الآن، يجب أن يكون قد أعطى الباقي لـ زيد. يجب أن يكون عدد الحلوى التي قدمها لـ زيد هو 20 - 12 = 8 حلوى. الجواب هو 8. س: هناك 15 شجرة في البستان. عمّال البستان سيزرعون شجرات في البستان اليوم. بعد الانتهاء، سيكون هناك 21 شجرة. كم عدد الشجرات التي زرعها عمّال البستان اليوم؟ ج: نبدأ بـ 15 شجرة. لاحقًا لدينا 21 شجرة. يجب أن يكون الفرق هو عدد الشجرات التي زرعوها. لذلك، يجب أن يكونوا قد زرعوا 21 - 15 = 6 أشجار. الجواب هو 6. س: إذا كان هناك 3 سيارات في موقف الشارقة ووصلت سيارتان إضافيتان، كم عدد السيارات في موقف ال شارقة؟ ج: هناك بالفعل 3 سيارات في موقف الشارقة. وصلت سيارتان إضافيتان. الآن يوجد 3 + 2 = 5 سيارات. الجواب هو 5. س: لدى ليلى 32 شوكولاتة وكانت أختها لديها 42. إذا أكلوا 35، كم عدد القطع المتبقية لديهما إجمالًا؟ ج: لدى ليلى 32 شوكولاتة وأخت ليلى كانت لديها 42. وهذا يعني أنه كان هناك في البداية 32 + 42 = 74 شوكولاتة. تم أكل 35. لذا بإجمالي لديهما لا يزال 74 - 35 = 39 شوكولاتة. الجواب هو 39. س: لدى حسام خمسة ألعاب. لمناسبة عيد الميلاد، حصل على لعبتين من والدته ووالده. كم لعبة لديه الآن؟ ج: لديه 5 ألعاب. حصل على 2 من والدته، لذا بعد ذلك لديه 5 + 2 = 7 ألعاب. ثم حصل على 2 أخريات من والده، لذا بإجمالي لديه 7 + 2 = 9 ألعاب. الجواب هو 9. س: كان هناك تسعة أجهزة كمبيوتر في غرفة الخادم. تم تثبيت خمسة أجهزة كمبيوتر إضافية كل يوم، من الاثنين إلى الخميس. كم عدد الأجهزة الموجودة الآن في غرفة الخادم؟ ج: هناك 4 أيام من الاثنين إلى الخميس. تمت إضافة 5 أجهزة كمبيوتر في كل يوم. وهذا يعني إجمالًا 4 * 5 = 20 أجهزة كمبيوتر تمت إضافتها. كان هناك 9 أجهزة كمبيوتر في البداية، لذا الآن يوجد 9 + 20 = 29 أجهزة كمبيوتر. الجواب هو 29. س: لدى محمد 58 كرة جولف. في يوم الثلاثاء، فقد 23 كرة جولف. في يوم الأربعاء، فقد 2 كرات أخرى. كم عدد كرات الجولف التي كانت لديه في نهاية يوم الأربعاء؟ ج: في البداية كان لدى محمد 58 كرة. فقد 23 يوم الثلاثاء، لذا بعد ذلك لديه 58 - 23 = 35 كرة. في يوم الأربعاء فقد 2 كرات أخرى، لذا الآن لديه 35 - 2 = 33 كرة. الجواب هو 33. س: لدى عائشة 23 دولارًا. اشترت خمسة بيجلز بقيمة 3 دولارات للواحدة. كم المبلغ المتبقي لديها؟ ج: اشترت 5 بيجلز بقيمة 3 دولارات للواحدة. هذا يعني أنها أنفقت 5 * 3 = 15 دولارًا. لديها بقيمة 23 - 15 = 8 دولارات. الجواب هو 8.</p>
<p style="text-align: right;">س : عندما كنت في السادسة من عمري ، كانت أختي في نصف عمري. عمري 70 سنة ، كم عمر أختي؟ <br />ج:</p>
</blockquote>
<p style="direction: rtl;">الجواب 67 سنة ، نعم صحيح ، سترى أن معظم الأمثلة تستعرض طرق التحليل المنطقي الرياضي لا أقل ولا أكثر ، عموما لا حاجةَ كي أذكرك مرة أخرى أنني سأشارك معك هذه التلقينات في صندوق الوصف .</p>
<p style="direction: rtl;">ثبت أن الاتساق الذاتي يحسن النتائج في المهام الحسابية والمنطقية و في التفكير الرمزي. حتى عندما تبين أن CoT العادي غير فعال ، كان الاتساق الذاتي لا يزال قادرًا على تحسين النتائج ، هذا ما ورد في ورقة علمية بعنوان &ldquo;Chain of Thought Prompting Elicits Reasoning in Large Language Models&rdquo;.</p>
<p style="direction: rtl;">سأتأكد من وضع رابطها في صندوق الوصف لتطلع على البحث والأمثلة .</p>
<p style="direction: rtl; text-align: right;">توجد تقنيات أخرى للتلقين لكن سنكتفي بما ذكرنا لأن هذه التقنيات هي أم التخصص، في الفصل التالي سنتحدث عن أفضل المعايير التي وضعها لك الخبراء كي تستفيد من هذه النماذج اللغوية بأفضل طريقة ممكنة ، وطبعاً سنتحدث عن سلوكيات غير فعالة نهائيا كي لا تضيع وقتك معها .</p>
<p style="text-align: right;">&nbsp;</p>
