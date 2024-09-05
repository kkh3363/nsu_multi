dnf update -y

dnf grouplist

dnf groupinstall "Server with GUI" "Graphical Administration Tools"


systemctl get-default

systemctl set-default graphical.target

systemctl get-default

reboot
