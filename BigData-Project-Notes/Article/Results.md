# بخش ۴
نتایج این بخش مربوط به لیست مجاورت نیست.
نتایج مربوط مدل به لیست مجاورت در پیوست F.5 و پیوست F.6‌ موجود است.

## خطا بر حسب حافظه
![[Pasted image 20220722120403.png]]
![[Pasted image 20220722120419.png]]
![[Pasted image 20220722120510.png]]

## خطای مربوط به تمام گراف‌ها
![[Pasted image 20220722120909.png]]



# پیوست F.5
* 10% از کل حافظه برای نگهداری یال‌های سنگین مصرف شده است.
* $Z$ بیشینه تعداد یالی است که اجازه داریم آن را ذخیره کنیم.
* $k=Z/10$ یال نگهداری می‌شود. این‌ یال‌ها دارای بیشترین مقدار $R_{uv}$ (یال‌های سنگین) است. برای یال‌های باقی‌مانده از روش برپایه نمونه‌برداری استفاده می‌شود. 
* غیرممکن است که k سنگین‌ترین یال را قبل از شروع جریان بشناسیم. در پیاده‌سازی k سنگین‌ترین یال نگهداشته می‌شود و یال‌های سبک زمانی که یک یال سنگین با پیش‌بینی اوراکل می‌رسد حذف می‌شود.
* از الگوریتم نمونه‌برداری چندلایه‌ای (multi-layer sub-sampling) که در پیوست B.2 توضیح داده شده است درنظر گرفته شده است که از اطلاعاتی بیشتری از اوراکل استفاده می‌شود.
* به این نتیجه رسیده‌اند که تعداد زیادی از یال‌ها تعداد کمی مثلث دارند. برای گراف Oregon و CAIDA تنها ۳٪ تا ۵٪ یال‌ها $R_e$ بیشترمساوی ۵ داشته‌اند. بنابراین با فضای کمتری هم می‌توان پیش‌بینی خوبی داشت.
* برای پیاده‌سازی نسخه نمونه‌برداری چندلایه از ۱۰٪ فضا برای نگهداری $k=Z/10$ یال استفاده کرده‌اند ۷۰٪ فضا برای نمونه‌برداری از یال‌هایی که اوراکل برای آن‌ها مقادیر خیلی کمی پیش‌بینی کرده است استفاده کرده‌اند. این حد آستانه برای Oregon و CAIDA برابر با ۵ درنظر گرفته شده است. ۲۰٪ فضا برای نمونه‌برداری یال‌های باقی‌مانده استافده کرده‌اند که در اصل همان یال‌های متوسط (meduim) هستند.

# پیوست F.6

نتایج برای سه مجموعه‌داده انتخاب‌شده در ادامه آورده شده است. همانطور که مشخص است برای هر کدام یک گراف از مجموعه گراف ارزیابی شده است؛ گراف ۳۰-ام برای CAIDA-2006، گراف 25-ام برای CAIDA-2007 و گراف 4-ام برای Oregon
![[Pasted image 20220718200122.png]]
![[Pasted image 20220718200155.png]]
![[Pasted image 20220718200303.png]]
