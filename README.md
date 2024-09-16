Datathon 2024 Ana Görev:

Verilerde Girişimcilik Vakfı'nın 2014 yılından itibaren aldığı başvuruları ve Değerlendirme Puanı isimli kolonu gözlemleyebilirsiniz (train.csv). Bu dosyanın içerisinde aynı zamanda başvuran kişilerin anonim olarak paylaşılmış üniversite, aile detayları, ikamet detayları vb. bir çok bilgiyi gözlemleyebilirsiniz.

2023 yılında başvuran 11.049 kişinin ise Değerlendirme Puanı kolonu hariç yeniden tüm verilerini bulabilirsiniz (test_x.csv). Görevimiz bu 11.049 kişinin Değerlendirme Puanı isimli kolonunu tahmin etmektir.

Örnek submission dosyasında olduğu gibi id,Degerlendirme Puani isimli 2 kolondan oluşan submission dosyanızda 11.049 kişinin skorları yer almalıdır (sample_submission.csv). 11.049 kişinin id'leri test_x.csv dosyasında olduğu sırayla verilmelidir.

Evaluation:

Bu yarışma, her bir örnek verinin Değerlendirme Puanını doğru bir şekilde tahmin etmeyi amaçlamaktadır. Yarışmanın başarısını ölçmek için kullanılacak metrik ise RMSE olacaktır.

Kök ortalama kare sapma veya kök ortalama kare hata (RMSE), bir yanda gerçek ya da tahmin edilen değerler ile diğer yanda gözlemlenen değerler ya da bir tahmin edici arasındaki farkların yakından ilişkili ve sıklıkla kullanılan iki ölçümünden biridir.

Sonuç:

11.049 kişinin degerlendirme puanını tahmin ettiğimiz bu yarışmada, "6.0063668338" RMSE skoru ile 364 kişinin yarıştığı bu yarışmada 68. olarak tamamladım. 
