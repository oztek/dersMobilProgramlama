# dersMobilProgramlama
İşletme Enformatiği bölümünde vermiş olduğum Mobil Programlama dersi için açılmıştır.

## Java Dili Hakkında Hatırlatmalar
### Sabit Tanımlama
Bu şekilde programın çalışması sırasında ilk değeri verilmiş değişkenin değeri programın icrası sırasında değiştirilmesi engellenmiş olur. Bu özellik genellikle pi sayısı, e sayısı gibi sabitlerin tanımlanmasında kullanılır.

Örneğin 
<pre><code>final String degisken1;
final int degisken2, degisken3;
final float pi=3.14;</code></pre>

### Tip Dönüşümleri
#### String

Temel veri tipinden String tipine toString() methodu ile  dönüşüm bulunmaktadır. Örneğin

<pre><code>String dize = Birdegisken.toString();</code></pre>

Stringden bir temel veri tipine dönüşüm için

<pre><code>
byte  birByte   = Byte.parseByte(dize);
short birShort  = Short.parseShort(dize);
int   birInteger    = Integer.parseInt(dize);
long  birLongInteger   = Long.parseLong(dize);
float  birFloat  = Float.parseFloat(dize);
double birDouble = Double.parseDouble(dize);
boolean birTrueFalse = Boolean.parseBoolean(dize);</code></pre>
