# Giriş

Bu kitap CosmWasm akıllı kontratları oluşturmak için bir rehberdir. Sizi adım adım yönlendirecek ve ilgili konuları en kolaydan en zor olana kadar açıklayacaktır.

Kitabın amacı size sadece akıllı kontratlar API'sini anlatmak değil, aynı zamanda bunu temiz ve sürdürülebilir bir şekilde nasıl yapacağınızı göstermektir. Size CosmWasm yaratıcılarının oluşturduğu ve kullanmanızı teşvik ettiği kalıpları göstereceğiz.

### [Ön Gereksinimler](./#prerequirements) <a href="#prerequirements" id="prerequirements"></a>

Bu kitap CosmWasm akıllı kontratlarını incelemektedir. Bu bir Rust eğitimi değildir ve temel Rust bilgisini varsayar. Muhtemelen bu kitapla birlikte öğreneceğiniz için, önce dilin kendisini kavramanızı önemle tavsiye ederim. Rust ile başlamak için mükemmel kaynakları [Learn Rust](https://www.rust-lang.org/learn) sayfasında bulabilirsiniz.

### [CosmWasm API dokümantasyonu](./#cosmwasm-api-dokuemantasyonu)

Bu kılavuz benzeri bir dokümantasyondur. API dokümantasyonu arıyorsanız, aşağıdakilerden birini kontrol etmek ilginizi çekebilir:

* [cosmwasm-std](https://crates.io/crates/cosmwasm-std)
* [cw-storage-plus](https://crates.io/crates/cw-storage-plus)
* [cw-multi-test](https://crates.io/crates/cw-multi-test)
* [cw-utils](https://crates.io/crates/cw-utils)
* [sylvia framework](https://crates.io/crates/sylvia)

### [Kitaba katkıda bulunmak için](./#kitaba-katkida-bulunmak-icin)

Bu kitap [Github](https://github.com/CosmWasm/book)'da tutulmakta ve oradan otomatik olarak dağıtılmaktadır. Herhangi bir [hata](https://github.com/CosmWasm/book/issues), bug veya belirsizlik bulursanız lütfen bir sorun veya çekme talebi oluşturun.

