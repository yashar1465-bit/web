# Rəqəmsal kriminalistika — imtahan üçün 14 sualın qısa cavabları

## 1. Rəqəmsal kriminalistika nədir? Fərqlər və sahələri

Rəqəmsal kriminalistika kompüter, telefon və digər elektron cihazlarda olan məlumatların toplanması, qorunması və təhlili ilə məşğul olan sahədir. Məqsəd rəqəmsal məlumatlardan hüquqi sübut kimi istifadə etməkdir. Ənənəvi kriminalistikada qan, barmaq izi kimi fiziki sübutlar, rəqəmsal kriminalistikada isə fayllar, loglar və elektron mesajlar araşdırılır. Əsas sahələri Computer Forensics, Mobile Forensics, Network Forensics, Cloud Forensics, E-mail Forensics və Malware Forensics-dir.

## 2. Rəqəmsal kriminalistikanın məqsədləri və əsas prinsipləri

Rəqəmsal kriminalistikanın əsas məqsədi sübutları aşkar etmək, silinmiş məlumatları bərpa etmək və hadisənin necə baş verdiyini müəyyənləşdirməkdir. Əsas prinsiplərə sübutun bütövlüyünün qorunması (Integrity), təhvil-təslim tarixçəsinin qeyd edilməsi (Chain of Custody), minimum müdaxilə (Minimal Intervention), sənədləşdirmə (Documentation), qanunlara əməl edilməsi (Legal Compliance) və araşdırmanın təkrarlana bilməsi (Repeatability) daxildir.

## 3. Hüquqi çərçivə və rəqəmsal kriminalistikanın mərhələləri

Rəqəmsal kriminalistikada sübutlar qanuni yolla əldə edilməli və dəyişdirilmədən qorunmalıdır. Bu sahədə Azərbaycan Respublikasının qanunlarından, ISO/IEC 27037 standartından və NIST tövsiyələrindən istifadə olunur. Araşdırma hadisə yerinin qorunması, sübutların toplanması, saxlanması, təhlili, hadisənin bərpası, hesabatın hazırlanması və sübutların təqdim edilməsi mərhələlərindən ibarətdir.

## 4. Rəqəmsal sübut anlayışı, xüsusiyyətləri, formaları və təsnifatı

Rəqəmsal sübut kompüter, telefon və şəbəkələrdə saxlanılan, hüquqi prosesdə istifadə oluna bilən elektron məlumatdır. Bu sübutlar asanlıqla dəyişdirilə və silinə bilər, müxtəlif cihazlarda kopyalana bilər və metadata daşıyır. Əsas formalarına fayllar, sistem logları, şəbəkə trafikləri, SMS-lər, GPS məlumatları, bulud məlumatları və IoT cihazlarının qeydləri daxildir. Sübutlar birbaşa və dolayı, ittihamedici və müdafiə xarakterli ola bilər.

## 5. Rəqəmsal sübutların qəbul edilmə şərtləri, standartlar və qəbul edilməmə səbəbləri

Rəqəmsal sübutun qəbul edilməsi üçün hadisə ilə əlaqəli olması (Relevance), həqiqiliyinin və bütövlüyünün qorunması (Integrity and Authenticity), etibarlı üsulla əldə edilməsi (Reliability) və qanuni olması (Legality) vacibdir. Sübutun bütövlüyünü yoxlamaq üçün Hash istifadə olunur. ISO/IEC 27037 və Budapeşt Konvensiyası bu sahədə əhəmiyyətli mənbələrdəndir. Sübut qanunsuz əldə edildikdə, dəyişdirildikdə və ya Chain of Custody pozulduqda qəbul edilməyə bilər.

## 6. Rəqəmsal sübutların qorunma prinsipləri

Rəqəmsal sübutların qorunmasında əsas məqsəd onların dəyişdirilməsinin qarşısını almaqdır. Buna görə analiz orijinal üzərində deyil, onun nüsxəsi üzərində aparılır. Hash vasitəsilə nüsxənin bütövlüyü yoxlanılır. Sübutlar təhlükəsiz yerdə saxlanılır, hər təhvil-təslim sənədləşdirilir və Write Blocker kimi vasitələrdən istifadə olunur. Bütün əməliyyatlar qanuni prosedurlara uyğun aparılmalıdır.

## 7. Fayl sisteminin funksiyaları və struktur elementləri

