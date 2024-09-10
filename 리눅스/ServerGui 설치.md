dnf update -y

dnf grouplist

dnf groupinstall "Workstation" -y


systemctl get-default

systemctl set-default graphical.target

systemctl get-default

reboot
