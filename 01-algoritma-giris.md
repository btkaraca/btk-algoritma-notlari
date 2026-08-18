# Algoritma Giriş

BTK Akademi Algoritma ve Veri Yapıları ders notları.

---

## Algoritma Nedir?

Bir problemi çözmek veya belirli bir amaca ulaşmak için uygulanan **sıralı ve mantıksal adımlardır.**

---

## Algoritmaların Genel Özellikleri

Bir algoritmanın geçerli olabilmesi için şu temel özellikleri taşıması gerekir:

1.  **Başlangıcı ve sonu olur:** Her algoritmanın bir başlangıç noktası ve sonlu bir bitişi vardır.
2.  **Açık ve anlaşılır olmalıdır:** Adımlar kesin ve net olmalı, yoruma açık olmamalıdır.
3.  **Kararsız kalmamalıdır:** Algoritma bir sonraki adımın ne olacağını tam olarak bilmelidir.
4.  **Sistematiği olmalıdır:** Adımlar birbiri ardına, mantıksal bir sıra ile (adım adım) gösterilmelidir.
5.  **Etkili ve verimli olmalıdır:** Çözüme giden en kısa, en az maliyetli ve en mantıklı yol tercih edilmelidir.
6.  **Kaynak tüketimi dikkate alınmalıdır:** Donanım (bellek, işlemci) kaynakları verimli kullanılacak şekilde tasarlanmalıdır.

---

## Algoritmanın Matematikteki Yeri ve Operatörler

Algoritmalarda karşılaştırma ve karar verme yapıları kurmak için matematiksel ve mantıksal operatörler kullanılır. Aşağıdaki tabloda C# dilindeki semboller gösterilmiştir:

| Operatör | Anlamı | C# Dilinde Sembolü |
| :--- | :--- | :---: |
| `and` (VE) | İki koşulun da sağlanması gerekir. | `&&` |
| `or` (VEYA) | Koşullardan en az birinin sağlanması yeterlidir. | `\|\|` |
| `not` (DEĞİL) | Koşulun tersini alır (doğruysa yanlış yapar). | `!` |

**Örnek Karşılaştırma Mantığı:**

*   `x == y` (x, y'ye eşit mi?)
*   `x != y` (x, y'den farklı mı?)
*   `x < y` (x, y'den küçük mü?)
*   `x > y` (x, y'den büyük mü?)

> **Not:** Algoritmalar, matematiğin temelindeki fonksiyon mantığına benzerlik gösterir; bir girdi alır, işlem yapar ve bir çıktı üretir.



# Kaba Kod (Pseudocode)
Makinenin değil insanın anlayacağı şekilde basit olmalıdır.


* **Yapı:** Yapılandırılmış bir metin biçimidir; doğrudan çalıştırılabilir bir bilgisayar programı değildir.
* **Amaç:** Bir veri yapısının veya algoritmanın üst düzey mantıksal analizini ve tasarımını kolaylaştırır.
* **Hedef Kitle:** Bilgisayar veya derleyici için değil, insan zihninin kolayca kavrayabileceği sadelikte yazılır.
# ardısikSayilarinToplami (n)

* **Problem Tanımı:** Limit olarak klavyeden belirtilen bir $n$ sayısına kadar olan ardışık sayıların toplamı için kaba kod tasarımı.



**Algoritma** *ardisikSayilarinToplami ($n$)*  
* **Giriş:** Limit değerini temsil eden $n$ sayısı.  
* **Çıkış:** Toplam sonucu  

```text
n değerini oku
i ← 0
toplam ← 0

while i ≤ n do
    toplam ← toplam + i
    i ← i + 1
end while

Toplamı yaz

