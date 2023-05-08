# MD Syntax Guide


**pipe Tables  sample:**


|تعداد | مستندات     | کیفیت       |
|---- | ---- | -----|
|11  |  داک    |12  |
|11   | ویدیو  |   34 |


|تعداد | مستندات     | کیفیت       |
|---- | ---- | -----|
|11  |  داک    |12  |

|سطح کاربری| سقف برداشت ریالی |سقف برداشت رمزارز| سقف واریز ریالی | سقف واریز رمزارز | مدارک احراز هویت|
|----|----|----|----|----|----|
|سطح صفر|0|0|نامحدود|نامحدود| بدون احراز هویت|
|سطح یک|100 میلیون ریال|500 دلار|نامحدود|نامحدود|موبایل به نام کاربری، کد ملی، شماره شبا/کارت، تاریخ تولد، تصویر کارت ملی (در صورت نداشتن کارت ملی صفحه اول شناسنامه) 
|سطح دو|3 میلیارد ریال|10000 دلار|نامحدود|نامحدود|آدرس و کدپستی، تلفن ثابت تأییدشده، عکس سلفی احراز هویت|
|سطح سه|10 میلیارد ریال|40000 دلار|نامحدود|نامحدود|سند قولنامه یا اجاره نامه  یا قبوض محل سکونت (ارائه فایل معتبر برای قبض)، عقد قرارداد حضوری|
|سطح ویژه|توافقی|توافقی|نامحدود|نامحدود|عقد قرارداد حضوری برای شرایط توافق|




|مدارک احراز هویت | سقف واریز رمزارز| سقف واریز ریالی|
|----|----|-----|
|بدون احراز هویت|نامحدود|نامحدود|

**Inline Code   sample:** 

```
SELECT @(this.SELECT(Children.Form.Subject).Order(Children.Form. CreateDate).TakeOrDefault(3,"0"))و(this.Form.Where(Children.number==90&&(Children.poljoin == 30||Children.numfirst==18)).Select(Children.Form.polformat))
```
OR


      SELECT @(this.SELECT(Children.Form.Subject).Order(Children.Form. CreateDate).TakeOrDefault(3,"0"))و(this.Form.Where(Children.number==90&&(Children.poljoin == 30||Children.numfirst==18)).Select(Children.Form.polformat))


**Link to MD File**

