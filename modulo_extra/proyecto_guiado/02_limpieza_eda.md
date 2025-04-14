<h2>
    <a id="limpieza-eda" class="anchor" href="#limpieza-eda" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Limpieza y EDA inicial
</h2>
<p>Empieza con una exploración básica:</p>
<pre><code>df.shape
df.columns
df.dtypes
df.describe()</code></pre>

<p>Luego elimina duplicados y trata valores nulos:</p>
<pre><code>df.drop_duplicates(inplace=True)
df.isna().sum()</code></pre>

<p>Rellena o elimina según convenga, explicando tus decisiones.</p>