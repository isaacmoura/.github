# Como contribuir

Vale para todos os repositórios da org **isaacmoura**. O detalhe de cada passo está no cofre de engenharia
(repositório `platform`, só para membros).

1. **Comece por uma issue** (formulários: Bug, Feature, Customização de cliente, Tarefa técnica). Algo fora do ar
   ou degradado para os usuários vira um **Incidente**, aberto no repositório privado `platform`.
2. **Crie uma branch curta** a partir da `main`: `feat/123-descricao`, `fix/456-descricao`, `chore/…`, `docs/…`.
3. **Abra o PR cedo.** O título segue Conventional Commits (`feat(orders): permite cancelar pedido`) — ele vira o commit.
4. **CI verde** é obrigatório: build, formatação, testes e varredura de segredos.
5. **Revisão**: o PR recebe um rótulo de governança automaticamente. Nível 2 (infra do produto) e
   nível 3 (plataforma compartilhada) pedem revisão de `@isaacmoura/platform`.
6. **Squash merge.** A branch é apagada automaticamente.
7. **Release** é automático: o release-please abre um PR de release com versão e CHANGELOG; ao mergear, publica.

Nunca faça push direto na `main`, não crie branches permanentes por cliente e não commite segredos ou dados pessoais.
