An MⷨaͣrͬiͥaͣDͩВ web server builds on 𝓐𝓵𝓹𝓲𝓷𝓮 𝓛𝓲𝓷𝓾𝔁.

Build and maintained by: Realm Chua < realm at mylinuxbox dot cloud>

https://github.com/realmchua/

https://hub.docker.com/repository/docker/realmsg/

https://mylinuxbox.cloud

𝗪𝗵𝗮𝘁 𝗶𝘀 𝗠𝗮𝗿𝗶𝗮𝗗𝗕❓

MariaDB Server is one of the most popular database servers in the world. It’s made by the original developers of MySQL and guaranteed to stay open source. Notable users include Wikipedia, DBS Bank, and ServiceNow.

𝗛𝗼𝘄 𝘁𝗼 𝗯𝘂𝗶𝗹𝗱 𝗳𝗿𝗼𝗺 𝘁𝗵𝗲 𝗗𝗼𝗰𝗸𝗲𝗿𝗳𝗶𝗹𝗲❓

wget https://github.com/realmchua/mariadb.git

cd mariadb

./build.sh (To build the image from the Dockerfile)

𝗛𝗼𝘄 𝘁𝗼 𝘂𝘀𝗲 𝗺𝘆 𝗶𝗺𝗮𝗴𝗲❓

./deploy (To deploy the image file) or

docker -itd -p 3306 -v /var/lib/mysql:/var/lib/mysql --name mysql realmsg/mariadb:stable

./push (To push the image to Docker Hub's Repository)
  
D̳i̳s̳c̳l̳a̳i̳m̳e̳r̳: 

Please visit https://pkgs.alpinelinux.org/ to view the license information for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under additional licenses (such as bash, etc., from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
