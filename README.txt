# Scout DNA Vôlei — versão inicial

## O que já funciona
- Cadastro de jogo, data, local, adversário e atletas.
- Registro de recepção com posição P1–P6, passe A/B/C/Quebrou, levantamento P/M/S/Pf/Sf/2ª e tipo de bola.
- Histórico por set com edição e exclusão.
- Substituição de atleta preservando os lançamentos anteriores.
- Fechamento de set com placar e abertura do próximo.
- Encerramento do jogo e relatório individual.
- Salvamento local no navegador e cache PWA para uso offline após instalação/carregamento inicial.
- Exportação de backup JSON.

## Como instalar no Android
1. Publique estes arquivos em um endereço HTTPS (por exemplo, GitHub Pages).
2. Abra o endereço no Chrome do Android com internet.
3. Aguarde carregar e use o menu ⋮ > **Instalar app** ou **Adicionar à tela inicial**.
4. Abra o app uma vez online. Depois, os arquivos do aplicativo ficam disponíveis offline.

## Importante
- Os dados ficam armazenados localmente no navegador/aplicativo daquele aparelho. Não limpe os dados do Chrome nem desinstale sem exportar um backup.
- A sincronização entre aparelhos ainda não está incluída.
- O relatório inicial considera passe A+B como positivo e Quebrou como erro; C fica separado. Essa regra deve ser validada pela comissão técnica antes de usar os indicadores como avaliação oficial.
- Posições sem observação não são inventadas como lançamentos; aparecem fora das estatísticas observadas. A estimativa por média será aprimorada na próxima versão, para não distorcer o scout.
- Esta é uma versão inicial para testes. Faça um jogo simulado e confira os dados antes de usar em competição oficial.
