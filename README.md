# tool_release

docker_.tar 命令 docker /sbin/init docker run --privileged --name cjw_rdp_ubuntu -p 29425:3389 -p 22425:22 -v /home/runner:/cjw -itd ubuntu:cjw /sbin/init 只有sysmed root 123456

docker_cjw_rdp_zh.tar 中文
docker_cjw_rdp.tar 英文
docker run --privileged --name cjw_rdp_ubuntu -p 29425:3389 -p 22425:22 -v /home/runner:/cjw -itd ubuntu:cjw_ubuntu-desktop /sbin/init


cjw_manishfoodtechs_xfcefulldesktop_ubuntu20.4.zip 需要解压


docker run -it -p 9096:3389 -e 3389 --shm-size 2g manishfoodtechs/xfcefulldesktop_ubuntu20.4
(2) Service start xrdp:

/etc/init.d/xrdp restart
In above command: -We are starting xrdp

then, ### visit : hostip:9096 in RDP client of your PC. More about RDP here⁠

USER ID: root and Password: 123456 . Please don't forget to change password with command passwd root and add some more users.

[manishfoodtechs/xfcefulldesktop_ubuntu20.4 - Docker Image | Docker Hub](https://hub.docker.com/r/manishfoodtechs/xfcefulldesktop_ubuntu20.4)
