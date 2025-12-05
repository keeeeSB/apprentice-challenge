# ディレクトリを操作できる

Linux にログインしてターミナル上で行ってください。

## 1. 現在のディレクトリ

自分が現在いるディレクトリを表示してください。

/home/ubuntu

## 2. ルートディレクトリ

現在のディレクトリから、"/" ディレクトリに移動してください。

cd /

## 3. ホームディレクトリ

現在のディレクトリから、ホームディレクトリに移動してください。

cd home

## 4. 一つ上のディレクトリ

現在のディレクトリから、一つ上の親ディレクトリに移動してください。

cd ..

## 5. ディレクトリの内容

現在のディレクトリの内容を表示してください。

ls
bin                boot  etc   lib                lost+found  mnt  proc  run   sbin.usr-is-merged  srv  tmp  var
bin.usr-is-merged  dev   home  lib.usr-is-merged  media       opt  root  sbin  snap                sys  usr

## 6. 隠しファイル

現在のディレクトリの隠しファイルを含む全てのファイルとディレクトリを表示してください。

ls -a
.   bin                boot  etc   lib                lost+found  mnt  proc  run   sbin.usr-is-merged  srv  tmp  var
..  bin.usr-is-merged  dev   home  lib.usr-is-merged  media       opt  root  sbin  snap                sys  usr

## 7. 詳細なリスト形式

"/etc" ディレクトリの内容を、詳細なリスト形式で表示してください。

ModemManager            cron.weekly           groff            ld.so.conf.d    modules                 plymouth      sensors.d          timezone
PackageKit              cron.yearly           group            ldap            modules-load.d          pm            sensors3.conf      tmpfiles.d
X11                     crontab               group-           legal           mtab                    polkit-1      services           ubuntu-advantage
adduser.conf            cryptsetup-initramfs  grub.d           libaudit.conf   multipath               pollinate     sgml               ucf.conf
alternatives            crypttab              gshadow          libblockdev     multipath.conf          profile       shadow             udev
apparmor                dbus-1                gshadow-         libibverbs.d    nanorc                  profile.d     shadow-            udisks2
apparmor.d              debconf.conf          gss              libnl-3         needrestart             protocols     shells             ufw
apport                  debian_version        hdparm.conf      locale.alias    netconfig               python3       skel               update-manager
apt                     default               host.conf        locale.conf     netplan                 python3.12    sos                update-motd.d
bash.bashrc             deluser.conf          hostname         locale.gen      network                 rc0.d         ssh                update-notifier
bash_completion         depmod.d              hosts            localtime       networkd-dispatcher     rc1.d         ssl                usb_modeswitch.conf
bash_completion.d       dhcp                  hosts.allow      logcheck        networks                rc2.d         subgid             usb_modeswitch.d
bindresvport.blacklist  dhcpcd.conf           hosts.deny       login.defs      newt                    rc3.d         subgid-            vconsole.conf
binfmt.d                dpkg                  init.d           logrotate.conf  nftables.conf           rc4.d         subuid             vim
byobu                   e2scrub.conf          initramfs        logrotate.d     nsswitch.conf           rc5.d         subuid-            vmware-tools
ca-certificates         ec2_version           initramfs-tools  lsb-release     opt                     rc6.d         sudo.conf          vtrgb
ca-certificates.conf    environment           inputrc          lvm             os-release              rcS.d         sudo_logsrvd.conf  wgetrc
cloud                   ethertypes            iproute2         machine-id      overlayroot.conf        resolv.conf   sudoers            xattr.conf
console-setup           flash-kernel          iscsi            magic           overlayroot.local.conf  rmt           sudoers.d          xdg
credstore               fonts                 issue            magic.mime      pam.conf                rpc           supercat           xml
credstore.encrypted     fstab                 issue.net        manpath.config  pam.d                   rsyslog.conf  sysctl.conf        zsh_command_not_found
cron.d                  fuse.conf             kernel           mdadm           passwd                  rsyslog.d     sysctl.d
cron.daily              fwupd                 landscape        mime.types      passwd-                 screenrc      sysstat
cron.hourly             gai.conf              ld.so.cache      mke2fs.conf     perl                    security      systemd
cron.monthly            gnutls                ld.so.conf       modprobe.d      pki                     selinux       terminfo

なおわからない場合は、"man ls" コマンドで ls コマンドの詳細を確認することができます。"List files in the long format" といった説明のあるオプションを付けてください。

## 8. ディレクトリの作成

ホームディレクトリに移動し、"projects" という名前のディレクトリを作成してください。

cd
mkdir projects

## 9. ディレクトリの削除

作成した "projects" ディレクトリを削除してください。
