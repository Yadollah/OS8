### &emsp; &emsp; به نام خدا ###
### &emsp; یدالله حبیب کاظمی ###
### تمرین 8 آزمایشگاه سیستم های عامل ###
<br>

__سوال 1 : بررسی کنید دستورات زیر چه می کنند__

`chmod 397`:

این دستور اشتباه ، نامعتبر و غیرقابل اجرااست زیرا اعداد تا 7 قابل قبول است

`chmod 440`:

این دستور نیز اشتباه است زیرا ناقص است و به فایلی اشاره نشده است ، اما بعد از اشاره

به فایل این دستور به "کاربر" و "گروه" دسترسی خواندن را می دهد

`chmod a=rx file1`:

این دستور به کاربر ، گروه و دیگران دسترسی های خواندن و اجرا کردن را در فایل1 میدهد و دسترسی نوشتن را میگیرد

`chmod g=w sample`:

این دستور به گروه ، دسترسی نوشتن را در سمپل میدهد و دسترسی های خواندن و اجرا کردن را میگیرد

`chmod r+x sample`:

این دستور اشتباه ، نامعتبر و غیرقابل اجرااست

`chmod u+g test`:

این دستور به کاربر ، دسترسی های گروه را در فایل تست اضافه می کند
<br><br>

__سوال 2 : 3 مورد از آرگومنت های دستور چمود را مختصرا توضیح دهید__

`chmod -R` :

سطح دسترسی مورد نظر را بصورت بازگشتی علاوه بر فولدر مورد نظر به فایل ها و فولدر های داخل آن هم اعمال می کند

`chmod -v` :

تغییرات در سطح دسترسی ها را نمایش می دهد

`chmod -c` :

مانند دستور قبلی عمل میکند با این تفاوت که فقط در صورتی که تغییری ایجاد شود گزارش می دهد
