# SIGA Madeira Android

Aplicação estática Leaflet + JavaScript com dados reais do feed GTFS SIGA versão 202609181215, válido entre 10/09/2026 e 30/11/2026.

## GitHub Pages

Extrair o ZIP do projeto e enviar **o conteúdo** da pasta para a raiz da branch `main` do repositório `Gfs_siga`, incluindo a pasta `data` e o ficheiro `data/siga.json`. Em Settings > Pages escolher Deploy from a branch, main, /(root). Não enviar apenas o ZIP.

A app consulta `data/siga.json` no mesmo domínio, eliminando problemas CORS e a necessidade de importar GTFS manualmente. Os trajetos foram amostrados para reduzir o volume de dados; as paragens desenhadas no mapa são os terminais das viagens, não todas as paragens intermédias. Os horários apresentados são apenas as partidas e chegadas programadas, não todas as passagens intermédias. Sem GPS em tempo real. Para dados posteriores a 30/11/2026 é necessário atualizar o feed.
