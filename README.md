# trabalho-ihc

Protótipo de interface de um sistema de biblioteca desenvolvido como trabalho da disciplina de Interação Humano-Computador (IHC). O projeto simula as telas e fluxos de navegação de um sistema real, sem integração com backend — todos os dados são estáticos.

## Sobre o Projeto

O protótipo apresenta dois perfis de acesso com menus e funcionalidades distintas: **Associado** e **Bibliotecário**. A navegação entre seções é feita via sidebar, e o conteúdo é exibido dinamicamente por alternância de visibilidade via JavaScript puro.

## Telas e Funcionalidades Simuladas

### Associado
- **Acervo** — listagem de itens com status de disponibilidade e botão de solicitação ou lista de espera
- **Empréstimos** — visualização dos empréstimos ativos com indicação de atraso e multa
- **Histórico** — registro de devoluções anteriores com status de pontualidade

### Bibliotecário
- **Cadastrar Usuário** — formulário de cadastro de novo associado
- **Cadastrar Item** — formulário com alternância entre cadastro de livro e revista
- **Gerenciar** — busca de associado e devolução de itens emprestados

## Tecnologias

- **HTML5** — estrutura semântica de toda a interface
- **CSS3** — layout com Flexbox, variáveis de cor, estilização de inputs e sidebar
- **JavaScript** — controle de login/logout, navegação entre seções e alternância de formulário por tipo de item

## Observação

Por se tratar de um protótipo de interface para fins acadêmicos, não há backend nem persistência de dados. As informações exibidas nas telas são estáticas e servem apenas para demonstração visual dos fluxos.

## Autor

Mateus Hahn — mateushahn333@gmail.com

- GitHub: [github.com/mateushahndev](https://github.com/mateushahndev)
- LinkedIn: [linkedin.com/in/mateushahndev](https://www.linkedin.com/in/mateushahndev)