# Apache Druid

## Idee

- Wird auf einen Kafka Stream geschaltet
- Liest Kafka Stream aus und speichert Daten in einer zeitbasierten(?) DB
- Dient als JDBC-Schnittstelle, damit Anwendungen, die nicht mit Kafka kompatibel sind, Kafka Streams auslesen können
- Wird eher als nicht so schöner Workaround angesehen, aber kein guter Workaround für Anwendungen vorhanden, die JDBC-Schnittstellen brauchen / mit Kafka Streams nicht kompatibel sind

## Schulungen
- [ImplyIO Schulung](https://learn.imply.io/)
