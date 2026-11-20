# Tomb Survivors — downloads oficiais

Roguelite de sobrevivência em uma tumba egípcia, com visual cartunesco e visão isométrica.

Este repositório guarda **só os downloads** do jogo (o código-fonte não fica aqui).

## Como jogar

- **Pelo NexStage:** o Tomb Survivors aparece na biblioteca do launcher, que instala, atualiza e verifica o jogo
  automaticamente.
- **Download manual:** na página [Releases](../../releases/latest), baixe `TombSurvivors-<versão>-windows.zip`,
  extraia e abra `TombSurvivors.exe`.

Requisitos: Windows 10/11 64 bits e placa de vídeo com Vulkan.

## Integridade

Cada versão publica um `manifest.json` com o tamanho e o SHA-256 de cada arquivo, assinado com Ed25519
(`manifest.json.sig`). O NexStage só instala arquivos de um manifesto com assinatura válida e confere o SHA-256
de tudo antes de trocar de versão.
