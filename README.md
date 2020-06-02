System:    Host: aayush-VirtualBox Kernel: 4.15.0-45-generic x86_64 (64 bit)
           Desktop: Unity 7.4.5  Distro: Ubuntu 16.04 xenial
Machine:   System: innotek (portable) product: VirtualBox v: 1.2
           Mobo: Oracle model: VirtualBox v: 1.2
           Bios: innotek v: VirtualBox date: 12/01/2006
CPU:       Quad core Intel Core i7-7500U (-MCP-) cache: 4096 KB 
           clock speeds: max: 2904 MHz 1: 2904 MHz 2: 2904 MHz 3: 2904 MHz
           4: 2904 MHz
Graphics:  Card: VMware SVGA II Adapter
           Display Server: X.Org 1.19.6 drivers: vmware (unloaded: fbdev,vesa)
           Resolution: 1360x768@60.02hz
           GLX Renderer: llvmpipe (LLVM 6.0, 256 bits)
           GLX Version: 3.0 Mesa 18.0.5
Audio:     Card Intel 82801AA AC'97 Audio Controller driver: snd_intel8x0
           Sound: Advanced Linux Sound Architecture v: k4.15.0-45-generic
Network:   Card: Intel 82540EM Gigabit Ethernet Controller driver: e1000
           IF: enp0s3 state: up speed: 1000 Mbps duplex: full
           mac: 08:00:27:4b:43:ee
Drives:    HDD Total Size: 131.5GB (6.2% used)
           ID-1: /dev/sda model: VBOX_HARDDISK size: 131.5GB
Partition: ID-1: / size: 120G used: 6.7G (6%) fs: ext4 dev: /dev/sda1
           ID-2: swap-1 size: 1.02GB used: 0.00GB (0%) fs: swap dev: /dev/sda5
RAID:      No RAID devices: /proc/mdstat, md_mod kernel module present
Sensors:   None detected - is lm-sensors installed and configured?
Info:      Processes: 188 Uptime: 28 min Memory: 831.3/3944.5MB
           Client: Shell (bash) inxi: 2.2.35 


openjdk version "1.8.0_252"
OpenJDK Runtime Environment (build 1.8.0_252-8u252-b09-1~16.04-b09)
OpenJDK 64-Bit Server VM (build 25.252-b09, mixed mode)

● mysql.service - MySQL Community Server
   Loaded: loaded (/lib/systemd/system/mysql.service; enabled; vendor preset: en
   Active: active (running) since Tue 2020-06-02 21:25:31 IST; 34min ago
 Main PID: 862 (mysqld)
   CGroup: /system.slice/mysql.service
           └─862 /usr/sbin/mysqld

Jun 02 21:25:25 aayush-VirtualBox systemd[1]: Starting MySQL Community Server...
Jun 02 21:25:31 aayush-VirtualBox systemd[1]: Started MySQL Community Server.
Jun 02 21:58:23 aayush-VirtualBox systemd[1]: Started MySQL Community Server.
Jun 02 21:59:32 aayush-VirtualBox systemd[1]: Started MySQL Community Server.

+--------------------+
| Database           |
+--------------------+
| information_schema |
| FIRSTDB            |
| mysql              |
| performance_schema |
| sys                |
+--------------------+


# Server
redis_version:6.0.4
redis_git_sha1:00000000
redis_git_dirty:0
redis_build_id:ae8d8d7511d46010
redis_mode:standalone
os:Linux 4.15.0-45-generic x86_64
arch_bits:64
multiplexing_api:epoll
atomicvar_api:atomic-builtin
gcc_version:5.4.0
process_id:1749
run_id:cf5ec11ffce333f2bbdf064f33d2ef069c42fd6f
tcp_port:6379
uptime_in_seconds:18
uptime_in_days:0
hz:10
configured_hz:10
lru_clock:14063455
executable:/home/aayush/redis-server
config_file:

# Clients
connected_clients:1
client_recent_max_input_buffer:2
client_recent_max_output_buffer:0
blocked_clients:0
tracking_clients:0
clients_in_timeout_table:0

# Memory
used_memory:866264
used_memory_human:845.96K
used_memory_rss:5312512
used_memory_rss_human:5.07M
used_memory_peak:866264
used_memory_peak_human:845.96K
used_memory_peak_perc:100.18%
used_memory_overhead:819778
used_memory_startup:802792
used_memory_dataset:46486
used_memory_dataset_perc:73.24%
allocator_allocated:1012048
allocator_active:1228800
allocator_resident:3637248
total_system_memory:4136476672
total_system_memory_human:3.85G
used_memory_lua:37888
used_memory_lua_human:37.00K
used_memory_scripts:0
used_memory_scripts_human:0B
number_of_cached_scripts:0
maxmemory:0
maxmemory_human:0B
maxmemory_policy:noeviction
allocator_frag_ratio:1.21
allocator_frag_bytes:216752
allocator_rss_ratio:2.96
allocator_rss_bytes:2408448
rss_overhead_ratio:1.46
rss_overhead_bytes:1675264
mem_fragmentation_ratio:6.45
mem_fragmentation_bytes:4488760
mem_not_counted_for_evict:0
mem_replication_backlog:0
mem_clients_slaves:0
mem_clients_normal:16986
mem_aof_buffer:0
mem_allocator:jemalloc-5.1.0
active_defrag_running:0
lazyfree_pending_objects:0

# Persistence
loading:0
rdb_changes_since_last_save:0
rdb_bgsave_in_progress:0
rdb_last_save_time:1591121742
rdb_last_bgsave_status:ok
rdb_last_bgsave_time_sec:-1
rdb_current_bgsave_time_sec:-1
rdb_last_cow_size:0
aof_enabled:0
aof_rewrite_in_progress:0
aof_rewrite_scheduled:0
aof_last_rewrite_time_sec:-1
aof_current_rewrite_time_sec:-1
aof_last_bgrewrite_status:ok
aof_last_write_status:ok
aof_last_cow_size:0
module_fork_in_progress:0
module_fork_last_cow_size:0

# Stats
total_connections_received:1
total_commands_processed:1
instantaneous_ops_per_sec:0
total_net_input_bytes:31
total_net_output_bytes:18499
instantaneous_input_kbps:0.00
instantaneous_output_kbps:0.00
rejected_connections:0
sync_full:0
sync_partial_ok:0
sync_partial_err:0
expired_keys:0
expired_stale_perc:0.00
expired_time_cap_reached_count:0
expire_cycle_cpu_milliseconds:0
evicted_keys:0
keyspace_hits:0
keyspace_misses:0
pubsub_channels:0
pubsub_patterns:0
latest_fork_usec:0
migrate_cached_sockets:0
slave_expires_tracked_keys:0
active_defrag_hits:0
active_defrag_misses:0
active_defrag_key_hits:0
active_defrag_key_misses:0
tracking_total_keys:0
tracking_total_items:0
tracking_total_prefixes:0
unexpected_error_replies:0

# Replication
role:master
connected_slaves:0
master_replid:6745724550a30429d4176c2e287aa2ce22a5aeec
master_replid2:0000000000000000000000000000000000000000
master_repl_offset:0
second_repl_offset:-1
repl_backlog_active:0
repl_backlog_size:1048576
repl_backlog_first_byte_offset:0
repl_backlog_histlen:0

# CPU
used_cpu_sys:0.022838
used_cpu_user:0.000000
used_cpu_sys_children:0.000000
used_cpu_user_children:0.000000

# Modules

# Cluster
cluster_enabled:0

# Keyspace


