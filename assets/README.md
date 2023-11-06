# install
sudo qemu-system-x86_64 \
    -nodefaults \
    -display none \
    -cpu host \
    -boot d \
    -no-reboot \
    -readconfig mgmt.txt \
    -cdrom Check_Point_R80.20_T117_Security_Management.iso
