# vars

ros_ip: "{{ ansible_ssh_host }}"
ros_master_uri: "http://{{ ansible_ssh_host }}:11311"

cpu_arch: "latest"

x_speed_multiplier: "1.0"
z_speed_multiplier: "1.0"
output_topic: "/cmd_vel"
manual_topic: "/cmd_vel/manual"
computer_topic: "/cmd_vel/computer"