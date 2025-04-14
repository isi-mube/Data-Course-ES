<h2>
    <a id="funciones" class="anchor" href="#funciones" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Funciones en Python
</h2>
<p>Las funciones permiten encapsular bloques de código reutilizable. Así evitamos repetirnos y organizamos mejor nuestros programas.</p>

<h3>
    <a id="definir-funcion" class="anchor" href="#definir-funcion" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Cómo definir una función
</h3>
<pre><code>def saludar():
    print("Hola desde una función")</code></pre>

<h3>
    <a id="argumentos" class="anchor" href="#argumentos" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Argumentos
</h3>
<pre><code>def saludar(nombre):
    print(f"Hola, {nombre}")</code></pre>

<h3>
    <a id="return" class="anchor" href="#return" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Valores de retorno
</h3>
<pre><code>def sumar(a, b):
    return a + b

resultado = sumar(5, 3)
print(resultado)  # 8</code></pre>

<h3>
    <a id="scope" class="anchor" href="#scope" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Alcance de las variables
</h3>
<p>Las variables definidas dentro de una función solo existen ahí (scope local).</p>

<h3>
    <a id="resumen" class="anchor" href="#resumen" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen
</h3>
<p>Las funciones hacen tu código más limpio, modular y reutilizable. Son una parte esencial de cualquier programa en Python.</p>