# Islamic Classical Text Library (المكتبة الإسلامية التراثية المفتوحة)
> **An open, comprehensive, multi-language digital corpus of classical Islamic scholarship in clean Plain Text (`.txt`) and Markdown (`.md`) formats with academic metadata, verified checksums, and persistent repository links.**

---

### Key Library Statistics
- **Structure**: 6 Foundational Sections (1: Quran, 2: Hadith, 3: Tafsir, 4: Shuruhaat, 5: Classical Turath, 6: Matn al-Usool)
- **Languages Supported**: Primary **Arabic (العربية)**, Secondary **English** and **Urdu (اردو)**
- **Verification Status**: **100% Passed** (Automated Text Integrity & Completeness Audit)
- **Quality Assurance Audit**: [View Standalone Verification Report](file:///home/arehman/00-code/00-projects/islamic_classical_library/VERIFICATION_REPORT.md)

---

## Complete Table of Contents
1. [The Holy Quran (القرآن الكريم)](#1-the-holy-quran-القرآن-الكريم)
   - [Prominent Bilingual Interlinear Editions (Ayah + Translation)](#prominent-bilingual-interlinear-editions)
   - [Monolingual Canonical Editions](#monolingual-canonical-editions)
2. [Canonical Hadith Collections (كتب الحديث الشريف)](#2-canonical-hadith-collections-كتب-الحديث-الشريف)
3. [Classical Tafsir Collections (كتب التفسير والتأويل)](#3-classical-tafsir-collections-كتب-التفسير-والتأويل)
4. [Classical Hadith Commentaries (شروح كتب السنة والحديث)](#4-classical-hadith-commentaries-شروح-كتب-السنة-والحديث)
5. [Classical Turath Treatises (كتب التراث والعلوم الشرعية)](#5-classical-turath-treatises-كتب-التراث-والعلوم-الشرعية)
6. [Matn al-Usool: Primers of Islamic Sciences (متون أصول العلوم الشرعية)](#6-matn-al-usool-primers-of-islamic-sciences-متون-أصول-العلوم-الشرعية)
7. [Comprehensive Text Verification & Quality Assurance Report](#7-comprehensive-text-verification--quality-assurance-report)
8. [Licensing, Scholarly Provenance & Upstream Repositories](#8-licensing-scholarly-provenance--upstream-repositories)
9. [Automation & Maintenance Scripts](#9-automation--maintenance-scripts)

---

## 1. The Holy Quran (القرآن الكريم)
📁 Detailed Section Catalog: [`01_Quran/README.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/README.md)

### Prominent Bilingual Interlinear Editions
Each Ayah is presented in its original Arabic Uthmani script followed immediately by its translation:
```markdown
### [1:1]
**بِسْمِ ٱللَّهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ**
*In the name of Allah, the Entirely Merciful, the Especially Merciful.*
```

| Edition | Language | Authority / Translator | Upstream Source | Directory |
| :--- | :--- | :--- | :--- | :--- |
| **Arabic + English (Saheeh Intl)** | Bilingual (Ar + En) | Saheeh International | [tanzil.net/trans/en.sahih](http://tanzil.net/trans/en.sahih) | [`01_Quran/Bilingual_Arabic_English_Sahih_International/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/Bilingual_Arabic_English_Sahih_International/) |
| **Arabic + Urdu (Jalandhry)** | Bilingual (Ar + Ur) | Fateh Muhammad Jalandhari | [tanzil.net/trans/ur.jalandhry](http://tanzil.net/trans/ur.jalandhry) | [`01_Quran/Bilingual_Arabic_Urdu_Jalandhry/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/Bilingual_Arabic_Urdu_Jalandhry/) |

### Monolingual Canonical Editions
| Edition | Language | Authority / Translator | Upstream Source | Directory |
| :--- | :--- | :--- | :--- | :--- |
| **Arabic Uthmani Script** | Arabic | King Fahad Complex | [api.alquran.cloud](https://api.alquran.cloud/v1/quran/quran-uthmani) | [`01_Quran/Arabic_Uthmani/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/Arabic_Uthmani/) |
| **English (Saheeh Intl)** | English | Saheeh International | [api.alquran.cloud](https://api.alquran.cloud/v1/quran/en.sahih) | [`01_Quran/English_Sahih_International/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/English_Sahih_International/) |
| **English (Yusuf Ali)** | English | Abdullah Yusuf Ali | [api.alquran.cloud](https://api.alquran.cloud/v1/quran/en.yusufali) | [`01_Quran/English_Yusuf_Ali/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/English_Yusuf_Ali/) |
| **Urdu (Jalandhry)** | Urdu | Fateh Muhammad Jalandhari | [api.alquran.cloud](https://api.alquran.cloud/v1/quran/ur.jalandhry) | [`01_Quran/Urdu_Jalandhry/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/Urdu_Jalandhry/) |
| **Urdu (Maududi)** | Urdu | Syed Abul A'la Maududi | [api.alquran.cloud](https://api.alquran.cloud/v1/quran/ur.maududi) | [`01_Quran/Urdu_Maududi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/01_Quran/Urdu_Maududi/) |

---

## 2. Canonical Hadith Collections (كتب الحديث الشريف)
📁 Detailed Section Catalog: [`02_Hadith/README.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/README.md)

Canonical Hadith works with full narrator chains (*asānīd*), Arabic matn, English and Urdu translations, and section breakdowns:
| Collection | Compiler / Era | Hadiths | Upstream Source Repositories | Directory |
| :--- | :--- | :--- | :--- | :--- |
| **Sahih al-Bukhari** | Imam al-Bukhari (194–256 AH) | 7,589 | [fawazahmed0/hadith-api (bukhari)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-bukhari.json) | [`02_Hadith/Sahih_al_Bukhari/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Sahih_al_Bukhari/) |
| **Sahih Muslim** | Imam Muslim (204–261 AH) | 7,564 | [fawazahmed0/hadith-api (muslim)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-muslim.json) | [`02_Hadith/Sahih_Muslim/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Sahih_Muslim/) |
| **Sunan Abi Dawud** | Imam Abu Dawud (202–275 AH) | 5,274 | [fawazahmed0/hadith-api (abudawud)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-abudawud.json) | [`02_Hadith/Sunan_Abi_Dawud/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Sunan_Abi_Dawud/) |
| **Jami' at-Tirmidhi** | Imam at-Tirmidhi (209–279 AH) | 3,998 | [fawazahmed0/hadith-api (tirmidhi)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-tirmidhi.json) | [`02_Hadith/Jami_at_Tirmidhi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Jami_at_Tirmidhi/) |
| **Sunan an-Nasa'i** | Imam an-Nasa'i (214–303 AH) | 5,765 | [fawazahmed0/hadith-api (nasai)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-nasai.json) | [`02_Hadith/Sunan_an_Nasai/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Sunan_an_Nasai/) |
| **Sunan Ibn Majah** | Imam Ibn Majah (209–273 AH) | 4,343 | [fawazahmed0/hadith-api (ibnmajah)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-ibnmajah.json) | [`02_Hadith/Sunan_Ibn_Majah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Sunan_Ibn_Majah/) |
| **Muwatta Malik** | Imam Malik ibn Anas (93–179 AH) | 1,889 | [fawazahmed0/hadith-api (malik)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-malik.json) | [`02_Hadith/Muwatta_Malik/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Muwatta_Malik/) |
| **Forty Hadith Nawawi** | Imam al-Nawawi (631–676 AH) | 42 | [fawazahmed0/hadith-api (nawawi)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-nawawi.json) | [`02_Hadith/Forty_Hadith_Nawawi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Forty_Hadith_Nawawi/) |
| **Forty Hadith Qudsi** | Canonical Hadith Qudsi | 40 | [fawazahmed0/hadith-api (qudsi)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-qudsi.json) | [`02_Hadith/Forty_Hadith_Qudsi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Forty_Hadith_Qudsi/) |
| **Forty Hadith Shah Waliullah** | Shah Waliullah Dehlawi (1114–1176 AH) | 40 | [fawazahmed0/hadith-api (dehlawi)](https://cdn.jsdelivr.net/gh/fawazahmed0/hadith-api@1/editions/ara-dehlawi.json) | [`02_Hadith/Forty_Hadith_Shah_Waliullah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/02_Hadith/Forty_Hadith_Shah_Waliullah/) |

---

## 3. Classical Tafsir Collections (كتب التفسير والتأويل)
📁 Detailed Section Catalog: [`03_Tafsir/README.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/README.md)

11 major classical commentaries structured ayah-by-ayah across all 114 Surahs:
| Work | Author / Era | Languages Available | Upstream Source Tree | Directory |
| :--- | :--- | :--- | :--- | :--- |
| **Tafsir Ibn Kathir** | Al-Hafidh Ibn Kathir (774 AH) | Arabic, English, Urdu | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/ar-tafsir-ibn-kathir) | [`03_Tafsir/Tafsir_Ibn_Kathir/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_Ibn_Kathir/) |
| **Tafsir al-Tabari** | Imam Ibn Jarir al-Tabari (310 AH) | Arabic (*Umm al-Tafasir*) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/ar-tafsir-al-tabari) | [`03_Tafsir/Tafsir_al_Tabari/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_al_Tabari/) |
| **Tafsir al-Qurtubi** | Imam Abu Abd Allah al-Qurtubi (671 AH) | Arabic (*Al-Jami' li-Ahkam*) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/ar-tafseer-al-qurtubi) | [`03_Tafsir/Tafsir_al_Qurtubi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_al_Qurtubi/) |
| **Tafsir al-Baghawi** | Imam al-Husayn al-Baghawi (516 AH) | Arabic (*Ma'alim al-Tanzil*) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/ar-tafsir-al-baghawi) | [`03_Tafsir/Tafsir_al_Baghawi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_al_Baghawi/) |
| **Tafsir al-Kashshaf** | Mahmud ibn Umar al-Zamakhshari (538 AH) | Arabic (*Balaghah & Rhetoric*) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/al-kashshaf-al-zamakhshari) | [`03_Tafsir/Tafsir_al_Kashshaf_Zamakhshari/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_al_Kashshaf_Zamakhshari/) |
| **Tafsir al-Razi** | Imam Fakhr al-Din al-Razi (606 AH) | Arabic (*Mafatih al-Ghayb*) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/tafsir-al-razi) | [`03_Tafsir/Tafsir_al_Razi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_al_Razi/) |
| **Fath al-Qadir** | Imam Muhammad al-Shawkani (1250 AH) | Arabic (*Riwayah & Dirayah*) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/fath-al-qadir-al-shawkani) | [`03_Tafsir/Fath_al_Qadir_Shawkani/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Fath_al_Qadir_Shawkani/) |
| **Tafsir al-Jalalayn** | Al-Mahalli (864 AH) & Al-Suyuti (911 AH) | Arabic, English | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/ar-tafsir-al-jalalayn) | [`03_Tafsir/Tafsir_al_Jalalayn/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_al_Jalalayn/) |
| **Tafsir as-Sa'di** | Shaykh Abd al-Rahman as-Sa'di (1376 AH) | Arabic, Urdu | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/ar-tafsir-as-saadi) | [`03_Tafsir/Tafsir_as_Sadi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Tafsir_as_Sadi/) |
| **Asbab al-Nuzul** | Imam Ali ibn Ahmad al-Wahidi (468 AH) | English (Occasions of Revelation) | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/en-asbab-al-nuzul-by-al-wahidi) | [`03_Tafsir/Asbab_al_Nuzul_Wahidi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Asbab_al_Nuzul_Wahidi/) |
| **Ma'arif-ul-Quran** | Mufti Muhammad Shafi Usmani (1396 AH) | English Detailed Commentary | [spa5k/tafsir_api](https://github.com/spa5k/tafsir_api/tree/main/tafsir/en-tafsir-maarif-ul-quran) | [`03_Tafsir/Maarif_ul_Quran/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/03_Tafsir/Maarif_ul_Quran/) |

---

## 4. Classical Hadith Commentaries (شروح كتب السنة والحديث)
📁 Detailed Section Catalog: [`04_Hadith_Commentaries_Shuruhaat/README.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/README.md)

Academic critical editions from OpenITI (Harvard/Leipzig/Aga Khan universities):
| Commentary | Author | Commentary On | Word Count | OpenITI Repository Link | Directory |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Fath al-Bari** (*فتح الباري*) | Al-Hafidh Ibn Hajar (852 AH) | Sahih al-Bukhari | 3,310,194 words | [OpenITI/0875AH/0852IbnHajarCasqalani.FathBari](https://github.com/OpenITI/0875AH/tree/master/data/0852IbnHajarCasqalani/0852IbnHajarCasqalani.FathBari) | [`04_Hadith_Commentaries_Shuruhaat/01_Fath_al_Bari_Ibn_Hajar/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/01_Fath_al_Bari_Ibn_Hajar/) |
| **Al-Minhaj** (*المنهاج شرح صحيح مسلم*) | Imam al-Nawawi (676 AH) | Sahih Muslim | 774,030 words | [OpenITI/0700AH/0676Nawawi.MinhajFiSharhMuslim](https://github.com/OpenITI/0700AH/tree/master/data/0676Nawawi/0676Nawawi.MinhajFiSharhMuslim) | [`04_Hadith_Commentaries_Shuruhaat/02_Al_Minhaj_Nawawi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/02_Al_Minhaj_Nawawi/) |
| **Ma'alim al-Sunan** (*معالم السنن*) | Imam al-Khattabi (388 AH) | Sunan Abi Dawud | 346,730 words | [OpenITI/0400AH/0388AbuSulaymanKhattabi.MacalimSunan](https://github.com/OpenITI/0400AH/tree/master/data/0388AbuSulaymanKhattabi/0388AbuSulaymanKhattabi.MacalimSunan) | [`04_Hadith_Commentaries_Shuruhaat/03_Maalim_al_Sunan_Khattabi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/03_Maalim_al_Sunan_Khattabi/) |
| **Sharh 'Ilal al-Tirmidhi** (*شرح علل الترمذي*) | Ibn Rajab al-Hanbali (795 AH) | Jami' at-Tirmidhi | 38,690 words | [OpenITI/0800AH/0795IbnRajabHanbali.SharhCilalTirmidhi](https://github.com/OpenITI/0800AH/tree/master/data/0795IbnRajabHanbali/0795IbnRajabHanbali.SharhCilalTirmidhi) | [`04_Hadith_Commentaries_Shuruhaat/04_Sharh_Ilal_Tirmidhi_Ibn_Rajab/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/04_Sharh_Ilal_Tirmidhi_Ibn_Rajab/) |
| **Zahr al-Ruba** (*زهر الربى شرح سنن النسائي*) | Imam al-Suyuti (911 AH) | Sunan an-Nasa'i | 89,819 words | [OpenITI/0925AH/0911Suyuti.SharhSunanNasai](https://github.com/OpenITI/0925AH/tree/master/data/0911Suyuti/0911Suyuti.SharhSunanNasai) | [`04_Hadith_Commentaries_Shuruhaat/05_Sharh_Sunan_Nasai_Suyuti/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/05_Sharh_Sunan_Nasai_Suyuti/) |
| **Misbah al-Zujajah** (*مصباح الزجاجة على ابن ماجه*) | Imam al-Suyuti (911 AH) | Sunan Ibn Majah | 234,876 words | [OpenITI/0925AH/0911Suyuti.MisbahZujaja](https://github.com/OpenITI/0925AH/tree/master/data/0911Suyuti/0911Suyuti.MisbahZujaja) | [`04_Hadith_Commentaries_Shuruhaat/06_Misbah_al_Zujajah_Suyuti/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/06_Misbah_al_Zujajah_Suyuti/) |
| **Al-Qabas fi Sharh Muwatta** (*القبس في شرح موطأ مالك*) | Qadi Ibn al-Arabi (543 AH) | Muwatta Malik | 209,449 words | [OpenITI/0550AH/0543IbnCarabiIshbili.QabasFiSharhMuwatta](https://github.com/OpenITI/0550AH/tree/master/data/0543IbnCarabiIshbili/0543IbnCarabiIshbili.QabasFiSharhMuwatta) | [`04_Hadith_Commentaries_Shuruhaat/07_Al_Qabas_Sharh_Muwatta_Ibn_Arabi/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/07_Al_Qabas_Sharh_Muwatta_Ibn_Arabi/) |
| **Jami' al-'Ulum wal-Hikam** (*جامع العلوم والحكم*) | Ibn Rajab al-Hanbali (795 AH) | 40 Hadith Nawawi | 187,150 words | [OpenITI/0800AH/0795IbnRajabHanbali.JamicCulumWaHikam](https://github.com/OpenITI/0800AH/tree/master/data/0795IbnRajabHanbali/0795IbnRajabHanbali.JamicCulumWaHikam) | [`04_Hadith_Commentaries_Shuruhaat/08_Jami_al_Ulum_wal_Hikam_Ibn_Rajab/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/04_Hadith_Commentaries_Shuruhaat/08_Jami_al_Ulum_wal_Hikam_Ibn_Rajab/) |

---

## 5. Classical Turath Treatises (كتب التراث والعلوم الشرعية)
📁 Detailed Section Catalog: [`05_Classical_Turath_Texts/README.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/README.md)

Foundational Sunni treatises from OpenITI (Harvard/Leipzig/Aga Khan universities):
| Treatise | Author | Era | Discipline | OpenITI Upstream Source | Directory |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Al-Aqeedah al-Tahawiyyah** | Imam Abu Ja'far al-Tahawi | 321 AH | Sunni Creed (Ar + En) | [OpenITI/0325AH/0321Tahawi.MatnCaqida](https://github.com/OpenITI/0325AH/tree/master/data/0321Tahawi/0321Tahawi.MatnCaqida) | [`05_Classical_Turath_Texts/01_Aqeedah_Tahawiyyah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/01_Aqeedah_Tahawiyyah/) |
| **Al-Fiqh al-Akbar** | Imam Abu Hanifa al-Nu'man | 150 AH | Early Kalam / Creed (Ar + En) | [OpenITI/0150AH/0150AbuHanifa.FiqhAkbar](https://github.com/OpenITI/0150AH/tree/master/data/0150AbuHanifa/0150AbuHanifa.FiqhAkbar) | [`05_Classical_Turath_Texts/02_Al_Fiqh_al_Akbar/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/02_Al_Fiqh_al_Akbar/) |
| **Al-Wasiyyah** | Imam Abu Hanifa al-Nu'man | 150 AH | Spiritual Testament (Ar + En) | [OpenITI/0150AH/0150AbuHanifa.Wasiyya](https://github.com/OpenITI/0150AH/tree/master/data/0150AbuHanifa/0150AbuHanifa.Wasiyya) | [`05_Classical_Turath_Texts/03_Al_Wasiyyah_Abu_Hanifa/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/03_Al_Wasiyyah_Abu_Hanifa/) |
| **Al-Risala** | Imam Muhammad ibn Idris al-Shafi'i | 204 AH | Usul al-Fiqh (Foundational) | [OpenITI/0225AH/0204Shafici.Risala](https://github.com/OpenITI/0225AH/tree/master/data/0204Shafici/0204Shafici.Risala) | [`05_Classical_Turath_Texts/04_Al_Risala_Shafii/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/04_Al_Risala_Shafii/) |
| **Sharh al-Sunnah** | Imam al-Barbahari | 329 AH | Athari Creed & Manhaj | [OpenITI/0350AH/0329Barbahari.SharhSunna](https://github.com/OpenITI/0350AH/tree/master/data/0329Barbahari/0329Barbahari.SharhSunna) | [`05_Classical_Turath_Texts/05_Sharh_al_Sunnah_Barbahari/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/05_Sharh_al_Sunnah_Barbahari/) |
| **Bidayat al-Hidayah** | Hujjat al-Islam al-Ghazali | 505 AH | Tazkiyah & Daily Adab | [OpenITI/0525AH/0505Ghazali.BidayatHidaya](https://github.com/OpenITI/0525AH/tree/master/data/0505Ghazali/0505Ghazali.BidayatHidaya) | [`05_Classical_Turath_Texts/06_Bidayat_al_Hidayah_Ghazali/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/06_Bidayat_al_Hidayah_Ghazali/) |
| **Al-Munqidh min al-Dalal** | Hujjat al-Islam al-Ghazali | 505 AH | Deliverance from Error | [OpenITI/0525AH/0505Ghazali.Munqidh](https://github.com/OpenITI/0525AH/tree/master/data/0505Ghazali/0505Ghazali.Munqidh) | [`05_Classical_Turath_Texts/07_Al_Munqidh_min_al_Dalal/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/07_Al_Munqidh_min_al_Dalal/) |
| **Qawa'id al-'Aqa'id** | Hujjat al-Islam al-Ghazali | 505 AH | Principles of Faith | [OpenITI/0525AH/0505Ghazali.QawacidCaqaid](https://github.com/OpenITI/0525AH/tree/master/data/0505Ghazali/0505Ghazali.QawacidCaqaid) | [`05_Classical_Turath_Texts/08_Qawaid_al_Aqaid_Ghazali/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/05_Classical_Turath_Texts/08_Qawaid_al_Aqaid_Ghazali/) |

---

## 6. Matn al-Usool: Primers of Islamic Sciences (متون أصول العلوم الشرعية)
📁 Detailed Section Catalog: [`06_Matn_al_Usool/README.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/README.md)

Essential foundational primers across four disciplines:
| Discipline | Primer Title | Classical Author | Era | Local Directory |
| :--- | :--- | :--- | :--- | :--- |
| **Usool al-Tafsir** | **Muqaddimah fi Usul al-Tafsir** | Shaykh al-Islam Ibn Taymiyyah | 728 AH | [`06_Matn_al_Usool/01_Usool_al_Tafsir/Muqaddimah_fi_Usul_al_Tafsir_Ibn_Taymiyyah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/01_Usool_al_Tafsir/Muqaddimah_fi_Usul_al_Tafsir_Ibn_Taymiyyah/) |
| **Usool al-Hadith** | **Nukhbat al-Fikar** | Al-Hafidh Ibn Hajar al-Asqalani | 852 AH | [`06_Matn_al_Usool/02_Usool_al_Hadith/Nukhbat_al_Fikar_Ibn_Hajar/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/02_Usool_al_Hadith/Nukhbat_al_Fikar_Ibn_Hajar/) |
| **Usool al-Hadith** | **Al-Manzumah al-Bayquniyyah** | Umar ibn Muhammad al-Bayquni | c. 1080 AH | [`06_Matn_al_Usool/02_Usool_al_Hadith/Al_Manzumah_al_Bayquniyyah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/02_Usool_al_Hadith/Al_Manzumah_al_Bayquniyyah/) |
| **Usool al-Fiqh** | **Matn al-Waraqat** | Imam al-Haramayn al-Juwayni | 478 AH | [`06_Matn_al_Usool/03_Usool_al_Fiqh/Matn_al_Waraqat_Juwayni/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/03_Usool_al_Fiqh/Matn_al_Waraqat_Juwayni/) |
| **Usool al-Aqeedah** | **Al-Aqeedah al-Wasitiyyah** | Shaykh al-Islam Ibn Taymiyyah | 728 AH | [`06_Matn_al_Usool/04_Usool_al_Aqeedah/Al_Aqeedah_al_Wasitiyyah_Ibn_Taymiyyah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/04_Usool_al_Aqeedah/Al_Aqeedah_al_Wasitiyyah_Ibn_Taymiyyah/) |
| **Usool al-Aqeedah** | **Lum'at al-I'tiqad** | Muwaffaq al-Din Ibn Qudamah | 620 AH | [`06_Matn_al_Usool/04_Usool_al_Aqeedah/Lumat_al_Itiqad_Ibn_Qudamah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/04_Usool_al_Aqeedah/Lumat_al_Itiqad_Ibn_Qudamah/) |
| **Usool al-Aqeedah** | **Al-Usul al-Thalathah** | Shaykh Muhammad ibn Abd al-Wahhab | 1206 AH | [`06_Matn_al_Usool/04_Usool_al_Aqeedah/Al_Usul_al_Thalathah/`](file:///home/arehman/00-code/00-projects/islamic_classical_library/06_Matn_al_Usool/04_Usool_al_Aqeedah/Al_Usul_al_Thalathah/) |

---

## 7. Comprehensive Text Verification & Quality Assurance Report

The text verification report below is automatically synchronized with [`VERIFICATION_REPORT.md`](file:///home/arehman/00-code/00-projects/islamic_classical_library/VERIFICATION_REPORT.md):

# Islamic Classical Text Library - Text Verification & Quality Assurance Report
> **Generated on**: `2026-10-27 12:31:55 UTC`  
> **Total Files Audited**: `86` files  
> **Audit Result**: **ALL CHECKS PASSED** (`115` passed, `0` failed)

---
## 1. Quran Verification Matrix (القرآن الكريم)
| Edition / Collection | Surahs | Benchmark | Key Verses Checked | Status |
| :--- | :--- | :--- | :--- | :--- |
| `Arabic_Uthmani` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |
| `Bilingual_Arabic_English_Sahih_International` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |
| `Bilingual_Arabic_Urdu_Jalandhry` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |
| `English_Sahih_International` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |
| `English_Yusuf_Ali` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |
| `Urdu_Jalandhry` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |
| `Urdu_Maududi` | **114** | 114 | ✓ Al-Fatiha & Al-Ikhlas | **`PASS`** |

---
## 2. Hadith Collections Verification Matrix (كتب الحديث الشريف)
| Collection | Language | Hadiths Extracted | MD File Size | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Forty_Hadith_Nawawi** | Arabic | **42** | 0.04 MB | **`PASS`** |
| **Forty_Hadith_Nawawi** | English | **42** | 0.03 MB | **`PASS`** |
| **Forty_Hadith_Qudsi** | Arabic | **40** | 0.05 MB | **`PASS`** |
| **Forty_Hadith_Qudsi** | English | **40** | 0.04 MB | **`PASS`** |
| **Forty_Hadith_Shah_Waliullah** | Arabic | **40** | 0.0 MB | **`PASS`** |
| **Forty_Hadith_Shah_Waliullah** | English | **40** | 0.0 MB | **`PASS`** |
| **Jami_at_Tirmidhi** | Arabic | **3,998** | 5.74 MB | **`PASS`** |
| **Jami_at_Tirmidhi** | English | **3,998** | 1.92 MB | **`PASS`** |
| **Jami_at_Tirmidhi** | Urdu | **3,998** | 4.44 MB | **`PASS`** |
| **Muwatta_Malik** | Arabic | **1,858** | 1.75 MB | **`PASS`** |
| **Muwatta_Malik** | English | **1,858** | 1.23 MB | **`PASS`** |
| **Muwatta_Malik** | Urdu | **1,889** | 1.12 MB | **`PASS`** |
| **Sahih_Muslim** | Arabic | **7,563** | 7.35 MB | **`PASS`** |
| **Sahih_Muslim** | English | **7,563** | 3.17 MB | **`PASS`** |
| **Sahih_Muslim** | Urdu | **7,564** | 6.37 MB | **`PASS`** |
| **Sahih_al_Bukhari** | Arabic | **7,589** | 8.39 MB | **`PASS`** |
| **Sahih_al_Bukhari** | English | **7,589** | 4.01 MB | **`PASS`** |
| **Sahih_al_Bukhari** | Urdu | **7,589** | 8.58 MB | **`PASS`** |
| **Sunan_Abi_Dawud** | Arabic | **5,274** | 5.59 MB | **`PASS`** |
| **Sunan_Abi_Dawud** | English | **5,274** | 2.71 MB | **`PASS`** |
| **Sunan_Abi_Dawud** | Urdu | **5,274** | 4.38 MB | **`PASS`** |
| **Sunan_Ibn_Majah** | Arabic | **4,343** | 4.13 MB | **`PASS`** |
| **Sunan_Ibn_Majah** | English | **4,343** | 1.9 MB | **`PASS`** |
| **Sunan_Ibn_Majah** | Urdu | **4,343** | 2.96 MB | **`PASS`** |
| **Sunan_an_Nasai** | Arabic | **5,765** | 5.42 MB | **`PASS`** |
| **Sunan_an_Nasai** | English | **5,765** | 2.07 MB | **`PASS`** |
| **Sunan_an_Nasai** | Urdu | **5,765** | 3.06 MB | **`PASS`** |

---
## 3. Classical Tafsir Verification Matrix (كتب التفسير)
| Tafsir Edition | Language | Surahs Verified | Surah 1 Verified | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Asbab_al_Nuzul_Wahidi [English]** | Multi | **75** | ✓ Verified | **`PASS`** |
| **Fath_al_Qadir_Shawkani [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Maarif_ul_Quran [English]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_Ibn_Kathir [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_Ibn_Kathir [English]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_Ibn_Kathir [Urdu]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Baghawi [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Jalalayn [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Jalalayn [English]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Kashshaf_Zamakhshari [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Qurtubi [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Razi [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_al_Tabari [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_as_Sadi [Arabic]** | Multi | **114** | ✓ Verified | **`PASS`** |
| **Tafsir_as_Sadi [Urdu]** | Multi | **114** | ✓ Verified | **`PASS`** |

---
## 4. Classical Hadith Commentaries Matrix (شروح كتب السنة)
| Commentary | Target Collection | Word Count | File Size (MD) | Status |
| :--- | :--- | :--- | :--- | :--- |
| **01_Fath_al_Bari_Ibn_Hajar** | Kutub al-Sittah | **3,310,311 words** | 28.79 MB | **`PASS`** |
| **02_Al_Minhaj_Nawawi** | Kutub al-Sittah | **774,142 words** | 6.87 MB | **`PASS`** |
| **03_Maalim_al_Sunan_Khattabi** | Kutub al-Sittah | **346,853 words** | 2.98 MB | **`PASS`** |
| **04_Sharh_Ilal_Tirmidhi_Ibn_Rajab** | Kutub al-Sittah | **38,802 words** | 0.28 MB | **`PASS`** |
| **05_Sharh_Sunan_Nasai_Suyuti** | Kutub al-Sittah | **89,935 words** | 0.8 MB | **`PASS`** |
| **06_Misbah_al_Zujajah_Suyuti** | Kutub al-Sittah | **234,987 words** | 2.08 MB | **`PASS`** |
| **07_Al_Qabas_Sharh_Muwatta_Ibn_Arabi** | Kutub al-Sittah | **209,573 words** | 1.83 MB | **`PASS`** |
| **08_Jami_al_Ulum_wal_Hikam_Ibn_Rajab** | Kutub al-Sittah | **187,277 words** | 1.64 MB | **`PASS`** |

---
## 5. Classical Turath Treatises Matrix (كتب التراث والعلوم الشرعية)
| Classical Treatise | Arabic Words | English Included | Status |
| :--- | :--- | :--- | :--- |
| **01_Aqeedah_Tahawiyyah** | **2,563 words** | Yes (Verified) | **`PASS`** |
| **02_Al_Fiqh_al_Akbar** | **1,863 words** | Yes (Verified) | **`PASS`** |
| **03_Al_Wasiyyah_Abu_Hanifa** | **2,514 words** | Yes (Verified) | **`PASS`** |
| **04_Al_Risala_Shafii** | **72,196 words** | Arabic Critical Text | **`PASS`** |
| **05_Sharh_al_Sunnah_Barbahari** | **7,945 words** | Arabic Critical Text | **`PASS`** |
| **06_Bidayat_al_Hidayah_Ghazali** | **15,125 words** | Arabic Critical Text | **`PASS`** |
| **07_Al_Munqidh_min_al_Dalal** | **11,792 words** | Arabic Critical Text | **`PASS`** |
| **08_Qawaid_al_Aqaid_Ghazali** | **20,218 words** | Arabic Critical Text | **`PASS`** |

---
## 6. Matn al-Usool Verification Matrix (متون أصول العلوم الشرعية)
| Discipline / Primer | Word Count | English Included | Status |
| :--- | :--- | :--- | :--- |
| **01_Usool_al_Tafsir/Muqaddimah_fi_Usul_al_Tafsir_Ibn_Taymiyyah** | **9,434 words** | Arabic Matn | **`PASS`** |
| **02_Usool_al_Hadith/Al_Manzumah_al_Bayquniyyah** | **765 words** | Yes (Verified) | **`PASS`** |
| **02_Usool_al_Hadith/Nukhbat_al_Fikar_Ibn_Hajar** | **2,341 words** | Arabic Matn | **`PASS`** |
| **03_Usool_al_Fiqh/Matn_al_Waraqat_Juwayni** | **1,901 words** | Yes (Verified) | **`PASS`** |
| **04_Usool_al_Aqeedah/Al_Aqeedah_al_Wasitiyyah_Ibn_Taymiyyah** | **5,067 words** | Yes (Verified) | **`PASS`** |
| **04_Usool_al_Aqeedah/Al_Usul_al_Thalathah** | **2,945 words** | Yes (Verified) | **`PASS`** |
| **04_Usool_al_Aqeedah/Lumat_al_Itiqad_Ibn_Qudamah** | **4,315 words** | Arabic Matn | **`PASS`** |

---

## 8. Licensing, Scholarly Provenance & Upstream Repositories

| Domain | Sponsoring Authority | License Terms | Persistent Link |
| :--- | :--- | :--- | :--- |
| **Quran Arabic** | King Fahad Complex (Medina) | Public Domain (ملك عام) | [qurancomplex.gov.sa](https://qurancomplex.gov.sa) |
| **Quran Tanzil** | Tanzil Project (Zarrabi-Zadeh et al.) | Creative Commons BY 3.0 | [tanzil.net/docs/license](http://tanzil.net/docs/license) |
| **Hadith Datasets** | Fawaz Ahmed & Sunnah.com | MIT Open Software / Public Domain | [github.com/fawazahmed0/hadith-api](https://github.com/fawazahmed0/hadith-api) |
| **Tafsir Corpus** | spa5k Academic API | MIT License | [github.com/spa5k/tafsir_api](https://github.com/spa5k/tafsir_api) |
| **Classical Shuruhaat** | OpenITI (Harvard / Leipzig / AKU) | CC-BY-SA 4.0 / DOI: 10.5281/zenodo.3083417 | [github.com/OpenITI](https://github.com/OpenITI) |
| **Turath & Matn al-Usool** | OpenITI Corpus | CC-BY-SA 4.0 | [github.com/OpenITI](https://github.com/OpenITI) |

---

## 9. Automation & Quality Assurance Pipeline
The library's acquisition, interlinear alignment, and structural verification were executed through a standardized processing and quality-assurance pipeline:
* **Interlinear Alignment**: Verses from the Uthmanic Mushaf are synchronized Ayah-by-Ayah with prominent translations into dual bilingual editions.
* **Corpus Ingestion**: Classical OpenITI and Hadith-API texts were parsed, enriched with standardized YAML frontmatter, and verified across all volumes.
* **Automated Quality Audit**: Multi-stage verification suite auditing file integrity, non-empty assertions, UTF-8 compliance, verse/hadith counts, and backlink fidelity.

---

## 🔗 Sister Libraries & Dedicated Collections
- 🌟 **[Library: The Golden Chain (مكتبة السلسلة الذهبية)](../library-the-golden-chain/README.md)**:
  Dedicated 211-work sister library collecting the complete classical Arabic corpus and English translations of:
  - **Shaykh al-Islam Ahmad ibn Taymiyyah (661–728 AH)** [124 Arabic + 6 English works]
  - **Imam Shams al-Din Ibn Qayyim al-Jawziyyah (691–751 AH)** [44 Arabic + 3 English works]
  - **Al-Hafidh Zayn al-Din Ibn Rajab al-Hanbali (736–795 AH)** [29 Arabic + 5 English works]
  - Verified test report: [`VERIFICATION_REPORT.md`](../library-the-golden-chain/VERIFICATION_REPORT.md) | Catalog: [`CATALOG.json`](../library-the-golden-chain/CATALOG.json)
