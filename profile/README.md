## Padrões de commit
- **feat**: Um novo recurso para a aplicação, e não precisa ser algo grande, mas apenas algo que não existia antes e que a pessoa final irá acessar.
- **fix**: Correções de bugs
- **docs**: Alterações em arquivos relacionados à documentações
- **style**: Alterações de estilização, formatação etc
- **refactor**: Um codigo de refatoração, ou seja, que foi alterado, que tem uma mudança transparente para o usuário final, porém uma mudança real para a aplicação
- **perf**: Alterações relacionadas à performance
- **test**: Criação ou modificação de testes
- **chore**: Alterações em arquivos de configuração, build, distribuição, CI, ou qualquer outra coisa que não envolva diretamente o código da aplicação para o usuário final

## Nome da Branch
### Padrão:
```<padrão-de-commit>/<resumo-da-task> ```

### Exemplo:
```git checkout -b feat/create-post-api```

## Padrão de descrição para Pull Request

### Card do Trello
https://trello.com/b/8kZmNsH2/gestão-morus

### Descrição da task
- Adicione a propridade description (optional) na interface ICardProps.

### Mudanças Feitas
- Adição de nova prop em ICardProps
  ```
  export interface ICardProps { id: string, title: string, description?: string }
  ```

## Contribuintes
<div>
  <a href="https://github.com/larissadantier"><img src="https://avatars.githubusercontent.com/larissadantier?size=100" /></a>
  <a href="https://github.com/eduardoangelosimon"><img src="https://avatars.githubusercontent.com/eduardoangelosimon?size=100" /></a>
  <a href="https://github.com/palharesgab"><img src="https://avatars.githubusercontent.com/palharesgab?size=100" /></a>
  <a href="https://github.com/Elisa-git"><img src="https://avatars.githubusercontent.com/Elisa-git?size=100" /></a>
  <a href="https://github.com/AlinePBrandao"><img src="https://avatars.githubusercontent.com/AlinePBrandao?size=100" /></a>
</div>

  [Angelo Salvador](https://github.com/AngeloSalvador)
  [Nicolas Montovaneli](https://github.com/nick000895)
