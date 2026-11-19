# Instruções para o Claude: repositório de criativos

Este repositório guarda **todos os criativos** que produzimos e a **inteligência** que
vamos acumulando (o que funciona, o que não funciona, tom de voz, público, referências).
O objetivo é que nada se perca entre uma conversa e outra.

## Ao começar qualquer sessão
1. Leia `marca/perfil.md` (quem é a marca, tom de voz, regras).
2. Leia `inteligencia/aprendizados.md` (o que já aprendemos; siga essas lições).
3. Leia as últimas entradas de `historico/registro.md` para saber onde paramos.

## Enquanto trabalha
- Cada campanha ou projeto ganha uma pasta em `campanhas/AAAA-MM-nome-curto/`,
  copiada de `campanhas/_modelo/`.
- Salve **tudo** que for produzido: briefing, textos, roteiros, prompts de imagem/vídeo,
  variações, e os arquivos finais em `entregas/`.
- Quando o usuário aprovar, rejeitar ou comentar algo, registre o motivo.
  Esses motivos viram aprendizados.

## Ao terminar uma tarefa (sempre)
1. Atualize `inteligencia/aprendizados.md` com qualquer lição nova
   (ex.: "headline com pergunta teve mais aprovação que afirmação").
2. Se surgir informação sobre a marca, o público ou referências, atualize
   `marca/perfil.md`, `inteligencia/publico.md` ou `inteligencia/referencias.md`.
3. Adicione uma entrada em `historico/registro.md` (data, o que foi feito, próximos passos).
4. Faça commit e push na `main`. Mensagens de commit em português, curtas e descritivas.
   O usuário pediu para manter tudo salvo, então o commit/push ao fim de cada tarefa
   é esperado, sem precisar perguntar.

## Convenções
- Tudo em português do Brasil.
- Nomes de arquivos e pastas em minúsculas, sem acento, com hífen: `post-lancamento-v2.md`.
- Versões: `-v1`, `-v2`... nunca sobrescreva uma versão aprovada; crie uma nova.
- Arquivos muito grandes (vídeos brutos, >50 MB) não vão para o Git: salve só o link
  e a descrição.
