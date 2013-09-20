<h1>Phing-common</h1>

Ohiko phing funtzioak biltzeko proiektuak. 

<h2>Erabilera</h2>
<p>
Zure PHP proiektuaren oinarrian kopiatu phing-common.<br />

<pre>
<code>git clone https://github.com/karrikas/phing-common</code>
</pre>


Karpeta horretan dauden fitxategiak copiatu zure proiektura bertan phing-ekine erabiltzeko.
<pre>
<code>cp phing-common/example.build.xml build.xml</code>
</pre>
<pre>
<code>cp phing-common/example.porperties .properties</code>
</pre>
<pre>
<code>cp phing-common/example.rsync_exclude rsync_exclude</code>
</pre>

<br />
Orain proiektuaren oinarrian kopiatu ditugun fitxategiak editatu ditzakegu geure funtzio propioak 
gehitzeko eta konfigurazio datuak aldatzeko. <br/>
<br/>
Funtzio zerrenda ikusteko:
<pre>
<code>phing -l</code>
</pre>
</p>


<h2>Fitxategiak</h2>
<p>
<b>example.porperties</b>: Izendatu .properties izenarekin zure proiektuan erabiltzeko. Bertan 
ohiko aldagaien izena topatuko dituzu eta gehiago behar baditugu gehitzeko aukera. 
</p>

<p>
<b>example.build.xml</b>: Izendatu .build.xml izenarekin zure proiektuan erabiltzeko. Bertan zure proiektuak 
defektuz erabiliko dituzun task egongo dira.
</p>

<p>
<b>example.rsync_exclude</b>: Izendatu rsync_exclude izenarekin hau rsync erabiltzeko behar da. Zure 
proiektuarentzako exprezioak gehitu ditzazkezu. 
</p>

<p>
<b>build.common.xml</b>: Fitxategi honek biltzen ditu ohiko funtzioak hemen ez da aldaketarik egin behar. 
</p>


