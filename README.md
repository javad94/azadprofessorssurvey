<h1 dir="rtl">پر کردن راحت سوالات نظرسنجی دانشگاه ازاد برای مشاهده نمره</h1>

<h2 dir="rtl">شیوه استفاده:</h2>
<p dir="rtl">- کد زیر رو به طور کامل انتخاب و اون رو با موس به سمت نوار بوکمارک مرورگرتون بکشید و رها کنید</p>

```javascript
javascript:(function(){var valid=[null,"12","14","16","18","20"];grade="";function askgrade(){grade=prompt("نمره استاد را وارد کنید:");};askgrade();while(valid.indexOf(grade)==-1){askgrade()};document.querySelectorAll("select").forEach(function(e){e.value=grade;});})();
```

<h3 dir="rtl">ویدیوی اضافه کردن بوکمارکلت به مرورگر</h3>

![addbook](https://user-images.githubusercontent.com/7765309/34643067-f9e73796-f332-11e7-8c5c-adc6fd03ece3.gif)

<p dir="rtl">- به صفحه نظرسنجی دانشگاه ازاد برید</p>

<p dir="rtl">- رو بوکمارکی که در نوار بوکمارک شما ایجاد شده کلیک کنید و براساس جدول زیر عدد مدنظرتون رو وارد کنید</p>

نمره | توضیح
:---: | :---:
12 | ضعيف
14 | متوسط
16 | خوب
18 | خيلي خوب
20 | عالي

