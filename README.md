# Procedimentos da Central de Ajuda — extensão AloChat

Extensão do AloChat (painel lateral do atendimento) que busca os artigos de
https://ajuda.minhaentrada.com.br e envia o procedimento, com as imagens do passo a passo, no chat.

- `manifest.json` — manifest da extensão (instale pela URL `https://eleuteriobrayan.github.io/alochat-ajuda-ext/manifest.json`).
- `painel.html` — contribuição `chatPanel`.
- `midias.json` — mapa imagem da central → `fileId` já cadastrado no AloChat (galeria "Ajuda - ...").

Para publicar uma versão nova: aumente `version` no manifest, faça push na `main` e rode
"Reconsultar o manifest" na instalação do AloChat.
