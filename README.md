# rhel-8.7-rt-kernel

Steps:

```
subscription-manager repos --enable rhel-8-for-x86_64-rt-rpms
yum groupinstall RT
sudo reboot
```

Result:
```
4.18.0-477.15.1.rt7.278.el8_8.x86_64
```
