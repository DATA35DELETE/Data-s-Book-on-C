# Data's Book on C
 
## C
 
### Ön Söz
- Ben kimim?
- Bu Data's Book on C nedir?
- Bu dokümantasyon ne öğretecek?
 
---
 
### C : Giriş
- **Yazılım Nedir?**
  - **Donanım Nedir?**
  - **Low-Level ve High-Level**
  - **Yazılım Dilleri**
- **C Nedir?**
  - **Kısa Tarihçesi**
  - **Nasıl Kullanılır?**
  - **Kullanım Alanları**
  - **Prosedürel Programlama**: Nedir? Avantajları
- **C'yi Kurma**
  - **GCC Kurulumu**: GCC Nedir? Nasıl Kurulur?
  - **IDE Seçimi**: VS Code
  - **İlk Proje**
- **İlk Kod**: printf
- **Parametreli Programlar Yazma**: argc ve argv. Tanım. Örnek.
- **Derleme Süreci**: Tanım. Neden Önemli?
  - **Ön İşleme (Preprocessor) (.i)**: Makro genişletme. Header birleştirme. Örnek.
  - **Derleme (.o)**: Object dosyası. Semboller. Örnek.
  - **Linking**: Object dosyalarını birleştirme. Static vs Dynamic. Link Hataları. Örnek.
 
---
 
### C : Değişkenler
- **Değişkenler Nedir?**: Tanımı. Kullanım Senaryoları
- **Sayısal Değişkenler**
  - **short**: Tanım. unsigned short. Örnek.
  - **int**: Tanım. unsigned int. Örnek.
  - **long**: Tanım. long long. unsigned long. Örnek.
  - **float**: Tanım. Örnek.
  - **double**: Tanım. long double. Örnek.
- **İsimlendirme Kuralları**: Tablo Halinde
- **Char**: Tanım. Örnek.
- **Depolama Sınıfları**: Tanım
  > Tablo Halinde
  - **auto**
  - **static**
  - **extern**
- **Kullanıcıdan Değişken Alma**: scanf. Örnek.
- **Değişkenlerin Türünü Değiştirme**: Tanım.
  - **int &rarr; float**: Örnek.
  - **float &rarr; int**: Örnek.
  - **char &rarr; int**: Örnek.
  - **int &rarr; char**: Örnek.
- **Sabitlik**: const. #define. Örnek.
- **typedef**: Tanım. Örnek.
 
---
 
### C : Operatörler
- **Operatörler Nedir?**: Tanımı. Kullanım Senaryoları
- **Atama Operatörü**: Tanım. Örnek.
- **Aritmetik Operatörler**
  - **+**: Tanım. Örnek.
  - **-**: Tanım. Örnek.
  - **\***: Tanım. Örnek.
  - **/**: Tanım. Örnek.
  - **%**: Tanım. Örnek.
  - **Bileşik Atama Operatörleri**: +=, -=, \*=, /=. Örnek.
- **Yorum Satırı**: // ve /* */. Tanım. Örnek.
- **Karşılaştırma Operatörleri**
  - **<, >, <=, >=, ==, !=**: Tanım. Örnek.
- **Mantıksal Operatörler**
  - **!**: Tanım. Örnek.
  - **&&**: Tanım. Örnek.
  - **||**: Tanım. Örnek.
- **Bitwise Operatörler**: &, |, ^, ~, <<, >>. Tanım. Örnek.
- **Ternary**: Tanım. Örnek. Avantajı.
- **sizeof Operatörü**: Tanım. Örnek.
- **Yazdırma Komutunda % İle Veri Yazdırma**: Tanım. Örnek.
 
---
 
### C : Karar Yapıları
- **Karar Yapısı Nedir?**: Tanım. Program Akışı. Örnek.
- **If-Else if-Else**: Tanım. Örnek.
- **Switch-Case-Default**: Tanım. Örnek.
 
---
 
