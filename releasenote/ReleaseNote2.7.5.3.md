# شرح تغییرات نسخه 2.7.5.3
###### 4 مهر 1402
##### قابلیت‌های جدید

- [**باشگاه مشتریان؛ اضافه شدن کارتابل مشتری (پیشخوان) در باشگاه مشتریان**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/home/CustomerClubPage_2.7.5.3.md#ClubCartable)<BR>
   جهت **تعامل با مشتری در طی یک فرآیند**، قابلیت کارتابل مشتری، به باشگاه مشتریان اضافه شده است. بنابراین فرآیندهای مرتبط با مشتری (مشتریانی که کاربری باشگاه مشتریان را داشته باشند) در این بخش قابل نمایش است و مشتری می‌تواند پس از انجام اقدامات لازم، فرآیند را به مرحله بعد ارجاع دهد.
- [**باشگاه مشتریان؛ امکان نمایش قالب چاپ متفاوت برای مشتری، در پنل باشگاه مشتریان**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/General-information/Shared-information-of-system-items/GeneralCustomization_2.7.5.3.md#CustomerPrintTemplate)<br>
   در باشگاه مشتریان قابلیت جدیدی به نام **پیش‌نمایش عمومی** اضافه شده که می‌توانید یک قالب چاپ ویژه در تنظیمات شخصی‌سازی آیتم‌ها جهت دریافت مشتری از باشگاه مشتریان، تنظیم کنید.
- [**فرآیند؛ اضافه شدن امکان ارجاع فرآیند به مشتری در باشگاه مشتریان در تنظیمات کارتابل**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/Process-design/Create-a-work-cycle/Cardboard/Cartable_2.7.5.3.md#CustomerCartableSettingInClub)<br>
   در تنظیمات کارتابل فرآیند امکان تخصیص کارتابلی از فرآیند به مشتری اضافه شده است. مشتریان از طریق **باشگاه مشتریان** > **پیشخوان** می‌توانند در فرآیندها با شما تعامل داشته باشند.
-	[**فرم عمومی؛ نمایش لوگوی پروفایل هویت هنگام ذخیره فرم عمومی در پرونده هویت مشخص**](https://github.com/1stco/PayamGostarDocs/blob/24c257f210e34f4e05f1f2df01b12ff3ba71fad9/Help/Settings/Personalization-crm/Form-management/GeneralForm_2.7.5.3.md)<BR>
   زمانی که تنظیمات فرم عمومی روی **ذخیره در سوابق هویت مشخص** باشد، تصویر لوگوی هویت در فرم عمومی قابل نمایش است.
- [**راهبری؛ تغییر مجوز نمایش سوابق، در صفحه سوابق آیتم‌ها**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Manage-groups-and-users/permissions/AllCRMObject'sPermission_2.7.5.3.md#Item'sHistoryPermission)<br>
   برای نمایش لیست آیتم‌های ثبت شده در صفحه سوابق هر CRM Object، مجوز جدیدی با عنوان **مشاهده در لیست سوابق موجودیت‌ها** اضافه شده است.
- [**فرآیند؛ بهبود ساختار Expression در فعالیت‌های «تخصیص‌ مقدار» و «اجرای دستورات پایگاه داده»**](https://github.com/1stco/PayamGostarDocs/blob/master/Help/Settings/Personalization-crm/Overview/Process-design/Create-a-work-cycle/Activity/SQL/Expression_2.7.5.3.md#ItemKey)<br>
   برای بهبود انتقال اطلاعات از طریق فعالیت‌های **تخصیص مقدار** و **اجرای دستورات پایگاه داده**، در حالت استفاده از **فیلد اضافه**، درج **کلید کاربر آیتم** در **Expression** اضافه شده است.

###### خطاهای برطرف شده

-	**انبارداری؛ رفع مشکل نمایش تمامی انبارها**<BR>
   زمانی که تعداد بسیار زیادی (بیش از 200 عدد) انبار در مدیریت انبارداری تعریف می‌شد، هنگام فیلتر روی نام انبار و نمایش انبارها، سیستم کلیه‌ی انبارهای تعریف شده قابل نمایش نبود که این مشکل در نسخه جدید برطرف گردیده است.
-	**انبارداری؛ رفع مشکل جستجوی اقلام کالا با سریال کالا**<BR>
   درصورتی که تعداد زیادی سریال محصول در انبارداری تعریف شده باشد هنگام جستجوی کالا با شماره سریال، نتیجه‌ای قابل نمایش نبود که این مورد در نسخه جدید برطرف شده است. 
-	**شخصی‌سازی آیتم‌ها؛ رفع مشکل ترتیب فایل‌ها در فیلد اضافه‌ی «لیست فایل**<br>
   ترتیب ذخیره فایل در فیلد اضافه از نوع **لیست فایل**، در این نسخه اصلاح شد.
-	**شخصی‌سازی آیتم‌ها؛ رفع مشکل فیلدهای محاسباتی**<br>
   عملکرد فیلدهای محاسباتی از طریق اکسل، در این نسخه بهبود یافت.
-	**مراحل آیتم‌ها؛ رفع خطای ذخیره آیتم هنگام تغییر مرحله**<br>
   درصورتی که روی آیتم‌ها مراحل تنظیم شده بود، هنگام تغییر مرحله و ذخیره آیتم، سیستم با خطا مواجه می‌شد و سوابق تغییر مراحل را به درستی نمایش نمی‌داد. این مورد در نسخه جدید برطرف شده است.
-	**گزارش‌ساز؛ رفع مشکل مقدار فیلد «تاریخ میلادی» در گزارش‌ساز**<br>
   خالی بودن مقدار فیلد تاریخ میلادی در گزارش‌ساز هنگام دریافت گزارش، در نسخه جدید برطرف شد.
-	**موبایل؛ رفع مشکل نمایش صفحات در حالت زبان انگلیسی در نسخه موبایل پیام‌گستر**<br>
   مشکل نمایش صفحات نرم‌افزار در نسخه موبایل پیام‌گستر هنگامی که زبان سیستم انگلیسی تنظیم شده بود، در این نسخه برطرف شده است.
-	**موبایل؛ رفع مشکل عملکرد نرم‌افزار در نسخه اندروید موبایل**<br>
   در نسخه اندروید موبایل پیام گستر، ثبت نظر، اسکرول بین ویجت‌ها و نوشتن متن در برخی فیلدها به درستی انجام نمیشد که در نسخه جدید این موارد اصلاح شد.