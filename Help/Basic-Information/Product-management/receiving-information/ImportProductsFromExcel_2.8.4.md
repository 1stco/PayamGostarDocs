#  بارگذاری محصولات از طریق اکسل
برای تعریف محصولات و خدمات به صورت یکجا، می‌توانید از روش ورود اکسلی استفاده نمایید. بدین ترتیب می‌توانید اطلاعات محصولات مورد نظر را در اکسل درج کرده (یا از سایر نرم‌افزارهای خود خروجی بگیرید) و سپس در پیام‌گستر بارگذاری کنید. در این حالت محصولات مورد نظر ایجاد شده و اطلاعات آن در فیلدهای مربوطه وارد می‌شود. علاوه بر ایجاد محصول یا خدمت، از این روش می‌توانید برای ویرایش محصولات یا خدمات موجود نیز استفاده نمایید.<br>
برای اینکه بارگذاری محصولات بدون مواجهه با خطا و با موفقیت به اتمام برسد، لازم است که قوانین تهیه و بارگذاری اکسل را رعایت کنید. در این راهنما تمامی موارد لازم برای تنظیم صحیح فایل اکسل، به همراه شیوه بارگذاری آن مطرح شده‌است. بدین منظور در این مقاله به موارد زیر می‌پردازیم:<br>

