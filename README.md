# 🌍 Calculadora CO2 - Calculadora de Emissões de Carbono

Este projeto foi desenvolvido como o desafio final do **Bootcamp CI&T - Do Prompt ao Agente**, oferecido pela **DIO (Digital Innovation One)**. O objetivo é criar uma ferramenta interativa que auxilie na conscientização ambiental, calculando o impacto de CO₂ de diferentes trajetos e meios de transporte.

## 🚀 Sobre o Projeto

A **EcoCalc CO2** permite que usuários planejem suas viagens com consciência ecológica. Através de uma interface intuitiva, é possível comparar emissões entre veículos e entender o custo de compensação ambiental através de créditos de carbono.

O grande diferencial deste projeto foi o fluxo de desenvolvimento **AI-Driven**, utilizando o **GitHub Copilot** como parceiro de programação desde a concepção da lógica até o deploy final.

---

## 🛠️ Funcionalidades

- **Cálculo de Rota:** Inserção de origem e destino com cálculo de distância (via pseudo-API ou entrada manual).
- **Seleção de Veículos:** Suporte para Bicicleta, Carro, Ônibus e Caminhão.
- **Painel de Resultados (Cards):**
    - **Card 1 (Detalhes da Viagem):** Exibe a rota traçada, distância total, emissão específica e o transporte escolhido.
    - **Card 2 (Comparativo):** Mostra o impacto visual das emissões em outros meios de transporte para a mesma distância.
    - **Card 3 (Crédito de Carbono):** Calcula o valor estimado para compensar o CO₂ emitido na viagem.

---

## 🍃 O que são Créditos de Carbono?

Créditos de carbono são certificados que representam a redução de uma tonelada de CO₂ da atmosfera. Ao adquirir esses créditos, indivíduos ou empresas financiam projetos de preservação ambiental e energias renováveis, neutralizando sua própria pegada de carbono. No projeto, calculamos uma estimativa financeira baseada na emissão gerada para educar o usuário sobre o custo da compensação.

---

## 🤖 Desenvolvimento Assistido por IA (Prompt Engineering)

O projeto foi construído utilizando técnicas de **Pair Programming com IA**. O fluxo seguiu os seguintes passos:
1.  **Ideação e Estrutura:** Prompts para definição da arquitetura de arquivos e esqueleto HTML.
2.  **Lógica de Negócio:** Uso do GitHub Copilot para gerar as fórmulas de cálculo de CO₂ e manipulação de dados de rotas.
3.  **Refinamento:** Iterações sobre o código gerado para otimização, tratamento de erros e melhoria da legibilidade.
4.  **Validação e Deploy:** Testes de interface e publicação automatizada via **GitHub Pages**.

---

## 🎨 Identidade Visual

A interface utiliza o conceito de **"Tecnologia Orgânica"**, uma paleta que equilibra a inovação técnica com a sustentabilidade:
- **Verde Musgo:** Natureza e sustentabilidade.
- **Azul Safira:** Tecnologia e precisão de dados.
- **Creme/Platina:** Limpeza e modernidade.
- **Tipografia:** Montserrat (Títulos) e Inter (Dados/Leitura) para máxima legibilidade.

---

## 💻 Tecnologias Utilizadas

- **Linguagens:** HTML5, CSS3, JavaScript (ES6+).
- **IA Generativa:** GitHub Copilot.
- **Hospedagem:** GitHub Pages.

---

## 📂 Estrutura de Pastas

```text
index.html          # Estrutura principal da página
|-- css/
|   |-- style.css    # Estilização e Design System (Tecnologia Orgânica)
|-- js/
|   |-- app.js        # Inicialização e controle de fluxo
|   |-- calculator.js # Lógica de cálculo de CO2 e Créditos de Carbono
|   |-- config.js     # Variáveis de ambiente e constantes (ex: fatores de emissão)
|   |-- route-data.js # Gerenciamento de rotas e integração com pseudo-API
|   |-- ui.js         # Manipulação do DOM e renderização dos cards
```

## 🏗️ Como rodar o projeto
Clone o repositório:

```Bash
git clone [https://github.com/Reivert/Calculadora-CO2](https://github.com/Reivert/Calculadora-CO2)
```
Navegue até a pasta do projeto e abra o arquivo index.html em seu navegador ou utilize a extensão Live Server no VS Code.

## 📄 Licença
Este projeto é fruto de um desafio educacional e está sob a licença MIT.

Developed by Reivert Zulato 🚀