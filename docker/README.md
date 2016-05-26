# Run rosnodes in docker container(s)
        docker build -t autovr .
        export ROSBAGDIR=/path/to/rosbags/
        docker-compose up
