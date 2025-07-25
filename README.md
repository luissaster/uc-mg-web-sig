# SIG UC Minas
## Sistema de Informações Geográficas das Unidades de Conservação de Minas Gerais

Projeto da disciplina SIN 420 - Bancos de Dados Geográficos, da Universidade Federal de Viçosa - *Campus* Rio Paranaíba

### Descrição

Aplicativo web desenvolvido para a visualização e análise das Unidades de Conservação de Minas Gerais. Utiliza Leaflet, GeoServer e dados do OpenStreetMap para oferecer mapas dinâmicos com ferramentas de busca e consulta espacial.

<img width="1912" height="962" alt="print_interface_geral2" src="https://github.com/user-attachments/assets/d7067b6b-6e49-48d5-8dd6-2e90ab206852" />

### Funcionalidades

- Visualização de camadas WMS
- Controle de opacidade das camadas
- Reordenação das camadas por drag-and-drop
- Busca geográfica por nome de localidade ou coordenadas (OpenStreetMap/Nominatim)
- Medição de distâncias no mapa
- Exibição de informações detalhadas das camadas (GetFeatureInfo)

### Tecnologias Utilizadas

- [Leaflet](https://leafletjs.com/) (mapas interativos)
- [GeoServer](https://geoserver.org/) (serviço WMS)
- [OpenStreetMap](https://www.openstreetmap.org/) (dados de base e busca)
- [SortableJS](https://sortablejs.github.io/Sortable/) (drag-and-drop)
- HTML5, CSS3, JavaScript
