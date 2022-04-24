Plugins to port X-T to stratum

root@localhost:~# /usr/bin/stratum_bf -chassis_config_file=/etc/stratum/x86-64-asterfusion-x312p-48y-t-r0/chassis_config.pb.txt  \
                    -bf_switchd_cfg=/usr/share/stratum/tofino_skip_p4.conf \
                    -bf_switchd_background=false \
                    -bf_sde_install=/usr/local/sde \
                    -enable_onlp=false \
                    -forwarding_pipeline_configs_file=/etc/stratum/x86-64-asterfusion-x312p-48y-t-r0/tna_exact_match.pipeline_config.pb.txt
