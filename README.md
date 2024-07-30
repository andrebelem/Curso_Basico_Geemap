# Curso Básico de Google Earth Engine no Python (via Google Colab)

Este curso é baseado no trabalho do prof. [Qiusheng Wu](https://github.com/giswqs), originalmente publicado no [workshop SatMOC 2024](https://geemap.org/workshops/SatMOC_2024) usando o [Google Earth Engine](https://earthengine.google.com) e o [`Geemap`](https://geemap.org). Os notebooks deste curso podem ser usados integralmente em uma *environment* preparada com o `geemap`e o `ee`, e considera que você já tem o seu projeto definido no [Console do Google Cloud](https://console.cloud.google.com/). Um pouco adiante vamos apontar para os requisitos básicos para você rodar os notebooks.<br>

**Nota importante**: na renderização dos notebooks no github, você não verá nenhum mapa. Eles aparecem apenas quando você abre e executa os notebooks.


## Introdução

Este curso foi elaborado considerando especificidades locais no Brasil, mas segue a mesma linha do Comitê de Meteorologia, Oceanografia e Climatologia de Satélites (SatMOC) da Sociedade Meteorológica Americana (AMS), com uma sequência similar a que foi apresentada pelo [Prof. Qiusheng Wu](https://www.linkedin.com/in/giswqs/). Aqui vamos explorar os mesmos recursos do curso, mas na região do sudeste e centro-oeste do Brasil.

## Para saber mais ... um pouco de ciência

Períodos de seca representam uma ameaça crítica aos recursos hídricos, à agricultura e aos ecossistemas em todo o mundo, e a ideia básica aqui é explorar o poder do Google Earth Engine (GEE) para monitorar e analisar padrões climáticos e também monitorar o ambiente. O vasto repositório de dados de satélite, de modelos e análise, contidos no GEE e os recursos de computação em nuvem serão aqui utilizados em conjunto para permitir sua pesquisa sobre clima e eventualmente auxiliar na tomada de decisões. Objetivamente, este curso está dividido em módulos que irão focar em: 
- Explorar os fundamentos do sensoriamento remoto para monitoramento ambiental;
- Dominar as técnicas de codificação GEE para processar grandes conjuntos de dados geoespaciais;
- Criar visualizações dinâmicas que acompanham a evolução das condições de seca ao longo do tempo;
- Enteder o cáclulo e interpretação dos principais índices de seca, como o Palmer Drought Severity Index (PDSI) e o Standardized Precipitation Index (SPI);
- Desenvolver ferramentas para apoiar estratégias locais e regionais de gestão de recursos hídricos.

## O que você precisa saber "antes" de começar

Para usar o geemap e a API Python do Earth Engine, você deve se registrar em uma conta do Earth Engine e seguir as instruções aqui para criar um projeto em nuvem. O Earth Engine é gratuito para uso não comercial e de pesquisa. Para testar se você pode usar a autenticação da API Python do Earth Engine, execute o notebook `0_teste_earthengine.ipynb` no Google Colab. É recomendado que os participantes tenham um conhecimento básico de Python e aprendam a usar o Jupyter Notebook, e um aspecto muito importante é *saber usar o markdown* para fazer suas anotações. Não é necessário ter familiaridade com a API JavaScript do Earth Engine, mas será útil se você quiser se aprofundar mais. A vantagem do Google Colab é que você não precisa instalar nada em no seu computador. Porém, se o seu objetivo é esse, basta você garantir que tem tudo instalado.

Ao final deste breve curso, você terá as habilidades e os recursos para integrar com segurança o Google Earth Engine em seus fluxos de trabalho de monitoramento ambiental e tomada de decisões.

## Como este curso está dividido

Este curso consiste em cinco módulos que podem ser completados em menos de 30 minutos (!) Porém, é aconselhável que vocẽ dedique um pouco mais de tempo à cada um deles. Durante cada módulo prático, os participantes percorrerão exemplos de notebooks Jupyter no Google Colab e no final de cada notebook, há uma proposta um exercício prático para aplicar o conhecimento aprendido em cada módulo. Veja em `soluções_exercícios_propostos` para comparar o seu exercício com o que é esperado.

- **Módulo 1**: Introdução ao curso e configuração do `geemap` e `ee` no ambiente Jupyter 
    - Introdução ao Earth Engine e geemap
    - Autenticação da API Python do Google Colab e do Earth Engine
    - Usando dados do Earth Engine
    - Tipos de dados do Earth Engine
    - Catálogo de dados do Earth Engine
    - Exercício: criando imagens sem nuvens
- **Módulo 2**: Visualização de dados do Earth Engine
    - Ferramenta Geemap Inspector, ferramenta de plotagem, GUI interativa para visualização de dados
    - Legendas, barras coloridas e rótulos
    - Mapa de painel dividido e mapas vinculados
    - Inspetor de série temporal e controle deslizante de tempo
    - Exercício: visualizando séries temporais de precipitação e dados de vegetação
- **Módulo 3**: Criação de animações de timelapse
    - Índices de vegetação MODIS
    - Dados de temperatura MODIS
    - Dados do satélite GOES
    - Exercício: criando animações de timelapse
- **Módulo 4**: Monitoramento de seca
    - Explorando conjuntos de dados de seca
    - Criação de animações de série temporal de seca
    - Computando estatísticas zonais
    - Criação de gráficos interativos
    - Exercício: visualizando dados de seca para uma região selecionada
- **Módulo 5**: Análise e visualização de dados de precipitação
    - Explorando conjuntos de dados de precipitação
    - Criando séries temporais de precipitação
    - Cálculo do Índice de Precipitação Padronizado (SPI)
    - Exercício: calculando o SPI para uma região selecionada
 
Se você tiver dúvidas sobre o material contido aqui, pode escrever para [andrebelem@id.uff.br](andrebelem@id.uff.br).
  
