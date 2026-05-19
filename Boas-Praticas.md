1 - Faça Commits Atômicos e Frequentes
O que é: Confirme pequenas alterações focadas em uma única funcionalidade, melhoria ou correção de bug de cada vez.

Por que adotar: Se um erro for introduzido, fica muito mais fácil encontrar qual commit causou o problema e, se necessário, reverter apenas aquela alteração específica sem afetar o resto do sistema.

2 - Escreva Mensagens de Commit Claras e Descritivas
O que é: Use um padrão reconhecível para explicar o que o commit faz. Prefira o modo imperativo (ex: "Adiciona botão de login", "Corrige falha na listagem") e inclua referências a tickets ou cartões de tarefas quando aplicável.

Por que adotar: O histórico do Git é a documentação viva do projeto. Mensagens objetivas permitem que qualquer pessoa da equipe entenda o motivo da alteração sem precisar ler o código-fonte.

3 - Isole o Desenvolvimento em Branches
O que é: Nunca altere o código diretamente na branch principal (main ou master). Crie ramificações (branches) separadas para cada nova funcionalidade (feature/) ou correção de erro (bugfix/).

Por que adotar: Isso mantém a branch principal sempre estável e pronta para produção. Além disso, permite que você submeta seu código para revisões (Pull Requests) de forma isolada
