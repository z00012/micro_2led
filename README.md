#LEDsame time:روشن شدن دو ال ای دی همزمان
```
digitalWrite(led2,HIGH);
delay(5000);
```
در دستور اول دو بخش داریم که قسمت اول ان  پایه را انتخاب می کنیم  و در قسمت دوم حالت ان را مشخص می کنیم که می تواند HIGH(روشن) یا LOW(خاموش) باشد.
در  دستور`delay()` عدد برحسب میلی ثانیه قرار می دهیم که مشخص میکند که led چقدر روشن یا خاموش باشد.
#led_aksham:یک ال ای دی روشن و دیگری خاموش
در این قسمت با استفاده از دستور `delay()` بین روشن شدن و خاموش شدن  دو led وقفه ایجاد میکنیم که همزمان انجام نشوند.
