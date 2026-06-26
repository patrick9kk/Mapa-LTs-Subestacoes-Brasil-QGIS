# Mapa-LTs-Subestacoes-Brasil-QGIS

> Nome atual no GitHub: `Mapas-de-linhas-de-transmissão-e-subestações`. Sugestão de nome mais descritivo (sem acentos, compatível com URLs): **`Mapa-LTs-Subestacoes-Brasil-QGIS`**.

Mapas interativos em **HTML** com as linhas de transmissão (LTs) e subestações de energia existentes e previstas no Brasil, construídos a partir de bases de dados públicas.

## Motivação

Consultar mapas de linhas de transmissão é uma necessidade recorrente, mas as opções existentes para visualização desses dados costumavam ser lentas ou não atendiam às necessidades específicas do autor. Este projeto cria mapas personalizáveis, de fácil exportação e compartilhamento com colegas de trabalho.

## Fontes de dados

- **EPE** (Empresa de Pesquisa Energética) — bases de linhas de transmissão e subestações.
- **IBGE** — bases geográficas/territoriais.

## Ferramentas utilizadas

- **QGIS** — software de SIG (Sistema de Informação Geográfica) usado para tratar e estilizar os dados.
- **Plugin `qgis2web`** — exporta o projeto QGIS para um mapa interativo em HTML/Leaflet.
- **Plugin `QuickMapServices`** — fornece camadas de mapa-base (basemaps).

## Conteúdo do repositório

| Arquivo | Descrição |
|---|---|
| `Mapas.rar` | Arquivo compactado contendo as pastas com os mapas exportados em HTML (gerados via `qgis2web`). |

## Como abrir os mapas

1. Extraia o conteúdo de `Mapas.rar`.
2. Cada mapa fica em sua própria pasta, contendo um arquivo `index.html`.
3. Abra o `index.html` correspondente diretamente no navegador para visualizar o mapa.

## Limitações conhecidas

- Não é possível filtrar/buscar subestações diretamente no mapa — apenas linhas de transmissão instaladas podem ser filtradas pelo plugin usado. Para localizar uma subestação específica, é necessário usar `Ctrl+F` na página HTML.
- Nem todas as ferramentas de visualização desejadas estão implementadas ainda.

## Próximos passos / ideias futuras

- Adicionar filtro/busca por subestação.
- Expandir camadas e ferramentas de interação no mapa exportado.

Sugestões de melhorias são bem-vindas — o autor está à disposição para discutir o andamento do projeto.
