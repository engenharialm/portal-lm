# Portal LM

Página inicial que reúne os sistemas da LM Construtora: **Licitações**, **Produção** (Diário de Produção) e **Controle** (mão de obra e equipamentos).

- Cada cartão abre o sistema no endereço dele; os sistemas continuam independentes.
- Senha por sistema: no início do script em `index.html`, troque `senha: null` por `senha: "suaSenha"`. É uma trava para uso casual (sem servidor), quem tiver o link direto do sistema ainda entra por ele.
- Atalhos: teclas 1, 2 e 3 abrem cada sistema.

**Status:** em uso geral (aprovado em 26/10/2026).

## Sistemas
- **Licitações** → https://engenharialm.github.io/licitacoes/ (site oficial, livre)
- **Controle** → https://engenharialm.github.io/controle-lm/ (site oficial, livre)
- **Obras** → pasta `producao/` deste repositório. **Em desenvolvimento**: no portal fica com a etiqueta e pede a senha de acesso geral. Usa os dados reais da equipe.

As pastas `licitacoes/` e `controle/` eram cópias de teste; agora só redirecionam para os sites oficiais (e removem o service worker antigo de quem as abriu).
