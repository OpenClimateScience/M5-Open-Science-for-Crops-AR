<div dir="rtl" style="direction: rtl; unicode-bidi: isolate; text-align: right;">

<p>
<a href="https://doi.org/10.5281/zenodo.18393840" dir="ltr">
<img src="https://zenodo.org/badge/967615825.svg" alt="DOI Badge">
</a>
</p>

<h1 style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
M5: العلوم المفتوحة لظروف المحاصيل
</h1>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
كيف يمكن استخدام مجموعات بيانات 
<span dir="ltr" style="unicode-bidi: isolate;">NASA</span> 
لرسم خرائط ظروف المحاصيل؟
</p>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
تركّز الوحدة الخامسة من 
<a href="https://openclimatescience.github.io/curriculum" dir="ltr">openclimatescience.github.io</a>
على كيفية بدء مشروع علمي حاسوبي قابل لإعادة الإنتاج، باستخدام ظروف المحاصيل كمثال موضوعي.
</p>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
<strong>في نهاية هذه الوحدة، ينبغي أن تكون قادرًا على ما يلي:</strong>
</p>

<ul>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
الوصول إلى مجموعات البيانات المعتمدة على الأقمار الصناعية والمتعلقة بإنتاجية النبات وحالته وعمليات النتح-التبخر، واستخدامها بفعالية.
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
حساب مؤشر رضا متطلبات المياه للمحاصيل الزراعية.
</li>
</ul>

<h2 style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
المحتويات
</h2>

<ol>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/01_Creating_a_Project_Plan.ipynb" dir="ltr">Creating a Project Plan</a>
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/02_Creating_a_Reproducible_Research_Environment.ipynb" dir="ltr">Creating a Reproducible Research Environment</a>
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/03_Setting_Up_Data_Processing_Workflows.ipynb" dir="ltr">Setting Up Data Processing Workflows</a>
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
<a href="https://github.com/OpenClimateScience/M5-Open-Science-for-Crops/blob/main/notebooks/04_Writing_a_Transparent_Algorithm.ipynb" dir="ltr">Writing a Transparent Algorithm</a>
</li>
</ol>

<h2 style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
البدء
</h2>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
راجع دليل التثبيت هنا:
<a href="https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md" dir="ltr">HOW_TO_INSTALL.md</a>
</p>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
يمكنك تشغيل دفاتر 
<span dir="ltr" style="unicode-bidi: isolate;">Jupyter</span> 
باستخدام 
<a href="https://docs.github.com/en/codespaces/overview" dir="ltr">Github Codespaces</a>
أو 
<a href="https://code.visualstudio.com/docs/devcontainers/containers" dir="ltr">VSCode Dev Container</a>.
</p>

<pre dir="ltr" style="unicode-bidi: isolate;">
# Create your own password when prompted
jupyter server password

# Then, launch Jupyter Notebook; enter your password when prompted
jupyter notebook
</pre>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
يمكن تثبيت مكتبات 
<span dir="ltr" style="unicode-bidi: isolate;">Python</span>
باستخدام مدير الحزم 
<span dir="ltr" style="unicode-bidi: isolate;">pip</span>:
</p>

<pre dir="ltr" style="unicode-bidi: isolate;">
pip install xarray netcdf4 dask
</pre>

<h2 style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
نواتج التعلم
</h2>

<ul>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
توثيق العلاقة بين الشيفرة والنتائج والبيانات الوصفية (<span dir="ltr" style="unicode-bidi: isolate;">CC1.5</span>)
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
استخدام مدير حزم لتثبيت وإدارة الاعتماديات البرمجية (<span dir="ltr" style="unicode-bidi: isolate;">CC1.10</span>)
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
القدرة على توسيع نطاق سير عمل حاسوبي (<span dir="ltr" style="unicode-bidi: isolate;">CC2.6</span>)
</li>
<li style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
فهم إصدارات البرمجيات وإدارة النسخ (<span dir="ltr" style="unicode-bidi: isolate;">CC4.4</span>)
</li>
</ul>

<h2 style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
شكر وتقدير
</h2>

<p style="direction: rtl; unicode-bidi: plaintext; text-align: right;">
تم تمكين هذا المنهج بفضل منحة من برنامج 
<span dir="ltr" style="unicode-bidi: isolate;">NASA Transition to Open Science (TOPS)</span>
رقم 
<span dir="ltr" style="unicode-bidi: isolate;">80NSSC23K0864</span>،
وهو جزء من 
<a href="https://nasa.github.io/Transform-to-Open-Science/" dir="ltr">NASA TOPS Program</a>.
</p>

</div>
