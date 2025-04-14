<h2>
    <a id="estadistica-descriptiva" class="anchor" href="#estadistica-descriptiva" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Estadística Descriptiva sin Darnos Cuenta
</h2>
<p>Exploraremos la distribución de los datos, sus promedios y variabilidad. Aunque no hablemos de "estadística" directamente, estarás usándola todo el tiempo.</p>

<h3>
    <a id="describe" class="anchor" href="#describe" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen con <code>.describe()</code>
</h3>
<pre><code>df.describe()</code></pre>

<h3>
    <a id="moda-media" class="anchor" href="#moda-media" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Media, moda y mediana
</h3>
<pre><code>df["nota"].mean()
df["nota"].median()
df["nota"].mode()</code></pre>

<h3>
    <a id="desviacion" class="anchor" href="#desviacion" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Dispersión de los datos
</h3>
<pre><code>df["nota"].std()</code></pre>

<p>
    También podemos visualizar estas métricas para entender mejor la forma de los datos.
</p>

<h3>
    <a id="resumen" class="anchor" href="#resumen" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen
</h3>
<p>Sin darte cuenta, acabas de aplicar estadísticas como media, mediana, desviación estándar... y todo con código.</p>