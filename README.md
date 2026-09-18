# Modern Arama Teknolojileri: BM25, Semantic ve Hybrid

[Canlı siteyi aç]([https://ismntr.github.io/-BM25-Semantic-Hybrid-Search/](https://ismntr.github.io/-BM25--Semantic--Hybrid-Search/modern_arama_teknolojileri.html) (Projenin GitHub deposunun adına göre bağlantıyı güncelleyin)

Modern arama teknolojileri olan BM25, Semantic (Anlamsal) ve Hybrid (Hibrit) arama kavramlarını Türkçe, görsel ve etkileşimli örneklerle anlatan tek sayfalık eğitim rehberi.

**Açıklama:** Türkçe, görsel ve etkileşimli arama teknolojileri eğitim rehberi.
**Konular:** bm25 semantic-search hybrid-search vector-database tf-idf nlp search-engine html javascript

## İçerik
- BM25 (En İyi Eşleşme 25) algoritması ve TF-IDF
- Semantic (Anlamsal) arama, Vektör Veritabanları ve Embeddings
- Hybrid (Hibrit) arama ve skor birleştirme (Alpha / RRF)
- Etkileşimli simülatör ile canlı arama testleri
- Teknolojilerin avantajları, dezavantajları ve kullanım senaryoları

## GitHub Pages ile yayınlama

Aşağıdaki anlatım GitHub ve Git kullanmaya yeni başlayanlar içindir. Yayınlamak için terminal kullanmanız gerekmez.

### 1. GitHub hesabı oluşturun
1. [github.com](https://github.com/) adresini açın.
2. Sağ üstteki **Sign up** düğmesine tıklayın.
3. E-posta adresinizle ücretsiz bir hesap oluşturun.
4. E-posta doğrulamasını tamamlayıp hesabınıza giriş yapın.

### 2. Yeni bir depo oluşturun
1. GitHub’da sağ üstteki **+** simgesine, ardından **New repository** seçeneğine tıklayın.
2. **Repository name** alanına `BM25-Semantic-Hybrid-Search` gibi bir isim yazın.
3. İsterseniz **Description** alanına `Modern arama teknolojileri rehberi` yazın.
4. **Public** seçeneğini işaretli bırakın. Açık kaynak paylaşım için depo herkese açık olmalıdır.
5. **Add a README file**, **.gitignore** ve lisans seçeneklerini bu aşamada boş bırakın. Bu projede bu dosyalar zaten bulunmaktadır.
6. **Create repository** düğmesine tıklayın.

### 3. Proje dosyalarını GitHub’a yükleyin
1. Yeni açılan deponun ana sayfasında **Add file > Upload files** seçeneğine tıklayın.
2. Bilgisayarınızdaki proje klasörünü açın (`-BM25, Semantic, Hybrid Search`).
3. Aşağıdaki dosyaların tamamını seçip GitHub’daki yükleme alanına sürükleyin:
   - `index.html`
   - `modern_arama_teknolojileri.html`
   - `README.md`
   - `LICENSE`
   - `.nojekyll`
4. `.git` klasörünü yüklemeyin. Bu klasör görünmüyorsa sorun değildir; GitHub kendi Git geçmişini oluşturur.
5. Sayfanın altındaki **Commit changes** bölümünde açıklama olarak `İlk sürüm` yazın.
6. **Commit changes** düğmesine tıklayın. Dosyalar artık GitHub deponuzdadır.

### 4. GitHub Pages’i etkinleştirin
1. Depo sayfasında üst menüden **Settings** sekmesine tıklayın.
2. Sol menüde **Pages** seçeneğini bulun ve açın. Gerekirse sol menüde **Code and automation** başlığını genişletin.
3. **Build and deployment** bölümündeki **Source** menüsünde **Deploy from a branch** seçin.
4. **Branch** menüsünde `main`, klasör menüsünde `/ (root)` seçin.
5. **Save** düğmesine tıklayın.
6. GitHub birkaç dakika içinde sitenizi yayınlar. Aynı Pages ekranında görünen bağlantıya tıklayın.

Site adresi genellikle şu biçimde olur:
`https://<kullanici-adiniz>.github.io/<depo-adiniz>/`

İlk açılışta birkaç dakika boyunca eski veya boş bir sayfa görünürse biraz bekleyip sayfayı yenileyin. GitHub Pages’in yayınlama işlemi tamamlanmamış olabilir.

### 5. Daha sonra yaptığınız değişiklikleri yayınlama
1. GitHub deponuzda değiştirmek istediğiniz dosyayı açın.
2. Sağ üstteki kalem simgesine (**Edit this file**) tıklayın.
3. Değişiklikleri yapın.
4. Sayfanın altına inip **Commit changes** düğmesine tıklayın.
5. GitHub Pages birkaç dakika içinde güncel siteyi otomatik yayınlar.

Bilgisayarınızdaki dosyayı değiştirdiyseniz **Add file > Upload files** yoluyla aynı dosyanın yeni sürümünü tekrar yükleyebilirsiniz. Dosya adı aynıysa GitHub eski dosyanın üzerine yeni sürümü koyar.

### Yayınlanmazsa kontrol listesi
- Depo **Public** mı?
- `index.html` depo kökünde mi, başka bir klasörün içinde mi?
- Pages ayarında dal `main`, klasör `/ (root)` olarak mı seçildi?
- Dosya yükleme işleminden sonra **Commit changes** düğmesine tıklandı mı?
- Sayfayı birkaç dakika bekledikten sonra yenilediniz mi?

## Yerel çalıştırma
Dosyayı doğrudan tarayıcıda açabilir veya basit bir statik sunucu kullanabilirsiniz:
```bash
python -m http.server 8000
```
Ardından [http://localhost:8000](http://localhost:8000/) adresini açın.

## Teknolojiler
- HTML5 ve vanilla JavaScript
- Tailwind CSS CDN
- Font Awesome CDN
- Google Fonts CDN

Derleme veya paket kurulumu gerektirmez. CDN kaynaklarını kullanabilmek için yayın ortamında internet bağlantısı gerekir.

## Önemli not
Sayfadaki BM25, Semantic ve Hybrid arama akışları eğitim amaçlı simülasyondur. Gerçek uygulamalarda Vektör Veritabanları (Milvus, Pinecone vb.) ve Arama Motorları (Elasticsearch, Solr vb.) arka planda kullanılmalıdır.

## Katkı
Katkılar memnuniyetle karşılanır. Değişiklik öncesinde bir issue açabilir veya doğrudan pull request gönderebilirsiniz. İçerik katkılarında teknik doğruluk ve anlaşılır Türkçe gözetilmelidir.

## Lisans
Bu proje [MIT License](LICENSE) ile lisanslanmıştır.
