# verrokki-index

Verrokin OpenSearch-hakuindeksi. AWS:ssä Amazon OpenSearch Service, lokaalisti
`opensearchproject/opensearch`

## Lokaalisti

Käynnistys:

```bash
docker compose up -d
```

- OpenSearch: http://localhost:9200
- OpenSearch Dashboards: http://localhost:5601

Lokaalisti security-plugin on pois päältä, joten kutsut eivät vaadi tunnistautumista.

Pysäytys (data säilyy volumessa):

```bash
docker compose down
```

Pysäytys ja datan poisto:

```bash
docker compose down -v
```
