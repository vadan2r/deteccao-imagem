# primeiro repositorio
## Projeto DIO Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso

## Passo a Passo: Criar um Primeiro Repositório no GitHub Para Compartilhar Seu Progresso

Este guia detalha como criar um repositório no GitHub e como usar o Git para enviar seu código para lá.

**Pré-requisitos:**

*   **Conta no GitHub:** Crie uma conta gratuita no GitHub se você ainda não tiver uma.
*   **Git Instalado:** Certifique-se de ter o Git instalado no seu computador. Você pode verificar digitando `git --version` no terminal/prompt de comando. Se não estiver instalado, baixe e instale a versão adequada para o seu sistema operacional em [https://git-scm.com/downloads](https://git-scm.com/downloads).

**Passo 1: Criar um Repositório no GitHub**

1.  **Acesse o GitHub:** Vá para o site do GitHub ([https://github.com/](https://github.com/)) e faça login na sua conta.

2.  **Clique no botão "+":** No canto superior direito da tela, clique no botão "+" e selecione "New repository".

3.  **Preencha as informações do repositório:**

    *   **Repository name:** Digite um nome descritivo para o seu repositório. Use letras minúsculas, números e hífens (ex: "meu-primeiro-repositorio").
    *   **Description (opcional):** Adicione uma breve descrição do que é o seu projeto.
    *   **Public ou Private:** Escolha se o repositório será público (visível para todos) ou privado (visível apenas para você e colaboradores que você adicionar). Para aprendizado e compartilhamento de projetos, geralmente *Public* é a melhor opção.
    *   **Initialize this repository with:**
        *   **Add a README file:** Marque esta opção. Um arquivo README é essencial para explicar o propósito e o uso do seu projeto.
        *   **Add .gitignore:** (Opcional) Se o seu projeto usa uma linguagem de programação específica (como Python, Java, etc.), você pode selecionar um template `.gitignore` para essa linguagem. Isso ajuda a evitar o envio de arquivos desnecessários (como arquivos de cache, arquivos de ambiente virtual) para o repositório.
        *   **Choose a license:** (Opcional, mas recomendado) Escolher uma licença define como outras pessoas podem usar o seu código.  Se você não tem certeza qual licença usar, a licença *MIT* é uma escolha comum e permissiva.

4.  **Clique em "Create repository":**  Depois de preencher as informações, clique no botão "Create repository" para criar o repositório.

**Passo 2: Clonar o Repositório para o Seu Computador**

1.  **Na página do repositório, clique no botão "Code":** Ele estará na cor verde.

2.  **Copie o URL do repositório:** Certifique-se de que "HTTPS" está selecionado e copie o URL exibido (algo como `https://github.com/seu-usuario/meu-primeiro-repositorio.git`).

3.  **Abra o terminal/prompt de comando:** Abra o terminal (Linux/macOS) ou o prompt de comando (Windows) no seu computador.

4.  **Navegue até o diretório onde você quer salvar o projeto:** Use o comando `cd` para navegar até a pasta onde você deseja clonar o repositório. Por exemplo: `cd Documentos/Projetos`.

5.  **Clone o repositório:** Use o comando `git clone` seguido do URL que você copiou:

    ```bash
    git clone https://github.com/seu-usuario/meu-primeiro-repositorio.git
    ```

    Substitua `https://github.com/seu-usuario/meu-primeiro-repositorio.git` pelo URL que você copiou.

6.  **Acesse a pasta do repositório:** Use o comando `cd` para entrar na pasta do repositório clonado:

    ```bash
    cd meu-primeiro-repositorio
    ```

**Passo 3: Adicionar e Enviar Seu Código**

1.  **Crie seus arquivos de código:** Crie os arquivos com seu código dentro da pasta do repositório clonado.

2.  **Adicione os arquivos ao Git:** Use o comando `git add` para adicionar os arquivos que você criou ao Git.

    *   Para adicionar todos os arquivos novos e modificados, use:

        ```bash
        git add .
        ```

    *   Para adicionar um arquivo específico, use:

        ```bash
        git add nome_do_arquivo.extensao
        ```

3.  **Faça um commit:** Use o comando `git commit` para registrar as alterações no seu repositório local. É fundamental escrever uma mensagem de commit clara e concisa descrevendo as mudanças que você fez.

    ```bash
    git commit -m "Adiciona meu primeiro código"
    ```

4.  **Envie as alterações para o GitHub:** Use o comando `git push` para enviar as alterações do seu repositório local para o repositório remoto no GitHub:

    ```bash
    git push origin main
    ```

    *   `origin` é o nome do repositório remoto (normalmente, é `origin` por padrão).
    *   `main` é o nome da branch para a qual você está enviando as alterações (normalmente, é `main` por padrão).  Se sua branch se chama `master`, você usaria `git push origin master`.

    **Autenticação:** Se for a primeira vez que você está enviando código para o GitHub a partir do seu computador, pode ser solicitado que você faça login na sua conta do GitHub através do seu navegador ou usando um token de acesso pessoal.

**Passo 4: Verifique Seu Repositório no GitHub**

1.  **Acesse o GitHub:** Vá para a página do seu repositório no GitHub.

2.  **Verifique os arquivos:** Você deverá ver os arquivos que você adicionou e enviou.

**Próximos Passos:**

*   **Modifique o README:** Edite o arquivo `README.md` para adicionar uma descrição mais detalhada do seu projeto.  Use a sintaxe Markdown para formatar o texto.

*   **Crie Branches:** Use branches para trabalhar em novas funcionalidades ou correções de bugs sem afetar a versão principal do seu código.

*   **Faça Pull Requests:** Se você estiver colaborando com outras pessoas, use pull requests para solicitar que suas alterações sejam revisadas e integradas à versão principal do código.

*   **Aprenda Mais sobre Git:** Explore os diversos comandos e recursos do Git para gerenciar seu código de forma eficiente. Existem muitos tutoriais e documentação online disponíveis.

Parabéns! Você criou seu primeiro repositório no GitHub e compartilhou seu progresso! Este é um passo importante para colaborar com outros desenvolvedores e construir projetos cada vez maiores e mais complexos.
