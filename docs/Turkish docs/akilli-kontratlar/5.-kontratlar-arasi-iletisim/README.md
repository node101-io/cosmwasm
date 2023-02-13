# 5. Kontratlar Arası İletişim

Tek bir izole edici kontrat oluşturma konusunu zaten ele almıştık. Ancak SOLID ilkeleri bize varlıkların tek bir sorumluluğa sahip olmaları gibi mümkün olduğunca küçük olmaları gerektiğini söylüyor. Şu anda odaklandığımız varlıklar akıllı kontratlardır ve her akıllı kontratın ilgilendiği [tek bir sorumluluğu](https://en.wikipedia.org/wiki/Single-responsibility\_principle) olduğundan emin olmak istiyoruz.

Ancak akıllı kontratları kullanarak karmaşık sistemler de inşa etmek istiyoruz. Bunu yapmak için, aralarında iletişim kurabilmemiz gerekiyor. Bir aktör modeli kullanarak böyle bir iletişimin neye benzediğinden zaten bahsetmiştik. Şimdi bu bilgiyi pratikte kullanmanın zamanı geldi.

Bu bölümde, getirdiğim sorunu çözmek için önceden oluşturulmuş admin grubu modelini geliştireceğiz - daha büyük bağış parçaları almak için tek bir admin tarafından kendi birden fazla adresini ekleme olasılığı.

Ayrıca adminlere admin olmanın yanı sıra yapacakları bazı işler de vereceğiz.

