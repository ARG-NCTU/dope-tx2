# dope-tx2
### setup
`git clone https://github.com/ARG-NCTU/dope-tx2.git`

`cd dope-tx2`

`source tx2_docker_run.sh`

`cd dope`

`source environment.sh`

`source tx2_catkin_make.sh`

## terminal 1
`cd dope-tx2`

`source tx2_docker_run.sh`

`cd dope`

`source environment.sh`

`roslaunch dope dope.launch`

## terminal 2 (if you need compressed image)
`cd dope-tx2`

`source tx2_docker_join.sh`

`cd dope`

`source environment.sh`

`rosrun image_transport republish raw in:=<topic_name> compressed out:=<topic_name>`

## modify object
`cd dope-tx2/catkin_ws/src/dope/config`

`vim config_pose.yaml`

