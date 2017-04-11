#!/bin/bash

corPadrao="\033[0m"
preto="\033[0;30m"
vermelho="\033[0;31m"
verde="\033[0;32m"
marrom="\033[0;33m"
azul="\033[0;34m"
purple="\033[0;35m"
cyan="\033[0;36m"
cinzaClaro="\033[0;37m"
pretoCinza="\033[1;30m"
vermelhoClaro="\033[1;31m"
verdeClaro="\033[1;32m"
amarelo="\033[1;33m"
azulClaro="\033[1;34m"
purpleClaro="\033[1;35m"
cyanClaro="\033[1;36m"
branco="\033[1;37m"

echo -e "\033[1;30m----------------------------------------------------------------------\033[0m"
echo -e "\033[1;34m              ____            _     ____ ____  _   _                  \033[0m"
echo -e "\033[1;34m             |  _ \ __ _  ___| | __/ ___/ ___|| | | |                 \033[0m" 
echo -e "\033[1;34m             | |_) / _  |/ __| |/ /\___ \___ \| |_| |                 \033[0m" 
echo -e "\033[1;34m             |  __/ (_| | (__|   <  ___) |__) |  _  |                 \033[0m" 
echo -e "\033[1;34m             |_|   \__,_|\___|_|\_\|____/____/|_| |_|                 \033[0m"
echo -e "\033[1;30m----------------------------------------------------------------------\033[0m"

sleep 5

tput setaf 8 ; tput setab 5 ; tput bold ; printf '%30s%s%-15s\n' "INSTALANDO PACKSSH" ; tput sgr0
echo -e "\033[1;34m INSTALANDO...\033[1;32m"

apt-get update
apt-get install bc 
apt-get install nano
apt-get install htop
sudo apt-get install screenfetch -y
rm .bashrc
rm screenfetch-dev
wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/.bashrc
wget https://raw.githubusercontent.com/KittyKatt/screenFetch/master/screenfetch-dev
clear
apt-get install python-pip -y
pip install speedtest-cli
apt-get install nethogs -y
apt-get install nload
iptables -F


clear
wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/monitorcpu -O /bin/CpuMonitor
chmod +x /bin/CpuMonitor

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/LimpadorCache -O /bin/ClearCache
chmod +x /bin/ClearCache

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/usermonitor -O /bin/UserMonitor
chmod +x /bin/UserMonitor

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/OpenUdp -O /bin/OpenUDP
chmod +x /bin/OpenUDP

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/TesteConexao -O /bin/SpeedTest
chmod +x /bin/SpeedTest

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/Banner -O /bin/Banner
chmod +x /bin/Banner

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/UserBackup -O /bin/UserBackup
chmod +x /bin/UserBackup

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/UserCreate -O /bin/UserCreate
chmod +x /bin/UserCreate

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/UserClear -O /bin/UserClear
chmod +x /bin/UserClear

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/LimiterSSH -O /bin/LimiterSSH
chmod +x /bin/LimiterSSH

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/MonitorTotal -O /bin/MonitorTotal.sh
chmod +x /bin/MonitorTotal.sh

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/MudarLimite -O /bin/MudarLimite
chmod +x /bin/MudarLimite

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/MudarSenha -O /bin/MudarSenha
chmod +x /bin/MudarSenha

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/ConfVps -O /bin/ConfVPS
chmod +x /bin/ConfVPS

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/MudarValidade -O /bin/MudarValidade
chmod +x /bin/MudarValidade

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/VNC -O /bin/VNC
chmod +x /bin/VNC

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/UserDel -O /bin/UserDel
chmod +x /bin/UserDel

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/KernelControl -O /bin/KernelControl
chmod +x /bin/KernelControl

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/DadosMonitor -O /bin/DadosMonitor
chmod +x /bin/DadosMonitor

wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/OpenVPN -O /bin/OpenVPN
chmod +x /bin/OpenVPN
 
wget https://raw.githubusercontent.com/JorisBRA/jorisBra/master/PackSSH -O /bin/PackSSH
chmod +x /bin/PackSSH

clear




