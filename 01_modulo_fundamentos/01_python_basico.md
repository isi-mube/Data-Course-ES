<h2>
    <a id="introduccion" class="anchor" href="#introduccion" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Introducción
</h2>
<p>Para construir un gestor de finanzas personales en Python, necesitamos conocer los tipos de datos más comunes y cómo organizarlos usando estructuras como listas y diccionarios.</p>

<h3>
    <a id="tipos-de-datos" class="anchor" href="#tipos-de-datos" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Tipos de datos
</h3>
<p>En Python, los tipos de datos más utilizados en este proyecto serán:</p>

<ul>
    <li><code>int</code>: valores enteros como <code>2024</code> o <code>15</code></li>
    <li><code>float</code>: cantidades con decimales como <code>89.99</code></li>
    <li><code>str</code>: texto como <code>"Comida"</code> o <code>"2024-04-10"</code></li>
    <li><code>bool</code>: valores lógicos: <code>True</code> o <code>False</code></li>
</ul>

<pre><code class="language-python"># Ejemplo de transacción individual
categoria = "Alquiler"
monto = 850.00
fecha = "2024-04-01"
es_ingreso = False
</code></pre>

<h3>
    <a id="estructuras" class="anchor" href="#estructuras" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Estructuras de datos
</h3>
<p>Para gestionar múltiples transacciones, usaremos <strong>listas</strong> y <strong>diccionarios</strong> en combinación.</p>

<h4>🔸 Diccionario: una transacción</h4>
<pre><code class="language-python">transaccion = {
    "categoria": "Supermercado",
    "monto": 45.20,
    "fecha": "2024-04-12",
    "tipo": "gasto"
}
</code></pre>

<h4>🔸 Lista de transacciones</h4>
<pre><code class="language-python">registro = [
    {"categoria": "Salario", "monto": 1200, "fecha": "2024-04-01", "tipo": "ingreso"},
    {"categoria": "Alquiler", "monto": 850, "fecha": "2024-04-03", "tipo": "gasto"},
    {"categoria": "Café", "monto": 3.5, "fecha": "2024-04-04", "tipo": "gasto"}
]
</code></pre>

<h3>
    <a id="visualizacion" class="anchor" href="#visualizacion" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Visualización de estructura
</h3>
<p style="text-align:center;">
    <img src="https://i.imgur.com/mqfzPYr.png" alt="Estructura de datos de transacciones" width="500">
</p>

<h3>
    <a id="lectura-y-acceso" class="anchor" href="#lectura-y-acceso" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Lectura y acceso a datos
</h3>

<pre><code class="language-python"># Mostrar el monto de la segunda transacción
print(registro[1]["monto"])  # 850

# Agregar una nueva transacción
registro.append({
    "categoria": "Internet",
    "monto": 40.0,
    "fecha": "2024-04-05",
    "tipo": "gasto"
})
</code></pre>

<h3>
    <a id="resumen" class="anchor" href="#resumen" aria-hidden="true">
        <span aria-hidden="true" class="octicon octicon-link"></span>
    </a>Resumen
</h3>
<p>Hemos aprendido a representar datos financieros usando tipos y estructuras en Python. Con estas herramientas podrás construir un sistema que registre y clasifique tus gastos e ingresos.</p>