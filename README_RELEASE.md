# کاتالوگ لوکس اتصالات فاضلابی — پارس زنده‌رود پلاست
نسخه ۳.۱

## اجرا از سورس
```
pip install -r requirements.txt
python pvc_fittings_catalog.py
```

## ساخت فایل اجرایی ویندوز (exe)
```
pip install flet openpyxl
flet pack pvc_fittings_catalog.py --name "ParsZendehroodCatalog" --icon icon.ico
```
یا با PyInstaller:
```
pyinstaller --noconfirm --onefile --windowed --name "ParsZendehroodCatalog" --icon icon.ico pvc_fittings_catalog.py
```

## امکانات
- جستجو و فیلتر هوشمند (سایز، قیمت، علاقه‌مندی)
- به‌روزرسانی قیمت از اکسل / csv
- چاپ و ذخیره PDF
- تم تیره/روشن، رنگ، فونت، زبان فارسی/انگلیسی
- دستیار هوشمند داخلی (بدون اینترنت)
- عکس واقعی محصولات در پوشه images

## پوشه داده
- ویندوز: %APPDATA%\ParsZendehrood\catalog
- یا کنار فایل برنامه (اگر قابل نوشتن باشد)

## عکس محصولات
فایل‌های jpg/png را با نام شناسه (مثل 12.jpg) یا نوع (elbow90.png, tee90.png, siphon.png, coupling.png, cap.png) در پوشه images بگذارید و از منو «بازخوانی تصاویر» را بزنید.

## پشتیبانی
پارس زنده‌رود پلاست
