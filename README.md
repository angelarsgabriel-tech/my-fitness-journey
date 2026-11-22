# My Fitness Journey — MVP 1

PWA estático em português. MVP inclui painel inicial, diário alimentar, transcrição de plano da nutricionista, IndexedDB e backup/restauração JSON.

## Teste local
IndexedDB e instalação PWA exigem contexto seguro (HTTPS ou localhost). Com Python instalado, na pasta do projeto:
`python -m http.server 8000`
Acesse `http://localhost:8000`.

## Hospedagem gratuita sugerida (GitHub Pages)
1. Crie uma conta no GitHub e um repositório novo.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Em Settings > Pages, selecione deploy from branch, branch `main`, pasta `/root`.
4. Aguarde o endereço HTTPS publicado.

## Instalar no Android
1. Abra o endereço HTTPS do site no Chrome.
2. Menu ⋮ > Instalar app (ou Adicionar à tela inicial).
3. Confirme. O app poderá abrir em modo de aplicativo.

## Backup e restauração
1. Abra Dados & backup ou toque Backup no topo.
2. Exporte o JSON e guarde-o fora do aparelho (Drive, computador, etc.).
3. Para restaurar: abra Dados & backup, selecione o JSON e confirme. A restauração substitui os dados atuais; faça backup antes.

## Privacidade e limites
- Os registros ficam no IndexedDB deste navegador/dispositivo; não há servidor nem sincronização.
- Limpar dados do navegador, desinstalar ou certos modos de navegação podem apagar dados. Faça backups periódicos.
- Não são estimados macros, calorias, metas, peso ou medidas.
- MVP 1 ainda não contém módulos de receitas, exercícios, água, peso/medidas, relatórios, calendário ou lembretes.
