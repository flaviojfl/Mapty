EN
# Mapty 🗺️

Mapty is an interactive web application created to log running and cycling workouts directly on a dynamic map. The project uses the browser's geolocation to center the map on your position and saves all your workouts locally, allowing you to view your progress at any time.

## Live Demo 🚀

You can see the project in action and test its features at the following link:

**[Access Mapty Live](https://flaviojfl.github.io/Mapty/)**

---

## Key Features ✨

* **Automatic Geolocation:** Finds the user's position to center the map.
* **Interactive Map:** Uses the **Leaflet.js** library to allow the user to click anywhere to log a new workout.
* **Log Two Types of Workouts:**
* 🏃‍♂️ **Running:** With fields for distance, duration, and cadence (steps per minute).
* 🚴‍♀️ **Cycling:** With fields for distance, duration, and elevation gain.
* **Automatic Calculations:** Calculates and displays the **Pace** (min/km) for runs and **Speed** (km/h) for cycling.
* **Data Persistence:** All workouts are saved in the browser's **Local Storage**, keeping the data even after the page is closed.
* **Dynamic Interface:** Renders workouts in a sidebar list and as custom markers on the map.
* **Focused View:** Clicking a workout in the list smoothly pans the map to that workout's location.

---

## Technologies Used 🛠️

This project was built using modern web technologies:

* **HTML5:** For the semantic structure of the page.
* **CSS3:** For styling, using **Flexbox** for layout and **CSS Variables** for a consistent color theme.
* **JavaScript (ES6+):** Main application logic, using **Classes**, **modules**, and other modern features for an Object-Oriented architecture.
* **[Leaflet.js](https://leafletjs.com/):** An open-source library for interactive maps.
* **Browser Geolocation API:** To obtain the user's coordinates.
* **Browser Local Storage API:** For data persistence.

---

## How to Run the Project Locally 🖥️

To run this project on your local machine, follow the steps below:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/flaviojfl/Mapty.git](https://github.com/flaviojfl/Mapty.git)
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd mapty
    ```
3.  **Open the `index.html` file** in your preferred browser (like Google Chrome, Firefox, etc.).

**Note:** An internet connection is required for the OpenStreetMap tiles and the Leaflet library (imported via CDN) to load correctly.

---

## Credits ✨

This project was developed as part of the JavaScript course by instructor **Jonas Schmedtmann**. The project's design and structure are based on the course's teachings, with personal adaptations and implementations.











PT-BR
# Mapty🗺️

Mapty é um aplicativo web interativo criado para registrar treinos de corrida e ciclismo diretamente em um mapa dinâmico. O projeto utiliza a geolocalização do navegador para centralizar o mapa na sua posição e salva todos os seus treinos localmente, permitindo que você visualize seu progresso a qualquer momento.

## Demonstração ao Vivo 🚀

Você pode ver o projeto em ação e testar suas funcionalidades no seguinte link:

**[Acessar o Mapty Live](https://flaviojfl.github.io/Mapty/)**

---

## Funcionalidades Principais ✨

* **Geolocalização Automática:** Encontra a posição do usuário para centralizar o mapa.
* **Mapa Interativo:** Utiliza a biblioteca **Leaflet.js** para permitir que o usuário clique em qualquer lugar para registrar um novo treino.
* **Registro de Dois Tipos de Treino:**
* 🏃‍♂️ **Corrida:** Com campos para distância, duração e cadência (passos por minuto).
* 🚴‍♀️ **Ciclismo:** Com campos para distância, duração e ganho de elevação.
* **Cálculos Automáticos:** Calcula e exibe o **Pace** (min/km) para corridas e a **Velocidade** (km/h) para ciclismo.
* **Persistência de Dados:** Todos os treinos são salvos no **Local Storage** do navegador, mantendo os dados mesmo após fechar a página.
* **Interface Dinâmica:** Renderiza os treinos em uma lista na barra lateral e como marcadores personalizados no mapa.
* **Visualização Focada:** Clicar em um treino na lista move o mapa suavemente para a localização daquele treino.

---

## Tecnologias Utilizadas 🛠️

Este projeto foi construído utilizando tecnologias web modernas:

* **HTML5:** Para a estrutura semântica da página.
* **CSS3:** Para a estilização, utilizando **Flexbox** para o layout e **Variáveis CSS** para um tema de cores consistente.
* **JavaScript (ES6+):** Lógica principal da aplicação, utilizando **Classes**, **módulos** e outros recursos modernos para uma arquitetura Orientada a Objetos.
* **[Leaflet.js](https://leafletjs.com/):** Uma biblioteca de código aberto para mapas interativos.
* **API de Geolocalização do Navegador:** Para obter as coordenadas do usuário.
* **API de Local Storage do Navegador:** Para persistência de dados.

---

## Como Executar o Projeto Localmente 🖥️

Para executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/flaviojfl/Mapty.git](https://github.com/flaviojfl/Mapty.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd mapty
    ```
3.  **Abra o arquivo `index.html`** no seu navegador de preferência (como Google Chrome, Firefox, etc.).

**Nota:** É necessária uma conexão com a internet para que os mapas do OpenStreetMap e a biblioteca Leaflet (importada via CDN) sejam carregados corretamente.

---

## Créditos ✨

Este projeto foi desenvolvido como parte do curso de JavaScript do instrutor **Jonas Schmedtmann**. O design e a estrutura do projeto são baseados nos ensinamentos do curso, com adaptações e implementações pessoais.