Fayl sistemi yaddaş qurğusunda məlumatları təşkil edən və idarə edən sistemdir. O, faylların saxlanmasını, adlandırılmasını, axtarılmasını, giriş icazələrinin idarə edilməsini və disk sahəsinin bölüşdürülməsini təmin edir. Əsas struktur elementləri File, Directory, Path, Metadata və Identifier-dir. Fayl sistemlərində məlumatların yerləşməsi üçün Data Blocks, ümumi struktur haqqında məlumat üçün isə Superblock istifadə olunur.

## 8. Faylın komponentləri, tipləri, məntiqi və fiziki aspektləri

Faylın iki əsas komponenti var: Metadata və Content. Metadata faylın adı, ölçüsü, tarixi və icazələri haqqında məlumat verir, Content isə faylın əsas məzmunudur. Fayllar mətn, ikili, sistem, multimedia, arxiv və verilənlər bazası fayllarına bölünür. Məntiqi aspekt faylın adı, yolu və xüsusiyyətləri ilə, fiziki aspekt isə onun diskdə yerləşdiyi bloklarla bağlıdır.

## 9. Windows və Linux fayl sistemləri və icazələr

Windows-da FAT32 və NTFS, Linux-da isə EXT4, XFS və Btrfs kimi fayl sistemlərindən istifadə olunur. NTFS giriş icazələrini və journaling funksiyasını dəstəkləyir, EXT4 isə Linux sistemlərində geniş yayılıb. Windows-da icazələr ACL vasitəsilə, Linux-da isə Owner, Group və Others əsasında idarə olunur. Linux-da `r` oxuma, `w` yazma, `x` isə icra icazəsidir. Məsələn, `755` — sahibə tam icazə, digərlərinə oxuma və icra icazəsi verir.

## 10. Disk image anlayışı və forensic imaging prinsipləri

Disk image HDD, SSD və USB kimi yaddaş qurğularının bit-by-bit surətidir. Bu surət mövcud faylları, boş sektorları və silinmiş məlumat qalıqlarını əhatə edə bilər. Forensic imaging zamanı orijinal qurğu qorunmalı, Write Blocker istifadə edilməli və surətin Hash dəyəri yoxlanılmalıdır. Sübutların götürülməsi və saxlanması Chain of Custody əsasında sənədləşdirilməlidir.

## 11. Disk image formatları

Disk image yaratmaq üçün əsasən RAW, E01 və AFF formatlarından istifadə olunur. RAW (`.dd`) sadə və universal formatdır, lakin əlavə metadata və sıxılma imkanları məhduddur. E01 formatı metadata, Hash məlumatları və sıxılma imkanlarını dəstəkləyir. AFF isə açıq formatdır və metadata ilə sıxılmanı dəstəkləyir. RAW sadəliyi, E01 isə əlavə imkanları ilə fərqlənir.

## 12. Imaging metodları

Imaging metodları sübutların hansı formada götürülməsini müəyyən edir. Physical Imaging disk sektorlarının surətini çıxarır, Logical Imaging isə fayl sistemi vasitəsilə görünən faylları və qovluqları götürür. Targeted Imaging yalnız seçilmiş faylları əhatə edir. Live Imaging işlək sistemdən məlumat toplayır, Memory Imaging isə RAM-dakı prosesləri, şifrələmə açarlarını və aktiv bağlantıları əldə etməyə imkan verir.

## 13. Forensic imaging alətləri

Forensic imaging üçün müxtəlif proqram və alətlərdən istifadə olunur. FTK Imager qrafik interfeys vasitəsilə disk surəti yaratmağa və Hash yoxlamağa imkan verir. `dd` Linux-da bit-by-bit surət çıxarmaq üçün istifadə edilir, `dcfldd` isə Hash və log imkanları ilə fərqlənir. Guymager, EnCase, X-Ways Forensics və Magnet AXIOM da sübutların əldə edilməsi və təhlilində istifadə olunan alətlərdir.

## 14. Imaging çətinlikləri, standartlar və tövsiyələr

Forensic imaging zamanı böyük disklər, şifrələmə, SSD-lərdə TRIM funksiyası və uzaqdan məlumatların əldə edilməsi çətinlik yarada bilər. Şifrələnmiş disklərdə məlumatlara giriş üçün qanuni açarlar tələb oluna bilər. TRIM silinmiş məlumatların bərpasını çətinləşdirə bilər. ISO/IEC 27037 sübutların əldə edilməsi və qorunması üçün əsas standartlardan biridir. Araşdırma zamanı orijinal qorunmalı, Hash yoxlanılmalı və bütün əməliyyatlar sənədləşdirilməlidir.
