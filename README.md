<!-- ... existing code ... -->
## 🚀 Como Usar

1. Abra o ficheiro `index.html` no seu navegador web.
2. Irá deparar-se com uma interface centralizada com fundo animado.
3. Clique em "📁 Escolher imagem do dispositivo..." para fazer upload de uma imagem do seu computador. Ela será automaticamente convertida para um link Base64, e o campo de texto será preenchido.
4. Em alternativa, no campo de texto, cole o link direto da imagem que deseja copiar.
5. Clique no botão **Copiar Link**. O botão mudará de estado para indicar que a cópia está em processamento.
6. Em caso de sucesso, o botão ficará verde indicando a conclusão, e o **texto do link (ou string Base64)** estará pronto para ser colado (`Ctrl+V` ou `Cmd+V`) em qualquer lugar.

## 📋 Histórico de Atualizações (Changelog)

Todas as alterações e melhorias notáveis neste projeto são documentadas nesta secção.

### [1.4.0] - Cópia de Texto e Links
**Alterado**
* A função de cópia foi reescrita para extrair e copiar o texto (URL ou código Base64) diretamente do campo de entrada usando `navigator.clipboard.writeText()`, em vez de baixar o arquivo de imagem.
* Textos da interface atualizados para refletir a nova ação (ex: "Copiar Link").

### [1.3.0] - Conversor de Imagens Locais (Base64)
<!-- ... existing code ... -->
## 🛠️ Tecnologias Utilizadas

* **HTML5:** Semântica e estruturação da nova interface (títulos, descrições, inputs).
* **CSS3:** Estilização avançada com Flexbox, gradientes lineares, `backdrop-filter` (Glassmorphism), sombras fluídas e animações (`@keyframes`, `transition`, `transform`).
* **JavaScript (Vanilla):** Lógica Assíncrona (`async/await`), manipulação da Área de Transferência (via `navigator.clipboard.writeText()`), alteração dinâmica de estilos do DOM para feedback visual, e **`FileReader API`** para conversão de ficheiros locais em links Base64.