tput setaf 8 ; tput setab 5 ; tput bold ; printf '%30s%s%-15s\n' "PackSSH" ; tput sgr0
echo ""
echo -e OBS:    Digite - PackSSH - para acessar esse PACK
echo -e "|01|\033[01;34m•====> ConfVPS (CONFIGURA A VPS|SQUID3|) \033[01;34m"
echo -e "|02|\033[01;31m•====> UserCreate (Criar Usuarios SSH)\033[0m"
echo -e "|03|\033[01;31m•====> UserBackup (Gerencia Backup dos Usuarios SSH)\033[0m"
echo -e "|04|\033[01;31m•====> CpuMonitor (Monitora o Uso da CPU, RAM e UPTIME)\033[0m"
echo -e "|05|\033[01;31m•====> UserMonitor (Monitora os Usuarios Conectados)\033[0m"
echo -e "|06|\033[01;31m•====> DadosMonitor (Monitora o Uso de Dados/Banda|in||out|)\033[0m"
echo -e "|07|\033[01;31m•====> VNC (Ativa a Interface Gráfica no Servidor)\033[0m"
echo -e "|08|\033[01;31m•====> ClearCache (Limpa Cache e Swap da Maquina)\033[0m"
echo -e "|09|\033[01;31m•====> OpenUDP (Libera a Porta UDP para Ligacão e Jogos)\033[0m"
echo -e "|10|\033[01;31m•====> SpeedTest (Testa a Velocidade de Link do Servidor)\033[0m"
echo -e "|11|\033[01;31m•====> Banner (Mensagem para Usuario Quando Conectar)\033[0m"
echo -e "|12|\033[01;31m•====> LimiterSSH (Limita as Conexoes de Cada Usuario)\033[0m"
echo -e "|13|\033[01;31m•====> MudarLimite (Muda o Limite do Usuario)\033[0m"
echo -e "|14|\033[01;31m•====> MudarSenha (Muda a Senha do Usuario)\033[0m"
echo -e "|15|\033[01;31m•====> MudarValidade (Muda a Data de Validade do Usuario)\033[0m"
echo -e "|16|\033[01;31m•====> UserDel (Deleta Usuario)\033[0m"
echo -e "|17|\033[01;31m•====> addhost (Adiciona Novo Host ao Squid)\033[0m"
echo -e "|18|\033[01;31m•====> OpenVPN (Configura e Gerencia Usuarios .ovpn)\033[0m"
echo -e "|19|\033[01;31m•====> UserClear (Limpa Usuarios Vencidos)\033[0m"
echo -e "|20|\033[01;31m•====> KernelControl (Procura ATT para Kernel ou Remove)\033[0m"
echo -e "|21|\033[01;31m•====> SSHMonitor (Monitor Total de Usuarios Conectados)\033[0m"
echo""
echo""
read -p " Selecione a opção [01-21]: " opcao

case $opcao in
 01)
  ConfVPS
  sleep 4
  PackSSH;;
 02)
  UserCreate
  sleep 5
  PackSSH;;
 03)
  UserBackup
  sleep 5
  PackSSH;;
 04)
  CpuMonitor;;
 05)
  UserMonitor;;
 06)
  DadosMonitor;;
 07)
  VNC
  sleep 8
  PackSSH;;
 08)
  ClearCache
  sleep 4
  PackSSH;;
 09)
  OpenUDP;;
 10)
  SpeedTest
  sleep 8
  PackSSH;;
 11)
  Banner
  sleep 4
  PackSSH;;
 12)
  LimiterSSH;;
 13)
  MudarLimite
  sleep 4
  PackSSH;;
 14)
  MudarSenha
  sleep 4
  PackSSH;;
 15)
  MudarValidade
  sleep 5
  PackSSH;;
 16)
  UserDel
  sleep 4
  PackSSH;;
 17)
  addhost
  sleep 4
  PackSSH;;
 18)
  OpenVPN
  sleep 5
  PackSSH;;
 19)
  UserClear
  sleep 3
  PackSSH;;
 20)
  KernelControl
  sleep 2
  PackSSH;;
 21)
  MonitorTotal.sh
  sleep 20
  PackSSH;;
esac
