# satellite-party
Anecdotes working with Red Hat Satellite and RHSM

## 

You will find scripts (Python, bash), API/hammer examples, for Red Hat Satellite and Red Hat Subscription Manager (RHSM)

```
$ subscription-manager identity   ## Get the ORG ID for the next command
$ curl -k -u <red hat user> --cert /etc/pki/consumer/cert.pem --key /etc/pki/consumer/key.pem https://subscription.rhsm.redhat.com/subscription/owners/5318211/consumers?include=name
```
