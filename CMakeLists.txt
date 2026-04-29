cmake_minimum_required(VERSION 3.16)
project(humanoid_qinglong)

install(PROGRAMS
    scripts/run_driver_qinglong.sh
    scripts/run_control_qinglong.sh
    scripts/run_hmi_qinglong.sh
    scripts/run_sim2sim_qinglong.sh
    scripts/download_models_qinglong.sh
    DESTINATION bin
)
