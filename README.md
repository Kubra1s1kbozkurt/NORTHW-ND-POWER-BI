[Power BI Raporunu Görüntüle](https://app.powerbi.com/links/fu_o4g_vqY?ctid=048e1d7c-5205-48c0-88ae-7a05c05e0151&pbi_source=linkShare&bookmarkGuid=8578c853-f7ad-48b4-8e7e-23b15b6bcb27)

# NORTHWIND POWER BI DASHBOARD

Northwind, bir toptan ticaret şirketi olarak tasvir edilir ve dünya genelindeki müşterilere yiyecek ve içecek ürünleri satar. Northwind'in ürün yelpazesi, çeşitli yiyecek ve içecek ürünlerinden oluşur ve şirketin müşteri portföyü dünya genelinde geniş bir yelpazeye yayılmıştır.

Herhangi bir teslim tarihi olmadığı için teslimat için herhangi bir analiz yapılmamıştır. Bu sebepten ötürü  nakliye ile alakalı analiz yapılmamıştır. 

Product tablosundaki unit price ile order details tablosundaki unit priceler da indirim tutarı uygulansa dahi tutmayan fiyatlar vardır ondan ötürü order details tablosundaki unit pricelar baz alınmıştır.

Bu çerçevede ürün, çalışan, müşteri ve rfm analizi yapılıp tooltiplerle görseller zenginleştirilmiştir. Ayrıca her sayfada bir ay slicerı eklenmiş aylık olarak incelenmek istenirsede oradan aksiyon alınabilir.

Rapor 6 sayfadan oluşmaktadır

## 1-Northwind:
Şirketin yaptığı satışlar, çalıştığı tedarikçiler ve kargo firmaları, cirosu, çalışanları vs. genel bilgiler yerleştirilmiştir.

![northwind](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/northwind.png)


## 2-Porduct: 
Talebin fazla olduğu yeniden sipariş edilen ürünler arasında ilk 8 sıralanmıştır. Fazla ürün olduğu için yatay bir line chartta ürünler sıralanmış ve üzerine detaylı bir tooltip yerleştirilmiştir. Toplam satış için kategorilere göre bir yatay linechart eklenmiştir, burada tooltip2 kullanılmıştır.

![product](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/product.png)


Tooltip: Bu tooltipte ürün ismi, kimin sattığı, ne kadar ürün satıldığı, bize kazandırdığı ciro, stok durumu, stoktaki ürün maliyeti ve aylara göre satış sayısı sıralnmıştır.

![product_tooltip1](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/product_tooltip1.png)


Tooltip2: Bu tooltipte kategorilerin hangi ülkeler tarafından ne kadar birim  alındıkları gösterilmektedir.

![product_tooltip2](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/product_tooltip2.png)


## 3- Employees:
Çalışan isimlerimiz, görevleri, satış adetleri, satışlardan şirkete kazandırdıkları gelirler yer alır.  Bir kategori slicerı eklenmiştir.  Hangi kategoride kimler ne kadar performance göstermiş sorusunun cevabı aranmaktadır.

![employees](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/employees.png)

##  4-Customer: 
Customer information adında bir tablomuz bulunmaktadır. Burada customer_id, country, Total sales, quantity, discount  yer almaktadır ve bir tooltip eklenmiştir.. Yine bir kategori slicerı eklenmiştir.  Hangi kategoriden hangi firmaların az önceki saydığımız metrikler neticesinde performansları ölçülmek istenmiştir.  Repeat Purchase Rate adında dikey bir barchart eklenmiştir.  Aylık olarak tekrar satın alma oranlarına bakılmıştır ve bu grafiğin diğer garfiklerle bağlantısı yoktur.

![customer](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/customer.png)

Tooltip3: Burada firmalar ayrımında hangi firmanın hangi ürünlerden ne kadar satın aldığı ve o ürünler için ayrı ayrı ödediği toplam tutar gösterilmektedir.

![customer_tooltip3](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/customer_tooltip3.png)

 ## 5-RFM:
 Müşteri segmentasyonu yapılmış olup recency, frequency ve monetary değerleri ortalaması alınıp müşteriler segmente edilmişitir. Tooltiple rfm analizi detaylandırılmıştır.

![rfm](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/rfm.png)

Tooltip4: Segmente edilen müşterilerin toplam kazandırdığı tutar, toplam uygulanan indirim tutarı, satış yapılan ades, kaç farklı ürün aldığı, kaç farklı sipariş verdiği gösterilmektedir. Aynı zamanda aylık olarak hangi aylarda sipariş verildiği ve sayısı , kaç adet ürün aldığı gösterilmektedir. 

![rfm_tooltip4](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/rfm_tooltip4.png)

## 6-Analiz:

![analiz](https://github.com/Kubra1s1kbozkurt/NORTHWIND-POWER-BI/blob/main/image/analiz.png)


