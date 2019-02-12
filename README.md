<div dir="rtl">

# پروژه دوره API نویسی حرفه ای در ASP.NET Core

در این دوره نکات و تکنیک های پیشرفته برای API نویسی اصولی و حرفه ای در ASP.NET Core بررسی شده اند.


## تکنولوژی، ابزار ها و قابلیت ها
در این دوره سعی شده بهترین و محبوب ترین تکنولوژی ها، کتابخانه ها و ابزار ها داخل پروژه استفاده بشه. همچنین Best Practice ها و تکنیک های حرفه ای و پرکاربرد را بررسی و استفاده می کنیم.

  - **لایه بندی اصولی پروژه (Project Layering and Architecture)** : در این دوره لایه بندی اصولی یک پروژه را از ابتدا شروع و هر بخش را بررسی می کنیم.
  - **احراز هویت (Authentication)**
    - **ASP.NET Core Identity** : احراز هویت توسط Identity + سفارشی سازی
    - **(Json Web Token) JWT** : احراز هویت توسط Jwt + یکپارچه سازی آن با Identity
    - **(Json Web Encryption) JWE** : ایمن سازی توکن ها بوسیله رمزنگاری توکن (JWE)
    - **Security Stamp** : جلوگیری از اعتبارسنجی توکن به هنگام تغییر دسترسی های کاربر جهت امنیت بیشتر
    - **Claims** : کار با Claim ها و تولید خودکار آنها توسط ClaimsFactory
  - **Logging (ثبت خطا ها)**
    - **Elmah** : استفاده از [Elmah]() برای لاگ خطا ها در Memory, XML File و Database
    - **NLog** : استفاده از [NLog]() برای لاگ خطا ها در File و Console
    - **Custom Middleware** : نوشتن یک میدلویر سفارشی جهت لاگ تمامی خطا (Exception) ها
    - **Custom Exception** : نوشتن Exception برای مدیریت ساده تر خطا ها
    - **Sentry** : ثبت خطا ها در سیستم مدیریت لاگ [sentry.io]() (مناسب برای پروژه های بزرگ)
  - **تزریق وابستگی (Dependency Injection**)
    - **ASP.NET Core IOC Container** : استفاده از Ioc container داخلی Asp Core
    - **Autofac** : استفاده از محبوب ترین کتابخانه [Autofac (Ioc Container)]()
    - **Auto Registeration** : ثبت خودکار سرویس ها توسط یک تکنیک خلاقانه با کمک Autofac
  - **ارتباط با دیتابیس (Data Access)**
    - **Entity Framework Core** : استفاده از EF Core
    - **Auto Entity Registration** : ثبت Entity های DbContext به صورت خودکار توسط Reflection
    - **Pluralizing Table Name** : جمع بندی نام جداول EF Core به صورت خودکار توسط کتابخانه [Pluralize.NET]() و Reflection
    - **Automatic Configuration** : اعمال کانفیگ های EntityTypeConfiguration (FluentApi) به صورت خودکار توسط Reflection
    - **Sequential Guid** : بهینه سازی مقدار دهی identity برای Guid به صورت خودکار توسط Reflection
    - **Repository** : توضیحاتی در مورد معماری اصولی Repository در EF Core
    - **Data Intitializer** : یک معماری اصولی برای Seed کردن مقادیر اولیه به Database
    - **Auto Migrate** : آپدیت Database به آخرین Migration به صورت خودکار
    - **Clean String** : اصلاح و یک دست سازی حروف "ی" و "ک" عربی به فارسی و encoding اعداد فارسی در DbContext به صورت خودکار به هنگام SaveChanges
  - **Versioning** : نسخه بندی و مدیریت نسخه های پروژه + سفارشی سازی و ایجاد یک معماری حرفه ای
  - **ابزار (Swashbuckle) Swagger**
    - **Swagger UI** : ساخت یک ظاهر شکیل برای APIها توسط [Swagger]() UI
    - **Versioning** : یکپارچه سازی اصولی Swagger با سیستم نسخه گذاری (Versioning)
    - **JWT Authentication** : یکپارچه سازی Swagger با سیستم احراز هویت بر اساس Jwt
    - **OAuth Authentication** : یکپارچه سازی Swagger با سیستم احراز هویت بر اساس OAuth
    - **Auto Summary Document Generation** : تولید خودکار داکیومنت (توضیحات) برای API های پروژه
    - **Advanced Customization** : سفارشی سازی های پیشرفته در Swagger
  - **دیگر قابلیت ها**
    - **API Standard Resulting** : استاندارد سازی و یک دست سازی خروجی API ها توسط ActionFilter
    - **Automatic Model Validation** : اعتبار سنجی خودکار
    - **AutoMapper** : جهت Mapping اشیاء توسط کتابخانه محبوب [AutoMapper]() 
    - **Auto Mapping** :  سفارشی سازی وایجاد [یک معماری حرفه ای]() برای Mapping اشیا توسط Reflection 
    - **Generic Controller** : ساخت کنترلر برای عملیات CRUD بدون کد نویسی توسط ارث بری از CrudController
    - **Site Setting** : مدیریت تنظیمات پروژ توسط Configuration و ISnapshotOptions
    - **Postman** : آشنایی و کار با Postman جهت تست API ها
    - **Minimal Mvc** : حذف سرویس های اضافه MVC برای افزایش پرفرمنس در API نویسی
    - **Best Practices** : اعمال Best Practices ها جهت بهینه سازی، افزایش پرفرمنس و کدنویسی تمیز و اصولی
    - **و چندین نکته مفید دیگر ...**
    - 

## دانلود ویدئو های آموزشی دوره
این دوره در قالب (در مجموع) 20 ساعت و 5 گیگابایت آموزش ویدئویی توسط محمد جواد ابراهیمی ([mjebrahimi]()) تدریس شده است.   

**لینک دانلود** :  [به زودی](http://dotnetzoom.com/commingsoon)



## پیش نیاز این دوره :
سطح دوره پیشرفته بوده و برای افراد **مبتدی** مناسب **نیست**. انتظار میره برای شروع این دوره پیش نیاز های زیر رو داشته باشین :
1. تسلط نسبی بر روی زبان سی شارپ
2. آشنایی با پروتکل Http و REST
3. آشنایی با معماری MVC (و ترجیحا آشنایی با WebAPI)
4. آشنایی با Entity Framework (ترجیحا EF Core)

## ارتباط با مدرس
جهت ارتباط با مدرس و ارائه هرگونه پیشنهاد، انتقاد، نظر و سوالاتتون میتونین با اکانت تلگرام **محمد جواد ابراهیمی** در ارتباط باشید [**mjebrahimi@**]()

</div>