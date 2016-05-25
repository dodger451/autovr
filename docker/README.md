# Run rosnodes in docker container(s)
        docker build -t $(IMAGE) .
        export ROSBAGDIR=/path/to/rosbags/
        docker-compose up
