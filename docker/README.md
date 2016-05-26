# Run rosnodes in docker container(s)
        docker build -t autovr .
 	
(optional) adapt name of rosbag to play in docker-compose.yml line 13 (default is 2016-05-11-00-00-01.bag)
        export ROSBAGDIR=/path/to/rosbags/
        docker-compose up
