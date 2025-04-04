# Terminal commands
´´´ sh
docker-compose exec mongodb bash
´´´
# Connect with mongo sh
´´´ sh
mongosh "mongodb://root:52863258@localhost:27017/?tls=false"
´´´
´´´ sh
show dbs
show collections
´´´
´´´ sh
use("platzi_store")
db.products.find()
´´´