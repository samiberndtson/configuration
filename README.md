# configuration
Using systemd-confext and systemd-sysupdate to configure my computers

systemd-confext status
systemd-confext unmerge
systemd-confext merge
systemd-confext list
systemd-confext refresh

/etc/systemd/confext.conf
[ConfExt]
Mutable=yes


systemctl reload systemd-confext.service
systemctl start systemd-sysupdate.service

systemd-sysupdate list
systemd-sysupdate update

/usr/lib/systemd/systemd-sysupdate update
/usr/lib/systemd/systemd-sysupdate list



 /usr/lib/confexts/

https://cfp.all-systems-go.io/media/all-systems-go-2025/submissions/GSRYLR/resources/asg_2025_confext-4_2a7RaBZ.pdf
