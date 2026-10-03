# Segurança

Encontrou uma vulnerabilidade ou um segredo exposto?

- **Não** abra issue pública nem comente em PR.
- **Fora da org:** use o reporte privado de vulnerabilidades do GitHub neste repositório — aba
  **Security → Report a vulnerability** em <https://github.com/isaacmoura/.github/security>. Só os mantenedores
  veem o relato.
- **Membros da org:** abra uma issue no repositório privado `isaacmoura/platform` (só membros têm acesso) com o
  rótulo `seguranca` — sem permissão para aplicar rótulos, comece o título com `[Segurança]` —, ou fale direto com
  alguém do time `@isaacmoura/platform`.
- Não cole o segredo no relato: diga onde ele está (repositório, arquivo, commit).
- Se for um segredo (token, senha, chave) que vazou: ele deve ser **revogado e trocado** — apagar do código não basta,
  porque continua no histórico do git.
