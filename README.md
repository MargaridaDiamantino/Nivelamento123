# Projeto de Processamento de Dados da ANS

Este projeto realiza web scraping, transformação de dados e operações em banco de dados para informações da ANS (Agência Nacional de Saúde Suplementar).

## Estrutura do Projeto
project/
├── src/
│ ├── web_scraping/ # Test 1 - Web Scraping
│ ├── PDFToCSVConverter/ # Test 2 - Data Transformation
│ └── database/ # Test 3 - Database Operations
├── libs/ # External libraries
├── README.md
## Requisitos

### Para implementação em Java:
- Java 8+
- Maven
- Bibliotecas:
  - PDFBox 3.0.4
  - OpenCSV 5.10
  - Jsoup (para web scraping)
 
Teste 1: Web Scraping
Descrição:
Faz download dos anexos em PDF do site da ANS e os compacta.
javac -cp ".;libs/pdfbox-3.0.4.jar;libs/fontbox-3.0.4.jar;libs/commons-logging-1.2.jar;libs/pdfbox-io-3.0.4.jar;libs/opencsv-5.10.jar" PDFToCSVConverter.java

Implementação:
Java: WebScraper.java