### C : Döngü Yapıları
- **Döngü Nedir?**: Tanım. Örnek.
- **while**: Tanım. Örnek.
- **for**: Tanım. Örnek.
- **break ve continue**: Tanım. Örnek.
 
---
 
### C : Diziler ve Stringler
- **Dizi Nedir?**: Tanım. Örnek. Avantajı.
- **Tek Boyutlu Diziler**: Tanım. Örnek.
  > Temel İşlemler
- **Çok Boyutlu Diziler**: Tanım. Örnek.
  > Temel İşlemler
- **String Yapısı**: Tanım. char dizisi olarak string. Örnek.
  > string.h Metodları
- **String Fonksiyonları**: strlen, strcpy, strcat, strcmp. Örnek.
 
---
 
### C : Pointerlar
- **Pointer Nedir?**: Tanım. Bellek Adresi. Örnek.
- **Pointer Tanımlama**: \* ve & operatörleri. Örnek.
- **Pointer Aritmetiği**: Tanım. Örnek.
  - **Char Dizisinde Pointer Aritmetiği**
- **Pointer ve Fonksiyonlar**: Call by Reference. Örnek.
- **Çift Pointer (Double Pointer)**: Tanım. Örnek.
- **NULL Pointer**: Tanım. Güvenli Kullanım. Örnek.
- **Function Pointers**: Tanım. Kullanım Senaryoları.
  - **Tanımlama ve Kullanma**: Sözdizimi. Örnek.
  - **Callback Yapısı**: Tanım. Örnek.
  - **Function Pointer Dizisi**: Tanım. Örnek.
  - **Plugin Sistemi**: Tanım. Örnek.
 
---
 
### C : Hata Yönetimi
- **Hata Yönetimi Nedir?**
- **errno**: Tanım. Örnek.
- **perror ve strerror**: Tanım. Örnek.
- **Return Kodları ile Hata Yönetimi**: Tanım. Örnek.
- **assert**: Tanım. Örnek.
 
---
 
### C : Fonksiyonlar
- **Fonksiyon Nedir?**: Tanım. main Fonksiyonu.
- **void'li Fonksiyonlar**: Tanım. Örnek.
- **Return'lü Fonksiyonlar**: Tanım. Örnek.
- **Parametreli Fonksiyonlar**: Tanım. Örnek.
- **Özyinelemeli Fonksiyonlar (Recursion)**: Tanım. Örnek.
- **Fonksiyon Prototipleri**: Tanım. Neden Gerekli? Örnek.
 
---
 
### C : Yapılar (Structs)
- **Struct Nedir?**: Tanım. OOP ile Karşılaştırma.
- **Struct Tanımlama ve Kullanma**: Tanım. Örnek.
- **Pointer ile Struct Kullanımı**: Tanım. -> operatörü. Örnek.
- **İç İçe Struct**: Tanım. Örnek.
- **Union**: Tanım. Struct ile Farkı. Örnek.
- **enum**: Tanım. Örnek.
 
---
 
### C : Bellek Yönetimi
- **Bellek Yönetimi Nedir?**: Stack vs Heap. Tanım.
- **Memory Layout**: Programın RAM'deki Yapısı. Görselleştirme.
  - **Text Segment**: Kod. Salt Okunur. Tanım.
  - **Data Segment**: Global ve Static Değişkenler. Initialized vs Uninitialized (BSS). Tanım.
  - **Stack**: Otomatik Ömürlü Değişkenler. LIFO. Stack Frame. Tanım.
  - **Heap**: Dinamik Bellek. malloc/free. Tanım.
  - **Segment Hataları**: Segmentation Fault. Neden Olur? Örnek.
