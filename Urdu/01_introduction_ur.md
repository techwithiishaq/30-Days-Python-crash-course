# 🐍 پائتھن کے 30 دن

| دن | موضوعات |
|------|:---------------------------------------------------------:|
| 01 | [تعارف](./01_introduction_ur.md) |
| 02 | [ویری ایبلز اور بلٹ اِن فنکشنز](../02_Day_Variables_builtin_functions/02_variables_builtin_functions.md) |
| 03 | [آپریٹرز](./03_Day_Operators/03_operators.md) |
| 04 | [اسٹرنگز](./04_Day_Strings/04_strings.md) |
| 05 | [لسٹس](./05_Day_Lists/05_lists.md) |
| 06 | [ٹیپلز](./06_Day_Tuples/06_tuples.md) |
| 07 | [سیٹس](./07_Day_Sets/07_sets.md) |
| 08 | [ڈکشنریز](./08_Day_Dictionaries/08_dictionaries.md) |
| 09 | [شرطی بیانات](./09_Day_Conditionals/09_conditionals.md) |
| 10 | [لوپس](./10_Day_Loops/10_loops.md) |
| 11 | [فنکشنز](./11_Day_Functions/11_functions.md) |
| 12 | [ماڈیولز](./12_Day_Modules/12_modules.md) |
| 13 | [لسٹ کمپری ہینشن](./13_Day_List_comprehension/13_list_comprehension.md) |
| 14 | [ہائیئر آرڈر فنکشنز](./14_Day_Higher_order_functions/14_higher_order_functions.md) |
| 15 | [پائتھن کی ٹائپ ایررز](./15_Day_Python_type_errors/15_python_type_errors.md) |
| 16 | [پائتھن کی تاریخ اور وقت](./16_Day_Python_date_time/16_python_datetime.md) |
| 17 | [ایکسپشن ہینڈلنگ](./17_Day_Exception_handling/17_exception_handling.md) |
| 18 | [ریگولر ایکسپریشنز](./18_Day_Regular_expressions/18_regular_expressions.md) |
| 19 | [فائل ہینڈلنگ](./19_Day_File_handling/19_file_handling.md) |
| 20 | [پائتھن پیکیج مینیجر](./20_Day_Python_package_manager/20_python_package_manager.md) |
| 21 | [کلاسز اور آبجیکٹس](./21_Day_Classes_and_objects/21_classes_and_objects.md) |
| 22 | [ویب اسکریپنگ](./22_Day_Web_scraping/22_web_scraping.md) |
| 23 | [ورچوئل انوائرنمنٹ](./23_Day_Virtual_environment/23_virtual_environment.md) |
| 24 | [شماریات](./24_Day_Statistics/24_statistics.md) |
| 25 | [Pandas](./25_Day_Pandas/25_pandas.md) |
| 26 | [پائتھن ویب](./26_Day_Python_web/26_python_web.md) |
| 27 | [پائتھن کے ساتھ MongoDB](./27_Day_Python_with_mongodb/27_python_with_mongodb.md) |
| 28 | [API](./28_Day_API/28_API.md) |
| 29 | [API بنانا](./29_Day_Building_API/29_building_API.md) |
| 30 | [اختتامیہ](./30_Day_Conclusions/30_conclusions.md) |

<small>🧡🧡🧡 کوڈنگ کرتے رہیں، خوش رہیں 🧡🧡🧡</small>

---

<div align="center">
  <h1>پائتھن کے 30 دن: دن 1 — تعارف</h1>
  <a target="_blank" href="https://www.linkedin.com/in/mdiishaq/">
    <img alt="LinkedIn پروفائل" src="https://img.shields.io/badge/LinkedIn-Muhammad%20Ishaq-blue?logo=linkedin&style=social">
  </a>
  <a target="_blank" href="https://github.com/muhammadiishaq">
    <img alt="GitHub پروفائل" src="https://img.shields.io/badge/GitHub-Muhammad%20Ishaq-black?logo=github&style=social">
  </a>
  <br>
  <sub>ترجمہ و ترتیب: <a href="https://www.linkedin.com/in/mdiishaq/" target="_blank">محمد اسحاق (Muhammad Ishaq)</a></sub>
  <br>
  <small>اصل کورس کے مصنف اور لائسنس سے متعلق معلومات کے لیے اصل منصوبے کی فائلیں ملاحظہ کریں۔</small>
