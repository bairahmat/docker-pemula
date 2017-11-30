#### Debian 9 Kambing UI
mv /etc/apt/sources.list /etc/apt/sources.list.bak 
touch /etc/apt/sources.list chmod 777 /etc/apt/sources.list 
cat <<EOF >>/etc/apt/sources.list deb 
deb http://kambing.ui.ac.id/debian/ stretch main contrib non-free
deb http://kambing.ui.ac.id/debian/ stretch-updates main contrib non-free
deb http://kambing.ui.ac.id/debian-security/ stretch/updates main contrib non-free
EOF
