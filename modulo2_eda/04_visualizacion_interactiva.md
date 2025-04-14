<h2>
    <a id="visualizacion" class="anchor" href="#visualizacion" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Visualización Interactiva de Datos
</h2>
<p>Una imagen vale más que mil líneas de código. Aquí vamos a visualizar la información para detectar patrones.</p>

<h3>
    <a id="histograma" class="anchor" href="#histograma" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Distribución de variables
</h3>
<pre><code>import seaborn as sns
import matplotlib.pyplot as plt

sns.histplot(df["nota"], kde=True)
plt.show()</code></pre>

<h3>
    <a id="categoricas" class="anchor" href="#categoricas" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Comparación entre grupos
</h3>
<pre><code>sns.boxplot(x="clase", y="nota", data=df)</code></pre>

<h3>
    <a id="correlaciones" class="anchor" href="#correlaciones" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Correlación
</h3>
<pre><code>sns.heatmap(df.corr(), annot=True, cmap="coolwarm")</code></pre>

<h3>
    <a id="resumen" class="anchor" href="#resumen" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen
</h3>
<p>Visualizar datos te ayuda a ver tendencias, detectar outliers y comunicar hallazgos de forma clara.</p>