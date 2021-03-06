<div dir="rtl">
# ي : لغة البرمجة 

ي : لغة البرمجة هي لغة برمجة مفتوحة المصدر

هنا يمكنك كتابة باللغة العربية python code

> من المستحسن استخدام [IntelliJ IDEA](https://www.jetbrains.com/idea/). 

- **اهلا** [ملف عينة اهلا.ي](https://github.com/yalang/examples/blob/master/اهلا.ي)
```python
اطبع("اهلا و سهلا يا عالم")؛
```
انتاج:
```bash
اهلا و سهلا يا عالم
```

- **شرط** [ملف عينة لو.ي](https://github.com/yalang/examples/blob/master/لو.ي)
```python
ع = ٧
لو ع ٪ ٢ == ٠:؛
    اطبع("ع الفردية")؛
ولو ٧ == ٠:؛
    اطبع("هذا صفر")؛
اخر:؛
    اطبع("ع الزوجية")؛
```
انتاج:
```bash
ع الزوجية
```

- **وظيفة** [ملف عينة وظيفة.ي](https://github.com/yalang/examples/blob/master/وظيفة.ي)
```python
وظيفة جمع(اولا، ثاني):؛
    كل = اولا + ثاني؛
    ارجع كل؛

اطبع("جمع = "، جمع(٢، ٣))؛
```
انتاج:
```bash
جمع =  ٥
```

**ملحوظة: `؛` هو اختياري في نهاية السطر**



لمزيد من عينة رمز انظر (https://github.com/yalang/examples)


## المتطلبات الأساسية
- macOS أو Ubuntu
- Python 3


## ابدء
### تعليمات التحميل
- انسخ هذا:
```bash
git clone https://github.com/yalang/ya.git
cd ya
```

- تنفيذ هذا install.sh:
```bash
./install.sh
```

- أو تنفيذ هذا Makefile:
```bash
make install
```

## تنفيذ 

- قم بإنشاء ملف جديد بالاسم `اهلا.ي` 

- فتح في المحرر

- اكتب هذا في الملف

```vim
اطبع("اهلا و سهلا يا عالم")؛
```

- احفظها

- افتح terminal 

- اذهب إلى المجلد حيث يتم حفظ الملف

- تنفيذ هذا

```bash
ي اهلا.ي
```

- انتاج 

```bash
اهلا و سهلا يا عالم
```
</div>