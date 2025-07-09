# # Bot de Futebol ao Vivo com API-Football e Telegram



Este bot detecta jogos ao vivo com base na estratégia "1º gol no primeiro tempo" e envia alertas para o Telegram.



## Estratégia usada:

- Entre 5 e 85 minutos de jogo

- Total de gols = 0

- Mínimo de 1 chute

- Mínimo de 1 escanteio

- Mínimo de 5 ataques perigosos

- Pelo menos 1 ataque perigoso por minuto



## Como publicar no Render.com:



1. Crie uma conta gratuita em: https://render.com

2. Crie um novo serviço: **New Web Service**

3. Escolha **Python 3**

4. Configure:

   - Build command: `pip install -r requirements.txt`

   - Start command: `python main.py`

   - Environment: Python 3.11

5. Faça deploy automático pelo GitHub **OU** envie ZIP com estes arquivos.



Este bot roda 24h por dia enviando alertas ao seu grupo do Telegram!

-
