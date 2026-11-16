# ClipForge — canal público de versões verificadas

**Estado: preparado, mas ainda sem atualizações publicadas.**

Este repositório distribui pacotes ClipForge com SHA-256 e assinatura Ed25519. O desenvolvimento fica no repositório privado clipforge-updates.

**Privacidade:** qualquer pessoa poderá baixar e ler o código contido nos ZIPs publicados. Não incluir chaves de API, tokens, config_local.bat, .env, dados pessoais, bancos de dados ou vídeos.

## URL estável do manifesto (depois da primeira release)

https://github.com/adriancesarpf1-cmyk/clipforge-releases/releases/latest/download/manifest.json

Até a primeira release assinada esse endereço pode responder 404. O atualizador Windows deve permanecer desativado.

## Assets previstos por versão

- clipforge-VERSAO.zip — pacote com release.json e arquivos permitidos pelo cliente 1.16
- manifest.json — versão, URL, hash SHA-256 e assinatura Ed25519
- clipforge-public-key.pem — chave pública de verificação inicial, nunca substituir uma chave já fixada sem revisão

A publicação depende de código completo, segredos GitHub Actions e testes no workflow privado. Nenhum programa Windows é instalado só por conectar este repositório.
