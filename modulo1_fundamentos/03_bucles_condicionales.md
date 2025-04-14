<h2>
    <a id="condicionales" class="anchor" href="#condicionales" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Condicionales y Bucles
</h2>
<p>Las condicionales permiten ejecutar código solo si se cumple una condición:</p>

<pre><code>if edad >= 18:
    print("Puedes votar")
else:
    print("No puedes votar")</code></pre>

<h3>
    <a id="comparadores" class="anchor" href="#comparadores" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Comparadores comunes
</h3>
<ul>
    <li><code>==</code> igual</li>
    <li><code>!=</code> distinto</li>
    <li><code>&gt;, &lt;, &gt;=, &lt;=</code> mayor, menor, etc.</li>
</ul>

<h3>
    <a id="bucle-for" class="anchor" href="#bucle-for" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Bucle <code>for</code>
</h3>
<pre><code>for i in range(5):
    print("Repetición:", i)</code></pre>

<h3>
    <a id="bucle-while" class="anchor" href="#bucle-while" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Bucle <code>while</code>
</h3>
<pre><code>n = 0
while n &lt; 3:
    print(n)
    n += 1</code></pre>

<h3>
    <a id="combinado" class="anchor" href="#combinado" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Condicionales dentro de bucles
</h3>
<pre><code>numeros = [1, 2, 3, 4]
for n in numeros:
    if n % 2 == 0:
        print(n, "es par")</code></pre>

<h3>
    <a id="resumen-final" class="anchor" href="#resumen-final" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen
</h3>
<p>Has aprendido a usar <code>if</code> para tomar decisiones y bucles <code>for</code>/<code>while</code> para repetir acciones.</p>