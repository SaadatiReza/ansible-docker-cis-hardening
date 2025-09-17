## 2 Docker daemon configuration
  [] 2.1 Run the Docker daemon as a non-root user, if possible (Manual)
  [x] 2.2 Ensure network traffic is restricted between containers on the
default bridge (Manual)
  [x] 2.3 Ensure the logging level is set to 'info' (Manual)
  [x] 2.4 Ensure Docker is allowed to make changes to iptables
(Manual)
  [x] 2.5 Ensure insecure registries are not used (Manual)
  [x] 2.6 Ensure aufs storage driver is not used (Manual)
  [x] 2.7 Ensure devicemapper storage driver is not used (Manual)
  [x] 2.8 Ensure TLS authentication for Docker daemon is configured (Manual) --> 
  By default, the Docker daemon binds to a non-networked Unix socket and runs with root privileges
  [x] 2.9 Ensure the default ulimit is configured appropriately (Manual)
  []  2.10 Enable user namespace support (Manual)
  [x] 2.11 Ensure the default cgroup usage has been confirmed (Manual)
  [] 2.12 Ensure base device size is not changed until needed (Manual)
      Remediation: Do not set --storage-opt dm.basesize until needed.
  [] 2.13 Ensure that authorization for Docker client commands is
enabled (Manual)
  [x] 2.14 Ensure centralized and remote logging is configured
(Manual)
  [x] 2.15 Ensure containers are restricted from acquiring new
privileges (Manual)
  [x] 2.16 Ensure live restore is enabled (Manual)
  [x] 2.17 Ensure Userland Proxy is Disabled (Manual)

