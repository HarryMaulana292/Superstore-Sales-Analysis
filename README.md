# Superstore Sales Analysis
---
# Background
Seiring dengan meningkatnya persaingan di industri ritel, perusahaan dituntut untuk mengambil keputusan yang cepat dan tepat berbasis data guna mempertahankan daya saing dan meningkatkan profitabilitas. Superstore yang beroperasi di berbagai wilayah yang ada di United States dengan beragam kategori produk dan segmen pelanggan menghasilkan data transaksi dalam jumlah besar setiap harinya sejak 2014-2017.

Data tersebut menyimpan berbagai informasi penting terkait performa penjualan, perilaku pelanggan, permintaan produk, serta efisiensi operasional. Namun, tanpa proses analisis dan visualisasi yang tepat, data tersebut sulit dimanfaatkan secara optimal untuk menghasilkan insight yang bernilai.

---
# Problem Statement

Pihak Superstore ingin melakukan analisis data yang komprehensif untuk mengidentifikasi produk, kategori, wilayah, dan segmen pelanggan yang memberikan performa terbaik maupun yang kurang optimal. Tanpa adanya insight yang jelas, proses pengambilan keputusan menjadi kurang optimal dan berpotensi menyebabkan strategi bisnis yang tidak efektif.

Oleh karena itu, project ini bertujuan untuk membangun dashboard visualisasi data yang interaktif guna menganalisis performa penjualan serta menghasilkan insight yang dapat digunakan sebagai dasar pengambilan keputusan yang lebih baik.

---
# Data

Dataset ini merupakan dataset Superstore United States dari tahun 2014-2017. Terdapat 21 column dengan jumlah data sebanyak 9993 baris. Dataset dan data dictionary dapat diakses [di sini].

Kolom yang ada dalam dataset ini meliputi :
| Kolom | Deskripsi |
| --- | --- |
| Row ID | Unique ID for each row |
| Order ID | Unique Order ID for each Customer |
| Order Date | Order Date of the product |
| Ship Date | Shipping Date of the Product |
| Ship Mode | Shipping Mode specified by the Customer |
| Customer ID | Unique ID to identify each Customer |
| Customer Name | Name of the Customer |
| Segment | The segment where the Customer belongs |
| Country | Country of residence of the Customer |
| City | City of residence of of the Customer |
| State | State of residence of the Customer |
| Postal Code | Postal Code of every Customer |
| Region | Region where the Customer belong |
| Product ID | Unique ID of the Product |
| Category | Category of the product ordered |
| Sub-Category | Sub-Category of the product ordered |
| Product Name | Name of the Product |
| Sales | Sales of the Product |
| Quantity | Quantity of the Product |
| Discount | Discount provided |
| Profit | Profit/Loss incurred |

---

### Kesimpulan

1. Meskipun performa penjualan di tiap bulan selalu mengalami fluktuasi, profit Superstore selalu meningkat tiap tahunnya.
1. Penurunan performa penjualan dapat disebabkan beberapa faktor musiman seperti post-holiday effect, tax season, kondisi cuaca (winter storm), dan peralihan pengeluaran ke aktivitas rekreasi di liburan musim panas.
1. State dengan penjualan terbaik adalah California dan New York. Hal ini dipengaruhi oleh kepadatan populasi dan daya beli masyarakat yang tinggi, sebagaimana diketahui bahwa kedua kota tersebut merupakan pusat bisnis di US.
1. State dengan penjualan terburuk adalah Texas. Adanya permasalahan regional seperti tingkat diskon dan strategi pricing yang kurang optimal menyababkan banyak kerugian di Texas.
1. Houston, San Antonio, dan Dallas merupakan City dengan kerugian terbesar di Texas. 
1. Di Texas, Binders merupakan core problem yang menyebabkan kerugian, sedangkan Appliances dan Machines menjadi secondary problem.
1. Accessories, Papers, Copiers dan Binders merupakan 4 Sub-Category dengan profit tertinggi di Los Angeles dan San Francisco.
1. Tables menjadi consistent loss maker di kota-kota dengan profit tinggi (New York, Los Angeles, San Francisco), sehingga ada peluang untuk meningkatkan penjualan Tables di kota tersebut.
1. Penetapan diskon yang tinggi dan strategi pricing yang kurang optimal merupakan root cause kerugian bagi Superstore.
1. Seattle memiliki karakteristik pasar yang mendukung, serta membuka peluang bagi perusahaan untuk mengembangkan strategi serupa di kota lain dengan potensi pertumbuhan tinggi.
1. Philadelphia termasuk Outlier Negatif dimana merupakan kota dengan kerugian terbesar, bahkan melebihi Houston.
1. Consumer menjadi kontributor utama profit karena didorong oleh tingginya volume transaksi dari pelanggan individu yang tersebar di berbagai wilayah.
1. Technology merupakan Fully Profitable Category tanpa ada penjualan yang negatif di Sub-Category secara keseluruhan.
1. Category Office Supplies tergolong stabil dimana hanya ada kerugian di Sub-Category Supplies yang relatif kecil.
1. 2 dari 4 Sub-Category di Furniture (Tables dan Bookcases) terdata memiliki performa yang negatif dan menyebabkan performa Furniture rendah secara keseluruhan.
1. Canon imageCLASS 2200 Advance Copier profit driver utama bagi, sementara Cubify CubeX 3D Printer Double Head Print mencatatkan kerugian terbesar.
