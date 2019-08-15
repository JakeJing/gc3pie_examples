## gc3pie.conf.template

This is the template for gc3pie.conf. You can download and replace the automatically generated gc3pie.conf.

> mv gc3pie.conf ~/.gc3/gc3pie.conf

**Note:** some parameters need to be changed according to your own resources (see also the gc3pie.conf for detailed comments). 

enabled=yes   (change to be yes)
instance_type=8cpu-32ram-hpc  (VM resources)
image_id=7fe5f2a8-a145-4afe-ada4-16a1dbf8ab82  (the image id of the snapshot)
network_ids=c86b320c-9542-4032-a951-c8a068894cc2  (UZH network id)
keypair_name=yingqi  (private key name, can be found in your computer under the folder .~/ssh/)
public_key=~/.ssh/yingqi.key.pub (public key name)
