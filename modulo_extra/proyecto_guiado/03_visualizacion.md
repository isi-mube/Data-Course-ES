<h2>
    <a id="visualizacion-proyecto" class="anchor" href="#visualizacion-proyecto" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Visualización de Resultados
</h2>
<p>Crea al menos 3 gráficos que ayuden a responder las siguientes preguntas:</p>
<ul>
    <li>¿Qué variables están más relacionadas con las notas?</li>
    <li>¿Hay diferencias según género o edad?</li>
</ul>

<pre><code>import seaborn as sns
sns.boxplot(x="genero", y="nota", data=df)</code></pre>

<p>Incluye comentarios y conclusiones debajo de cada gráfico.</p>