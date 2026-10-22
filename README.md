# Botão de Cópia para a Área de Transferência

Um projeto elegante e interativo construído com HTML, CSS e JavaScript. Ele permite copiar imagens diretamente para a área de transferência do utilizador através de um link, com apenas um clique. A interface foi desenhada com foco na experiência do utilizador, utilizando animações suaves e um design moderno.

## 🚀 Como Usar

1. Abra o ficheiro `index.html` no seu navegador web.
2. Irá deparar-se com uma interface centralizada com fundo animado.
3. No campo de texto, cole o link direto da imagem que deseja copiar (ou utilize o ficheiro de teste sugerido).
4. Clique no botão **Copiar Imagem**. O botão mudará de estado para indicar que a cópia está em processamento.
5. Em caso de sucesso, o botão ficará verde indicando a conclusão, e a imagem estará pronta para ser colada (`Ctrl+V` ou `Cmd+V`) em editores de imagem, documentos ou chats.
*(Nota: Bloqueios de CORS por parte do servidor da imagem podem impedir a cópia).*

## 📋 Histórico de Atualizações (Changelog)

Todas as alterações e melhorias notáveis neste projeto são documentadas nesta secção.

### [1.2.0] - Modernização da Interface (UI/UX)
**Adicionado**
- Interface totalmente centralizada utilizando Flexbox.
- Implementação de um design "Glassmorphism" para o container principal.
- Animação infinita em gradiente no fundo da página (`@keyframes`).
- Título descritivo e instruções claras integradas na página.
- Animações de foco no campo de entrada de texto (aumento de escala e brilho).
- Efeitos avançados de `hover` e `active` no botão, incluindo alteração visual de texto ("Copiando...", "Copiado com Sucesso! ✔") ao interagir.

### [1.1.0] - Imagens por Link
**Adicionado**
- Funcionalidade para baixar e copiar imagens diretamente para a área de transferência usando a `Clipboard API` e `fetch`.
- Lógica de tratamento de erros com alertas para o utilizador.

### [1.0.0] - Lançamento Inicial
**Adicionado**
- Estrutura base e cópia simples de caracteres estáticos.

---

## 🛠️ Tecnologias Utilizadas
- **HTML5:** Semântica e estruturação da nova interface (títulos, descrições, inputs).
- **CSS3:** Estilização avançada com Flexbox, gradientes lineares, `backdrop-filter` (Glassmorphism), sombras fluídas e animações (`@keyframes`, `transition`, `transform`).
- **JavaScript (Vanilla):** Lógica Assíncrona (`async/await`), requisições de rede (`Fetch API`), manipulação da Área de Transferência (`Clipboard API`), e alteração dinâmica de estilos do DOM para feedback visual.
