# [Portfólio - Sthefany Anaide]

## Descrição

Este projeto é um portfólio pessoal, sendo um site de página única (one-page) com navegação por âncoras, apresentando trajetória profissional, habilidades técnicas, projetos desenvolvidos e formulário de contato funcional, tudo em um visual inspirado em jogos 8-bit.

*   **Motivação:** Eu precisava criar um portfólio e também queria praticar HTML e CSS, então foi uma boa prática iniciar este projeto, inclusive desenvolvendo o protótipo no Figma.

## Tecnologias Utilizadas

* HTML5 semântico
* CSS3 
* JavaScript (vanilla)

## Instalação e Uso

Siga os passos abaixo para rodar o projeto na sua máquina:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/SthefanySaturnino/Meu-Portfolio.git
    ```
    
2.  **Entre na pasta do projeto:**
    ```bash
    cd NOME_DO_REPOSITORIO
    ```

3.  **Execute o projeto:**
    ```bash
    npm start
    # ou
    python main.py
    ```
## Configurando o formulário de contato

O formulário usa o serviço gratuito Web3Forms para enviar as mensagens direto para uma caixa de e-mail, sem precisar de backend próprio.

Acesse web3forms.com e gere sua Access Key com o e-mail de destino
No index.html, substitua o valor do campo oculto:

html<input type="hidden" name="access_key" value="SUA_ACCESS_KEY_AQUI">

## Contribuição

Se você quiser melhorar este projeto, sinta-se à vontade para:

1.  Fazer um **Fork** do projeto.
2.  Criar uma nova *branch* (`git checkout -b feature/melhoria`).
3.  Fazer suas alterações e *commit*.
4.  Abrir um **Pull Request**.