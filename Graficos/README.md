COMANDOS PARA GERAR OS GRÁFICOS NAS MÁQUINAS VIRTUAIS:
===============================================================================================
CENARIO1

sadf -T -s 16:00 -e 20:00 -g /var/log/sysstat/sa12 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_ALLINONE_RHFINAL.svg

===============================================================================================
CENARIO2

sadf -T -s 13:45 -e 21:45 -g /var/log/sysstat/sa28 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQ01_RHFINAL.svg
sadf -T -s 13:45 -e 21:45 -g /var/log/sysstat/sa28 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_APP01_RHFINAL.svg
sadf -T -s 13:45 -e 21:45 -g /var/log/sysstat/sa28 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_WEB01_RHFINAL.svg

===============================================================================================

CENARIO3

sadf -T -s 16:50 -e 21:10 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_WEB01_FRW_RHFINAL.svg
sadf -T -s 16:50 -e 21:10 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_APP01_FRW_RHFINAL.svg
sadf -T -s 16:50 -e 21:10 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQ01_FRW_RHFINAL.svg
sadf -T -s 16:50 -e 21:10 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_FIREWALL_RHFINAL.svg

===============================================================================================
CENARIO4

sadf -T -s 14:00 -e 20:00 -g /var/log/sysstat/sa04 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_ALLINONE_OCI_RHFINAL.svg

===============================================================================================

CENARIO5

sadf -T -s 20:25 -e 23:59 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_WEB01_FRW_RHFINAL.svg
sadf -T -s 20:25 -e 23:59 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_APP01_FRW_RHFINAL.svg
sadf -T -s 20:25 -e 23:59 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS__MQCLIENT_MQ01_FRW_RHFINAL.svg
sadf -T -s 20:25 -e 23:59 -g /var/log/sysstat/sa09 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_FIREWALL_RHFINAL.svg

===============================================================================================

CENARIO6

sadf -T -s 14:00 -e 22:00 -g /var/log/sysstat/sa10 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_APP01_WEB_VPN_RHFINAL.svg
sadf -T -s 14:00 -e 22:00 -g /var/log/sysstat/sa10 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS__MQCLIENT_MQ01_VPN_RHFINAL.svg
sadf -T -s 14:00 -e 22:00 -g /var/log/sysstat/sa10 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_FIREWALL_VPN_RHFINAL.svg
sadf -T -s 14:00 -e 22:00 -g /var/log/sysstat/sa10 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_VPN01_RHFINAL.svg
sadf -T -s 14:00 -e 22:00 -g /var/log/sysstat/sa10 -- -u -r -b -S -B -q -n IP -n DEV > GRAFICOS_MQCLIENT_VPN02_RHFINAL.svg
