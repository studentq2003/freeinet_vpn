# Setup your VPN server

## first step
1. Get VPS and domain
2. Link domain to VPS
3. Install Ubuntu to VPS
## second step
Download script.sh to VPS server:

wget https://raw.githubusercontent.com/jawj/IKEv2-setup/master/setup.sh
chmod u+x setup.sh
./setup.sh

## third step
Follow the instructions, add domain, create user, password for connect

## connect on macos
1. Add VPN configuration -> IKEv2
2. Choose server address your domain and remote id the same
3. Choose authentication type by username, select username and password
4. Connect to VPN
