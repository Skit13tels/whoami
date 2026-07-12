# whoami
Вырезка практики (июнь – июль 2026)

Инфраструктура и сети

Развернул виртуальный полигон на базе VirtualBox: Kali Linux, Metasploitable 2, Windows Server 2022, Ubuntu Server.

Настроил изолированные и маршрутизируемые сети (Internal Network, NAT, Host-Only). Решал проблемы ARP, DHCP, статической маршрутизации, двойного NAT, блокировок DPI.

Подключил и настроил старый D-Link DIR-300 как точку доступа и полигон для атак.

Linux и скриптинг

Прошёл 15 уровней OverTheWire Bandit: работа с правами, фильтрация текста, hex-дампами, многократным сжатием.

Освоил базовое администрирование: systemctl, netplan, ip, chmod, ssh, scp.

DevOps (онлайн-интенсив): написал конфигурационный файл systemd (unit) для автоматического запуска скрипта при загрузке системы. Начал осваивать Vim.

Кибербезопасность и атаки

Провёл эксплуатацию двух уязвимостей (vsftpd 2.3.4, UnrealIRCd) на Metasploitable 2 с использованием Metasploit. Получил root-доступ, работал с Meterpreter.

Развернул SIEM (Wazuh Manager + агент на Windows Server). Обнаруживал атаки брутфорса (RDP, WinRM) по событиям Event ID 4624/4625.

Инструменты

nmap (разведка и сканирование), hydra, evil-winrm, msfconsole, Wireshark (базовый анализ).