[تست لینک به داکیومنت](https://github.com/1stco/PayamGostarDocs/blob/master/Other/Mds/test.md)

**BooKmark link Sample:**

[شاخص های رضایت مشتری](https://github.com/1stco/PayamGostarDocs/blob/master/Other/CRMIndex.md#test)

[شاخص های رضایت مشتری](https://github.com/1stco/PayamGostarDocs/blob/master/Other/CRMIndex.md#Index)

**Link to Website**

[تست لینک به گوگل](https://www.google.com/)



**Image Relative Address Sample:**

![پاییز](./Images/image.jpg)


**highlight text sample**

`اپلیکیشن آندروید پیام‌گستر جهت دسترسی به کارتابل‌ها و امکانات سیستم بر روی گوشی ‌های هوشمند`

**Quote Sample with br:**

> **Note**<br>
> Description1<br>
> Description2<br>

**Quote  sample with one >**

> **Note**<br>
 Description

*************************
**Quote Sample with 1 Enter:**
> **Note**
> <br>
> Description

*********************
**Quote Sample with 2 Enter:**
> Description

> Description

********************
**Nested Quote**

> **Note**<br>
>> Description
***********************************
**Quote Sample with Bullets:**
> **Note:**<br>
> - Description
> - Description

********************************
**Quote Sample with Order List:**
> **Note:**<br>
> 1. Description
> 2. Description



**Heading Sample (Without Enter):**

# این شماره را به‌صورت دستی به عدد 1 تغییر دهید. 
## این شماره را به‌صورت دستی به عدد 2 تغییر دهید.
### این شماره را به‌صورت دستی به عدد 3 تغییر دهید. 
#### این شماره را به‌صورت دستی به عدد 4 تغییر دهید. 
##### این شماره را به‌صورت دستی به عدد 5 تغییر دهید. 
###### این شماره را به‌صورت دستی به عدد 6 تغییر دهید. 

**Heading Sample (With Enter):**

# این شماره را به‌صورت دستی به عدد 1 تغییر دهید. 

## این شماره را به‌صورت دستی به عدد 2 تغییر دهید.

### این شماره را به‌صورت دستی به عدد 3 تغییر دهید. 

#### این شماره را به‌صورت دستی به عدد 4 تغییر دهید. 

##### این شماره را به‌صورت دستی به عدد 5 تغییر دهید. 

###### این شماره را به‌صورت دستی به عدد 6 تغییر دهید. 


**Alternate Syntax Heading**

 تیتر 1
 ======
 تیتر 2



**Bold & Italic Sample**

این یک متن **بلد** است.<br>
I just love __bold text__.<br>
این یک متن *ایتالیک* است.<br>
این یک متن _ایتالیک_ است.<br>
ثبت ***مستندات جدید***

**Line space by br tag and Enter**

This is test<br>
This is test
**********************

This is test
This is test
********************
This is test

This is test
*******************
This is test<br>

This is test


**Bullet Smple**

- This is test
- This is test
*******************
- This is test
   - This is test
*******************

**Order List Sample**

1. This is test
2. This is test
3. This is test

*******************
**Video Tag in Markdown**

![Video without preview picture](./Video/NewMainOutput.mp4)

![Video , with preview picture](https://septadocs.1st.co.com:1313/playback?fileId=1a8ab13e-0232-4fe1-6d26-08d971bffc91)

[![Video with prview picture](./Images/image.jpg)](https://www.aparat.com/v/HJ9nD)

![Video by Link, without preview picture](https://www.aparat.com/v/HJ9nD)

![Video by link of payamgostar help](https://help.payamgostar.com/docs/EducationalVideos/%D8%AA%D9%86%D8%B8%DB%8C%D9%85%D8%A7%D8%AA-%D9%85%D9%86---%D8%AA%D9%85%D8%A7%D8%B3%E2%80%8C%D9%87%D8%A7_di9e2664c7-17e8-4475-b6de-08d971bffc8f)

[![Video by Link, with preview picture](./Images/md.png)](https://help.payamgostar.com/docs/EducationalVideos/%D8%AA%D9%86%D8%B8%DB%8C%D9%85%D8%A7%D8%AA-%D9%85%D9%86---%D8%AA%D9%85%D8%A7%D8%B3%E2%80%8C%D9%87%D8%A7_di9e2664c7-17e8-4475-b6de-08d971bffc8f)

#  شرح تغییرات نسخه 2.7.1
###### اردیبهشت 1402

- [**انبار؛ امکان در دسترس قرار گرفتن پارامترهای هوشمند هویت برای آیتم‌های تراکنش‌های انبار**]() - در آیتم‌های مربوط به تراکنش‌های انبار (حواله و رسید)، در صورت وارد کردن تحویل‌دهنده/تحویل گیرنده، اطلاعات آن در سوابق هویت مرتبط ثبت می‌شود. از آنجا که اطلاعات مربوط به هویت مانند آدرس و شماره تلفن می‌تواند در تنظیم قالب چاپ موردنیاز باشد، امکان اضافه‌شدن پارامترهای هوشمند هویت برای این آیتم‌ها فراهم شده است.
- [**فرایند؛ امکان تخصیص مقدار پیشرفته روی آیتم فرصت**]() - امکان تخصیص مقدار به فیلدها با استفاده از عبارت (Expression)، بر روی آیتم فرصت فراهم شده است.

### خطاهای رفع‌شده

- **شخصی‌سازی آیتم‌ها؛ اصلاح عملکرد جستجو در فیلدهای افزوده شده به آیتم در قسمت شخصی‌سازی آیتم**
   در بخش شخصی‌سازی آیتم‌ها، قسمت جستجوی فیلدهای اضافه‌شده عمل نمی‌کرد و فیلد موردنظر پس از فیلتر نمایش داده نمی‌شد. این مورد در نسخه جدید برطرف شده است.

- **شخصی‌سازی آیتم‌ها- اضافه‌نشدن فیلد افزوده‌شده به فیلدهای ردیف فاکتور برگشت از فروش**<br>
در شخصی‌سازی آیتم فاکتور برگشت از فروش، در صورت افزودن فیلد به فیلدهای ردیف فاکتور و فعال‌کردن گزینه «فیلد در ردیف فاکتور نمایش داده شود»، فیلد به ردیف‌های فاکتور برگشت از فروش اضافه نمی‌شد. در نسخه جدید این مشکل برطرف شده است.
