# Manual de comentários do Git Commit
| Tipo      | Quando usar                                                                 | Exemplos de mensagem                                                    |
|----------|------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| feat     | Para **nova funcionalidade** que o usuário final consegue perceber.         | `feat: adiciona página de perfil do usuário`                            |
| fix      | Para **correção de bug** ou comportamento errado.                           | `fix: corrige erro ao calcular total do carrinho`                       |
| chore    | Para **tarefas de manutenção** que não alteram a funcionalidade em si.      | `chore: atualiza dependências`, `chore: configura ambiente de testes`   |
| refactor | Para **melhorar o código** sem mudar o comportamento externo.               | `refactor: simplifica lógica de autenticação`                           |
| docs     | Para mudanças **apenas em documentação**.                                   | `docs: adiciona instruções de setup no README`                          |
| style    | Para mudanças de **formatação** sem impacto na lógica.                      | `style: aplica formatação com prettier`                                 |
| test     | Para adicionar ou alterar **testes automatizados**.                         | `test: adiciona testes para serviço de pagamento`                       |
| perf     | Para mudanças focadas em **melhorar performance**.                          | `perf: otimiza consulta ao banco de dados`                              |
| build    | Para mudanças em **build, bundlers ou ferramentas de compilação**.          | `build: ajusta configuração do webpack`                                 |
| ci       | Para mudanças em **pipelines de CI/CD**.                                    | `ci: ajusta workflow do GitHub Actions`                                 |
| revert   | Para **reverter** um commit anterior.                                       | `revert: reverte commit abc123 que alterava layout do header`           |
| chore(wip)| (opcional, em branch própria) para **trabalho em progresso** não finalizado.| `chore(wip): protótipo de tela de configurações`                         |
