UV Editing ve Wrapping İşlemleri – Blender
1. Giriş
3D modelleme sürecinde, modellerin üzerine doku (texture) kaplamak için UV Mapping işlemi büyük önem taşır. UV Mapping, bir 3B modelin yüzeyinin 2B bir düzleme açılması işlemidir. Bu işlem sayesinde, dokular modelin yüzeyine doğru ve düzgün bir şekilde uygulanabilir. Blender gibi 3B modelleme yazılımları, bu işlemi kullanıcıya hem otomatik hem de manuel olarak gerçekleştirme imkânı sunar. UV Editing ise bu süreçte oluşturulan UV haritalarının düzenlenmesi işlemidir.

2. UV Mapping Nedir?
UV Mapping, 3B bir nesnenin yüzey koordinatlarının, 2B bir düzlemde temsil edilmesini sağlar. Bu işlem sırasında, 3B modelin yüzeyi "unwrap" edilir, yani adeta bir kağıt gibi açılarak düzleştirilir. Bu düzleştirme sonucunda ortaya çıkan UV haritası üzerinde 2B dokular, modelin ilgili bölgelerine denk gelecek şekilde yerleştirilir.

Not: “UV” terimi, 2B koordinat sistemindeki yatay ve dikey eksenleri temsil eden U ve V harflerinden gelir. Bu, 3B uzaydaki X, Y, Z eksenlerinden ayırt edilmesini sağlar.

3. Blender’da UV Wrapping İşlemi
Blender’da UV unwrap işlemi şu adımlarla gerçekleştirilir:

Model Seçimi ve Edit Mode: 3B model seçilerek Tab tuşu ile Edit Mode’a geçilir.

Yüzey Seçimi: A tuşu ile tüm yüzeyler seçilir.

Unwrap Komutu: U tuşuna basılarak açılan menüden uygun unwrap yöntemi seçilir. Blender’da yaygın kullanılan unwrap yöntemleri:

Unwrap: Manuel olarak belirlenen seam’lara göre çalışır.

Smart UV Project: Otomatik unwrap için kullanılır.

Cube/Cylinder/Sphere Projection: Belirli geometrilere uygun unwrap seçenekleri.

Seam Belirleme (Opsiyonel): Edge Select modunda seçilen kenarlara Ctrl + E > Mark Seam komutu verilerek modelin nerelerden kesileceği belirlenebilir. Bu işlem daha düzgün ve optimize UV haritaları oluşturmak için kullanılır.

4. UV Editing İşlemi
Unwrap işlemi tamamlandıktan sonra, Blender arayüzünde UV Editing sekmesine geçilerek UV haritası düzenlenir. Bu ekranda:

3B model sağ panelde görüntülenirken,

Sol panelde UV haritasının 2B açılımı yer alır.

Kullanıcı bu harita üzerinde yüzeyleri taşıyabilir, ölçeklendirebilir ve döndürebilir. Bu sayede doku, istenilen alanlara hizalanabilir. UV Editing işlemi, dokuların model üzerinde düzgün görünmesi için kritik bir adımdır.