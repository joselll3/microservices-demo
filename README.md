explorar topics kafka

docker run -it --network=host confluentinc/cp-kafkacat /bin/bash

kafkacat -C -b localhost:19092 -t twitter-topic