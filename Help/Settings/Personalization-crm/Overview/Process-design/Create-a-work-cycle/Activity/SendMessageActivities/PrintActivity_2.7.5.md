# فعالیت چاپ (Print)
موضوعاتی که در این مقاله مطالعه خواهید کرد:
- [فعالیت چاپ و کاربرد آن](#PrintActivityPurpose)
- [تنظیمات فعالیت چاپ در فرآیند](#PrintActivitySettings)

## فعالیت چاپ چیست و چه کاربردی دارد؟{#PrintActivityPurpose}
به کمک این فعالیت می‌توانید به صورت **خودکار** در طی یک فرآیند، یک متنی را به پرینتر تنظیم شده در سیستم ارسال کرده و چاپ نمایید.<br>
در فعالیت چاپ می‌توانید به روش‌های مختلفی محتوای چاپ خود را انتخاب و ارسال نمایید:
- یک متن مشخص
- پیش‌نمایش آیتمی که فرآیند روی آن درحال اجرا است
- پیش‌نمایش "آیتم ثبت شده در فیلد اضافه CRM" روی آیتم تحت چرخه

## تنظیمات فعالیت چاپ در فرآیند{#PrintActivitySettings}
تنظیمات فعالیت چاپ، در چندین بخش شامل **تنظیمات نام و توضیحات فعالیت**، **تنظیمات گیرنده/گیرندگان چاپ**،  **تنظیمات متن پیام** و **تنظیمات خط** است.<br>

> **نکته**<br>
> دقت داشته باشید که هر تنظیماتی برای فعالیت چاپ انجام دهید، چرخه‌ی کاری هر بار که به این مرحله برسد، طبق همان تنظیمات عمل می‌کند.

### تنظیمات نام و توضیحات فعالیت چاپ
**نام:** در کادر نام باید نامی برای فعالیت انتخاب کنید که گویای عملی باشد که در طی فرآیند انجام می‌دهد. دقت داشته باشید انتخاب نام مناسب برای فعالیت، عملیات ویرایش و نگهداری فرآیند را برای شما و راهبر سیستم در آینده آسان‌تر می‌کند.<br>
**نوع:** در این قسمت نقطه شروع فرآیند را مشخص می‌کنید:
- **اولیه:** از هر مرحله، فعالیت یا کارتابلی که فرآیند شما شروع می‌شود، باید این فیلد روی **اولیه** تنظیم شود. 
- **معمولی:** غیر از مرحله‌ای که فرآیند با آن شروع شده و نوع آن را روی اولیه تنظیم کرده‌اید، سایر اجزا فرآیند روی حالت معمولی قرار می‌گیرند.

> **نکته**<br>
> دقت داشته باشید که یک فرآیند **تنها یک حالت اولیه** و **یک حالت نهایی** باید داشته باشد. در غیر این صورت فرآیند شما موقع اجرا به خطا برمی‌خورد.

**کد:** به کمک کدی که در این قسمت تعیین می‌کنید، می‌توانید از طریق وب سرویس عملکرد فعالیت چاپ را با نرم‌افزار دیگری ارتباط دهید.

**توضیحات:** به تعداد زبان‌هایی که در تنظیمات زبان سیستم تعریف کرده باشید می‌توانید برای فعالیت چاپ، توضیحاتی ثبت نمایید که راهنمایی برای راهبری چرخه‌کاری باشد.

![تنظیمات نام و توضیحات فعالیت چاپ](./Images/Send-fax-activity-set-name_2.7.5.jpg)

### تنظیمات گیرنده/گیرندگان در فعالیت چاپ
برای تعیین کردن گیرنده چاپ در طی فرآیند به روش‌های مختلفی می‌توانید عمل کنید. 
- **شرکت/فرد مرتبط**<br>
   با انتخاب این گزینه چاپ برای شماره **هویت مرتبط با آیتم تحت چرخه** ارسال می‌شود. بنابراین هر بار که چرخه‌کاری به این مرحله برسد، اگر تنظیمات روی این گزینه باشد، گیرنده چاپ هویت مرتبط با آیتم تحت چرخه است.<br>
    دقت داشته باشید که **شماره چاپ پیش‌فرض** تعیین شده در اطلاعات هویت، برای چاپ در نظر گرفته می‌شود.

![شرکت/فرد مرتبط در تنظیمات فعالیت چاپ](./Images/Related-contact_2.7.5.jpg)

- **گیرنده دلخواه**<br>
   با این گزینه می‌توانید یک شماره چاپ را در کادر نمایش داده شده ثبت کنید که هر بار فرآیند به این مرحله رسید، چاپ را به آن شماره ارسال کند. <br>
   لازم به ذکر است که این شماره همیشه **ثابت** است و تنها **راهبر** یا **کاربر دارای مجوز شخصی‌سازی موجودیت‌ها**، می‌تواند شماره را در تنظیمات فعالیت چاپ تغییر دهد.

![گیرنده دلخواه در تنظیمات فعالیت چاپ](./Images/Preffered-contact-send-message-activities_2.7.5.jpg)

- **کاربر/سمت/گروه/دپارتمان**<br>
   با انتخاب این گزینه، می‌توانید گیرنده/گیرندگان فعالیت چاپ را از بین کاربران سیستم خود (پرسنل سازمانتان) در حالت‌های کاربر، سمت، گروه کاربری و دپارتمان انتخاب کنید.<br>
   ***به عنوان مثال***<br>
   فرض کنید سازمانی دارای چندین شعبه باشد و فرآیند ارزیابی سالانه‌ برای عملکرد شعب اجرا شده باشد.<br> می‌توان با ایجاد یک گروه کاربری از مدیران شعب مختلف، تنظیمات گیرنده چاپ را روی این گزینه قرار داد و گروه کاربری مدیران شعب انتخاب شود. در این حالت بخشنامه ارزیابی سالیانه در این مرحله از فرآیند به گروه مدیران به صورت خودکار چاپ می‌شود. 

![گیرنده کاربر، دپارتمان، سمت و گروه در تنظیمات فعالیت چاپ](./Images/User-Department-Group-Send-message-activities_2.7.5.jpg)

- **فیلد**<br>
   با انتخاب این گزینه گیرنده چاپ، از فیلد اضافه تعیین شده روی آیتم می‌خواند. فیلد اضافه تنها می‌تواند از نوع **کاربر** و **شرکت/شخص** باشد. در این حالت در طی فرآیند هویتی که در این فیلد تعیین شده باشد، گیرنده چاپ خواهد بود. 

![فیلد گیرنده در تنظیمات فعالیت چاپ](./Images/field-of-contact-in-send-message-activities_2.7.5.jpg)

### تنظیمات متن پیام در فعالیت چاپ
به روش‌های مختلفی می‌توانید متن ارسالی خود به پرینتر را تنظیم نمایید.
- **ارسال متن مشخص (Spesific Content)**<br>
   در صورتی که بخواهید یک متن ثابت در طی فرآیند توسط این فعالیت چاپ شود، باید این گزینه را انتخاب نمایید. <br>
   در این قسمت تنظیمات متن پیام انجام می‌شود که به روش‌های بارگذاری فایل ورد، انتخاب قالب پیام آماده و نگارش در Web client tool می‌توانید اقدام نمایید.

![تصویر Specific content در فعالیت چاپ](./Images/send-specific-content-in-fax-activity_2.7.5.jpg)

- **ارسال این آیتم (Send this object)**<br>
   با انتخاب این گزینه، پیش‌نمایش (قالب چاپ تنظیم شده) همین آیتم، یعنی آیتمی که روی آن چرخه‌کاری پیاده‌سازی شده است، برای چاپ انتخاب می‌شود. (در فعالیت‌های ارسال پیام‌کوتاه و ارسال پیام شبکه اجتماعی این گزینه وجود ندارد)
- **ارسال این فیلد (Send This Field)**<br>
   با انتخاب این گزینه می‌توانید **قالب چاپ** یکی از **فیلدهای اضافه‌ی CRM** پیوست شده به این آیتم (فیلدهایی مانند فرم، فاکتور، حواله انبار و ...) را برای چاپ در نظر بگیرید. (در فعالیت های ارسال پیام کوتاه و ارسال پیام شبکه اجتماعی قابل انتخاب نیست)
   
![send this field در فعالیت چاپ](./Images/Send-this-field-in-fax-activity_2.7.5.jpg)

#### قابلیت کوتاه‌سازی لینک در متن پیام {#ShortlinkPrint}
به کمک چک باکس **کوتاه‌سازی لینک‌های متن** می‌توانید لینک‌هایی که در متن پیام خود ارسال می‌کنید را کوتاه کرده و لینک کوتاه شده را در متن خود چاپ نمایید.<br>
این قابلیت برای "فعالیت‌های ارسال پیام کوتاه"، ا"رسال چاپ" و "چاپ" قابل استفاده است.

![کوتاه‌سازی لینک در متن پیام](./Images/short-link-in-fax-activity_2.7.5.jpg)
### تنظیمات خط در فعالیت چاپ
در این قسمت پرینتری که با آن باید چاپ در طی فرآیند انجام شود را تعیین کنید. نحوه تنظیم آن به دو روش انتخابی و پیش‌فرض است که در ادامه شرح داده می‌شود:
- **انتخاب خط:**  در صورت انتخاب این گزینه، می‌توانید از لیست خطوط چاپ تعریف شده در نرم‌افزار خط ارسال کننده پیام خود را انتخاب نمایید.
- **خط پیش‌فرض:** در صورت انتخاب خط پیشفرض، خط انتخاب شده به عنوان پیش‌فرض در قسمت[ تنظیمات کلی > خطوط پیش‌فرض > چاپ ](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/General-settings/Default-lines/Default-lines.md)ارسال کننده پیام خواهد بود،.
   
### تعیین مرحله بعدی فرآیند
پس از تکمیل تنظیمات فعالیت، باید **حالت بعدی** فرآیند را در این مرحله تعیین نمایید. دقت داشته باشید این قسمت در تمامی فعالیت‌های چرخه‌کاری وجود دارد و به کمک آن اتصال بین فعالیت‌ها و کارتابل برقرار می‌شود.