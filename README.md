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

Dataset ini merupakan dataset Superstore United States dari tahun 2014-2017. Terdapat 21 column dengan jumlah data sebanyak 9993 baris.

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

* Meskipun performa penjualan di tiap bulan selalu mengalami fluktuasi, profit Superstore selalu meningkat tiap tahunnya.
* Penurunan performa penjualan dapat disebabkan beberapa faktor musiman seperti post-holiday effect, tax season, kondisi cuaca (winter storm), dan peralihan pengeluaran ke aktivitas rekreasi di liburan musim panas.
* State dengan penjualan terbaik adalah California dan New York. Hal ini dipengaruhi oleh kepadatan populasi dan daya beli masyarakat yang tinggi, sebagaimana diketahui bahwa kedua kota tersebut merupakan pusat bisnis di US.
* State dengan penjualan terburuk adalah Texas. Adanya permasalahan regional seperti tingkat diskon dan strategi pricing yang kurang optimal menyababkan banyak kerugian di Texas.
* Houston, San Antonio, dan Dallas merupakan City dengan kerugian terbesar di Texas. 
* Di Texas, Binders merupakan core problem yang menyebabkan kerugian, sedangkan Appliances dan Machines menjadi secondary problem.
* Accessories, Papers, Copiers dan Binders merupakan 4 Sub-Category dengan profit tertinggi di Los Angeles dan San Francisco.
* Tables menjadi consistent loss maker di kota-kota dengan profit tinggi (New York, Los Angeles, San Francisco), sehingga ada peluang untuk meningkatkan penjualan Tables di kota tersebut.
* Penetapan diskon yang tinggi dan strategi pricing yang kurang optimal merupakan root cause kerugian bagi Superstore.
* Seattle memiliki karakteristik pasar yang mendukung, serta membuka peluang bagi perusahaan untuk mengembangkan strategi serupa di kota lain dengan potensi pertumbuhan tinggi.
* Philadelphia termasuk Outlier Negatif dimana merupakan kota dengan kerugian terbesar, bahkan melebihi Houston.
* Consumer menjadi kontributor utama profit karena didorong oleh tingginya volume transaksi dari pelanggan individu yang tersebar di berbagai wilayah.
* Technology merupakan Fully Profitable Category tanpa ada penjualan yang negatif di Sub-Category secara keseluruhan.
* Category Office Supplies tergolong stabil dimana hanya ada kerugian di Sub-Category Supplies yang relatif kecil.
* 2 dari 4 Sub-Category di Furniture (Tables dan Bookcases) terdata memiliki performa yang negatif dan menyebabkan performa Furniture rendah secara keseluruhan.
* Canon imageCLASS 2200 Advance Copier profit driver utama bagi, sementara Cubify CubeX 3D Printer Double Head Print mencatatkan kerugian terbesar.

### Rekomendasi
* Optimasi Low Season (Januari, Februari, April, Juli) dengan mengunakan promosi terarah (bundling / diskon terbatas) serta efisiensi stok untuk menjaga demand tanpa menekan margin.
* Maksimalkan High Season (September) dengan meningkatkan ketersediaan produk (terutama Technology & Office Supplies) dan optimalkan pricing tanpa ketergantungan pada diskon besar.
* Terapkan Strategy Berbasis Seasonality dengan menyesuaikan pricing, inventory, dan campaign marketing dengan pola musiman untuk menjaga stabilitas penjualan dan memaksimalkan profit sepanjang tahun.
* Superstore disarankan untuk menerapkan strategi segmentasi yang lebih spesifik per wilayah, dengan mengoptimalkan segment yang terbukti memberikan profit tertinggi di masing-masing state. 
* Superstore disarankan untuk melakukan evaluasi menyeluruh terhadap sub-category Binders di wilayah Texas, khususnya terkait strategi harga dan pemberian diskon.
* Superstore disarankan untuk mempertahankan strategi penjualan yang telah berjalan efektif di Los Angeles, khususnya pada sub-category dengan performa tinggi seperti Accessories. Sementara itu, di San Francisco, diperlukan evaluasi lebih lanjut terhadap sub-category Tables, terutama terkait strategi harga dan biaya, guna mengurangi kerugian dan meningkatkan profitabilitas secara keseluruhan.
* Perusahaan disarankan untuk mengevaluasi kebijakan pemberian diskon pada sub-category Tables, khususnya dengan membatasi diskon pada level yang lebih rendah agar tetap menjaga margin keuntungan. Selain itu, strategi dapat difokuskan pada produk dengan performa tinggi seperti Machines dan Phones untuk memaksimalkan profit di wilayah dengan potensi besar seperti New York City.
* Perusahaan disarankan untuk mempertahankan dan mengoptimalkan performa di kota dengan profit tinggi seperti New York City dan Los Angeles, serta menjadikannya sebagai benchmark strategi. Di sisi lain, diperlukan evaluasi mendalam pada kota dengan performa rendah seperti Philadelphia dan kota-kota di Texas, khususnya terkait strategi harga, distribusi produk, dan segmentasi pasar, guna mengurangi kerugian dan meningkatkan profitabilitas.
* Superstore disarankan untuk memaksimalkan segment Consumer sebagai pendorong utama pertumbuhan dengan berfokus pada kategori Technology dan Office Supplies yang terbukti memberikan kontribusi profit terbesar. 
* Pada segment Corporate, strategi dapat diarahkan untuk meningkatkan nilai transaksi melalui penjualan produk Technology dan kontrak Office Supplies. 
* Sementara itu, segment Home Office dapat dikembangkan secara lebih targeted dengan menawarkan produk yang sesuai kebutuhan pasar niche.
* Secara keseluruhan, Superstore perlu memperkuat strategi berbasis kategori dengan menjadikan Technology dan Office Supplies sebagai core profit driver di seluruh segment, serta melakukan evaluasi mendalam terhadap kategori Furniture, khususnya dalam hal strategi harga, pengendalian diskon, dan pemilihan produk, guna meningkatkan margin dan mengurangi ketimpangan profit antar kategori.
* Perusahaan disarankan untuk mempertahankan dan mengoptimalkan sub-category dengan performa tinggi seperti Copiers, Phones, dan Accessories sebagai pendorong utama profit. Di sisi lain, perlu dilakukan evaluasi terhadap sub-category yang merugi seperti Bookcases, Tables, dan Supplies, khususnya dalam hal strategi harga dan pengendalian diskon. Selain itu, sub-category Machines juga perlu dioptimalkan agar dapat meningkatkan kontribusi profit dalam kategori Technology.
* Perusahaan disarankan untuk mempertahankan dan mengoptimalkan produk dengan performa tinggi seperti Canon Copier sebagai profit driver utama. Di sisi lain, perlu dilakukan evaluasi menyeluruh terhadap sub-category Machines yang secara konsisten menunjukkan performa rendah, termasuk pada level produk. Evaluasi ini dapat mencakup penyesuaian strategi harga, pengendalian diskon, serta optimalisasi portofolio produk guna meningkatkan kontribusi profit dan mengurangi ketimpangan performa secara keseluruhan.
