# Quiz de Mandarim HSK 🇨🇳🇵🇹

Um quiz interativo e divertido, baseado na web, projetado para ajudar estudantes de mandarim (falantes de português) a testarem e melhorarem seu vocabulário com base nos níveis HSK.

## ✨ Funcionalidades

*   **Seleção de Nível HSK:** Escolha praticar o vocabulário do HSK 1 até o HSK 6 (No momento estamos apenas com o HSK1).
*   **Vocabulário Cumulativo:** Ao selecionar um nível (ex: HSK 3), o quiz incluirá palavras dos níveis anteriores (HSK 1 e HSK 2) também.
*   **Múltiplos Tipos de Pergunta:** Teste seu conhecimento de diferentes formas:
    *   Hanzi (汉字) ➔ Tradução em Português
    *   Tradução em Português ➔ Hanzi (汉字)
    *   Pinyin ➔ Tradução em Português
*   **Feedback Imediato:** Saiba na hora se sua resposta está correta ou errada.
*   **Áudio:**
    *   Efeitos sonoros para respostas certas e erradas.
    *   Música de fundo temática (royalty-free) para ambientação.
    *   Botão para mutar/desmutar a música de fundo.
*   **Controles do Quiz:**
    *   Pule perguntas que você não sabe.
    *   Peça uma dica (revela a primeira letra/caractere da resposta).
    *   Recomece o quiz a qualquer momento.
*   **Pontuação:** Acompanhe seu progresso e veja sua pontuação final ao terminar o quiz.
*   **Interface:** Design simples e limpo (em Português).

## 🚀 Como Usar

1.  **Faça o download dos arquivos:**
    *   `Quiz_Mandarim_HSK.html` (ou o nome que você deu ao arquivo principal)
    *   `correct.mp3` (arquivo de som para resposta correta)
    *   `wrong.mp3` (arquivo de som para resposta errada)
    *   `background.mp3` (arquivo de música de fundo)
    *   **IMPORTANTE:** Certifique-se de que todos esses arquivos estejam na **MESMA PASTA** em seu computador.

2.  **Abra o Arquivo:**
    *   Abra o arquivo `Quiz_Mandarim_HSK.html` (ou similar) diretamente no seu navegador web preferido (Google Chrome, Firefox, Microsoft Edge, etc.). Não é necessário um servidor web.

3.  **Jogue!**
    *   Clique em "Iniciar Quiz".
    *   Selecione o nível HSK desejado no menu dropdown.
    *   Responda às perguntas clicando nas opções.
    *   Use os botões de controle (Recomeçar, Pular, Dica) conforme necessário.
    *   Divirta-se aprendendo!

## 🛠️ Tecnologias Utilizadas

*   HTML5
*   CSS3
*   JavaScript (Vanilla JS - sem frameworks externos)

## 📚 Estrutura do Vocabulário

*   O vocabulário está atualmente embutido diretamente no arquivo HTML, dentro da constante JavaScript `levels`.
*   A estrutura de dados para cada palavra segue o formato:
    ```javascript
    {
      "汉字": "爱",      // Caracteres chineses
      "Pinyin": "ài",     // Romanização Pinyin
      "Português": "amar", // Tradução em Português
      "HSK": 1          // Nível HSK da palavra
    }
    ```
*   **Nota Importante:** No momento, **apenas o vocabulário completo do HSK 1 está incluído** no código. As listas para HSK 2, HSK 3, HSK 4, HSK 5 e HSK 6 estão presentes como placeholders (listas vazias ou com poucos exemplos) dentro da constante `levels`. **Você precisará encontrar e adicionar os dados de vocabulário para esses níveis** para que eles funcionem completamente no quiz.

## 🔮 Planos Futuros / Melhorias Possíveis

*   Carregar o vocabulário de arquivos JSON externos para melhor organização e performance.
*   Adicionar mais tipos de perguntas (ex: ouvir o pinyin e escolher o hanzi, completar frases).
*   Implementar um sistema para salvar pontuações (usando `localStorage`).
*   Melhorar o design e a responsividade para diferentes tamanhos de tela.
*   Adicionar opção para desativar efeitos sonoros separadamente da música.
*   Incluir a opção de mostrar/esconder os tons do Pinyin.

## 🤝 Contribuição

*   Encontrou um bug ou tem uma sugestão? Abra uma (https://github.com/CintiaAraujo-Zoo/Mandarim_Quiz/issues)!
*   Quer adicionar uma funcionalidade ou corrigir algo? Pull Requests são bem-vindos!
*   **Ajuda na compilação e formatação das listas de vocabulário HSK 2-6 no formato correto seria especialmente apreciada!**

## 📄 Licença

Este projeto está licenciado sob a Licença MIT.

---

Feito com ❤️ e muito 咖啡! Espero que ajude seus estudos de Mandarim!