</div>

🇫🇷 [فرانسیسی](../../French/README_fr.md)  
🇪🇸 [ہسپانوی](../../Spanish/readme.md)  
🇩🇪 [جرمن](../../German/readme.md)  
🇧🇷 [پرتگالی](../../Portuguese/README.md)  
🇨🇳 [چینی](../../Chinese/README.md)  
🇬🇷 [یونانی](../../Greek/readme.md)  
🇸🇦 [عربی](../../Arabic/readme.md)  
🇰🇷 [کوریائی](../../Korean/readme_ko.md)  
🇺🇦 [یوکرینی](../../Ukrainian/readme.md)  
🇺🇿 [ازبک](./Uzbek)  
🇮🇷 [فارسی](../../Persain/readme.md)  
🇷🇺 [روسی](../../Russian/readme.md)  
🇵🇰 [اردو](../readme.md)

[اگلا سبق: دن 2 »](../02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)

![30DaysOfPython](../../images/30DaysOfPython_banner3@2x.png)

- [🐍 پائتھن کے 30 دن](#-پائتھن-کے-30-دن)
- [📘 دن 1](#-دن-1)
  - [خوش آمدید](#خوش-آمدید)
  - [تعارف](#تعارف)
  - [پائتھن کیوں؟](#پائتھن-کیوں)
  - [ماحول کی تیاری](#ماحول-کی-تیاری)
    - [پائتھن انسٹال کرنا](#پائتھن-انسٹال-کرنا)
    - [پائتھن شیل](#پائتھن-شیل)
    - [Visual Studio Code انسٹال کرنا](#visual-studio-code-انسٹال-کرنا)
      - [Visual Studio Code استعمال کرنے کا طریقہ](#visual-studio-code-استعمال-کرنے-کا-طریقہ)
  - [پائتھن کی بنیادی باتیں](#پائتھن-کی-بنیادی-باتیں)
    - [پائتھن کا سنٹیکس](#پائتھن-کا-سنٹیکس)
    - [پائتھن انڈینٹیشن](#پائتھن-انڈینٹیشن)
    - [کمنٹس](#کمنٹس)
    - [ڈیٹا کی اقسام](#ڈیٹا-کی-اقسام)
      - [نمبر](#نمبر)
      - [اسٹرنگ](#اسٹرنگ)
      - [بولین](#بولین)
      - [لسٹ](#لسٹ)
      - [ڈکشنری](#ڈکشنری)
      - [ٹیپل](#ٹیپل)
      - [سیٹ](#سیٹ)
    - [ڈیٹا کی اقسام چیک کرنا](#ڈیٹا-کی-اقسام-چیک-کرنا)
    - [پائتھن فائل](#پائتھن-فائل)
  - [💻 مشقیں — دن 1](#-مشقیں--دن-1)
    - [مشق: لیول 1](#مشق-لیول-1)
    - [مشق: لیول 2](#مشق-لیول-2)
    - [مشق: لیول 3](#مشق-لیول-3)

# 📘 دن 1

## خوش آمدید

**مبارک ہو!** آپ نے پائتھن پروگرامنگ کے 30 دن کے چیلنج میں حصہ لینے کا فیصلہ کیا ہے۔ اس چیلنج میں آپ پائتھن پروگرامر بننے کے لیے ضروری بنیادی باتیں اور پروگرامنگ کے اہم تصورات سیکھیں گے۔ چیلنج مکمل کرنے پر آپ کو _30DaysOfPython_ چیلنج کا سرٹیفکیٹ مل سکتا ہے۔

اگر آپ اس چیلنج میں فعال طور پر حصہ لینا چاہتے ہیں تو [30DaysOfPython کے ٹیلیگرام گروپ](https://t.me/ThirtyDaysOfPython) میں شامل ہو سکتے ہیں۔

## تعارف

پائتھن ایک ہائی لیول پروگرامنگ زبان ہے جسے مختلف مقاصد کے لیے استعمال کیا جاتا ہے۔ یہ اوپن سورس، انٹرپریٹڈ اور آبجیکٹ اورینٹڈ پروگرامنگ زبان ہے۔ پائتھن کو نیدرلینڈز کے پروگرامر Guido van Rossum نے بنایا تھا۔ اس زبان کا نام برطانوی اسکیچ کامیڈی سیریز *Monty Python's Flying Circus* سے لیا گیا ہے۔ پائتھن کا پہلا ورژن 20 فروری 1991 کو جاری ہوا۔

پائتھن کے یہ 30 دن آپ کو Python 3 مرحلہ وار سیکھنے میں مدد دیں گے۔ موضوعات کو 30 دنوں میں تقسیم کیا گیا ہے۔ ہر دن میں کئی موضوعات، آسان وضاحتیں، حقیقی دنیا کی مثالیں، عملی مشقیں اور منصوبے شامل ہیں۔

یہ چیلنج ان ابتدائی سیکھنے والوں اور تجربہ کار افراد کے لیے بنایا گیا ہے جو پائتھن سیکھنا چاہتے ہیں۔ اسے مکمل کرنے میں 30 سے 100 دن لگ سکتے ہیں۔ ٹیلیگرام گروپ میں فعال طور پر حصہ لینے والوں کے چیلنج مکمل کرنے کے امکانات زیادہ ہو سکتے ہیں۔

یہ مواد عام فہم اور گفتگو کے انداز میں لکھا گیا ہے، دلچسپ اور حوصلہ افزا بھی ہے، لیکن اسے مکمل کرنے کے لیے آپ کو باقاعدگی سے وقت دینا ہوگا۔ اگر آپ ویڈیوز کے ذریعے سیکھنا پسند کرتے ہیں تو [Washera کے YouTube چینل](https://www.youtube.com/channel/UC7PNRuno1rzYPb1xLa4yktw) پر ویڈیو اسباق دیکھ سکتے ہیں۔ آپ [Python for Absolute Beginners ویڈیو](https://youtu.be/OCCWZheOesI) سے آغاز کر سکتے ہیں۔ ویڈیوز پر سوالات پوچھیں، تبصرے کریں اور سیکھنے میں فعال رہیں۔

## پائتھن کیوں؟

پائتھن کی زبان کا انداز انسانی زبان سے نسبتاً قریب ہے، اس لیے اسے سیکھنا اور استعمال کرنا آسان ہے۔

مختلف صنعتیں اور کمپنیاں، بشمول Google، پائتھن استعمال کرتی ہیں۔ اسے ویب ایپلی کیشنز، ڈیسک ٹاپ ایپلی کیشنز، سسٹم ایڈمنسٹریشن اور مشین لرننگ لائبریریز بنانے کے لیے استعمال کیا جاتا ہے۔ ڈیٹا سائنس اور مشین لرننگ کی کمیونٹی میں بھی پائتھن بہت مقبول ہے۔ امید ہے کہ یہ باتیں آپ کو پائتھن سیکھنا شروع کرنے کے لیے کافی حوصلہ دیں گی۔

## ماحول کی تیاری

### پائتھن انسٹال کرنا

پائتھن اسکرپٹ چلانے کے لیے آپ کے کمپیوٹر پر پائتھن انسٹال ہونا ضروری ہے۔ اسے [پائتھن کی سرکاری ویب سائٹ](https://www.python.org/) سے ڈاؤن لوڈ کریں۔

اگر آپ Windows استعمال کرتے ہیں تو سرخ دائرے سے نشان زد بٹن پر کلک کریں۔

[![Windows پر انسٹال کرنا](../../images/installing_on_windows.png)](https://www.python.org/)

اگر آپ macOS استعمال کرتے ہیں تو سرخ دائرے سے نشان زد بٹن پر کلک کریں۔

[![macOS پر انسٹال کرنا](../../images/installing_on_macOS.png)](https://www.python.org/)

یہ چیک کرنے کے لیے کہ پائتھن انسٹال ہے یا نہیں، ٹرمینل میں یہ کمانڈ چلائیں:

```shell
python3 --version
```

![پائتھن ورژن](../../images/python_versio.png)

مثال میں Python 3.7.5 استعمال کیا گیا ہے۔ آپ کے کمپیوٹر پر پائتھن کا ورژن مختلف ہو سکتا ہے، لیکن بہتر ہے کہ وہ 3.6 یا اس سے نیا ہو۔ اگر ٹرمینل میں ورژن نظر آ جائے تو پائتھن انسٹال ہے۔ اب اگلے حصے کی طرف بڑھیں۔

### پائتھن شیل

پائتھن ایک interpreted scripting language ہے، اس لیے اسے چلانے سے پہلے compile کرنا ضروری نہیں۔ یہ کوڈ کو لائن بہ لائن چلاتی ہے۔ پائتھن کے ساتھ **Python Shell** یا **Python Interactive Shell** بھی آتا ہے۔ اس میں آپ ایک پائتھن کمانڈ چلا کر فوراً نتیجہ دیکھ سکتے ہیں۔

Python Shell صارف کے کوڈ کا انتظار کرتا ہے۔ جب آپ کوڈ لکھتے ہیں تو یہ اسے سمجھ کر اگلی لائن میں نتیجہ دکھاتا ہے۔

اپنا ٹرمینل یا Command Prompt کھولیں اور یہ لکھیں:

```shell
python
```

![پائتھن اسکرپٹنگ شیل](../../images/opening_python_shell.png)

اب Python Interactive Shell کھل جائے گا۔ آپ `>>>` کے نشان کے بعد پائتھن کوڈ لکھیں اور Enter دبائیں۔

![پائتھن شیل میں اسکرپٹ لکھنا](../../images/adding_on_python_shell.png)

بہت خوب! آپ نے Python Interactive Shell میں اپنا پہلا اسکرپٹ لکھ لیا۔ اسے بند کرنے کے لیے `>>>` کے بعد `exit()` لکھیں اور Enter دبائیں۔

![پائتھن شیل بند کرنا](../../images/exit_from_shell.png)

اب آپ جانتے ہیں کہ Python Interactive Shell کیسے کھولنا اور بند کرنا ہے۔

اگر آپ ایسا کوڈ لکھیں جسے پائتھن سمجھ سکے تو یہ نتیجہ دے گا؛ ورنہ ایرر دکھائے گا۔ آئیے جان بوجھ کر ایک غلطی کرتے ہیں اور دیکھتے ہیں کہ پائتھن کیا جواب دیتا ہے۔

![غلط سنٹیکس کا ایرر](../../images/invalid_syntax_error.png)

ایرر بتاتا ہے کہ مسئلہ کہاں ہے۔ پائتھن میں ضرب کے لیے `x` استعمال کرنا درست نہیں؛ اس کے بجائے ستارے کا نشان `*` استعمال کیا جاتا ہے۔ ایرر پیغام ہمیں بتاتا ہے کہ کیا درست کرنا ہے۔

کسی پروگرام میں غلطیوں کو تلاش کرنے اور دور کرنے کے عمل کو **debugging** کہتے ہیں۔ آئیے `x` کی جگہ `*` لگا کر اسے درست کریں۔

![سنٹیکس ایرر درست کرنا](../../images/fixing_syntax_error.png)

اب غلطی درست ہو گئی، کوڈ چل گیا اور ہمیں مطلوبہ نتیجہ مل گیا۔ پروگرامنگ کرتے ہوئے آپ کو روزانہ اس طرح کے ایررز مل سکتے ہیں، اس لیے debugging سیکھنا ضروری ہے۔ پائتھن میں آپ کو `SyntaxError`، `IndexError`، `NameError`، `ModuleNotFoundError`، `KeyError`، `ImportError`، `AttributeError`، `TypeError`، `ValueError` اور `ZeroDivisionError` جیسے ایررز مل سکتے ہیں۔ ہم بعد کے اسباق میں مختلف **error types** کو مزید تفصیل سے دیکھیں گے۔

آئیے Python Interactive Shell کی مزید مشق کریں۔ ٹرمینل یا Command Prompt میں `python` لکھیں۔

![پائتھن اسکرپٹنگ شیل](../../images/opening_python_shell.png)

اب ہم ریاضی کے چند بنیادی آپریشن کریں گے: جمع، تفریق، ضرب، تقسیم، باقی معلوم کرنا اور طاقت نکالنا۔

پہلے ان حسابی مثالوں کو دیکھیں:

- `2 + 3 = 5`
- `3 - 2 = 1`
- `3 * 2 = 6`
- `3 / 2 = 1.5`
- `3 ** 2 = 3 × 3 = 9`

پائتھن میں ان کے علاوہ یہ آپریشن بھی ہیں:

- `3 % 2 = 1` — اس سے تقسیم کے بعد باقی معلوم ہوتا ہے۔
- `3 // 2 = 1` — یہ تقسیم کا اعشاری حصہ ہٹا دیتا ہے۔

اب ان حسابی مثالوں کو پائتھن کوڈ میں تبدیل کرتے ہیں۔ شیل کھلا ہو تو شروع میں ایک comment لکھیں۔

**Comment** کوڈ کا ایسا حصہ ہوتا ہے جسے پائتھن execute نہیں کرتا۔ اس کا مقصد کوڈ میں وضاحتی نوٹس لکھنا اور اسے زیادہ قابلِ فہم بنانا ہے۔ پائتھن میں comment کی ابتدا `#` سے ہوتی ہے۔

```python
# comment starts with hash
# this is a python comment, because it starts with a (#) symbol
```

![پائتھن شیل میں حساب](../../images/maths_on_python_shell.png)

اگلے حصے سے پہلے مزید مشق کریں۔ شیل میں `exit()` لکھ کر اسے بند کریں، پھر دوبارہ کھولیں اور اس میں متن لکھنے کی مشق کریں۔

![پائتھن شیل میں اسٹرنگ لکھنا](../../images/writing_string_on_shell.png)

### Visual Studio Code انسٹال کرنا

Python Interactive Shell چھوٹے اسکرپٹس آزمانے کے لیے مفید ہے، لیکن بڑے منصوبوں کے لیے مناسب نہیں۔ حقیقی کام میں ڈویلپرز کوڈ لکھنے کے لیے مختلف code editors استعمال کرتے ہیں۔ اس 30 روزہ چیلنج میں ہم **Visual Studio Code (VS Code)** استعمال کریں گے۔ یہ ایک مقبول اوپن سورس ایڈیٹر ہے۔ آپ اسے [یہاں سے ڈاؤن لوڈ](https://code.visualstudio.com/) کر سکتے ہیں۔ اگر آپ کوئی دوسرا ایڈیٹر استعمال کرنا چاہتے ہیں تو وہ بھی استعمال کر سکتے ہیں۔

[![Visual Studio Code](../../images/vscode.png)](https://code.visualstudio.com/)

اگر آپ نے Visual Studio Code انسٹال کر لیا ہے تو اب اسے استعمال کرنا سیکھتے ہیں۔ اگر آپ ویڈیو کے ذریعے سیکھنا چاہتے ہیں تو [Visual Studio Code for Python ویڈیو ٹیوٹوریل](https://www.youtube.com/watch?v=bn7Cx4z-vSo) دیکھ سکتے ہیں۔

#### Visual Studio Code استعمال کرنے کا طریقہ

Visual Studio Code کے آئیکن پر ڈبل کلک کرکے اسے کھولیں۔ آپ کو اس طرح کا انٹرفیس نظر آئے گا۔ اس میں موجود مختلف آئیکنز کو استعمال کرکے دیکھیں۔

![Visual Studio Code](../../images/vscode_ui.png)

اپنے Desktop پر `30DaysOfPython` نام کا فولڈر بنائیں، پھر Visual Studio Code میں اسے کھولیں۔

![Visual Studio Code میں پروجیکٹ کھولنا](../../images/how_to_open_project_on_vscode.png)

![پروجیکٹ کھولنا](../../images/opening_project.png)

پروجیکٹ کھولنے کے بعد آپ کو اس فولڈر کے اندر فائلیں اور فولڈرز بنانے کے اختیارات نظر آئیں گے۔ مثال کے طور پر `helloworld.py` نام کی پہلی فائل بنائیں۔ آپ بھی یہی کریں۔

![پائتھن فائل بنانا](../../images/helloworld.png)

کوڈنگ کے بعد جب آپ ایڈیٹر بند کرنا چاہیں تو کھلا ہوا پروجیکٹ اس طرح بند کر سکتے ہیں۔

![پروجیکٹ بند کرنا](../../images/closing_opened_project.png)

مبارک ہو! آپ نے اپنا development environment تیار کر لیا ہے۔ اب کوڈنگ شروع کرتے ہیں۔

## پائتھن کی بنیادی باتیں

### پائتھن کا سنٹیکس

پائتھن اسکرپٹ Python Interactive Shell یا code editor میں لکھا جا سکتا ہے۔ پائتھن فائل کا ایکسٹینشن `.py` ہوتا ہے۔

### پائتھن انڈینٹیشن

Indentation سے مراد متن یا کوڈ کے آغاز میں خالی جگہ دینا ہے۔ بہت سی زبانوں میں indentation کوڈ کو پڑھنے میں آسان بناتی ہے، لیکن پائتھن میں اس سے code blocks بھی بنائے جاتے ہیں۔ دوسری زبانوں میں اکثر code blocks کے لیے curly brackets `{}` استعمال ہوتے ہیں۔ پائتھن میں غلط indentation ایک عام غلطی ہے۔

![انڈینٹیشن ایرر](../../images/indentation.png)

### کمنٹس

Comments کوڈ کو سمجھنے میں آسان بناتے ہیں اور ڈویلپرز کو کوڈ کے اندر نوٹس لکھنے دیتے ہیں۔ پائتھن میں `#` سے شروع ہونے والا متن comment ہوتا ہے اور پروگرام چلنے پر execute نہیں ہوتا۔

**مثال: ایک لائن کا کمنٹ**

```python
# This is the first comment
# This is the second comment
# Python is eating the world
```

**مثال: متعدد لائنوں کا کمنٹ**

اگر triple quotes کو کسی variable میں assign نہ کیا جائے تو انہیں متعدد لائنوں پر مشتمل comment جیسی وضاحت لکھنے کے لیے استعمال کیا جا سکتا ہے۔

```python
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```

### ڈیٹا کی اقسام

پائتھن میں ڈیٹا کی کئی اقسام ہوتی ہیں۔ پہلے چند عام اقسام سے واقف ہوتے ہیں۔ ہر قسم کو آگے تفصیل سے پڑھیں گے؛ فی الحال صرف ان سے بنیادی واقفیت حاصل کریں۔ ابھی ہر چیز کو مکمل طور پر سمجھنا ضروری نہیں۔

#### نمبر

- **Integer:** منفی، صفر اور مثبت مکمل اعداد۔

  مثال: `... -3, -2, -1, 0, 1, 2, 3 ...`

- **Float:** اعشاری اعداد۔

  مثال: `... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...`

- **Complex:** کمپلیکس اعداد۔

  مثال: `1 + j`, `2 + 4j`

#### اسٹرنگ

ایک یا زیادہ حروف کا مجموعہ جو single quotes یا double quotes کے اندر لکھا جاتا ہے۔ اگر اسٹرنگ میں ایک سے زیادہ جملے ہوں تو triple quotes استعمال کیے جا سکتے ہیں۔

**مثال:**

```python
'Asabeneh'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying the first day of 30DaysOfPython Challenge'
```

#### بولین

Boolean ڈیٹا ٹائپ کی دو ممکنہ قدریں ہوتی ہیں: `True` یا `False`۔ ان میں `T` اور `F` بڑے حروف میں لکھے جاتے ہیں۔

**مثال:**

```python
True   # Is the light on? If it is on, then the value is True
False  # Is the light on? If it is off, then the value is False
```

#### لسٹ

پائتھن کی list ایک ترتیب وار مجموعہ ہے جس میں مختلف ڈیٹا ٹائپس کی اشیا رکھی جا سکتی ہیں۔ یہ JavaScript کے array سے ملتی جلتی ہے۔

**مثال:**

```python
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits)
['Finland', 'Estonia', 'Sweden', 'Norway'] # all the same data types - a list of strings (countries)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### ڈکشنری

پائتھن کی dictionary ایک مجموعہ ہے جس میں ڈیٹا `key:value` کی شکل میں رکھا جاتا ہے۔

**مثال:**

```python
{
    'first_name': 'Asabeneh',
    'last_name': 'Yetayeh',
    'country': 'Finland',
    'age': 250,
    'is_married': True,
    'skills': ['JS', 'React', 'Node', 'Python']
}
```

#### ٹیپل

Tuple بھی list کی طرح مختلف ڈیٹا ٹائپس کا ترتیب وار مجموعہ ہے، لیکن بننے کے بعد اس میں تبدیلی نہیں کی جا سکتی۔ اسی لیے اسے **immutable** کہا جاتا ہے۔

**مثال:**

```python
('Asabeneh', 'Pawel', 'Brook', 'Abraham', 'Lidiya')  # Names
```

```python
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury')  # planets
```

#### سیٹ

Set ڈیٹا کی ایسی collection ہے جو list اور tuple سے ملتی جلتی ہے۔ لیکن list اور tuple کے برعکس set میں اشیا کی ترتیب اہم نہیں ہوتی۔ ریاضی کے set کی طرح، پائتھن کا set صرف منفرد اشیا محفوظ کرتا ہے۔

اگلے اسباق میں ہم پائتھن کی ہر ڈیٹا ٹائپ کو تفصیل سے دیکھیں گے۔

**مثال:**

```python
{2, 4, 3, 5}
{3.14, 9.81, 2.7}  # order is not important in set
```

### ڈیٹا کی اقسام چیک کرنا

کسی ڈیٹا یا variable کی قسم معلوم کرنے کے لیے `type()` فنکشن استعمال کیا جاتا ہے۔ نیچے دی گئی تصویر میں مختلف پائتھن ڈیٹا ٹائپس دکھائی گئی ہیں۔

![ڈیٹا کی اقسام چیک کرنا](../../images/checking_data_types.png)

### پائتھن فائل

اپنا `30DaysOfPython` فولڈر کھولیں۔ اگر یہ موجود نہیں تو اسے بنائیں۔ اس کے اندر `helloworld.py` نام کی فائل بنائیں۔ اب Visual Studio Code میں وہی کام کریں جو آپ نے Python Interactive Shell میں کیا تھا۔

Interactive Shell میں نتیجہ دکھانے کے لیے لازمی طور پر `print()` استعمال نہیں کرنا پڑتا، لیکن Visual Studio Code میں نتیجہ دیکھنے کے لیے ہمیں built-in function `print()` استعمال کرنا ہوگا۔ یہ فنکشن ایک یا زیادہ arguments لے سکتا ہے، مثلاً `print('argument1', 'argument2', 'argument3')`۔

**مثال:**

فائل کا نام `helloworld.py` ہے۔

```python
# Day 1 - 30DaysOfPython Challenge

print(2 + 3)             # addition(+)
print(3 - 1)              # subtraction(-)
print(2 * 3)              # multiplication(*)
print(3 / 2)              # division(/)
print(3 ** 2)             # exponential(**)
print(3 % 2)              # modulus(%)
print(3 // 2)             # Floor division operator(//)

# Checking data types
print(type(10))           # Int
print(type(3.14))         # Float
print(type(1 + 3j))       # Complex number
print(type('Asabeneh'))   # String
print(type([1, 2, 3]))    # List
print(type({'name': 'Asabeneh'}))  # Dictionary
print(type({9.8, 3.14, 2.7}))      # Set
print(type((9.8, 3.14, 2.7)))      # Tuple
```

پائتھن فائل چلانے کے لیے نیچے دی گئی تصویر دیکھیں۔ آپ Visual Studio Code میں سبز Run بٹن دبا کر یا ٹرمینل میں `python helloworld.py` لکھ کر فائل چلا سکتے ہیں۔

![پائتھن اسکرپٹ چلانا](../../images/running_python_script.png)

🌕 آپ بہت اچھا کر رہے ہیں! آپ نے دن 1 کا سبق مکمل کر لیا ہے اور سیکھنے کے سفر میں آگے بڑھ رہے ہیں۔ اب اپنے ذہن اور عملی صلاحیتوں کی مشق کے لیے یہ exercises حل کریں۔

## 💻 مشقیں — دن 1

### مشق: لیول 1

1. معلوم کریں کہ آپ پائتھن کا کون سا ورژن استعمال کر رہے ہیں۔
2. Python Interactive Shell کھولیں اور `3` اور `4` کو استعمال کرتے ہوئے یہ آپریشن کریں:
   - جمع (`+`)
   - تفریق (`-`)
   - ضرب (`*`)
   - باقی معلوم کرنا (`%`)
   - تقسیم (`/`)
   - طاقت (`**`)
   - فلور ڈویژن (`//`)
3. Python Interactive Shell میں یہ strings لکھیں:
   - آپ کا نام
   - آپ کا خاندانی نام
   - آپ کا ملک
   - `I am enjoying 30 days of python`
4. درج ذیل ڈیٹا کی اقسام معلوم کریں:
   - `10`
   - `9.8`
   - `3.14`
   - `4 - 4j`
   - `['Asabeneh', 'Python', 'Finland']`
   - آپ کا نام
   - آپ کا خاندانی نام
   - آپ کا ملک

### مشق: لیول 2

1. `30DaysOfPython` فولڈر کے اندر `day_1` نام کا فولڈر بنائیں۔ اس فولڈر میں `helloworld.py` نام کی پائتھن فائل بنائیں اور سوالات 1، 2، 3 اور 4 دوبارہ حل کریں۔ فائل میں کام کرتے وقت `print()` استعمال کرنا یاد رکھیں۔ پھر ٹرمینل میں اس ڈائریکٹری تک جائیں جہاں فائل محفوظ کی ہے اور اسے چلائیں۔

### مشق: لیول 3

1. پائتھن کی مختلف ڈیٹا ٹائپس کی مثالیں لکھیں، مثلاً Number (`Integer`, `Float`, `Complex`)، String، Boolean، List، Tuple، Set اور Dictionary۔
2. ان دو نقاط `(2, 3)` اور `(10, 8)` کے درمیان [Euclidean distance](https://en.wikipedia.org/wiki/Euclidean_distance#:~:text=In%20mathematics%2C%20the%20Euclidean%20distance,being%20called%20the%20Pythagorean%20distance.) معلوم کریں۔

🎉 **مبارک ہو!** 🎉

[اگلا سبق: دن 2 »](../02_Day_Variables_builtin_functions/02_variables_builtin_functions.md)
