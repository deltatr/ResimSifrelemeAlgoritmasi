# ResimSifrelemeAlgoritmasi

Merhabalar, Kendi yeteneklerimi test etmek için yapmış olduğum JavaScript kod alt yapılı, resimleri şifreleyebilen basit bir algoritma yazdım. Genel olarak piyasadaki resim şifreleme uygulamalarına benzetmiyorum çünkü her resme otomatik olarak kendine has bir kod betiği verir RFC 7519 JWT olarak da düşünebiliriz ve bu kod betiğini generate edip resme gömülmesine ve bu gömülen kod betiğinin çözülmesiyle tekrardan resim orjinal haliyle gözükebilmektedir

Kodlarımızda kullandığımız canvas etiketi ile grafiksel çizim yapabiliriz örn. gradient, renkli çizimler, dairesel, vb. gibi bu kombinasyonları kullanarak ve özellikle renkleri kullanarak şifreleme işlemlerini gerçekleştirir

Resim dosyasını upload ettikten sonra şifrlenemiş dosya karşınıza gelir, şifrelenmiş dosyayı tekrar upload ederseniz token çözülür yani resmin şifresi çözülür ve dosya eski haline döner

