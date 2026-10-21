# Portal LM

Página inicial que reúne os sistemas da LM Construtora: **Licitações**, **Produção** (Diário de Produção) e **Controle** (mão de obra e equipamentos).

- Cada cartão abre o sistema no endereço dele; os sistemas continuam independentes.
- Senha por sistema: no início do script em `index.html`, troque `senha: null` por `senha: "suaSenha"`. É uma trava para uso casual (sem servidor), quem tiver o link direto do sistema ainda entra por ele.
- Atalhos: teclas 1, 2 e 3 abrem cada sistema.

**Status:** em teste, ainda não aprovado.

## Cópias de teste com o visual novo
As pastas `licitacoes/`, `producao/` e `controle/` são cópias dos sistemas oficiais com o visual do portal e o botão "← Portal".
Elas usam **os mesmos dados da equipe** (o que for salvo nelas vale de verdade). Os sites oficiais não foram alterados.
Na aprovação: aplicar o visual nos repositórios oficiais, apontar os cartões do portal de volta para os endereços oficiais e apagar estas pastas.
