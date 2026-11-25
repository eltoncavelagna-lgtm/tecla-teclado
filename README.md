# Tecla

Aplicativo estático de aprendizagem de teclado, em português. Pode ser instalado como aplicativo web (PWA) em celulares e computadores compatíveis.

## Arquivos

- `index.html`: telas e conteúdo.
- `styles.css`: layout responsivo e animações.
- `app.js`: aulas, teclado virtual, entrada MIDI/microfone, melodias, instalação e progresso local.
- `manifest.webmanifest`: nome, ícones e comportamento da instalação.
- `sw.js`: cache dos arquivos principais para abrir o app offline depois da primeira visita.
- `icons/`: ícones para a tela inicial e a instalação.

## Instalar no celular

- Android: abra o site em um navegador compatível e toque em **Instalar app**; se o navegador não oferecer o aviso, use o menu ⋮ e escolha **Instalar app** ou **Adicionar à tela inicial**.
- iPhone/iPad: abra o site no Safari, toque em **Compartilhar** e escolha **Adicionar à Tela de Início**.
- Computador: use **Instalar app** no site ou o comando de instalação do navegador.

É um aplicativo web instalável, sem arquivo APK ou pacote de loja. O primeiro acesso exige internet; depois, os arquivos da interface ficam disponíveis offline. MIDI, microfone e fontes externas continuam dependendo do navegador e da conexão.

## Uso com teclado físico

- MIDI: conecte um teclado com saída MIDI USB e use um navegador compatível.
- Microfone: permita o acesso quando o navegador solicitar; toque uma nota por vez, em ambiente silencioso.

## Dados e conteúdo

Esta versão ainda não tem cadastro, usuário ou senha. O nome e o progresso ficam salvos apenas no armazenamento local do navegador e não sincronizam entre dispositivos. O botão **Reiniciar progresso** limpa os dados guardados naquele navegador. As aulas são animações interativas com narração do navegador; esta versão não contém filmagens de professores. As melodias do repertório são originais.

