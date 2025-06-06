<div dir="rtl">

# ردیابی آنلاین  با Arduino  🗺️  
[🔗 مشاهده آنلاین پروژه](https://m9stafa.github.io/GPS-tracker/)

 پروژه‌‌ای برای **ردیابی آنلاین** موقعیت اتوبوس‌ها ( یا هر وسیله دیگه )! 🛰️  
 لوکیشن سوژه توسط ماژول GPS و برد آردوینو جمع‌آوری شده و از طریق WiFi به پایگاه داده ابری **Supabase** ارسال می‌شوند. سپس با استفاده از کتابخانه‌ی **Leaflet.js** موقعیت‌ها روی نقشه‌ی OpenStreetMap نمایش داده می‌شوند. 🌍✨


## 🛠️ تکنولوژی‌های استفاده‌شده

- **سخت‌افزار:** Arduino UNO R4 WiFi، ماژول GPS مدل NEO-6M  
- **نرم‌افزار آردوینو:** C/C++ همراه با کتابخانه‌های `TinyGPSPlus`، `WiFiS3` و `ArduinoJson`  
- **بک‌اند:** Supabase (پایگاه داده PostgreSQL، Realtime API) ☁️  
- **فرانت‌اند:** HTML، CSS، JavaScript و Leaflet.js 🌐  
- **هاست وب:** GitHub Pages 📄

## ⚙️ مراحل راه‌اندازی سریع

1. 🔌 **اتصالات سخت‌افزاری:**  
   ماژول GPS را به پایه‌های D3 و D4 آردوینو متصل کنید.

2. 🧱 **تنظیمات Supabase:**  
   - یک پروژه جدید ایجاد کنید.  
   - جدول `locations` را اضافه نمایید.  
   - URL و API Key را دریافت کنید.  
   - (اختیاری) قابلیت Realtime را برای جدول `locations` فعال کنید.

3. 👨‍💻 **پیکربندی آردوینو:**  
   - اطلاعات WiFi و Supabase (URL و `service_role` key) را در فایل `arduino_secrets.h` وارد نمایید.  
   - برنامه را روی برد آپلود کنید.

4. 🌍 **راه‌اندازی صفحه وب:**  
   - در فایل `index.html`، اطلاعات Supabase (URL و `anon` key) و (در صورت نیاز) مسیر GeoJSON را وارد کنید.  
   - صفحه را در GitHub Pages منتشر کنید.


📍 **[مشاهده آنلاین پروژه](https://m9stafa.github.io/GPS-tracker/)**

</div>
