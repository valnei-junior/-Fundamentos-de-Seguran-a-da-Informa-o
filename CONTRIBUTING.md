# Guia de Contribuição

## Como Contribuir

1. **Faça um Fork do Repositório**:
   - Acesse o repositório principal em: [https://github.com/vlimap/cursos_gratis_com_certificado.git](https://github.com/vlimap/cursos_gratis_com_certificado.git).
   - Clique em "Fork" para criar uma cópia do repositório na sua conta do GitHub.
   - Esse repositório *forked* será o espaço de trabalho do seu grupo.

2. **Clone o Repositório Forked**:
   - Clone o repositório *forked* para a sua máquina local:
     ```bash
     git clone https://github.com/sua-conta/cursos_gratis_com_certificado.git
     ```
   - Substitua `sua-conta` pelo seu nome de usuário no GitHub.

3. **Criação de Branch Individual**:
   - Cada integrante deve criar uma branch própria para seu subtema:
     ```bash
     git checkout -b nome-da-branch
     ```
   - Use um nome de branch relacionado ao subtema que você está desenvolvendo, como `desenvolvimento_web` ou `seguranca_informacao`.

4. **Desenvolvimento da Pesquisa**:
   - Crie um arquivo Markdown (`.md`) contendo sua pesquisa sobre o subtema.
   - Nomeie o arquivo de forma que reflita o conteúdo, por exemplo: `desenvolvimento_web.md`, `gestao_projetos_ti.md`.
   - Adicione e comite suas alterações:
     ```bash
     git add .
     git commit -m "docs: adiciona pesquisa sobre [subtema]"
     ```
   - Realize pelo menos 5 commits ao longo do desenvolvimento, registrando o progresso do trabalho.

5. **Sincronize com o Repositório Forked**:
   - Antes de enviar suas alterações, certifique-se de atualizar sua branch com possíveis mudanças do repositório original:
     ```bash
     git fetch origin
     git merge origin/main
     ```

6. **Envie suas Alterações para o Repositório Forked**:
   - Suba suas alterações para o GitHub:
     ```bash
     git push origin nome-da-branch
     ```

7. **Criação de um Pull Request (PR)**:
   - No GitHub, acesse seu repositório *forked* e clique em "Compare & pull request".
   - Escreva uma descrição clara sobre as alterações feitas e a pesquisa desenvolvida.
   - Envie o PR para a branch `main` do repositório *forked* do seu grupo.

8. **Revisão e Aprovação do Pull Request**:
   - Os outros membros do grupo devem revisar o PR e sugerir melhorias, se necessário.
   - Após a aprovação do PR, faça o *merge* das alterações no repositório *forked* do grupo.

9. **Envio do Pull Request Final**:
   - Com todas as contribuições dos membros integradas ao repositório *forked* do grupo, crie um PR para o repositório principal: [cursos_gratis_com_certificado](https://github.com/vlimap/cursos_gratis_com_certificado.git).
   - A descrição do PR deve conter um resumo das contribuições de cada integrante e links para os arquivos dos subtemas.

10. **Acompanhe o Feedback e Realize Ajustes**:
    - Acompanhe o PR no repositório principal para responder a feedbacks ou realizar ajustes até que o PR seja aceito.
