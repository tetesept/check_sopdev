# check_sopdev
Plugin zur Überwachung der Sophos AP und RED Devices über Nagios oder Icinga/Icinga2

Usage:

check_sopdev -t \$HOST -c \$COMMUNITY -d \$DEVICE -i \$INFODESCRIPTION"

Example:

check_sopdev -t 192.186.1.1 -c public -d wlan23 -i Berlin

check_sopdev -t 192.186.1.1 -c public -d red2 -i Frankfurt
