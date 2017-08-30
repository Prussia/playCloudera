# playCloudera

## Get Started
- [How to setup Cloudera Quickstart Virtual Machine](https://community.cloudera.com/t5/Hadoop-101-Training-Quickstart/How-to-setup-Cloudera-Quickstart-Virtual-Machine/ta-p/35056)
### VM Virtual Box
- Installing Oracle VirtualBox(free/opensource)
- [Download VM files of CDH 5.12](https://www.cloudera.com/downloads/quickstart_vms/5-12.html)
- VirtualBox, you would have downloaded and extracted a *.ovf file from Cloudera. Use the “File -> Import Appliance” menu inside VirtualBox to open your downloaded *.ovf file, or simply double-click on the file itself and VirtualBox should handle it from there.

### Container
- [Cloudera Docker Container](https://www.cloudera.com/documentation/enterprise/5-6-x/topics/quickstart_docker_container.html)
```
tar xzf cloudera-quickstart-vm-*-docker.tar.gz
docker import - cloudera/quickstart:latest < cloudera-quickstart-vm-*-docker/*.tar
```

```
docker run --hostname=quickstart.cloudera --privileged=true -t -i -p 8888:8888 cloudera/quickstart:latest /usr/bin/docker-quickstart
```

