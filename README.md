# APACHE KAFKA® FOR PYTHON DEVELOPERS

Based on course https://developer.confluent.io/courses/kafka-python

```shell
virtualenv env

source env/bin/activate

pip install confluent-kafka

confluent local kafka start
confluent services schema-registry start
```

Update `config.py` with the Plaintext Ports output from starting local kafka.

```shell
chmod u+x producer.py

./producer.py 
```

```shell
chmod u+x consumer.py

./consumer.py 
```

```shell
pip install jsonschema
pip install requests
```

```shell
chmod u+x json_producer.py

./json_producer.py
```

```shell
chmod u+x json_consumer.py

./json_consumer.py
```

```shell
chmod u+x admin.py

./admin.py
```

```shell
confluent local services sr stop
confluent local kafka stop
```

```shell
deactivate
```