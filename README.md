# cloudinit
### userdata scripts

<h3>ubuntu_ec2_instance_connect </h3>
<p> paste the following in AWS userdata section to install ec2-instance-connect on an Ubuntu instance </p>

 ```bash
 #!/bin/bash
 wget https://git.io/fjjYi -O ec2-instance-connect.sh
 bash ec2-instance-connect.sh
 ```
