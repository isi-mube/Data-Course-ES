<h1 style="color: #00BFFF;">Tipos de datos y estructuras de datos</h1>

<p style="text-align: center;">
  <img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" alt="Intro gif" width="300">
</p>

<h2 style="color: #008080;">Tipos de datos</h2>

<p>En Python, los <strong>tipos de datos</strong> nos permiten representar diferentes tipos de información. Para nuestro proyecto de <strong>gestor de finanzas personales</strong>, los más relevantes son:</p>

<ul>
  <li><strong>int</strong>: Números enteros (ej. número de gastos).</li>
  <li><strong>float</strong>: Números con decimales (ej. cantidades de dinero).</li>
  <li><strong>str</strong>: Texto, como categorías o fechas.</li>
  <li><strong>bool</strong>: Verdadero o falso, útil para clasificar entre ingreso/gasto.</li>
</ul>

<pre><code class="language-python">
# Ejemplo de variables de transacción
categoria = "Comida"
monto = 23.50
es_ingreso = False
</code></pre>

<p>Podemos comprobar su tipo con <code>type()</code>:</p>

<pre><code class="language-python">
type(categoria)   # str
type(monto)       # float
type(es_ingreso)  # bool
</code></pre>

<h2 style="color: #008080;">Operadores aritméticos</h2>

<p>Nos permiten realizar cálculos, como sumar gastos o calcular balances:</p>

<pre><code class="language-python">
saldo_inicial = 1000
gasto = 120.75
saldo_restante = saldo_inicial - gasto
print(saldo_restante)  # 879.25
</code></pre>

<p>También puedes usar operadores como <code>+=</code> o <code>*=</code> para actualizar valores:</p>

<pre><code class="language-python">
saldo = 500
saldo += 200  # saldo ahora es 700
</code></pre>

<h2 style="color: #008080;">Estructuras de datos</h2>

<p>Las estructuras de datos nos permiten organizar múltiples elementos como listas de movimientos.</p>

<h3>Listas</h3>

<p>Sirven para almacenar múltiples elementos en orden:</p>

<pre><code class="language-python">
categorias = ["Alquiler", "Comida", "Salario"]
print(categorias[0])  # "Alquiler"
</code></pre>

<h3>Diccionarios</h3>

<p>Relacionan claves y valores, ideales para representar una transacción:</p>

<pre><code class="language-python">
transaccion = {
  "categoria": "Transporte",
  "monto": 15.80,
  "fecha": "2024-04-15",
  "tipo": "gasto"
}
print(transaccion["monto"])  # 15.80
</code></pre>

<h3>Lista de diccionarios</h3>

<p>Para almacenar varias transacciones:</p>

<pre><code class="language-python">
registro = [
  {"categoria": "Salario", "monto": 1500, "tipo": "ingreso"},
  {"categoria": "Supermercado", "monto": 75.20, "tipo": "gasto"},
  {"categoria": "Cine", "monto": 12.00, "tipo": "gasto"}
]
</code></pre>

<h3>Acceso y modificación</h3>

<pre><code class="language-python">
# Acceder al segundo gasto
print(registro[1]["monto"])  # 75.20

# Añadir una nueva transacción
registro.append({
  "categoria": "Internet",
  "monto": 29.99,
  "tipo": "gasto"
})
</code></pre>

<h3>Imagen: estructuras de datos</h3>

<p style="text-align: center;">
  <img src="https://github.com/data-bootcamp-v4/lessons/blob/main/img/data-structures.png?raw=true" width="500" alt="Estructuras de datos">
</p>

<h3>Diccionarios anidados</h3>

<pre><code class="language-python">
usuarios = {
    "Juan": {
        "edad": 34,
        "movimientos": [200, -50, -100]
    },
    "Diego": {
        "edad": 28,
        "movimientos": [300, -120, -30]
    }

print(usuarios["Diego"]["movimientos"][1])  # -120
</code></pre>

<h2 style="color: #008080;">Resumen</h2>

  <li><code>list</code>: Colecciones ordenadas de elementos (ej. transacciones).</li>
  <li><code>dict</code>: Estructuras clave-valor para representar datos con contexto.</li>
  <li>Estas estructuras son esenciales para automatizar, analizar y visualizar tus datos financieros.</li>