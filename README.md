# Criando-seu-Primeiro-Site-Completo-com-HTML

Entendendo melhor o projeto e dando exemplos práticos. Vamos dividir o projeto em módulos, conforme as páginas que precisa criar.

### Módulo 1: Página Principal
A **Página Principal** é a primeira impressão que o visitante terá do site, então é importante que ela seja convidativa e informativa. Aqui está um exemplo de como você pode estruturar o HTML:

```html
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <title>Clínica Médica</title>
</head>
<body>
    <nav>
        <!-- Menu de navegação -->
    </nav>
    <header>
        <!-- Imagem do Header -->
    </header>
    <main>
        <!-- Breve descrição sobre a clínica -->
    </main>
    <footer>
        <!-- Informações de contato -->
    </footer>
</body>
</html>
```

### Módulo 2: Sobre a Clínica
Na página **Sobre a Clínica**, você deve fornecer informações detalhadas sobre a clínica, como história, missão, visão e valores. Exemplo:

```html
<main>
    <!-- Texto falando sobre a clínica -->
</main>
```

### Módulo 3: Horário de Atendimento
A página de **Horário de Atendimento** deve listar os serviços oferecidos e os horários disponíveis. Use uma tabela para organizar as informações:

```html
<main>
    <!-- Pequeno texto sobre os serviços -->
    <table>
        <!-- Tabela de preços e horários -->
    </table>
</main>
```

### Módulo 4: Contato
A página de **Contato** deve facilitar a comunicação entre a clínica e os pacientes. Inclua um formulário de contato e informações para que os pacientes possam entrar em contato facilmente:

```html
<main>
    <!-- Informações de contato e formulário -->
</main>
```

Lembre-se de que cada página deve seguir o template fornecido, com as devidas alterações no conteúdo (`<main>`), imagens (`<header>`) e informações de contato (`<footer>`). As tags `<nav>`, `<header>`, `<main>` e `<footer>` ajudam a estruturar semanticamente o seu site.

Para adicionar imagens no **header** e no **footer** do seu site HTML, você pode usar a tag `<img>` dentro das tags `<header>` e `<footer>`. Aqui está um exemplo de como você pode fazer isso:

```html
<header>
    <!-- Imagem do Header -->
    <img src="caminho_para_sua_imagem.jpg" alt="Descrição da Imagem">
</header>
...
<footer>
    <!-- Informações de contato e imagem no Footer -->
    <img src="caminho_para_sua_imagem_no_footer.jpg" alt="Descrição da Imagem">
    <!-- Outras informações de contato -->
</footer>
```

No atributo `src`, você deve colocar o caminho para a imagem que deseja exibir. Pode ser um caminho relativo ao seu projeto ou um URL absoluto. O atributo `alt` é uma descrição alternativa da imagem, que é importante para acessibilidade e SEO, caso a imagem não possa ser exibida.

Lembre-se de substituir `"caminho_para_sua_imagem.jpg"` pelo caminho real da imagem que você quer usar. Se as imagens estiverem na mesma pasta que o seu arquivo HTML, basta colocar o nome do arquivo da imagem. Se estiverem em pastas diferentes, você precisará especificar o caminho relativo ou absoluto.

https://github.com/digitalinnovationone/trilha-html-modulo-2
