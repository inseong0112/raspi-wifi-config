# raspi-wifi-config

sudo vi /etc/wpa_supplicant/wpa_supplicant.conf

ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1
country=EU

network={
        ssid="*************"
        psk="********"
}
