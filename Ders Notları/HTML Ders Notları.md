# **HTML Ders Notları**



## Temel HTML Etiketleri 

### * <!DOCTYPE> Tanımlaması

##### HTML belgenizi tanımlayın!

------------------------------------------------------------------------

Tüm HTML belgeleri bir tanımlama ile başlamalıdır . Bu bildirim etiket değil, tarayıcıya hangi belge türü olduğu hakkında bir "bilgi"dir.

````html
<!DOCTYPE html>
````

### **Not**

Tanımlama; `<!DOCTYPE>`büyük/küçük harfe duyarlı *DEĞİLDİR*.



***

### * < html> Etiketi

#####  Basit bir HTML belgesi!

------------------------------------------------------------------------

Tüm HTML belgelerinin kökünü temsil eder, diğer tüm HTML öğelerinin kapsayıcısıdır( !DOCTYPE etiketi hariç) .

### **Not**

Web sayfasının dilini bildirmek için her zaman etiketin içine *lang* niteliğini eklemelisiniz.

````html
<html lang="tr">
````



***

### * < head> Etiketi 

##### HTML belgeniz için bir başlık tanımlayın!

------------------------------------------------------------------------

Metadata'lar için bir kapsayıcıdır  ve < html> etiketi ile < body> etiketi arasına yerleştirilir. Meta veriler, HTML belgesiyle ilgili verilerdir, sayfa üzerinde görüntülenmez.

Meta veriler, HTML belgesiyle ilgili verilerdir. Meta veriler görüntülenmiyor.

farklı etiketler < head> içerisinde olabilir.

* < title> (her sayfada muhakkak bulunmalı)

* < style>

* < base>

* < link>

#### Kod Örneği

````html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {color:green;}
p {color:black;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
````



***

### * < body> Etiketi 

##### Basit bir HTML belgesi...

------------------------------------------------------------------------

Bu etiket belgenin gövdesini tanımlar. Öğeler;  başlıklar, paragraflar, resimler, linkler, tablolar, listeler vb. gibi bir HTML belgesinin tüm içeriğini bulundurur.

### **Not**

Web sayfasında sadece bir adet  *< body>* etiketi bulunur.

#### Kod Örneği

````html
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-image: url(https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png);
}
</style>
</head>
<body>

<h1>Hello world!</h1>
<p><a href="https://www.google.com">Visit google.com!</a></p>

</body>
</html>

````



***

### * < h1> - < h6> Etiketi 

##### HTML belgeleriniz için bir başlık ölçüsü tanımlayın!

------------------------------------------------------------------------

< h1> den < h6> ya kadar olan etiketler, başlık ölçülerini tanımlamak için kullanılır. 

 < h1> en önemli başlığı tanımlar. < h6> en önemsiz başlığı tanımlar.

### **Not**

Web sayfasında sadece bir adet  *< h1>* etiketi bulunur. Diğer başlıkları *< h6>* 'ya kadar düşerek yazın.



#### Kod Örneği

````html
<h1>H1 Başlığı</h1>
<h2>H2 Başlığı</h2>
<h3>H3 Başlığı</h3>
<h4>H4 Başlığı</h4>
<h5>H5 Başlığı</h5>
<h6>H6 Başlığı</h6>
````



***

### * < p> Etiketi 

##### HTML belgelerinizde paragraf tanımı yapın...

------------------------------------------------------------------------

< p> etiketi paragraf tanımlamak için kullanılır. 

 Tarayıcılar her < p> < /p> tanımlamasının öncesi ve sonrasına tek bir satır boşluk ekler.

### **Not**

  *< p>* sadece paragraf tanımlamak için kullanılır. Stil vermek için *css* komutlarını kullanın.



#### Kod Örneği

````html
<p>Yazıların olduğu paragraf örneği.</p>
````



***

### * < br> Etiketi 

##### HTML belgelerinizde satır boşluğu bırakın...

------------------------------------------------------------------------

< br> etiketi metne bir satır boşluk bırakmak için kullanılır. Genellilkle şiir, adres gibi formatlarda kullanmak için uygundur. 

 *< br>* etiketi boş bir yapıdır, bitiş etiketi yoktur. 

### **Not**

*< br>* sadece satır sonu girmek için kullanın. Paragraflar arası boşluk vermek için kullanmayın!

#### Kod Örneği

````html
<p>Bugün pazar<br> Bugün beni ilk defa güneşe çıkardılar.<br> Ve ben ömrümde ilk defa gökyüzünün<br> Bu kadar benden uzak<br> Bu kadar mavi <br> Bu kadar geniş olduğuna şaşarak<br> Kımıldamadan durdum.<br></p> <p>Nazım Hikmet</p>
````



***

### * < hr> Etiketi 

##### HTML belgelerinizde konu sonu belirleyin ya da bir görsel bir çizgi oluşturun!

------------------------------------------------------------------------

< hr> etiketi tematik değişimi yani konu sonunu belirtmek için ya da sayfa içerisinde içerikleri ayırmak istendiğinde çizgi çizmek için kullanılır. 

### **Not**

*< hr>* etiketine özellik tanımlamak için *css* kodları ile kullanmayı unutmayın.

#### Kod Örneği

````html
<h1>The Main Languages of the Web</h1>

<p>HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page, and consists of a series of elements. HTML elements tell the browser how to display the content.</p>

<hr>
````



***

### * < !--     --> Etiketi 

##### HTML belgelerinizde açıklama satırları oluşturmak mı istiyorsun?

------------------------------------------------------------------------

< !--     --> kaynak kod içerisine yorum ve ya açıklama satırları ekleme için kullanılır. Bu etiket ile tanımlanan satırlar tarayıcı üzerinde gözükmekler.

### **Not**

*< hr>*  özellikle karmaşık kod yapılarında bazı özellikleri kapatıp açmak için kullanılabilir. Visual Studio Code üzerinde *ctrl+ö* kısayolu ile kullanılabilir.

#### Kod Örneği

````html
<h1>The Main Languages of the Web</h1>

<p>HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page, and consists of a series of elements. HTML elements tell the browser how to display the content.</p>

<hr>
````

