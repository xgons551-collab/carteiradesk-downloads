# CarteiraDesk — Downloads e Atualizações

Este repositório público serve **exclusivamente para distribuir versões compiladas** do CarteiraDesk para Windows.

## Conteúdo publicado
As versões oficiais serão disponibilizadas em **Releases**, cada uma contendo:
- `CarteiraDesk_Windows.zip`: aplicativo Windows (sem dados de usuário).
- `carteiradesk-update.json`: manifesto de atualização assinado digitalmente (Ed25519).

O aplicativo deve confirmar a assinatura e o hash SHA-256 do arquivo antes de instalar atualizações.

## Privacidade e segurança
- O código-fonte é mantido em repositório **privado** separado.
- Não publique carteiras, bancos de dados SQLite, credenciais, tokens ou chaves privadas.
- A assinatura privada de atualizações **não é armazenada neste repositório**.
- Até que uma versão seja publicada, este canal **não disponibiliza instaladores**.

## Sobre
CarteiraDesk é um gerenciador pessoal de investimentos. Não executa ordens de compra ou venda em corretoras.
