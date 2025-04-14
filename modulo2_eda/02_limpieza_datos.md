<h2>
    <a id="limpieza" class="anchor" href="#limpieza" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Limpieza y Preparación de Datos
</h2>
<p>Antes de analizar, los datos deben estar limpios. Revisaremos valores nulos, duplicados y datos incoherentes.</p>

<h3>
    <a id="valores-nulos" class="anchor" href="#valores-nulos" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Valores nulos
</h3>
<pre><code>df.isna().sum()</code></pre>

<h3>
    <a id="rellenar" class="anchor" href="#rellenar" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Rellenar valores nulos
</h3>
<pre><code>df["nota"] = df["nota"].fillna(df["nota"].mean())</code></pre>

<h3>
    <a id="duplicados" class="anchor" href="#duplicados" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Eliminar duplicados
</h3>
<pre><code>df = df.drop_duplicates()</code></pre>

<h3>
    <a id="resumen" class="anchor" href="#resumen" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen
</h3>
<p>Un dataset limpio reduce errores, acelera el análisis y mejora los resultados.</p>