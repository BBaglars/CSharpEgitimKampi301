<h3>🚀 C# Eğitim Kampı 301 🚀</h3>

🎈 Projede Code First yapısının kullanıldığı ve Katmanlı Mimari alanı için oluşturulmuş bir bölüm mevcut.
    Bu kısımda Entitiy Framework ile oluşturduğumuz varlıkları migration yapısı ile veritabanında tabloları oluşturduk.
    Katmanlar:
    <ul>
      <li>Entity layer</li>
      <li>Data Access Layer</li>
      <li>Business Layer</li>
      <li>Presentation Layer</li>
    </ul>
    Bu katmanlar code first mantığı çerçevesinde oluşturuldu.
    
🎈 Projede Data First yapısını anlamak için EFProject dosyası oluşturdum. Bu kısıma başlamadan önce bir tur şirketi projesi fikriyle başlanıldı.
   Burada data first yapısı için öncellikle bir veritabanı oluşturdum. Oluşturduğum veritabanını projeye entegre etmek için DataModel ekleyerek 
   veritabanını entegre ettim. Bu işlem sonunda varlıklarım data first sayesinde oluşturulmuş oldu.
   <ul>
      <li> Form1: Burada oluşturduğum Guide(Rehber)'ler için veritabanı üzerinde işlemler gerçekleştirmemize olanak sağlar. Aşağıda da gördünüz üzere 
      rastgele seçilen isimlerle oluşturduğum veritabanındaki verileri Listeleme, Ekleme, Silme, Güncelleme ve Id'ye göre getirme işlemleri 
      gerçekleştirebiliyoruz. Entity Framework sayesinde uzun kod satırları yerine 2,3 satır kodla işlemlerimi gerçekleştirebiliyorum. Uzun 
      işlemleri benim yerime entity framework kendisi hallediyor.
     
  ![Ekran görüntüsü 2024-12-27 000838](https://github.com/user-attachments/assets/97a9f91c-4929-457f-88e3-0ebc7578d656)
      </li>
      <li> FrmLocation: Data First yapısıyla oluşturduğum "Location" için bir form oluşturdum. Bu form Form1 gibi işlemler gerçekleştirebiliyor.
      Ama burada "Location" varlığı için işlemler gerçekleştiriyoruz. Bu kısım için de Entity Framework'den yardım alarak işlemleri gerçekleştirdim.
      Buradaki en önemli konulardan biri de lokasyonlar ile rehberleri ilişkilendirmiş olmak. Bu sayede turlara rehberleri ID'leri sayesinde 
      görevlendirebiliriz. Gerçekleştirilen işlemleri aşağıdaki görselden de inceleyebilirsiniz.
    
  ![Ekran görüntüsü 2024-12-27 000859](https://github.com/user-attachments/assets/93540bad-66f1-45c8-bb9a-ebb9c9e6972a)
      </li>
       <li> FrmStatistics: İStatistik formu veritabanında tuttuğum verileri yani bunlara Form1 ve FrmLocations'dan daha sonra eklenebilecek, silinebilecek
       veya güncellenebilecek tüm veriler üzerinde çeşitli işlemler yapar. Hangi tur daha pahalı? Toplam rehber sayısı ne? gibi sorulara cevap bulmak ve veriler 
       üzerimnde matematiksel işlemler yapmak için bu form oluşturuldu. Form verilerin istatistiksel hesaplamalarını tutan bir yapıdadır.
    
  ![Ekran görüntüsü 2024-12-26 234351](https://github.com/user-attachments/assets/037879a6-2512-45a5-8cad-ba5b2706cb41)
      </li>
  </ul>
  <h3>.</h3>
  <h3>.</h3>
  <h3>.</h3>
  <h3>Güncellemeler devam edecektir.</h3>
