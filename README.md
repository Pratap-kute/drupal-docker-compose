
# Sample Drupal docker compose Image 

Drupal with PostgreSQL

## How to run

Access via "http://localhost:8080" \
(or "http://$(docker-machine ip):8080" if using docker-machine)

### During initial Drupal setup 

Database type: PostgreSQL \
Database name: postgres \
Database username: postgres \
Database password: example \
ADVANCED OPTIONS; Database host: postgres [this is name of the services that we specify]