# محصولات 

نحوه انتقال محصولات به‌صورت یک‌طرفه از پیوست به پیام‌گستر می‌باشد.

## نقطه اشتراک همگام‌سازی:

مقدار داشتن فیلد کد کالا در پیام‌گستر، کد فنی و کد محصول در پیوست به‌عنوان مبنا برای سینک بین دو نرم‌افزار الزامی می‌باشد.

## فیلدهای قابل انتقال:

نام کالا، قیمت پایه، کد کالا، واحد شمارش، قابل‌فروش، مالیات و توضیحات از پیوست به پیام‌گستر انتقال پیدا می‌کنند.

## نکات مرتبط با محصولات:

•    علاوه بر محصولات، خدمات نیز انتقال می‌یابد.

•    موجودی کالا در هر انبار و نام انبار از طریق وب‌سرویس خوانده می‌شود.

•    حذف و ویرایش محصول فقط از سمت پیوست به پیام‌گستر تأثیر دارد.

•    برای انتقال واحد اندازه‌گیری از پیوست به پیام‌گستر لازم است واحدهای اندازه‌گیری پیوست عیناً در پیام‌گستر تعریف شوند. در صورت یکسان نبودن واحدهای پیوست و پیام‌گستر فیلد واحد انتقال پیدا نمی‌کند.

•    موجودی کالا در هر انبار از طریق وب‌سرویس خوانده می‌شود؛ درصورتی‌که برای سرویس همگام ساز چند پایگاه‌داده وجود داشته باشد، طبق تنظیمات وب‌سرویس، محصول از انبار کد شرکتی که در آدرس

	http://localhost:9092/api/inventory/{کد شرکت}

  تعریف شده است می‌خواند و درصورتی‌که کد شرکت خالی باشد و تعریف نشده باشد، محصول را در تمام انبارهای تعریف شده در پایگاه‌داده جست‌وجو می‌کند و مجموع محصول را در تمامی انبارها نشان می‌دهد. 