- **malloc**: Tanım. Örnek.
- **calloc**: Tanım. malloc ile Farkı. Örnek.
- **realloc**: Tanım. Örnek.
- **free**: Tanım. Bellek Sızıntısı(Valgrind). Örnek.
- **Bellek Hataları**: Dangling Pointer. Buffer Overflow. Örnek.
- **RAM'de İletişim (Shared Memory)**: Tanım. Kullanım Senaryoları.
  - **mmap**: Tanım. Örnek.
  - **POSIX Shared Memory**: shm_open. shm_unlink. Örnek.
  - **Windows Shared Memory**:
    - **File Mapping Nedir?**: CreateFileMapping. Tanım. Parametreler.
    - **Belleğe Bağlama**: MapViewOfFile. Tanım. Örnek.
    - **Bağlantıyı Kesme**: UnmapViewOfFile. CloseHandle. Örnek.
 
---
 
### C : Dinamik Liste Yapımı
- **Dinamik Liste Nedir?**: Tanım. Array ile Farkı. Kullanım Senaryoları.
- **Linked List**: Tanım. Node Yapısı. Örnek.
  - **Tek Yönlü (Singly)**: Tanım. Örnek.
  - **Çift Yönlü (Doubly)**: Tanım. Örnek.
  - **Dairesel (Circular)**: Tanım. Örnek.
- **Stack (Yığın)**: Tanım. LIFO. Örnek.
  > Metodları
- **Queue (Kuyruk)**: Tanım. FIFO. Örnek.
  > Metodları
- **Generic Liste**: void pointer ile genel liste. Örnek.

---
 
### C : Dosya İşlemleri
- **Dosya İşlemleri Nedir?**
- **Dosya Açma ve Kapama**: fopen. fclose. Modlar. Örnek.
  > Metodları
- **Dosya Yazma İşlemleri**: fprintf, fputs, fwrite. Örnek.
  > Metodları
- **Dosya Okuma İşlemleri**: fscanf, fgets, fread. Örnek.
  > Metodları
- **Dosya Konumlandırma**: fseek. ftell. rewind. Örnek.
- **İkili (Binary) Dosyalar**: Tanım. Örnek.
- **Klasör İşlemleri**: Tanım. Kullanım Senaryoları.
  - **Linux — Klasör Operasyonları**:
    - **Klasör Oluşturma**: mkdir. Tanım. Parametreler. Örnek.
    - **Klasör Silme**: rmdir. Tanım. Örnek.
    - **Klasör İçeriğini Listele**: opendir. readdir. closedir. Örnek.
    - **Dosya/Klasör İstatistikleri**: stat. lstat. Tanım. Örnek.
    - **Dosya Türü Kontrolü**: S_ISREG. S_ISDIR. S_ISLNK. Örnek.
    - **Çalışan Klasör**: vschdir. Örnek.
  - **Windows — Klasör Operasyonları**:
    - **Klasör Oluşturma**: CreateDirectoryA. Tanım. Parametreler. Örnek.
    - **Klasör Silme**: RemoveDirectoryA. Tanım. Örnek.
    - **Klasör İçeriğini Listele**: FindFirstFileA. FindNextFileA. FindClose. Örnek.
    - **Dosya Bilgisi**: GetFileAttributesA. Tanım. Örnek.
    - **Dosya/Klasör Kontrolü**: FILE_ATTRIBUTE_DIRECTORY. Örnek.
    - **Çalışan Klasör**: GetCurrentDirectoryA. SetCurrentDirectoryA. Örnek.
- **Native Dosya İşlemleri**: Tanım. stdio.h vs OS API. Kullanım Senaryoları.
  - **Linux — .so Dosyaları**:
    - **Shared Object Nedir?**: .so ve .a Farkı. Dinamik vs Statik.
    - **Derleme**: gcc -shared -fPIC. Örnek.
    - **Yükleme (Runtime)**: dlopen. Tanım. Parametreler. Örnek.
    - **Sembol Çözümleme**: dlsym. Tanım. Örnek.
    - **Hata Yönetimi**: dlerror. Örnek.
    - **Kapatma**: dlclose. Bellek Yönetimi. Örnek.
    - **LD_LIBRARY_PATH**: Tanım. Kullanım. Örnek.
    - **ldd Komutu**: Bağımlılık Analizi. Örnek.
  - **Windows — .dll Dosyaları**:
    - **DLL Nedir?**: .dll ve .lib Farkı. Implicit vs Explicit Linking.
    - **DLL Oluşturma**: __declspec(dllexport). Örnek.
    - **Implicit Linking**: .lib ile Derleme. Tanım. Örnek.
    - **Explicit Linking (Runtime)**: LoadLibrary. Tanım. Parametreler. Örnek.
    - **Sembol Çözümleme**: GetProcAddress. Tanım. Örnek.
    - **Hata Yönetimi**: GetLastError. FreeLibrary. Örnek.
    - **DllMain**: Tanım. DLL_PROCESS_ATTACH / DETACH. Örnek.
    - **Dependency Walker / dumpbin**: Bağımlılık Analizi. Örnek.
