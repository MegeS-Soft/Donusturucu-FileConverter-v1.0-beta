# Donusturucu-FileConverter v1.0-beta 🚀

# EN English

**Donusturucu-FileConverter** is a lightweight and user-friendly **desktop file conversion tool** designed to simplify everyday document conversion tasks.

The application is currently in **Beta** and is actively being improved based on user feedback and future requirements.

---

## ✨ Features

- 📄 **CSV → Excel (XLSX)** conversion  
- 📄 **PDF → Word (DOCX)** conversion  
- 📊 Optional numeric formatting for Excel outputs  
- 🖱️ Clean, simple, and user-friendly interface  
- 📁 Drag & drop file support  
- 🖥️ Windows desktop application (WinForms)

---

## 🛠️ Supported Conversions

| Source File |  Target File  |
|-------------|---------------|
| CSV         | Excel (.xlsx) |
| PDF         | Word (.docx)  |

---

## ⚙️ Technology Stack

- **Language:** C# (.NET)
- **UI Framework:** WinForms
- **CSV Processing:** CsvHelper
- **Excel Generation:** ClosedXML
- **PDF → Word Conversion:** Microsoft Word Interop

> ⚠️ **Microsoft Word must be installed** on the system to enable PDF → Word conversion.

---

## ⏳ Why Can PDF → Word Conversion Take Longer?

Converting PDF files into editable Word documents is naturally more complex than many other file conversions.

This application uses **Microsoft Word’s built-in PDF import engine** to ensure:
- Tables are preserved
- Images remain intact
- Page layout is maintained
- Special characters (including non-English characters) are handled correctly

Because this process relies on Word’s internal system, conversion time may vary depending on file size and content.

👉 This is **not a limitation or bug**, but a **deliberate design choice** to prioritize accuracy and document quality.

---

## 🧪 About the Beta Version

This project is currently in **Beta**.

What this means:
- ✔️ The application is stable and usable
- ✔️ Core features are complete
- 🔄 Performance improvements may be introduced
- 💡 User feedback is welcome and valued

Planned improvements may include:
- Performance optimizations
- Additional format support
- User experience enhancements

---

---

## 🇹🇷 Türkçe

**Donusturucu-FileConverter**, günlük belge dönüştürme ihtiyaçlarını pratik, hızlı ve anlaşılır bir şekilde karşılamak için geliştirilmiş bir **masaüstü dosya dönüştürücü uygulamadır**.

Uygulama şu anda **Beta sürümündedir** ve kullanıcı geri bildirimlerine göre geliştirilmeye devam etmektedir.

---

## ✨ Özellikler

- 📄 **CSV → Excel (XLSX)** dönüştürme  
- 📄 **PDF → Word (DOCX)** dönüştürme  
- 📊 Excel çıktılarında isteğe bağlı sayısal veri formatlama  
- 🖱️ Sade ve kullanıcı dostu arayüz  
- 📁 Sürükle & bırak dosya desteği  
- 🖥️ Windows masaüstü uygulaması (WinForms)

---

## 🛠️ Desteklenen Dönüşümler

| Kaynak Dosya | Hedef Dosya |
|--------------|--------------|
| CSV          | Excel (.xlsx)|
| PDF          | Word (.docx) |


---

## ⚙️ Teknik Altyapı

- **Dil:** C# (.NET)
- **Arayüz:** WinForms
- **CSV İşleme:** CsvHelper
- **Excel Oluşturma:** ClosedXML
- **PDF → Word:** Microsoft Word Interop

> ⚠️ PDF → Word dönüşümünün çalışabilmesi için bilgisayarınızda **Microsoft Word yüklü olmalıdır**.

---

## ⏳ PDF → Word Dönüşümü Neden Biraz Daha Uzun Sürebilir?

PDF dosyalarının Word formatına dönüştürülmesi, teknik olarak daha karmaşık bir işlemdir.

Bu uygulama, PDF → Word dönüşümünde **Microsoft Word’ün kendi içe aktarma altyapısını** kullanır.  
Bu sayede:

- Tablolar
- Görseller
- Sayfa düzeni
- Türkçe ve özel karakterler

mümkün olan en doğru şekilde korunur.

👉 Ancak bu yöntem, Word’ün sistem altyapısını kullandığı için dosya boyutuna ve içeriğe bağlı olarak dönüşüm süresi biraz uzayabilir.

Bu durum bir hata değildir; **belge kalitesini korumayı önceliklendiren bilinçli bir tercihtir**.

---

## 🧪 Beta Sürüm Hakkında

Bu proje şu anda **Beta** aşamasındadır.

Bu ne anlama gelir?
- ✔️ Uygulama çalışır ve kullanılabilir durumdadır
- ✔️ Temel özellikler stabildir
- 🔄 Performans iyileştirmeleri yapılabilir
- 💡 Geri bildirimlere açıktır

İlerleyen sürümlerde:
- Performans optimizasyonları
- Yeni dosya formatı destekleri
- Kullanıcı deneyimi geliştirmeleri
  planlanmaktadır.
