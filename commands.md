# Linux commands
1. `stat -c %s filename` shows the size of a file
2. `du -h --max-depth=2` shows the size of the current folder
3. `df -h` displayis information about disk space usage on a system
4. `wget -P dir URL` downloads files from the internet to the target dir
5. `tar xpzf filename` extracts files from a compressed tarball in a specific format:
   * `x` stands for extract;
   * `p` stands for preserve;
   * `z` stands for gzip;
   * `f` specifies the file to be extracted. The following argument after f should be the name of the tarball.
6. `su` switches to root user; the default password is `root`
7. `export PATH=/path/to/your/file:$PATH` adds a dir to PATH
8. Sometimes you need to set some environment variables for installation. For example, when install nvidia hpc sdk, you need to set the following environment variabls for installation.
   ```bash
   export NVHPC_SILENT="true"
   export NVHPC_INSTALL_DIR="/opt/nvidia/hpc_sdk"
   export NVHPC_INSTALL_TYPE="auto"
   ```
9. `uname -s` displays the operating system name:
   * Linux: This indicates that the operating system is a Linux distribution.
   * Darwin: This indicates that the operating system is macOS.
   * FreeBSD: This indicates that the operating system is FreeBSD.
11. `uname -m` displays the machine hardware name or architecture.
   * x86_64: This indicates a 64-bit x86 (Intel/AMD) architecture.
   * i686 or i386: These indicate a 32-bit x86 architecture.
   * armv7l or similar: These indicate an ARM architecture, with different versions such as ARMv7.
13. 

# Docker commands
1. `docker inspect container_name | grep -i size` shows the size of a container
2. `docker start container_name` runs a existing container
3. `docker attach container_name` enters the terminal of a running container
4. `docker system df` show you the amount of space used by different Docker components, including images, containers, and volumes.
