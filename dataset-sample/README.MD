## Command to import dataset to Elasticsearch ##
curl -H "Content-Type: application/json" -XPOST "http://localhost:9200/product/_doc/_bulk?pretty" --data-binary "@test-data.json"
