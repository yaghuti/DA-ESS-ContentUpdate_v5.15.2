# DA-ESS-ContentUpdate_v5.15.2 - مستندِ روابطِ ریپازیتوری‌ها

این README به‌منظور ثبتِ مستندِ واضح و بدون هیچ حدسی دربارهٔ ارتباطِ چهار ریپازیتوری زیر نوشته شده است. همهٔ اطلاعاتِ این سند یا از متادیتا/README ریپازیتوری‌ها استخراج شده‌اند یا مستقیماً توسط صاحبِ حساب (yaghuti) اعلام شده‌اند. این سند فقط شامل حقایقِ مستند است.

ریپازیتوری‌های مرتبط

1) yaghuti/security_content
- آدرس: https://github.com/yaghuti/security_content
- شرح: فورکِ مخزن رسمی splunk/security_content (parent: https://github.com/splunk/security_content).
- مدرک: متادیتای ریپازیتوری حاوی parent و README این ریپازیتوری دستورالعمل‌هایی برای نصب و استفاده از ابزار contentctl (مثلاً "pip install contentctl" و نمونهٔ "contentctl build --enrichments") و همچنین اشاره به بستهٔ منتشرشده DA-ESS-ContentUpdate.spl را شامل می‌شود. (مستند در READMEِ ریپازیتوری استخراج شده است.)

2) yaghuti/contentctl
- آدرس: https://github.com/yaghuti/contentctl
- شرح: فورکِ ابزار رسمی contentctl (parent: https://github.com/splunk/contentctl). این ابزار برای ساخت/اعتبارسنجی/بسته‌بندیِ محتوای security_content استفاده می‌شود.
- مدرک: متادیتای ریپازیتوری نشان از fork شدن از splunk/contentctl دارد و READMEِ security_content این ابزار را به‌عنوان پیش‌نیاز و ابزارِ ساخت معرفی می‌کند.

3) yaghuti/security_content_wiki
- آدرس: https://github.com/yaghuti/security_content_wiki
- شرح: فورکِ ویکیِ security_content که برای متمرکز کردنِ مستندات و راهنماها ایجاد شده است.
- مدرک: این مورد توسط صاحبِ حساب (yaghuti) اعلام شده و هدفِ آن دسترسیِ آسان به مستندات اعلام شده است.

4) yaghuti/DA-ESS-ContentUpdate_v5.15.2 (این ریپازیتوری)
- آدرس: https://github.com/yaghuti/DA-ESS-ContentUpdate_v5.15.2
- شرح: این ریپازیتوری توسط صاحبِ حساب (yaghuti) ایجاد شده است و محتوای آن از فایلِ release رسمی استخراج و آپلود شده است.
- مدرک: توضیحِ مالکِ ریپو: محتوای این ریپازیتوری از فایل DA-ESS-ContentUpdate-latest.tar.gz که از آدرس رسمی
  https://github.com/splunk/security_content/releases/download/v5.15.2/DA-ESS-ContentUpdate-latest.tar.gz
  دانلود، استخراج و سپس در این ریپازیتوری آپلود شده است. همچنین متادیتای این ریپازیتوری دارای description = "security_content/releases" است.

خلاصهٔ مستندِ رابطهٔ بینِ چهار ریپازیتوری (فقط بر اساس مدارک)
- منبعِ محتوا: yaghuti/security_content (فورکِ splunk/security_content) — شامل detections، playbooks، stories و سایر محتوای امنیتی.
- ابزارِ تولید: yaghuti/contentctl (فورکِ splunk/contentctl) — ابزارِ معرفی‌شده در READMEِ security_content برای build/validate/package محتوا.
- آرتیفکت/خروجیِ منتشرشده: yaghuti/DA-ESS-ContentUpdate_v5.15.2 — محتوایی که از بستهٔ رسمی DA-ESS-ContentUpdate (release v5.15.2) استخراج و در این ریپو قرار داده شده است.
- مستندات/ویکی: yaghuti/security_content_wiki — نسخهٔ فورک‌شدهٔ ویکی برای دسترسی متمرکز به راهنماها و مستندات.

عباراتِ کلیدی و منابعِ مستقیمِ موردِ استناد
- READMEِ yaghuti/security_content (ارجاع به نصب contentctl و به‌کارگیری contentctl برای ساخت بسته‌ها).
- متادیتای ریپازیتوری‌ها که نشان‌دهندهٔ fork بودن و parent repoها است (splunk/security_content و splunk/contentctl).
- آدرسِ رسمیِ release که فایل tar.gz از آن دانلود شده است:
  https://github.com/splunk/security_content/releases/download/v5.15.2/DA-ESS-ContentUpdate-latest.tar.gz
- اظهارنظرِ مستقیمِ صاحبِ ریپو (yaghuti) مبنی بر اینکه DA-ESS-ContentUpdate_v5.15.2 با دانلودِ آن tar.gz و استخراجِ محتوی آن ساخته و آپلود شده است.

بیانیهٔ نهایی
این README به‌طور دقیق و صرفاً بر مبنای مدارکِ موجود و اظهاراتِ صاحبِ حساب تهیه شده و هیچ حدس و گمانی در آن وجود ندارد. هدف این فایل آن است که هر شخص یا عامل (از جمله چت‌بات‌ها) در گفتگوهای بعدی نیازی به عبور دوباره از همان مسیر طولانی برای فهمِ روابط بین این ریپازیتوری‌ها نداشته باشد.



# Splunk ES Content Update

This subscription service delivers pre-packaged Security Content for use with Splunk Enterprise Security. Subscribers get regular updates to help security practitioners more quickly address ongoing and time-sensitive customer problems and threats.

Requires Splunk Enterprise Security version 4.5 or greater.

For more information please visit the [Splunk ES Content Update user documentation](https://help.splunk.com/en/splunk-enterprise-security-8/security-content-update).
