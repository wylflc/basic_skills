# Linux commands
1. `stat -c %s filename` shows the size of a file
2. `du -h --max-depth=2` shows the size of the current folder
3. `df -h` displayis information about disk space usage on a system
4. `wget URL` downloads files from the internet
5. `tar xpzf filename` extracts files from a compressed tarball in a specific format:
    * `x` stands for extract;
    * `p` stands for preserve;
    * `z` stands for gzip;
    * `f` specifies the file to be extracted. The following argument after f should be the name of the tarball.

# Docker commands
1. `docker inspect container_name | grep -i size` shows the size of a container
2. `docker start container_name` runs a existing container
3. `docker attach container_name` enters the terminal of a running container
