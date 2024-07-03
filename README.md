# mobile_base_operator
**Author** : <a href="https://github.com/mjlee111"><img src="https://img.shields.io/badge/Myeong Jin Lee-white?style=flat&logo=github&logoColor=red"/></a>
**Version** : 1.0   
**License** : Apache 2.0      
**Maintainor** : Lee <menggu1234@naver.com>   
**Bug / feature tracker** : https://github.com/RO-BIT-Intelligence-Robot-Team/mobile_base_operator/issues   
**Source** : https://github.com/RO-BIT-Intelligence-Robot-Team/mobile_base_operator.git (branch : master)

## Description
Team RO:BIT Mobile Base Robot KULS Operator package.

## How to use
#### Build from source.
```shell
$ cd ~/${workspace_name}/src
$ git clone https://github.com/RO-BIT-Intelligence-Robot-Team/mobile_base_operator.git
$ cd mobile_base_operator
$ git submodule init
$ git submodule update
$ cd ../..
$ catkin_make
```

#### launch file usage
```shell
$ roslaunch robot_operator kuls.launch
```

#### Launch Parameters
- joy_type  
Type: string
Default Value: deck

- cam1_topic  
Type: string
Default Value: /camera_auto/usb_cam_auto/image_raw  

- cam2_topic  
Type: string  
Default Value: /split_image/output/vertical00/horizontal00  

- cam3_topic  
Type: string  
Value: /split_image/output/vertical00/horizontal01

<div align="center">
<img src="https://github.com/RO-BIT-Intelligence-Robot-Team/mobile_base_operator/blob/master/doc/gui.png" alt="gui" width="1600" height="900">
</div>
