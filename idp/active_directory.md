## Active Directory Notes

### Tips & Tricks ###

**Snag a copy of the AD CA certs via ldapsearch**

```bash
export LDAP_SERVER="ldap.college.edu"
export LDAP_USER_DN="CN=Jim Bob,OU=linuxadmins,DC=adrealm,DC=college,DC=edu"
export ADREALM_DN="dc=adrealm,dc=college,dc=edu"

 ldapsearch -h $LDAP_SERVER -D $LDAP_USER_DN -b "cn=configuration,$ADREALM_DN" "cacertificate=*" -W

```

