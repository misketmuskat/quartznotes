Up: [[014_embedded-meaning]]

**Title:** Exploring the Role of Gender in 19th Century Fiction Through the Lens of Word Embeddings

## Notes:
- Makale 19. yüzyıl İngiliz ve İrlanda edebiyatındaki toplumsal cinsiyet rollerini word embeddings modeliyle inceliyor:
	- Kadın ve erkek yazarların eserlerindeki dilsel farklar karşılaştırılıyor.
- **Neye dikkat edilmiş?**
	- Kadın ve erkek yazarların toplumsal cinsiyetle ilişkili kelimeleri (zamirler, sıfatlar, meslekler) nasıl kulandığını karşılaştırmak.
	- Yöntemsel olarak *distant reading* / in contrast to *close reading*
- **Word Embeddings ve Gender:**
	- Makale, word embeddings modellerinin, kelimeler arasındaki *bağlam ilişkilerini sayısal olarak temsil etme* yeteneğinden faydalanıyor.
- **Veri Hazırlığı**
	- Romanlar, Project Gutenberg gibi açık kaynaklardan alınıp **manuel olarak** işlenmiş.
	- Karakter isimleri, zamirler ve toplumsal cinsiyetle ilişkili kelimeler **manuel olarak** etiketlenmiş.
- **Word Embeddings Modeli:**
	- **Skip-Gram:** Bu model, bir kelimenin bağlamındaki kelimeleri tahmin etmek için çalışır ve kelimelerin anlamını matematiksel bir vektörle ifade eder.
	- **Kullanılan parametreler:**
		- 300 boyutlu bir vektör uzayı,
		- 5 kelimelik bir bağlam penceresi
		- Minimum kelime sıklığı: 50
	- Bu model, zamirler gibi toplumsal cinsiyetle ilişkili kelimelerin bağlamlarını yakalamak için kullanılmış. Örneğin, "she" kelimesinin etrafında hangi kelimeler sıklıkla yer alıyor?
- **Kelime Vektörlerinin Görselleştirilmesi:**
	- 300 boyutlu kelime vektörlerini görselleştirmek için **t-Distributed Stochastic Neighbor Embedding (t-SNE)** kullanılmış.
		- Bu yöntem, yüksek boyutlu verileri 2D veya 3D bir uzaya indirerek insan gözüyle daha kolay anlaşılabilir hale getiriyor.
- **Bağlam Benzerliği (Cosine Similarity)**
	- Kadın ve erkek yazarların aynı kelimeleri nasıl farklı bağlamlarda kullandığını analiz etmek için **cosine similarity** yönetmini kullanmış.
		- Bu, iki kelimenin vektörlerinin birbirine ne kadar benzediğini ölçen bir yöntem. 1'e yakın değerler benzer bağlamları gösterirken, 0'a yakın değerler farklı bağlamları gösteriyor.
		- **Örnek:** "husband" kelimesi, erkek ve kadın yazarlar tarafından hangi bağlamlarda kullanılıyor?
- **Sonuçlar:**
	- **Zamir analizi:**
		- Erkek yazarların metinlerinde "he" zamiri, kadın yazarların metinlerine kıyasla çok daha fazla yer alıyor
		- Kadın yazarlar ise "she" zamirini daha sık kullanmış
		- Bu durum, erkek yazarların metinlerinde erkek karakterlere, kadın yazarların ise kadınlara yer verdiğini gösteriyor
	- **Cinsiyetle İlişkili Kelimelerin Bağlamları:**
		- Kadın yazarların metinlerinde, *kadın karakterlerle ilişkili kelimeler (wife, daughter) genellikle aile bağlarına vurgu yaparken*, erkek yazarların metinlerinde *erkek karakterlerle ilişkili kelimeler (husband, son) daha bireysel bağlamlarda* kullanılmış.
		- Örneğin, *husband* kelimesi, erkek yazarlar için **bir statü göstergesi** (sosyal bir pozisyon), kadın yazarlar içinse **kişisel bir ilişki** bağlamında ele alınmış.
	- **Bağlamsal Analiz Sonuçları (Cosine Similarity)**
		- Bazı kelimelerin benzer bağlamlarda kullanıldığı, bazılarının ise farklı anlam çağrışımları olduğu gözlenmiş
			- Örneğin *fellow* kelimesi her iki grup için de benzer bağlamlara sahip, ama *husband* kelimesi oldukça farklı bağlamlarda yer alıyor
			- 