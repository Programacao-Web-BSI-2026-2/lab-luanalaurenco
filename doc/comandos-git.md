# Guia de Comandos Git

Aqui estão os 4 comandos básicos do Git que utilizamos para versionar e enviar nossos projetos para o GitHub:

*   **`git clone <url-do-repositorio>`**
    *   **O que faz:** Baixa (copia) um repositório que está no GitHub (remoto) para a sua máquina local pela primeira vez.

*   **`git add .`** *(ou `git add nome-do-arquivo`)*
    *   **O que faz:** Prepara os arquivos modificados ou criados para serem "salvos". Ele coloca as alterações na área de *staging*.

*   **`git commit -m "sua mensagem aqui"`**
    *   **O que faz:** Salva as alterações que estavam no *staging* no histórico do seu repositório local. A mensagem entre aspas deve explicar brevemente o que você mudou.

*   **`git push origin main`**
    *   **O que faz:** Envia os commits que você fez na sua máquina local para o repositório remoto no GitHub, deixando o projeto online atualizado.
