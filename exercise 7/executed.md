* Ensure package manager repositories are configured
   !["configured package manager"](screen/package-manager.png)

* Ensure GPG keys are configured (Manual)
   !["configured GPG keys"](screen/gpg-keys.png)

* Ensure AppArmor is installed (Automated)
    !["AppArmor"](screen/apparmor.png)

* Ensure all AppArmor Profiles are in enforce or complain
mode (Automated)
    !["AppArmor-status"](screen/apparmor-status.png)

* Ensure permissions on /etc/issue are configured

* Ensure updates, patches, and additional security software are
installed (Manual)
   !["ensure-updats"](screen/ensure-updats.png)

* Ensure LDAP server is not installed (Automated)

* Ensure NFS is not installed (Automated)
    {command: apt purge nfs-kernel-server}

*  Ensure CUPS is not installed (Automated)
     !["ensure-cup not installed"](screen/cups.png)

