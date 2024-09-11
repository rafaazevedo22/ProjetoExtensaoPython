# Projeto IoT Integrado com Planilhas Excel

## Descrição do Projeto
Este projeto tem como objetivo demonstrar a integração de dispositivos IoT com planilhas Excel para automatizar a coleta de dados de sensores e atualizar informações em tempo real. A solução foi desenvolvida para empresas que atualmente dependem de Excel para a gestão de seus processos, proporcionando uma maneira mais eficiente e menos propensa a erros para lidar com grandes volumes de dados. Utilizando plataformas de prototipação, como o **Raspberry Pi** e **Arduino**, e a biblioteca **openpyxl** para manipulação de arquivos Excel via Python, o projeto automatiza o registro de dados dos sensores diretamente em planilhas.

## Requisitos

### Hardware:
- Raspberry Pi (ou Arduino)
- Sensor de Temperatura e Umidade DHT11 (ou similar)
- Conexões e cabos para o sensor
- Acesso a um computador para editar e rodar o código Python

### Software:
- Python 3.x instalado
- Bibliotecas Python necessárias:
  - `openpyxl` (para manipular Excel)
  - `Adafruit_DHT` (para leitura do sensor DHT11)
  
### Instalação das dependências:
```bash
pip install openpyxl
sudo pip install Adafruit_DHT