- **JSON Dosyası**: JSON Nedir?
  - **JSON Mantığı**: Tanım. Yapısı.
  - **cJSON Kütüphanesi**: Kurulum. Örnek.
  - **JSON Oluşturma**: Örnek.
  - **JSON Yazma**: Örnek.
  - **JSON Okuma**: Örnek.
- **XML Dosyası**: XML Nedir?
  - **XML Mantığı**: Tanım. Yapısı. JSON ile Farkı.
  - **libxml2 Kütüphanesi**: Kurulum. Örnek.
  - **XML Okuma (DOM)**: xmlReadFile. xmlDocGetRootElement. Örnek.
  - **Node Gezinme**: xmlFirstElementChild. xmlNextElementSibling. Örnek.
  - **Attribute Okuma**: xmlGetProp. Örnek.
  - **XPath ile Sorgulama**: Tanım. xmlXPathEvalExpression. Örnek.
  - **XML Yazma**: xmlNewDoc. xmlNewNode. xmlSaveFile. Örnek.
  - **Bellek Yönetimi**: xmlFreeDoc. xmlCleanupParser. Örnek.
- **Zlib ile Sıkıştırılmış Dosyalar**: Tanım. Kullanım Senaryoları.
  - **Zlib Nedir?**: Kurulum. Örnek.
  - **Dosya Sıkıştırma**: deflate. Örnek.
  - **Dosya Açma**: inflate. Örnek.
  - **gzip Formatı**: Tanım. Örnek.
  
---
 
### C : Önişlemci (Preprocessor)
- **Önişlemci Nedir?**: Tanım. Derleme Süreci.
- **#include**: Tanım. <> ve "" Farkı. Örnek.
- **#define**: Tanım. Makro. Örnek.
- **#ifdef / #ifndef / #endif**: Koşullu Derleme. Örnek.
- **Header Dosyaları (.h)**: Tanım. Oluşturma. Kullanım. Örnek.
- **Makro Fonksiyonlar**: Tanım. Inline ile Farkı. Örnek.
- **Önceden Tanımlı Makrolar**: __FILE__, __LINE__, __DATE__, __TIME__. Örnek.
 
---
 
### C : CMake ile Kapsamlı Proje
- **CMake Nedir?**: Tanım. Makefile ile Farkı. Kullanım Senaryoları.
- **CMake Kurulumu**: Tanım. Örnek.
- **CMakeLists.txt**: Tanım. Temel Yapı. Örnek.
- **Çoklu Dosya Projesi**: Tanım. Örnek.
- **Kütüphane Oluşturma**: Static vs Shared. Örnek.
- **Dış Kütüphane Bağlama**: find_package. Örnek.-
 
---
 
### C : Asenkron Programlama
- **Asenkron Nedir?**: Tanım. Senkron vs Asenkron. Kullanım Senaryoları.
- **Thread Nedir?**: Tanım. Process vs Thread. Örnek.
- **POSIX Threads (pthread)**:
  - **Thread Oluşturma**: pthread_create. Örnek.
  - **Thread Bekleme**: pthread_join. Örnek.
  - **Mutex**: Tanım. Race Condition. pthread_mutex. Örnek.
  - **Condition Variable**: Tanım. Örnek.
- **Windows Threads**:
  - **Thread Oluşturma**: CreateThread. Örnek.
  - **Thread Bekleme**: WaitForSingleObject. Örnek.
 
