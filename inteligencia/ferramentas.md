# Ferramentas de IA

Quais ferramentas usamos para gerar criativos e como acessá-las.

## Vídeo: Kling (via Higgsfield)
Não existe conector oficial do Kling no Claude. Usamos os modelos Kling pelo
conector **Higgsfield**, que já está ligado e cobra por créditos da conta Higgsfield.

| Modelo | Quando usar |
|---|---|
| `kling4_0` | Melhor qualidade: texto, imagem, referências ou edição de vídeo, até 30 s, 1080p |
| `kling_4_0_flash` | Testes rápidos e baratos, 720p, até 20 s |
| `kling3_0` | Primeiro e último quadro, áudio nativo, modo 4K |
| `kling_o3_image_reference` | Até 7 imagens de referência (produto, personagem), multi-cena |
| `kling3_0_motion_control` | Transferir o movimento de um vídeo para uma imagem |
| `kling_video_edit` | Editar um vídeo existente com instruções em texto |

Formatos: 9:16 (reels/stories), 1:1 (feed), 16:9 (YouTube).
Fluxo sugerido: testar no `kling_4_0_flash` e gerar a versão final no `kling4_0`.
Sempre salvar o prompt usado no briefing da campanha.
