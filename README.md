# 🎁 Grinch for Twitch

Automatize sua participação em sorteios da Twitch!

## 📥 Download e Instalação

1. Vá para a página de [Releases](https://github.com/cccarv82/grinch-for-twitch-releases/releases)
2. Baixe o arquivo `Grinch for Twitch-Setup-X.Y.Z.exe` mais recente
3. Execute o instalador
4. O aplicativo será instalado e configurado automaticamente

## ⚙️ Configuração Inicial

### Obtendo Credenciais da Twitch

1. Acesse o [Console de Desenvolvedores da Twitch](https://dev.twitch.tv/console)
2. Faça login com sua conta da Twitch
3. Clique em 'Register Your Application'
4. Preencha o formulário:
   - **Name**: Nome único para sua aplicação
   - **OAuth Redirect URLs**: `http://localhost:3000`
   - **Category**: Chat Bot ou Other
5. Clique em Create
6. Na lista de aplicações, clique em 'Manage'
7. Copie o **Client ID**
8. Clique em 'New Secret' para gerar o **Client Secret**

### Configurando o Aplicativo

1. Abra o Grinch for Twitch
2. Clique no ícone ⚙️ para acessar as configurações
3. Na seção Twitch:
   - Cole o **Client ID** e **Client Secret**
   - Configure a categoria de jogo (opcional)
   - Adicione palavras-chave para identificar sorteios

### Adicionando Bots

1. Na seção Bots, clique em 'Conectar com Twitch'
2. Faça login com a conta que será usada como bot
3. Autorize o aplicativo
4. Repita o processo para adicionar mais bots

## 🎮 Como Usar

### Busca de Streams
1. Use o ícone 🔍 para acessar a busca
2. O app buscará streams com potenciais sorteios
3. Selecione as streams que deseja monitorar

### Monitoramento
1. Use o ícone 👁️ para acessar o monitoramento
2. Clique em 'Iniciar Monitoramento'
3. Os bots conectarão automaticamente aos chats

### Dashboard de Sorteios
1. Use o ícone 🎁 para ver os sorteios
2. Acompanhe sorteios ativos e histórico
3. Veja estatísticas de participação

## ⚠️ Notas Importantes

- O app atualiza automaticamente quando há novas versões
- Mantenha suas credenciais da Twitch seguras
- Evite usar contas principais como bots
- Respeite os limites da API da Twitch

## 🆘 Suporte

Se encontrar problemas ou tiver sugestões, por favor abra uma [issue](https://github.com/cccarv82/grinch-for-twitch-releases/issues).