- [شیوه تهیه و تنظیم فایل اکسل محصولات](#ProductsExcelSetting)
- [روش بارگذاری فایل اکسل محصولات](#ProductsExcelUpload)
- [مجوزهای لازم برای بارگذاری اکسل محصولات](#ProductsExcelPermission)

## تنظیمات فایل اکسل{#ProductsExcelSetting}
برای بارگذاری و ورود اطلاعات محصولات/خدمات از طریق اکسل، ابتدا باید اکسل مورد نظر را بر اساس فرمت مورد پذیرش نرم‌افزار تنظیم کنید. بدین منظور می‌توانید از فایل محصولات ارائه شده در سایت [پیام‌گستر](https://www.payamgostar.com/fa/services/adoption-services/requirements) استفاده کنید و یا اکسلی مشابه تصویر نمونه ایجاد کنید. علاوه بر آن می‌توانید از پیام‌گستر یک خروجی اکسل بگیرید و از قالب آن برای ورود اطلاعات خود استفاده کنید.<br>
برای تکمیل فایل اکسل، به موارد زیر توجه فرمایید:<br>
- در صورت استفاده از اکسل نمونه‌ی موجود در سایت،‌ فرمت و کامنت‌های آن را حذف نمایید. بدین منظور جدول را نتخاب کرده و از Clear Comment و Clear Format استفاده نمایید.
- برای محصولات و خدمات هر دسته‌بندی، اکسل جداگانه‌ای تهیه کنید. به عنوان مثال اگر دو دسته‌بندی «قطعات» و «ابزار» در قسمت مدیریت محصولات ایجاد کرده‌اید، برای بارگذاری اقلامی که می‌خواهید در دسته‌بندی قطعات قرار بگیرند یک فایل اکسل و برای اقلام دسته‌بندی ابزارها یک فایل اکسل دیگر تهیه نمایید.
- در تهیه اکسل توجه داشته‌باشید که تمامی اطلاعات در یک Sheet قرار گیرد. در غیر این صورت بارگذاری اکسل با موفقیت انجام نخواهدشد.

![نمونه فایل اکسل نمونه محصولات](./Images/products-excel-sample-2.8.4.png)

تصویر فوق،‌ ستون‌های مورد نیاز برای بارگذاری محصولات و خدمات را بر اساس فیلدهای پیش‌فرض نرم‌افزار نشان می‌دهد. برای تکمیل اطلاعات مربوط به این فیلدها، به راهنمایی‌های زیر توجه داشته‌باشید:<br>
- **نام‌:** نام محصول یا خدمت مورد نظر را در این قسمت وارد کنید.
- **کد:** کد محصول را در این قسمت درج کنید. کد محصول می‌تواند شامل حروف انگلیسی/فارسی و عدد باشد.

> **نکته**<br>
> در صورت همگام‌سازی پیام‌گستر با سایر نرم‌افزارها، کد محصول باید در هر دو نرم‌افزار یکسان تعریف شده‌باشد.<br>

- **خدمت:** برای تعریف محصول، این ستون را با عبارت «خیر» و برای تعریف خدمت، ستون مربوطه را به عبارت «بلی» پر کنید.
- **قیمت واحد:** قیمت واحد همان قیمت فروش است که در پیش‌فاکتور و فاکتورها به صورت خودکار برای محصول ثبت می‌شود. قیمت واحد محصول/خدمت مورد نظر را به ریال در این ستون وارد نمایید.
- **قیمت خرید:** قیمت خرید محصول را در این قسمت وارد کنید. هنگام ثبت پیش‌فاکتور یا فاکتور خرید، قیمت خرید به صورت خودکار برای آن ثبت خواهدشد. از این قیمت برای محاسبه‌ی ارزش ریالی محصولات موجود در انبار نیز استفاده می‌شود. توجه داشته‌باشید که در ردیف‌های مربوط به خدمت، لازم به پر کردن این ستون نمی‌باشد.
- **واحد** : در ردیف‌های مربوط به محصول، واحد شمارش کالا را در این بخش مشخص کنید. توجه داشته‌باشید که واحد مورد نظر را صرفاً از عناوین تعریف شده در لیست واحدها می‌توانید انتخاب کنید. برای مشاهده‌ی واحدها، از صفحه مدیریت محصولات، صفحه اطلاعات یک محصول را باز کرده و از اسامی موجود در لیست واحدها، عنوان دقیق واحد مورد نظر را پیدا کنید. در صورت نیاز به ویرایش عنوان یک واحد یا افزودن واحد جدید، از بخش **مدیریت آیتم‌های سیستم**، «واحد شمارش محصول» را جستجو کرده و واحد مورد مورد نظر را به لیست اضافه کنید.
- **برند:** در صورت نیاز برند محصول را در این ستون وارد نمایید. درج اطلاعات در این ستون برای ردیف‌های خدمت، مفهومی ندارد.
- **اطلاعات فنی**: در این ستون می‌توانید توضیحات فنی مرتبط با محصول مانند ابعاد، میزان مصرف انرزی و .. را مشخص کنید. 
- **کشور سازنده**:  کشور سازنده و تولید‌کننده محصول را مشخص نمایید.
- **توضیحات**: در این بخش می‌توانید توضیحاتی در خصوص محصول مانند مزایای استفاده و نحوه استفاده یا توضیحاتی در مورد خدمت مورد نظر، ثبت کنید.
- **قابل فروش**: برای تکمیل این ستون، از عبارت «بلی» یا «خیر» استفاده نمایید، در این حالت مشخص می‌کنید که فروش این کالا برای کاربران مجاز است یا خیر. چنانچه این گزینه غیر فعال باشد، هنگام صدور فاکتور یا پیش‌فاکتور فروش این کالا به کاربر نمایش داده‌نمی‌شود.
- **قابل خرید:** برای تکمیل این ستون از جدول از عبارت «بلی» یا «خیر» استفاده نمایید. با تکمیل این بخش مشخص کنید که خرید این کالا برای کاربران مجاز است یا خیر. چنانچه این گزینه غیر فعال باشد، هنگام صدور فاکتور یا پیش‌فاکتور خرید این کالا به کاربر نمایش داده‌نمی‌شود.
- **محاسبه پورسانت:** برای تکمیل این ستون، از عبارت «بلی» یا «خیر»استفاده نمایید، در این حالت مشخص می‌کنید که برای این محصول باید پورسانت لحاظ شود یا خیر. در صورتی که محاسه پورسانت فروش فعال ‌باشد، باید میزان و نوع پورسانت را نیز مشخص کنید.
- **نوع پورسانت:** نوع پورسانت می‌تواند رقم یا درصد مشخصی باشد. اگر محاسبه پورسانت را با درج «بلی» فعال کرده‌اید، نوع‌ آن را با درج عبارت «رقم» یا «درصد»، مشخص کنید.
- **پورسانت فروش:** پورسانت فروش بر اساس نوع سیاست شرکت می‌تواند درصد یا عدد ثابتی درنظر گرفته‌شود. تنها در صورتی که گزینه «بلی» را برای محاسبه پورسانت انتخاب کرده‌باشید، باید میزان آن را مشخص کنید.
- **انبارداری:** برای محصولات، انبارداری را با درج «بلی» فعال و با درج «خیر» غیرفعال اعلام کنید. توجه داشته‌باشید که اگر از انبارداری تعدادی استفاده می‌کنید، از این طریق می‌توانید مشخص کنید که موجودی محصول مورد نظر در انبار کنترل شود یا خیر. با فعال بودن این گزینه، کاربر هنگام استفاده از محصول مذکور در پیش‌فاکتور و فاکتور، می‌تواند موجودی محصول در انبار را مشاهده کند. لازم به ذکر است که در صورت استفاده از انبارداری سریالی، اگر انبارداری یک محصول غیرفعال باشد، امکان افزودن آن محصول به قسمت مدیریت محصولات هیچ یک انبارها وجود ندارد. بدیهی است که برای خدمات، این ستون باید با عبارت «خیر» پر شود.
- **اعمال نقطه سفارش:** نقطه سفارش، میزان حداقل موجودی قابل قبول، برای سفارش مجدد محصول می‌باشد. برای اعمال نقطه سفارش (فعال کردن این قابلیت) از عبارت «بلی» و برای غیرفعال بودن آن از «خیر» استفاده کنید.
- **نقطه سفارش:** در صورت فعال بودن نقطه سفارش، میزان نقطه سفارش را در این قسمت مشخص ‌کنید. با تعیین نقطه سفارش مشخص می‌کنید هر زمان موجودی به میزان مشخص‌شده رسید، اقدامی که در بخش [تنظیمات نقطه سفارش تنظیمات کلی](https://help.payamgostar.com/docs/WarehousingManagement/%D8%AA%D9%86%D8%B8%DB%8C%D9%85%D8%A7%D8%AA-%D8%A7%D9%86%D8%A8%D8%A7%D8%B1%D8%AF%D8%A7%D8%B1%DB%8C_di1b3bb477-bba1-eb11-a032-ac1f6bc6cd90) تعیین کرده‌اید، انجام پذیرد. توجه داشته‌باشید که نقطه سفارش محصولات برای حالت انبارداری سریالی، از بخش مدیریت انبارها، برای هر انبار قابل تنظیم می‌باشد.
- **اعمال گارانتی:** برای ردیف‌های مرتبط با محصول، با انتخاب یکی از عبارت‌های «بلی» یا «خیر» مشخص کنید که محصول مورد نظر شامل گارانتی می‌شود یا خیر. با انتخاب گزینه «بلی» گارانتی برای محصول فعال خواهد شد و در مرحله بعد باید نوع و مدت گارانتی را تعیین کنید.
- **نوع گارانتی:** در این قسمت باید مشخص کنید که گارانتی چه زمانی اعمال شود. برای نوع گارانتی باید یکی از عبارات «هنگام ثبت»، «تایید صلاحیت کالا» و یا «هیچکدام» را انتخاب کنید.
- **مدت گارانتی(روز):** می‌توانید مدت زمان گارانتی را برحسب روز در نظر بگیربد
- **مدت گارانتی(ماه):** می‌توانید مدت زمان گارانتی را برحسب ماه در نظر بگیرید.
- **اعمال مالیات:** رای تکمیل این ستون از جدول از عبارت «بلی» یا «خیر» استفاده نمایید. در این حالت مشخص می‌کنید که هنگام ثبت فاکتور فروش باید برای این محصول مالیات لحاظ شود یا خیر. مقدار مالیات با توجه به تنظیمات آیتم (پیش‌فاکتور یا فاکتور مربوطه) اعمال می‌شود.
- **قابل ویرایش در فاکتور:** با درج «بلی» به کاربر این امکان را می‌دهید که بتواند نام محصول/خدمات را در فاکتور ویرایش کند. در صورتی که نمی‌خواهید عنوان مربوطه توسط کاربران قابل ویرایش باشد، عبارت «خیر» را در این ستون درج نمایید.
- **قابل استفاده در باشگاه مشتریان:** با درج «بلی» در این ستون، عنوان محصول/خدمت مربوطه، در فیلدهای انتخاب محصول (جدول انتخاب محصول پیش‌فرض در آیتم‌هایی مثل فاکتور و لیست محصولات اضافه شده به آیتم‌ها) به کاربران باشگاه مشتریان نمایش داده‌شده و قابل افزودن به جدول می‌باشد. در صورتی که نمی‌خواهید کاربران، عنوان محصول/خدمت مورد نظر را در باشگاه مشاهده کنند، ستون مربوطه را با عبارت «خیر» پر کنید.
- **تعداد**: برای ردیف‌های مرتبط با محصولات، تعداد موجودی فعلی را با درج عدد مشخص کنید. در انبارداری این تعدادی این عدد به صورت مستقیم به عنوان موجودی محصول در نظر گرفته شده و در انبارداری سریالی، به تعداد مندرج در این بخش، برای هر محصول رسیدی از نوع انتخابی (که در مرحله اول بارگذاری انتخاب می‌کنید) صادر می‌شود.

## مراحل بارگذاری فایل اکسل{#ProductsExcelUpload}
بارگذاری اکسل محصولات در پیام‌گستر، دو گام اصلی دارد:<br>
### انتخاب فایل اکسل
برای بارگذاری فایل اکسل از مسیر  **اطلاعات پایه** > **مدیریت محصولات** وارد صفحه مدیریت محصولات شوید و از بین دسته‌بندی‌های موجود، دسته‌بندی مورد نظر برای ثبت محصولات یا خدمات را انتخاب کنید. سپس بر روی کلید «دریافت اطلاعات» کلیک کنید تا صفحه بارگذاری به شما نمایش داده‌شود.<br>

![بارگذاری فایل اکسل نمونه محصولات](./Images/products-excel-setting-2.8.4.png)

 با ورود به صفحه بارگذاری، باید تنظیمات مورد نیاز برای بارگذاری اکسل را بر اساس راهنمایی‌‌های زیر تکمیل نمایید:<br>
 - **1. فایل اکسل:** فایلی که در قسمت قبلی تهیه کردید را در این قسمت بارگذاری کنید.
 - **2. انتخاب انبار و نوع رسید:** این بخش فقط برای حالت انبارداری پیشرفته (سریالی) نمایش داده‌می‌شود و در حالت انبارداری تعدادی نیازی به تکمیل این بخش نمی‌باشد. در صورتی که از انبارداری پیشرفته استفاده می‌کنید، باید نام انبار و نوع رسید انبار برای ورود محصولات به انبار  را انتخاب کنید. با انجام این کار پس از بارگذاری اکسل، سیستم به صورت خودکار در انبار مشخص شده یک رسید با تعداد مندرج در اکسل ثبت خواهد‌کرد. تعداد هر محصول بر اساس عدد مندرج در ستون تعداد، ثبت می‌شود.
 - **3. روش ورود اطلاعات تکراری:** این بخش شامل سه گزینه به شرح زیر می‌باشد:<br>
- **صرف نظر کردن در صورت تکراری بودن کد محصول:** در صورت فعال بودن این گزینه، چنانچه کد محصول/خدمتی که قصد ورود آن‌ها در نرم‌افزار را دارید تکراری باشند، نرم‌افزار آن محصول/خدمت را نادیده خواهدگرفت. به عنوان مثال، اگر کالایی با کد 10012 پیش‌تر در سیستم وجود داشته‌باشد و مجدد در فایل اکسل، محصولی جدید با کد 10012 تعریف شود، نرم‌افزار محصول را تکراری در نظر گرفته و از ورود آن جلوگیری می‌کند.<br>
- **به‌روزرسانی در صورت تکراری بودن کد محصول:** در صورت فعال بودن این گزینه، چنانچه یک کد محصول/خدمت در اکسل تکراری باشد (پیش‌تر محصولی با این کد در پیام‌گستر تعریف شده‌باشد)، نرم‌افزار محصول جدیدی برای ردیف مذکور ایجاد نکرده و اطلاعات محصول/خدمت قبلی را بر اساس اطلاعات مندرج در اکسل، ویرایش و به‌روزرسانی می‌کند. این گزینه برای به‌روزرسانی اطلاعات کالا/خدمات بسیار مناسب است. <br>
- **افزودن محصول در صورت خالی بودن فیلد کد محصول:** در صورت غیرفعال بودن این گزینه، تنها محصولات/خدماتی که در فایل اکسل برای آن‌‌ها کد محصول مشخص کرده‌باشید در نرم‌افزار بارگذاری می‌شود. اگر قصد تعریف محصول/خدمت بدون درج کد محصول را دارید، این گزینه را فعال کنید. توجه داشته‌باشید که حتی اگر تنها یک رکرود از اکسل فاقد کد است، این گزینه را برای بارگذاری بدون مشکل، فعال کرده‌باشید.<br>

>**نکته**<br>
>  اگر برای محصولات  کد تعریف نشود، امکان به‌روزرسانی اطلاعات آن از طریق فایل اکسل وجود نخواهدداشت؛ زیرا شناسایی محصولات و خدمات برای به‌روزرسانی فقط از روی کد محصول انجام می‌شود.<br>

## تعریف ارتباط ستون‌ها
در این گام باید ستون‌هایی که در اکسل خود تعریف کرده‌اید را با عناوینی که در نرم‌افزار پیام‌گستر برای تعریف محصول وجود دارد، نگاشت کنید. در واقع مشخص می‌کنید که اطلاعات هر فیلد، بر اساس کدام ستون اکسل درج شود.<br>

![نگاشت محصولات](./Images/products-excel-sync-2.8.4.png)

**1. نگاشت خودکار ستون های هم نام:** نرم‌افزار به صورت خودکار ستون‌هایی که با عناوین فیلدهای نرم‌افزار یکسان باشد را کنار هم قرار می‌دهد. برای اینکه نگاشت خودکار انجام شود، بر روی کلید «نگشات خودکار ستون‌های هم نام» کلیک کنید. <br>
**2. انتخاب نگاشت:** اگر قبلا نگاشتی را ذخیره کرده‌باشید، از این لیست می‌توانید آن را انتخاب کنید.<br>
**3. اضافه کردن:** پس از انجام نگاشت دستی، می‌توانید این نگاشت (ترتیبی که عناوین اکسل شما با عناوین نرم‌افزار در کنار یکدیگر قرار‌گرفته‌اند) را در سیستم ذخیره کنید تا در بارگذاری‌های بعدی از آن‌ استفاده کنید.<br>

>**نکته**<br>
> توجه داشته‌باشید که داشتن ستون‌های نام و تعداد (که عنوان‌ آن‌ها با رنگ قرمز متمایز شده) اجباری است. یعنی تمامی محصولات اکسل شما باید این دو مقدار را داشته‌باشند. اگر قصد به‌روزرسانی محصولات را داشته‌باشید (انتخاب گزینه‌ی دوم در مرحله‌ی قبلی)، ستون کد هم به‌ صورت اجباری نمایش داده‌می‌شود .<br>

**4. ستون های اکسل:** ستون‌های اکسل در سمت را و فیلدهای محصول در سمت چپ به شما نمایش داده‌می‌شود. عناوینی که نگاشت آن‌ها به صورت خودکار انجام نشده‌است را به صورت دستی نگاشت کنید. کافیست که هر عنوان را از ستون سمت راست انتخاب کرده، کشیده و در ستون سمت چپ، کنارر فیلد متناظر آن رها کنید. <br>
**5. ورود اطلاعات:** با انتخاب این کلید محصولات فایل اکسل وارد نرم‌افزار خواهدشد.<br>

## مجوز مورد نیاز برای بارگذاری محصولات از طریق اکسل{#ProductsExcelPermission}
برای ثبت محصولات از طریق اکسل کاربر باید مجوز «مدیریت  محصولات» را داشته‌باشد تا بتواند محصولات و خدمات را بارگذاری کند.