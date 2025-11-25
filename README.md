# 🏃🏽‍♂️ Projeto-de-certificao-media-atletas 
Calcular a média das notas dos atletas 
## 💡 Sobre o Projeto 

Este projeto é uma aplicação em JavaScript desenvolvida para auxiliar na avaliação de atletas em uma competição de 
ginástica artística. Ele calcula a média de desempenho de cada atleta com base nas notas fornecidas por cinco jurados,
aplicando um critério específico: a maior e a menor nota são desconsideradas no cálculo da média final.

## 🗒️ Contexto da Competição

Em uma competição de ginástica artística, os atletas realizam apresentações para uma banca de cinco jurados.
Cada jurado avalia um critério específico: tempo de duração da apresentação, originalidade da coreografia, 
postura do atleta, dificuldade das acrobacias e sincronismo.

A regra de avaliação é a seguinte:
* Cada jurado pode fornecer uma nota de 1 a 10.
* A média final é calculada com base nas três notas do meio, desconsiderando a maior e a menor nota atribuídas ao atleta.

## ⚙️ Funcionalidades

* Recebimento de dados de atletas (nome e cinco notas).
* Cálculo da média das notas, excluindo a maior e a menor.
* Apresentação clara dos resultados: nome do atleta, notas individuais e média calculada.

## 🤖 Tecnologias Utilizadas

* JavaScript (Vanilla JS)

## 🔨 Como Instalar e Executar 

Para configurar e rodar este projeto localmente, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd [NOME_DO_SEU_REPOSITORIO]
    ```
3.  **Execute a aplicação:**
    * Se for um script Node.js (apenas console):
        ```bash
        node seu_script.js
        ```

## 👩‍💻 Como Usar

A função principal `calcularMediaAtleta` (ou o nome que você der à sua função) espera uma matriz de objetos, 
onde cada objeto representa um atleta com suas notas. Veja um exemplo:

```javascript
const dadosDosAtletas = [
    { nome: "João Silva", notas: [8.5, 9.2, 7.8, 10.0, 6.5] },
    { nome: "Maria Souza", notas: [7.0, 7.5, 8.0, 9.0, 7.2] },
    { nome: "Pedro Rocha", notas: [9.1, 9.5, 8.0, 10.0, 7.5] }
];

// Exemplo de chamada da função (supondo que a função exista)
// processarAvaliacoes(dadosDosAtletas);
