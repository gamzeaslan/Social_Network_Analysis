# SOCIAL NETWORK ANALYSIS PROJESİ

* Projeye ait kodlar CodeFile dosyası içerisinde
* Projeye ait dökümanlar Document içerisinde
* Projede kullanılan veri seti DataSet içerisinde
  
## Proje Amacı
* Bu proje, sosyal ağ analizi üzerine odaklanarak, bir Graph Neural Network (GNN) modeli kullanarak sosyal ağdaki düğümler üzerinden bir öneri sistemi geliştirmeyi amaçlamaktadır. Bu sistem, ağa katılan herhangi bir kişi için en öncelikli 10 kişiyi tahmin edip öneren bir yapıya sahiptir.

## Veri Seti Hakkında
* Bu proje kapsamında kullanılan veri seti, Stanford Üniversitesi'nin SNAP (Stanford Network Analysis Project) platformundan alınmıştır. Veri seti, Facebook'a ait veriler içermekte ve sosyal ağ analizi için uygun yapıdadır. Veri setinde beş tip dosya bulunmaktadır:

  * circles Dosyaları: Ego kullanıcısının çemberlerini içerir. Her bir çember, kullanıcıların belirli bir grup içinde nasıl gruplandırıldığını gösterir ve sosyal ağdaki toplulukları veya grupları analiz etmek için kullanılır.
  * edges Dosyaları: Kullanıcılar arasındaki bağlantıları (kenarları) içerir. Her satır, iki kullanıcı arasındaki bir bağlantıyı temsil eder.
  * egofeat Dosyaları: Ego kullanıcısının özelliklerini içerir. Bu özellikler, ego kullanıcısının profiline özgüdür ve diğer kullanıcılarla karşılaştırmak için kullanılabilir.
  * feat Dosyaları: Ağdaki her bir düğümün özelliklerini içerir. Bu özellikler, düğümlerin profilleriyle ilişkilendirilebilir ve kullanıcıların belirli özelliklerini temsil eder.
  * featnames Dosyaları: Özellik isimlerini içerir ve özelliklerin neyi temsil ettiğini anlamaya yardımcı olur.

## Proje Adımları
* Veri Setinin İçe Aktarılması: Proje, SNAP platformundan indirilen veri setinin işlenmesiyle başlar.
* Graf Yapısının Oluşturulması: İçe aktarılan veriler kullanılarak bir graf yapısı oluşturulur ve düğümler arasındaki bağlantılar belirlenir.
* GNN Modelinin Oluşturulması ve Eğitilmesi: GNN modeli tanımlanır ve eğitilir. Model, düğümler arasındaki ilişkileri öğrenir ve öneri sistemi için kullanılır.
* Modelin Test Edilmesi: Eğitim tamamlandıktan sonra, modelin performansı test edilir ve doğrulanır.
* Neo4j Entegrasyonu: Oluşturulan graf yapısı ve model, Neo4j veritabanına entegre edilir. Bu sayede, dinamik olarak yeni düğümler ve bağlantılar eklenip çıkarılabilir.
* Öneri Sisteminin Uygulanması: Yeni bir kişi ağa katıldığında, model kullanılarak bu kişiye en uygun 10 kişi önerilir.
## Sonuç
* Bu proje, sosyal ağ analizi ve öneri sistemleri alanında önemli bir adım olup, GNN modeli kullanılarak sosyal ağlarda etkili ve doğru önerilerde bulunmayı amaçlamaktadır. Proje, veri bilimi ve makine öğrenimi tekniklerini kullanarak sosyal ağlar üzerinde derinlemesine analizler yapmayı hedeflemektedir.

# Kaynaklar
* Stanford SNAP Platformu: https://snap.stanford.edu/data/
