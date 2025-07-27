# Calculadora

Uma calculadora simples e elegante desenvolvida em HTML, CSS e JavaScript puro.

## 📋 Descrição

Esta é uma calculadora web que permite realizar operações matemáticas básicas como adição, subtração, multiplicação e divisão. A interface possui um design moderno com gradiente de fundo e botões estilizados.

## ✨ Funcionalidades

- **Operações básicas**: Adição (+), subtração (-), multiplicação (×), divisão (/)
- **Interface intuitiva**: Botões bem organizados em layout de tabela
- **Design responsivo**: Interface adaptável e visualmente atrativa
- **Funcionalidades extras**:
  - Botão "C" para limpar a tela
  - Botão "<" para apagar o último caractere
  - Suporte a números decimais
  - Botão "=" para calcular o resultado

## 🎨 Características do Design

- **Gradiente de fundo**: Combinação de preto e vermelho (crimson)
- **Tema escuro**: Interface com botões escuros e texto branco
- **Efeitos hover**: Botões mudam de cor ao passar o mouse
- **Layout centralizado**: Calculadora posicionada no centro da tela
- **Bordas arredondadas**: Design moderno com cantos suaves

## 🔗 Links do Projeto

- **Demo ao vivo**: [Calculadora Online](https://seu-usuario.github.io/calculadora)
- **Repositório**: [GitHub](https://github.com/seu-usuario/calculadora)
- **Download**: [ZIP do projeto](https://github.com/seu-usuario/calculadora/archive/main.zip)

## 🚀 Como usar

1. Abra o arquivo `index.html` em qualquer navegador web
2. Use os botões numéricos para inserir números
3. Selecione a operação desejada (+, -, ×, /)
4. Pressione "=" para ver o resultado
5. Use "C" para limpar ou "<" para apagar o último caractere

## 📁 Estrutura do Projeto

```
calculadora/
├── index.html      # Arquivo principal com HTML, CSS e JavaScript
└── README.md       # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **CSS3**: Estilização e design responsivo
- **JavaScript**: Lógica da calculadora

## 📱 Compatibilidade

- Funciona em todos os navegadores modernos
- Interface responsiva para diferentes tamanhos de tela
- Não requer instalação de dependências

## 🔧 Funcionalidades Técnicas

### Funções JavaScript

- `insert(num)`: Insere números e operadores na tela
- `clean()`: Limpa completamente a tela
- `back()`: Remove o último caractere inserido
- `calcular()`: Executa o cálculo usando `eval()`

### Estilização CSS

- Gradiente de fundo com cores preto e vermelho
- Botões com efeito hover
- Layout centralizado com posicionamento absoluto
- Design responsivo e moderno

## 📝 Licença

Este projeto é de código aberto e pode ser usado livremente para fins educacionais e pessoais.

## 👨‍💻 Autor

Desenvolvido como projeto de aprendizado em desenvolvimento web.

---

**Nota**: Esta calculadora utiliza a função `eval()` do JavaScript para executar os cálculos. Em um ambiente de produção, seria recomendável implementar um parser matemático mais seguro.