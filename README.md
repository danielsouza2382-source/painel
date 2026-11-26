# Meu painel

Agenda (dia, semana e mês), finanças e investimentos, faculdade, trabalho e hábitos num site só, que funciona no celular e no computador e pode ser instalado como app.

O site é este repositório publicado pelo GitHub Pages. **Os seus dados não ficam aqui**: ficam no repositório privado `painel-dados`, um arquivo por área (`data/agenda…`, `data/fin-2026.json` etc.). Cada alteração é enviada na hora, e as dos outros aparelhos chegam a cada 20 segundos. Sem internet, o painel continua funcionando e envia tudo quando a conexão volta.

## Primeira configuração (uma vez só)

1. Crie um token em <https://github.com/settings/personal-access-tokens/new>:
   - **Repository access**: *Only select repositories* → `painel-dados`
   - **Permissions**: *Contents* → *Read and write*
   - Validade: a mais longa disponível
2. Abra o site, informe `seu-usuario/painel-dados` e cole o token.

## Outros aparelhos

No aparelho já conectado, vá em **Ajustes › Conectar outro aparelho** e aponte a câmera do celular para o QR code. O link contém o token: não compartilhe.

## Instalar como app

- **iPhone (Safari)**: Compartilhar › Adicionar à Tela de Início.
- **Android (Chrome)**: menu ⋮ › Instalar app / Adicionar à tela inicial.
- **Computador (Chrome/Edge)**: ícone de instalar na barra de endereço.

## Quando o token vencer

O indicador no topo fica vermelho (“Reconectar GitHub”). Crie um token novo do mesmo jeito e conecte de novo; nenhum dado se perde.
