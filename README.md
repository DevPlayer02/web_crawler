# Simple Web Crawler

Um script Python básico que faz *crawling* de URLs, extraindo todos os links HTTP de páginas web e explorando-os recursivamente.


##  Sobre

Este crawler simples utiliza as bibliotecas `requests` e `BeautifulSoup` para:

- Requisitar e obter o conteúdo HTML de uma URL inicial.
- Extrair todos os links que começam com `http://` ou `https://`.
- Armazenar em filas (`TO_CRAWL`) os links ainda não explorados e marcá-los como visitados (`CRAWLED`).
- Continuar recursivamente até esgotar os links disponíveis.


##  Requisitos

- Python 3.x  
- Bibliotecas Python:
  ```bash pip install requests beautifulsoup4```


## Uso

- Exemplo:
  ```bash python web_crawler.py https://exemplo.com```
  
  - Troque https://exemplo.com pela URL que deseja iniciar o crawling.
  - O console exibirá, a cada link processado.


## Observações

  - Use de forma ética e legal, apenas em sites que você tem permissão para testar.
