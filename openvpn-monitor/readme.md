#need to run following commands
echo management 0.0.0.0 5555 >> /etc/openvpn/server/server.conf
sudo systemctl restart openvpn-server@server.service