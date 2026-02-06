# S2DR4 - Super-resolução Automatizada para Sentinel-2

## Descrição do Projeto

Este repositório contém uma implementação adaptada do módulo **S2DR4 (Sentinel-2 Deep Resolution 4.0)**, desenvolvido pela Gamma Earth. A aplicação utiliza algoritmos de Deep Learning para realizar a super-resolução de imagem única (Single Image Super-Resolution - SISR) das 10 bandas multiespectrais do satélite Sentinel-2, elevando a resolução espacial nativa (10m e 20m) para **1 metro por pixel**.

## Adaptação e Funcionalidades

A presente versão, adaptada por **Samuel Santos (NGEO/IDEFLOR-BIO)**, introduz uma camada de automação integrada ao **Google Earth Engine (GEE)**. Diferente da implementação padrão que requer inserção manual de metadados, esta adaptação permite:

* Filtragem automatizada de cenas com base em coordenadas geográficas.
* Seleção de imagens por critérios de nebulosidade (Cloud Cover) e intervalos temporais dinâmicos.
* Extração automática de datas para processamento imediato via API Gamma Earth.

## Créditos e Propriedade Intelectual

O motor de processamento core e os modelos de inferência são de propriedade exclusiva da **Gamma Earth Sarl (2026)**. O uso deste software é destinado a fins de teste, avaliação de desempenho e validação técnica.

### Como Citar

Para fins de documentação técnica ou publicações acadêmicas, deve-se observar a seguinte estrutura de citação:

**Referência Original:**

> AKHTMAN, Yosef. **S2DR4: Effective 10-Band 10x Single Image Super-Resolution for Sentinel-2**. Gamma Earth, 2026. Disponível em: [https://medium.com/@ya_71389/c71a601a2253](https://medium.com/@ya_71389/c71a601a2253).

**Citação da Adaptação (Apud):**

> AKHTMAN, Yosef. S2DR4: Effective 10-Band 10x Single Image Super-Resolution for Sentinel-2. 2026. *apud* SANTOS, Samuel. **S2DR4_Inferencia_Automatizada_Sentinel2_NGEO.ipynb**: Implementação para automação via Google Earth Engine. Belém: NGEO/IDEFLOR-BIO, 2026.

## Licença e Termos de Uso

O software é fornecido "como está" (AS IS), sem garantias expressas ou implícitas de comercialização ou adequação a fins específicos. Os autores não se responsabilizam por quaisquer danos decorrentes do uso desta ferramenta. Imagens geradas por usuários anônimos podem ser utilizadas pela detentora da tecnologia para fins de divulgação.

Para funcionalidades estendidas ou uso comercial, deve-se contatar diretamente info@gamma.earth.
