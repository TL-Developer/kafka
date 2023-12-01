# KAFKA CONSOLE CONSUMER

Enter the kafka docker container
```
docker-compose exec kafka bash
```

Log Consumer realtime
```
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=sales
```

Log Consumer history
```
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=sales --from-beginning
```

# KAFKA CONSOLE PRODUCER

Enter the kafka docker container
```
docker-compose exec kafka bash
```

Log Producer realtime
```
kafka-console-producer --bootstrap-server=localhost:9092 --topic=sales
```