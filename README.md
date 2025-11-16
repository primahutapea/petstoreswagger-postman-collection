Cara Import Collection di Postman

1. Buka Postman.
2. Klik **Import**.
3. Pilih file `PetStoreSwagger.postman_collection.json`.


Cara jalankan Collection dengan Newman di CMD

newman run PetStoreSwagger.postman_collection.json \
  -r htmlextra \
  --reporter-htmlextra-export reports/newman-report.html

Requirement :
- Windows 11
- nodeJs v22
- Postman v11.71.7
