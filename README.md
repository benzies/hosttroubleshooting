# Toubleshooting


## Host 1
```
Apr 06 09:09:01 HoneyPot1 CRON[29488]: pam_unix(cron:session): session failed for user comf_au
Apr 06 09:10:05 HoneyPot1 sshd[5351]: Bad protocol version identification '\003' from 185. port 1610
Apr 06 09:11:57 HoneyPot1 sshd[6306]: Bad protocol version identification '\003' from 185. port 1610
Apr 06 09:11:57 HoneyPot1 sshd[6306]: Failed '\003' from 185. port 1609
Apr 06 09:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 06 09:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session closed for user comf_au
Apr 06 09:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 06 16:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session closed for user comf_au
Apr 06 16:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session timeout for user comf_au
```
## Host 2
```
Apr 07 08:09:01 HoneyPot1 CRON[29488]: pam_unix(cron:session): session failed for user comf_au
Apr 07 08:10:05 HoneyPot1 sshd[5351]: Bad protocol version identification '\003' from 185. port 8101
Apr 07 08:11:57 HoneyPot1 sshd[6306]: Bad protocol version identification '\003' from 185. port 8101
Apr 07 08:11:57 HoneyPot1 sshd[6306]: Failed '\003' from 185. port 8100
Apr 07 08:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 07 08:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session closed for user comf_au
Apr 07 08:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 07 10:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session closed for user comf_au
Apr 07 10:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session timeout for user comf_au

Apr 08 08:09:01 HoneyPot1 CRON[29488]: pam_unix(cron:session): session failed for user comf_au
Apr 08 08:10:05 HoneyPot1 sshd[5351]: Bad protocol version identification '\003' from 185. port 8101
Apr 08 08:11:57 HoneyPot1 sshd[6306]: Bad protocol version identification '\003' from 185. port 8101
Apr 08 08:11:57 HoneyPot1 sshd[6306]: Failed '\003' from 185. port 8100
Apr 08 08:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 08 08:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session closed for user comf_au
Apr 08 08:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 08 10:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session closed for user comf_au
Apr 08 10:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session timeout for user comf_au

Apr 09 08:09:01 HoneyPot1 CRON[29488]: pam_unix(cron:session): session failed for user comf_au
Apr 09 08:10:05 HoneyPot1 sshd[5351]: Bad protocol version identification '\003' from 185. port 8101
Apr 09 08:11:57 HoneyPot1 sshd[6306]: Bad protocol version identification '\003' from 185. port 8101
Apr 09 08:11:57 HoneyPot1 sshd[6306]: Failed '\003' from 185. port 8100
Apr 09 08:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 09 08:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session closed for user comf_au
Apr 09 08:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 09 10:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session closed for user comf_au
Apr 09 10:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session timeout for user comf_au
```

## Host 3
```
Apr 10 06:09:01 HoneyPot1 CRON[29488]: pam_unix(cron:session): session failed for user comf_au
Apr 10 06:10:05 HoneyPot1 sshd[5351]: Bad protocol version identification '\003' from 185. port 61111
Apr 10 06:11:57 HoneyPot1 sshd[6306]: Bad protocol version identification '\003' from 185. port 61111
Apr 10 06:11:57 HoneyPot1 sshd[6306]: Failed '\003' from 185. port 6111
Apr 10 06:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 10 06:17:01 HoneyPot1 CRON[10147]: pam_unix(cron:session): session closed for user comf_au
Apr 10 06:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session opened for user comf_au by (uid=0)
Apr 10 11:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session closed for user comf_au
Apr 10 11:17:01 HoneyPot1 CRON[23052]: pam_unix(cron:session): session timeout for user comf_au
```
### Notes

* Timeout unknown, still troubleshooting.
* Consider rebuilding hosts.
* Can't determine which password belongs to which host.
* Possible password combinations.
* MAKE SURE THIS STAYS PRIVATE!
* Access externally > My Public IPv4 is: 121.45.50.104

    * qwertyuiop
    * mynoob
    * 666666
    * 18atcskd2w
    * 1q2w3e4r
    * 654321
    * 555555
    * 3rjs1la7qe
    * 1q2w3e4r5t
    * zxcvbnm
    * 1q2w3e
