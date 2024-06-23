# ZkSNARK "Tarifi"

ZkSNARK'ları karmaşık bir tarif olarak düşünün, üç temel bileşen içeriyor:

1. **Sorun:** Bu kanıtlamak istediğiniz ifadedir. Örneğin, bir finansal işlemde "Yeterli bakiyeye sahibim" olabilir.

2. **Şahit:** Bu, gizli malzemenizdir, ifadenin doğru olduğunu kanıtlamanıza izin veren bilgidir. Örneğimizde şahit, gerçek hesap bakiyeniz olurdu.

3. **ZkSNARK "Araç Kutusu":** Bu, ZkSNARK'ların kullandığı kriptografik araçlar ve algoritmaları ifade eder. Bu araçlar, eliptik eğriler ve polinom taahhütleri gibi ileri düzey konseptleri içerir, ancak temel fikir şudur:

   - **Sorunun Dönüştürülmesi:** ZkSNARK sistemi, sorun ifadesini (örneğin, yeterli bakiyeye sahip olmak) karmaşık bir matematik denklemine dönüştürür.

   - **Şahit, Çözüm Gibi:** Gizli şahit (hesap bakiyeniz), bu denklem için benzersiz bir çözüm olarak işlev görür. Bu, ifadenin doğruluğunu açan gizli bir anahtar gibi düşünülebilir.

   - **Kanıt, Şahit Değil:** Gizli şahidi (hesap bakiyenizi) ortaya çıkarmak yerine, ZkSNARK sistemi size bir kriptografik kanıt üretmenize yardımcı olur. Bu kanıt, gerçek çözümü ortaya çıkarmadan (hesap bakiyeniz) denklemin bir çözümü olduğuna ikna eden matematiksel bir el sıkışması gibi işlev görür.

Bunu şöyle düşünün: Bir kilidin açmak için belirli bir anahtara sahip olduğunuzu kanıtlamak, ancak anahtarı kendisini göstermeden. ZkSNARK'lar, bir matematiksel "el sıkışması" oluşturarak size anahtarı (şahidi) göstermeden birini ikna etmenizi sağlar.



**Önemli Not:** Bu bölümde, eliptik eğriler, polinom taahhütleri ve diğer kriptografik kavramların teknik detaylarına girmedik. Ancak, ZkSNARK'ların matematik gücünü kullanarak etkileyici bir şekilde sıkıştırılmış ve verimli sıfır bilgi kanıtları sağladığına dair temel bir anlayış sunar.

Daha derinlere dalmak isteyenler için: ZkSNARK'ların kriptografik temellerine dair birçok kaynak bulunmaktadır. Matematiksel karmaşaya dalıp keşfetmeye hazırsanız, kendi araştırmalarınızı yapabilir ve daha fazla bilgi edinebilirsiniz!
