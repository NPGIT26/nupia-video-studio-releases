# NUPIA Video Studio — Releases

Este repositório guarda **apenas os binários assinados** e o `latest.json` que o auto-updater do app consome. 

**O código-fonte NÃO está aqui** — ele é privado.

Cada release contém:
- `NUPIA-Video-Studio_<versao>_aarch64.app.tar.gz` — bundle de atualização (assinado)
- `latest.json` — manifesto lido pelo updater
- `.dmg` — instalador para download manual

A segurança vem da assinatura (rsign/Ed25519): o app só instala updates carimbados com a chave privada do autor, então a hospedagem pública não compromete nada.
