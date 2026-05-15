# Perfil Dev Jr

## Descrição
Aplicativo criado em React Native com Expo para apresentar um perfil profissional de um candidato a Desenvolvedor Mobile Júnior. O app demonstra navegação por abas, organização em telas separadas e uso de componentes básicos do React Native.

## Tecnologias utilizadas
- React Native
- Expo
- JavaScript
- React Navigation
- Git
- GitHub

## Funcionalidades implementadas
- Exibe informações de perfil com nome, cargo, imagem e seção "Sobre mim"
- Lista de habilidades usando `FlatList`
- Tela de projetos com descrições de projetos concluídos
- Seção de contato com e-mail, GitHub e LinkedIn
- Formulário de contato com campo de mensagem e botão "Enviar contato"
- Navegação inferior por abas entre as telas

## Telas
- **Perfil:** mostra o nome do candidato, a imagem de perfil, o cargo e um texto descritivo sobre a pessoa.
- **Habilidades:** apresenta uma lista de pelo menos 5 habilidades em cartões simples.
- **Projetos/Contato:** exibe dois projetos desenvolvidos e uma área de contato com e-mail, links de GitHub e LinkedIn, campo de mensagem e botão para enviar.

## Organização do código
- `App.js` configura a navegação por abas usando React Navigation.
- `screens/PerfilScreen.js` contém a tela de perfil com `ScrollView`, `Image`, `Text` e `View`.
- `screens/HabilidadesScreen.js` contém a tela de habilidades usando `FlatList`.
- `screens/ProjetosScreen.js` contém a tela de projetos e contato com `TextInput`, `Button`, `Alert` e `Linking`.
- `assets/` armazena a imagem usada no perfil.
- Estilização realizada com `StyleSheet` em cada tela.

## Diferenciais
- Layout simples e organizado, com navegação por abas.
- Uso correto de componentes básicos do React Native.
- Tela de contato funcional com validação básica de envio.
- Estrutura de arquivos clara, facilitando manutenção.

## Como executar o projeto
1. Clone o repositório:
   ```bash
   git clone <link-do-repositorio>
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd "ativ-du"
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Execute o projeto:
   ```bash
   npx expo start
   ```
5. Abra no Expo Go, no navegador ou emulador.

## Autor
Bianca Luisa Teodoro Silva
