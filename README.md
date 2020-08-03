# TR-il-ilce-Semt-Mahalle__City-County-Street-Neighborhood-06.2020_Json
Türkiye Bütün il,ilçe,semt ve mahalleleri. 06.2020


.Net Kullananlar İçin;
StreamReader r = new StreamReader(@"TR-İl-İlçe-Mahalle_(City-County-Neighborhood).json");
string json = r.ReadToEnd();
List<il> allCities = JsonConvert.DeserializeObject<List<il>>(json);
            

Sql Hazır Tablo ve Veriler İçin;

https://raw.githubusercontent.com/semihferik/il-ilce-semt-mahalle/master/Aktarilmis%20Sql%20Dosyalari/2020/2020-06-04%20Aktarilmis%20(yil-ay-gun).sql
