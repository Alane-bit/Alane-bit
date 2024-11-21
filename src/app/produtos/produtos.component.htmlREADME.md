@@ -0,0 +1,20 @@
<main>
<section>
<h1>Lista de produtos</h1>
<table>
<thead>
    <th>Nome do produto</th>
</thead>
<tbody>
    <tr *ngFor="let p of listaProdutos">
        <td>{{p.nome}}</td>
    </tr>
</tbody>
</table>
</section>
</main>
