# Django Weather App

Portuguese version at the end 


The Django Weather App is a web application that allows users to compare weather information and forecasts for two cities. It utilizes the OpenWeatherMap API to fetch real-time weather data and 5-day forecasts for the specified cities.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)

## Features

- Users can input the names of two cities for weather comparison.
- The app displays the current weather information and a 5-day forecast for each city.
- Responsive design for optimal user experience on various devices.

## Installation

1. Clone the repository:


git clone https://github.com/Reis567/weather-django.git
cd weather-django


2. Install the required packages:


pip install -r requirements.txt


3. Set up environment variables:

   - Create a `.env` file in the project root directory.
   - Add your OpenWeatherMap API key to the `.env` file:

     
     OPENWEATHERMAP_API_KEY=your_api_key_here
     

4. Apply database migrations:


python manage.py migrate


5. Run the development server:


python manage.py runserver


## Usage

1. Access the app in your web browser at `http://localhost:8000/`.

2. Enter the names of two cities in the provided input fields and click the "Procurar" (Search) button.

3. The app will display the current weather information and 5-day forecast for each city.

## Configuration

- The `WeatherAppConfig` class in `apps.py` provides app-specific configuration settings.

- The API key is stored as an environment variable (`OPENWEATHERMAP_API_KEY`) for security.

## Contributing

Contributions to the project are welcome! If you find any issues or want to add new features, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature/fix:


git checkout -b feature-name


3. Commit your changes:


git commit -m "Add your message here"


4. Push the branch to your fork:


git push origin feature-name


5. Create a pull request on GitHub.

---

**Project created by [Reis567](https://github.com/Reis567)**

# Aplicativo de Clima Django

O Aplicativo de Clima Django é uma aplicação web que permite aos usuários comparar informações meteorológicas e previsões para duas cidades. Ele utiliza a API OpenWeatherMap para buscar dados meteorológicos em tempo real e previsões de 5 dias para as cidades especificadas.

## Índice

- [Recursos](#recursos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Configuração](#configuração)
- [Contribuição](#contribuição)

## Recursos

- Os usuários podem inserir os nomes de duas cidades para comparação do clima.
- O aplicativo exibe as informações meteorológicas atuais e a previsão de 5 dias para cada cidade.
- Design responsivo para uma experiência ideal em vários dispositivos.

## Instalação

1. Clonar o repositório:


git clone https://github.com/Reis567/weather-django.git
cd weather-django


2. Instalar os pacotes necessários:


pip install -r requirements.txt


3. Configurar variáveis de ambiente:

   - Crie um arquivo `.env` no diretório raiz do projeto.
   - Adicione sua chave de API OpenWeatherMap ao arquivo `.env`:

     
     OPENWEATHERMAP_API_KEY=sua_chave_de_api_aqui
     

4. Aplicar migrações do banco de dados:


python manage.py migrate


5. Executar o servidor de desenvolvimento:


python manage.py runserver


## Uso

1. Acesse o aplicativo em seu navegador da web em `http://localhost:8000/`.

2. Insira os nomes das duas cidades nos campos de entrada fornecidos e clique no botão "Procurar".

3. O aplicativo exibirá as informações meteorológicas atuais e a previsão de 5 dias para cada cidade.

## Configuração

- A classe `WeatherAppConfig` no arquivo `apps.py` fornece configurações específicas do aplicativo.

- A chave da API é armazenada como uma variável de ambiente (`OPENWEATHERMAP_API_KEY`) para segurança.

## Contribuição

Contribuições para o projeto são bem-vindas! Se você encontrar problemas ou quiser adicionar novos recursos, siga estas etapas:

1. Faça um fork do repositório.

2. Crie um novo branch para a sua funcionalidade/correção:


git checkout -b nome-da-funcionalidade


3. Faça commits das suas alterações:


git commit -m "Adicione a sua mensagem aqui"


4. Faça push do branch para o seu fork:


git push origin nome-da-funcionalidade


5. Crie um pull request no GitHub.

---

**Projeto criado por [Reis567](https://github.com/Reis567)**
