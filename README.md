# Octa-Access

Painel de controle alternativo, totalmente acessível por voz, para a interface de áudio USB Roland OCTA-CAPTURE — pensado desde o início para o [NVDA](https://www.nvaccess.org/), já que o software oficial da Roland não é utilizável com leitor de tela.

Controla ganho, phantom power, low cut, phase invert, compressor (Gate/Attack/Release/Threshold/Ratio/Output Gain), os 4 mixes de Monitoramento Direto e de Playback, Masters, Patch Bay, Reverb, Auto-Sens e Sample Rate — tudo lido e escrito ao vivo no hardware real. Tem um Monitor de Clipping com reação de poucos milissegundos (ouve o áudio diretamente de todas as 10 entradas), roda em segundo plano na bandeja do sistema, e troca de idioma (English/Français/Español/Português) ao vivo, sem reiniciar.

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)** deste repositório. O pacote já vem pronto pra rodar no Windows — não precisa instalar Python nem compilar nada.

Cada Release traz as notas da versão com o hash **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali — cópias obtidas por qualquer outro canal não têm garantia de integridade.

## Requisitos

- Windows 10/11 (64 bits), com o driver da Roland OCTA-CAPTURE instalado e a interface conectada por USB.
- [NVDA](https://www.nvaccess.org/) é o leitor de tela com suporte principal (o programa também tem rotas alternativas pra leitores compatíveis com Tolk e pro SAPI do Windows).

## Manual

O manual completo, em English/Français/Español/Português, vem incluso dentro do zip do programa e também disponível como arquivo separado na página de Releases.

## Licença

Veja [LICENSE](LICENSE) para termos de uso e créditos de terceiros.
