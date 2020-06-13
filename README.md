# Grids Responsivas - HTML & CSS | Documentação
###### Desenvolvido por: Julimar "Akira" Jr.
**Aviso:** Não é possível utilizar Bootstrap em conjunto com esse CSS.

**Como utilizar:**
<br>
Adicione o grid.css em seu projeto HTML.
```
<link rel="stylesheet" type="text/css" href="css/grid.css">
```
Para adicionar um **container**, use:
```
<div class="container">
  content
</div>
```
Para adicionar **linhas**, use:
```
<div class="row">
  content
</div>
```
Para adicionar **colunas**, use:
```
<div class="col">
  content
</div>
```
- As colunas devem obrigatóriamente possuir a class **col** em suas **div**, e também, o tamanho da coluna.
- As colunas funcionam como no **Bootstrap**, 12 por linha.
- Utilize col-x para determinar o tamanho da coluna, onde **x** deve ser substituito por números de 1 até 12.
- Cada linha, suportará então, apenas 12 colunas, utilize os números com soma entre eles para determinar a quantidade de colunas.
**Exemplo:**
```
<div class="col col-4">
  content
</div>
```
##Exemplo de código contendo uma linha com 3 colunas:
```
<div class="container">
  <div class="row">
    <div class="col col-6">
      content
    </div>
    <div class="col col-3">
      content
    </div>
    <div class="col col-3">
      content
    </div>
  </div>
</div>
```
<img src="https://i.imgur.com/As2n2A3.png">

