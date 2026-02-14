<div dir="rtl" align="right">

<p align="right">
<a href="https://doi.org/10.5281/zenodo.18393840">
<img src="https://zenodo.org/badge/967615825.svg" alt="DOI">
</a>
</p>

<h1 align="right"> العلوم المفتوحة لظروف المحاصيل:M5</h1>

<blockquote>
<p align="right">كيف يمكن استخدام مجموعات بيانات <span dir="ltr">NASA</span> لرسم خرائط ظروف المحاصيل؟</p>
</blockquote>

<p align="right">
تركّز الوحدة الخامسة من
<a href="https://openclimatescience.github.io/curriculum"><span dir="ltr">openclimatescience.github.io/curriculum</span></a>
على كيفية بدء مشروع علمي حاسوبي قابل لإعادة الإنتاج، باستخدام ظروف المحاصيل كمثال موضوعي.
<strong>في نهاية هذه الوحدة، ينبغي أن تكون قادرًا على ما يلي:</strong>
</p>

<ul>
<li align="right">الوصول إلى مجموعات البيانات المعتمدة على الأقمار الصناعية والمتعلقة بإنتاجية النبات وحالته وعمليات النتح-التبخر، واستخدامها بفعالية.</li>
<li align="right">حساب مؤشر رضا متطلبات المياه للمحاصيل الزراعية.</li>
</ul>

<h2 align="right">المحتويات</h2>

<ol dir="rtl">
<li align="right">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/01_Creating_a_Project_Plan.ipynb">
<span dir="ltr">Creating a Project Plan</span>
</a><br>
إنشاء خطة مشروع
</li>
<li align="right">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/02_Creating_a_Reproducible_Research_Environment.ipynb">
<span dir="ltr">Creating a Reproducible Research Environment</span>
</a><br>
إنشاء بيئة بحثية قابلة لإعادة الإنتاج
</li>
<li align="right">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/03_Setting_Up_Data_Processing_Workflows.ipynb">
<span dir="ltr">Setting Up Data Processing Workflows</span>
</a><br>
إعداد سير عمل معالجة البيانات
</li>
<li align="right">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/04_Writing_a_Transparent_Algorithm.ipynb">
<span dir="ltr">Writing a Transparent Algorithm</span>
</a><br>
كتابة خوارزمية شفافة
</li>
</ol>

<h2 align="right">البدء</h2>

<p align="right">
<a href="https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md">راجع دليل التثبيت هنا</a>.
</p>

<p align="right">
يمكنك تشغيل دفاتر <span dir="ltr">Jupyter</span> في هذا المستودع باستخدام
<a href="https://docs.github.com/en/codespaces/overview"><span dir="ltr">Github Codespaces</span></a>
أو كحاوية تطوير في
<a href="https://code.visualstudio.com/docs/devcontainers/containers"><span dir="ltr">VSCode Dev Container</span></a>.
بعد تشغيل الحاوية، شغّل <span dir="ltr">Jupyter Notebook</span> كما يلي:
</p>

<pre dir="ltr"><code># Create your own password when prompted
jupyter server password

# Then, launch Jupyter Notebook; enter your password when prompted
jupyter notebook
</code></pre>

<p align="right">
يمكن تثبيت مكتبات <span dir="ltr">Python</span> المطلوبة للتمارين باستخدام مدير الحزم <span dir="ltr">pip</span>:
</p>

<pre dir="ltr"><code>pip install xarray netcdf4 dask
</code></pre>

<h2 align="right">نواتج التعلم</h2>

<p align="right">
يغطي هذا المقرر الكفاءات الأساسية التالية في
<a href="https://github.com/OpenClimateScience/Core-Competencies/blob/main/ScienceCore-Competencies.md">علم البيانات الحاسوبي</a>:
</p>

<ul>
<li align="right">توثيق العلاقة بين الشيفرة والنتائج والبيانات الوصفية (<span dir="ltr">CC1.5</span>)</li>
<li align="right">استخدام مدير حزم لتثبيت وإدارة الاعتماديات البرمجية (<span dir="ltr">CC1.10</span>)</li>
<li align="right">القدرة على توسيع نطاق سير عمل حاسوبي (<span dir="ltr">CC2.6</span>)</li>
<li align="right">فهم إصدارات البرمجيات وإدارة النسخ (<span dir="ltr">CC4.4</span>)</li>
</ul>

<p align="right"><strong>بالإضافة إلى ذلك، سيتعلم المشاركون كيفية:</strong></p>

<ul>
<li align="right">استخدام <span dir="ltr">Pixi</span> لإدارة بيئة البرمجيات والاعتماديات.</li>
<li align="right">استخدام <span dir="ltr">Snakemake</span> لأتمتة المهام القابلة لإعادة الإنتاج.</li>
<li align="right">حساب مؤشر رضا متطلبات المياه.</li>
</ul>

<h2 align="right">شكر وتقدير</h2>

<p align="right">
تم تمكين هذا المنهج بفضل منحة من برنامج
<span dir="ltr">NASA Transition to Open Science (TOPS)</span>
رقم <span dir="ltr">80NSSC23K0864</span>،
وهو جزء من
<a href="https://nasa.github.io/Transform-to-Open-Science/"><span dir="ltr">NASA TOPS Program</span></a>.
</p>

</div>
