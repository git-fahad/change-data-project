# change-data-project
Change data project where a notification is sent whenever there is an update on the database.

## Architecture:
Posgresql >> debezium >> kafka '<zookeeper> <control-center>' >> Storm >> Power BI
