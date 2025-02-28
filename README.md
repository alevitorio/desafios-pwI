Claro! Aqui vai uma sugestão de desafio que você pode passar para os alunos depois de explicar os conceitos de CSS, como margem, preenchimento, seletores e regras de estilo:

---

### **Desafio: Criando uma página de perfil pessoal com CSS**

**Objetivo:** O aluno deve criar uma página simples de perfil, aplicando as propriedades que foram explicadas durante a aula.

**Instruções:**
1. **Estrutura HTML:**
   - Crie um arquivo HTML contendo as seguintes seções:
     - Um título com o nome da pessoa.
     - Uma imagem de perfil (use uma imagem qualquer ou um link de uma imagem).
     - Uma breve descrição sobre a pessoa (um parágrafo).
     - Uma lista de três habilidades ou interesses.
   
2. **Estilização CSS:**
   - Aplique as seguintes alterações usando CSS:
     - Altere o **tamanho e a cor** do título.
     - Aplique um **bordo arredondada** na imagem de perfil.
     - Coloque um **preenchimento (padding)** na descrição e nas habilidades.
     - Defina uma **margem (margin)** para separar as seções da página.
     - Estilize a lista de habilidades de modo que cada item tenha um **ícone** (pode ser um emoji ou um ícone simples).
     - Alterar a **cor de fundo** da página e o **alinhamento** do texto.
   
3. **Especificidade e Seletores:**
   - Use **classes** para as seções de título, imagem e descrição.
   - Aplique um **seletor de ID** no parágrafo de descrição.
   - Adicione **pseudo-classes** ao link de uma rede social fictícia (como um `hover` para mudar a cor quando o mouse passa sobre ele).

4. **Extras (se houver tempo):**
   - Faça a página responsiva, ajustando o layout para dispositivos móveis (por exemplo, alterando o tamanho da imagem de perfil em telas menores).
   - Adicione uma **sombra** no título ou na imagem.

---

### **Exemplo do que deve ser feito:**

**HTML:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Perfil de Aluno</title>
</head>
<body>
  <h1 id="titulo">João Silva</h1>
  <img src="imagem.jpg" alt="Imagem de perfil" class="perfil">
  <p id="descricao">Sou estudante de programação e apaixonado por tecnologia!</p>
  <ul class="habilidades">
    <li>Desenvolvimento Web</li>
    <li>Design Gráfico</li>
    <li>Redes de Computadores</li>
  </ul>
  <a href="https://linkedin.com" class="rede-social">Conecte-se comigo!</a>
</body>
</html>
```

**CSS (incompleto, a ser feito pelos alunos):**
```css
body {
  background-color: #f5f5f5;
  font-family: Arial, sans-serif;
}

#titulo {
  /* Alterar a cor e o tamanho */
}

.perfil {
  /* Adicionar borda arredondada */
}

#descricao {
  /* Adicionar padding */
}

.habilidades li {
  /* Estilizar os itens da lista */
}

.rede-social:hover {
  /* Alterar cor ao passar o mouse */
}
```
