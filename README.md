# SHARK7 AUTOPOST — versão inicial

Interface inicial mobile-first para FTV SHARK7.

## O que funciona nesta versão
- Interface preta e amarela responsiva.
- Pré-visualização local de um vídeo escolhido no aparelho.
- Geração de rascunhos de legenda usando modelos locais (não IA).
- Cópia de legenda.
- Planejamento local de data/horário durante a sessão do navegador.

## O que ainda NÃO funciona
- Não analisa automaticamente o conteúdo do vídeo com IA.
- Não envia vídeos para um servidor.
- Não salva os planos de forma permanente.
- Não agenda nem publica Reels no Instagram.
- Não contém integração com Meta API nem chaves secretas.

## Publicar como site
1. Crie um repositório público chamado `shark7-autopost` no GitHub.
2. Envie os arquivos `index.html`, `manifest.json` e `sw.js` para a raiz do repositório.
3. Em Settings > Pages, selecione deploy from branch, branch `main`, pasta `/(root)` e salve.
4. Aguarde o endereço publicado aparecer no GitHub Pages.

## Próximas etapas para produção
- Criar backend seguro para autenticação, armazenamento e chamadas de IA.
- Configurar app da Meta, permissões de publicação, OAuth e tokens armazenados no servidor.
- Validar o tipo de conta Instagram e a ligação com uma Página do Facebook conforme os requisitos atuais da API.
- Implementar upload de mídia, agendamento real, estados de publicação e tratamento de erros.

Nunca coloque access tokens, client secrets ou senhas em arquivos públicos do GitHub.