---
 
### C : Güvenlik ve Şifreleme
- **Güvenlik Nedir?**: Tanım. Yaygın Açıklar.
- **Buffer Overflow Koruması**: Tanım. Örnek.
- **Input Validation**: Tanım. Örnek.
- **OpenSSL Kütüphanesi**: Kurulum. Tanım.
  - **Hashing**: MD5, SHA-256. Örnek.
  - **Simetrik Şifreleme**: AES. Örnek.
  - **Asimetrik Şifreleme**: RSA. Örnek.
- **Rastgele Sayı Üretme**: libsouim ile randombytes_uniform. Örnek.
- **Bellek Temizleme**: memset. Örnek.
 
---
 
### C : Log Sistemi
- **Loglama Nedir?**: Tanım. Kullanım Senaryoları.
- **Log Seviyeleri**: DEBUG, INFO, TRACE, WARNING, ERROR, FATAL. Tanım.
- **Log Formatı**: Timestamp. Seviye. Mesaj. Örnek.
- **Konsola Loglama**: Tanım. Örnek.
- **Dosyaya Loglama**: Tanım. Örnek.
- **Basit Log Kütüphanesi Yazma**: Tanım. Örnek.
 
---
 
### C : Veritabanı İşlemleri (SQLite)
- **Veritabanı Nedir?**: Tanım. Kullanım Senaryoları.
- **SQLite Nedir?**: Tanım. Kurulum.
- **sqlite3 Kütüphanesi**: Tanım. Kurulum. Örnek.
- **Bağlantı Kurma**: sqlite3_open. Database Dosyası. Örnek.
- **Veri Ekleme (INSERT)**: Tanım. Örnek.
  > Metodları
- **Veri Sorgulama (SELECT)**: Tanım. Örnek.
  > Metodları
- **Veri Güncelleme (UPDATE)**: Tanım. Örnek.
  > Metodları
- **Veri Silme (DELETE)**: Tanım. Örnek.
  > Metodları
- **Prepared Statements**: Tanım. SQL Injection Koruması. Örnek.
 
---
 
### C : HTTP İstekleri Yönetimi
- **HTTP Nedir?**: Tanım. Kullanım Senaryoları.
- **libcurl Kütüphanesi**: Tanım. Kurulum. Örnek.
- **GET İsteği**: Tanım. Örnek.
  > Seçenekler
- **POST İsteği**: Tanım. Örnek.
  > Seçenekler
- **Header Yönetimi**: Tanım. Örnek.
- **JSON ile HTTP**: İstek ve Yanıt. Örnek.
- **HTTPS ve SSL**: Tanım. Örnek.
- **Hata Yönetimi**: curl_easy_strerror. Örnek.
 
---
 
### C : Socket Programlama
- **Socket Nedir?**: Tanım. Kullanım Senaryoları.
- **TCP vs UDP**: Farkları. Tablo Halinde.
- **TCP Socket**:
  - **Server Oluşturma**: socket, bind, listen, accept. Örnek.
  - **Client Oluşturma**: socket, connect. Örnek.
  - **Veri Gönderme/Alma**: send, recv. Örnek.
- **UDP Socket**:
  - **Server ve Client**: sendto, recvfrom. Örnek.
- **Çok İstemcili Server**: fork veya thread ile. Örnek.

---
 
### C : Test Sistemi
- **Test Nedir?**: Tanım. Önemi. Kullanım Senaryoları.
- **Unit Test Nedir?**: Tanım. Örnek.
- **CUnit**: Kurulum. Tanım. Örnek.
- **cmocka**: Kurulum. Tanım. Örnek.
- **Test Yazma Prensipleri**: AAA (Arrange-Act-Assert). Örnek.
- **Mock ve Stub**: Tanım. Örnek.
- **CMake ile Test Entegrasyonu**: CTest. Örnek.
- **Kod Kapsama (Coverage)**: gcov. lcov. Örnek.
