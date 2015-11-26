# ez_tf_broadcaster

## Install

```
$ cd ~/catkin_ws/src
$ git clone https://github.com/mu-777/ez_tf_broadcaster.git
$ cd ~/catkin_ws
$ catkin_make
```

## Activation

```
$ rqt
# In the first time to use this, 
# you should use $ rqt --force-discover
```
And select "Easy TF Broadcaster" from Plugin tab -> My rqt

or 

```
$ rosrun rosrun ez_tf_broadcaster tf_broadcaster
```

## Usage

1. Set your desired "frame_name" and "child_frame_name"
2. Click each "update" buttons 
**(Otherwise, "frame_name" and "child_frame_name" will not be applied)**
3. Choose radio button on the top then TF is broadcasted
4. Adjust sliders whatever you want



