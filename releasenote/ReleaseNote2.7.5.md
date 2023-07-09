#  شرح تغییرات نسخه 2.7.5
###### 12 تیر 1402
##### قابلیت‌های جدید
- [**بانک اطلاعاتی، تغییر نمایش صفحه سوابق به صورت تمام کانال (Omni Channel)**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Integrated-bank/Database/Records/Records_2.7.5.md)<br>
   نمایش سربرگ سوابق به صورت تمام کانال (Omni channel) تغییر پیدا کرده است. بر اساس این تغییرات علاوه بر آیتم‌های ثبت شده توسط کاربران، لاگ‌های تماس‌های ورودی و خروجی به صورت یکپارچه قابل مشاهده است. این ساختار همچنین قابلیت ارسال پیام در صفحه سوابق را فراهم می‌آورد. 
- [**سیستم ردیابی کاجو؛ اضافه شدن ماژول سیستم ردیابی کارجو (ATS)**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/PayamgostarATS/WhatIsPayamgostarATS.md)<br>
   سیستم ATS پیام‌گستر ابزاری است که به تیم استخدام و مدیران سازمان کمک می‌کند که روند بررسی رزومه متقاضیان کار با کیفیت و سرعت بالاتری انجام شود.
- [**فرآیند، قابلیت کوتاه‌سازی لینک در فعالیت‌ها**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/Process-design/Create-a-work-cycle/Activity/SendMessageActivities/SendSMSActivity_2.7.5.md#ShortingSMS)<br>
   امکان کوتاه‌سازی لینک به هنگام ارسال در فعالیت‌های [پیام کوتاه](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/Process-design/Create-a-work-cycle/Activity/SendMessageActivities/SendSMSActivity_2.7.5.md#ShortingSMS)، [فکس](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/Process-design/Create-a-work-cycle/Activity/SendMessageActivities/SendFaxActiviy_2.7.5.md#ShortingFax) و [چاپ](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/Process-design/Create-a-work-cycle/Activity/SendMessageActivities/PrintActivity_2.7.5.md#ShortingPrint) اضافه شده است. در نتیجه از این پس می‌توان به جای لینک مورد نظر (لینک می‌تواند مربوط به هر آیتمی باشد)، لینک کوتاه شده را (بدون نیاز به استفاده از سایت‌های کوتاه‌سازی لینک) طی فرآیند ارسال کند.
- [**سوابق موجودیت‌ها، امکان درج/عدم درج موجودیت ثبت شده در سوابق موجودیت پدر**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/General-information/Add-features/AddFeatures2.7.5.md#NotSavedToParentStory)<br>
   امکان انتخاب اتصال/عدم اتصال موجودیت ثبت شده از روی موجودیتی  دیگر به هنگام ثبت آیتم جدید از روی فیلدهای CRM   ایجاد شده است.
- [**فرم عمومی؛ امکان ثبت فرم عمومی در سابقه هویت مشخص**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Form-management/GeneralForm2.7.5.md#GeneralFormForSpecificIdentity)<br>
   با استفاده از این قابلیت می‌توان فرم عمومی ثبت شده را به جای ثبت در سوابق هویت ایجادکننده، در سوابق هویت مورد نظر ذخیره کرد.<br>


 ##### خطاهای برطرف شده
- **فرم عمومی؛ رفع خطای پیام موفقیت عملیات ذخیره فرم عمومی**<br>
   هنگام ذخیره فرم عمومی اگر پیام ثبت در تنظیمات شخصی‌سازی لحاظ شده بود، نمایش داده نمیشد که این مورد برطرف گردید.
- **فرم عمومی؛ رفع خطای جستجوی هویت مرتبط هنگام ذخیره فرم عمومی**<br>
   هنگام ذخیره فرم عمومی درصورتی که در تنظیمات آن لحاظ شده باشد که جستجوی هویت مرتبط را در تمام انواع زیرنوع‌های هویت انجام دهد، تنها در سرنخ حقوقی جستجو می‌کرد که در نسخه جدید برطرف شده است.
