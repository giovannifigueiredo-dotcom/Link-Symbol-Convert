<!-- ... existing code ... -->
## 🚀 Como Usar

1. Abra o ficheiro `index.html` no seu navegador web.

2. Irá deparar-se com uma interface centralizada com fundo animado.

3. **(Novo)** Clique em "📁 Escolher imagem do dispositivo..." para fazer upload de uma imagem do seu computador. Ela será automaticamente convertida para um link Base64, e o campo de texto será preenchido.

4. Em alternativa, no campo de texto, cole o link direto da imagem que deseja copiar (ou utilize o ficheiro de teste sugerido).

5. Clique no botão **Copiar Imagem**. O botão mudará de estado para indicar que a cópia está em processamento.

6. Em caso de sucesso, o botão ficará verde indicando a conclusão, e a imagem estará pronta para ser colada (`Ctrl+V` ou `Cmd+V`) em editores de imagem, documentos ou chats.
   *(Nota: Bloqueios de CORS por parte do servidor da imagem podem impedir a cópia de links externos).*

## 📋 Histórico de Atualizações (Changelog)

Todas as alterações e melhorias notáveis neste projeto são documentadas nesta secção.

### \[1.3.0\] - Conversor de Imagens Locais (Base64)

**Adicionado**

* Botão de upload de ficheiros (`input file`) perfeitamente integrado na interface *Glassmorphism*.
* Lógica JavaScript utilizando a `FileReader API` para converter imagens carregadas localmente num Link Data URL (Base64).
* Inserção automática do link Base64 gerado no campo de texto e feedback visual (ícones e texto) durante o carregamento.

### \[1.2.0\] - Modernização da Interface (UI/UX)
<!-- ... existing code ... -->
## 🛠️ Tecnologias Utilizadas

* **HTML5:** Semântica e estruturação da nova interface (títulos, descrições, inputs).

* **CSS3:** Estilização avançada com Flexbox, gradientes lineares, `backdrop-filter` (Glassmorphism), sombras fluídas e animações (`@keyframes`, `transition`, `transform`).

* **JavaScript (Vanilla):** Lógica Assíncrona (`async/await`), requisições de rede (`Fetch API`), manipulação da Área de Transferência (`Clipboard API`), alteração dinâmica de estilos do DOM para feedback visual, e **`FileReader API`** para conversão de ficheiros locais em links Base64.
