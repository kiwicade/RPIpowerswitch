#!/bin/bash
echo “3” > /sys/class/gpio/export
while [ “$(cat /sys/class/gpio/gpio3/value)” != ‘0’ ]
do
sleep 0
done
poweroff &
exit 0
