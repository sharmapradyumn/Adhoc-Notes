#  DAY9

### amazon EBS(elastic block storage)
* today session is about  connecting google drive with aws and use python to store and access data.

~protocol that combine different-2 storage virtually

many HD connected to a single device ---that combine all HD called DEVICE MAPPING.

device mapping===>(1)`LVM`
                  (2) `Stratis`
# LVM(logical volume management)

* combine two hard disk and create a virtual HDD
* make partition from virtual hard disk

## How

* add two hard disk on amazon instance
## creat physical volume
* command --->`` pvcreate ``
* ``pvcreate /dev/xvdh  /dev xvdg``
* system show pvcreate ot found
* command ---> yum which provides */pvcreate
* command ---> ``vgcreate   anyname  /dev/xvdh /dev/xvdg``
* check size of volume--->
* command --->``vgdisplay name``
####  create hard disk
* ``` lvcreate   --name part1   --size 400M myhddrive```
* ``lvdisplay`` diaplay the content of logiacl volume

## how to formate
* `` mkfs.xfs  /dev/mapper/myvirhdd-part1``
## how to mount
* `` mount  /dev/mapper/myvirhdd-part1``
## permanent mount
* ``vim /etc/fstab``
* `` mount -a ``


# add a new user on amazon 
* go to instance
* useradd adhoc
* passwd adhoc
* 


# Micro Services
1. ``Software + OS`` both are launching together are called micro services
 1. linux container(lxc)
 2. process level security(this is use for remove the conflicting of multiple softwares ) 
 4. micro os 1.84 KB
 5. Rhel-8=====> 1.`` podman``
               2. ``buildah``
6. Rhel/U 18.04 -> ``Docker``             

# python part ==>
* today topics in python
### python data streaming
* (module,file handling,input,print,)
* (IP,Port,TCP,UDP)
* UDP example.....DNS,video streaming,DHCP
* TCP example ...... http,https

ip---->127.0.0.1(common)for everyone
*  ``ping`` show  the connectivity
192.168.10.201(between---0-255)ipv4
* port Byte- 2 Byte 

* Broadcast -- single sender ---multiple reciver
* unicast--- single seder --- single reciver
* multicast--- multiple sender ---fixed reciver



