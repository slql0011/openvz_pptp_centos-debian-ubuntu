openvz_pptp_centos-debian-ubuntu
============================
forked from [lknife/openvz_pptp_centos-debian-ubuntu](https://github.com/lknife/openvz_pptp_centos-debian-ubuntu)

首先检查端口：
============================

    cat /dev/ppp
    cat /dev/net/tun

出现

    No such device or address
    File descriptor in bad satae

则表示可以继续

============================
1.CentOS-5x86-6 OpenVZ安装方法：
============================

    wget --no-check-certificate https://github.com/slql0011/openvz_pptp_centos-debian-ubuntu/raw/master/openvps_vpn_centos-5-6.sh
    chmod a+x openvps_vpn_centos-5-6.sh
    bash openvps_vpn_centos-5-6.sh

2.Debian/Ubuntu OpenVZ安装方法：
============================

    wget --no-check-certificate https://github.com/slql0011/openvz_pptp_centos-debian-ubuntu/raw/master/auto-debian-ovz-pptp.sh
    sh auto-debian-ovz-pptp.sh

或者进FTP编辑/etc/ppp/chap-secrets创建和修改账号
