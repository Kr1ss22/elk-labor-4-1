# Labor 4.1 – Elasticsearch ja Kibana (ELK Stack)

See repositoorium sisaldab töö jaoks vajalikke faile Docker Compose abil ELK Stacki (Elasticsearch + Kibana + Logstash) käivitamiseks.

## Sisaldab:
- `docker-compose.yml`
- `.env`
- Logstash, Elasticsearch ja Kibana konfiguratsiooni
- Labori juhend, mille järgi teostati:
  - Elasticsearchi käivitamine
  - Kibana avamine
  - Dev Tools testid
  - Indeksite loomine
  - Dokumentide lisamine
  - Otsingud (match, bool, range, sortimine)
  - Indeksi haldus
  - Stacki peatamine ja puhastamine

## Labori eesmärgid
Labori lõpuks tegin:
1. Elasticsearchi ja Kibana paigalduse Docker Compose abil  
2. Esimese indeksi loomise  
3. Dokumentide lisamise  
4. Päringute täitmise Kibana Dev Toolsis  
5. Tulemuste sorteerimise, filtreerimise ja analüüsi  
6. Indeksite haldamise  
7. Stacki sulgemise ja ressursside puhastamise  

## Kuidas käivitada (taastamiseks):
```bash
docker compose up setup
docker compose up -d
