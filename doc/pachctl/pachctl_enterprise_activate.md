## pachctl enterprise activate

Activate the enterprise features of Pachyderm with an activation code

### Synopsis


Activate the enterprise features of Pachyderm with an activation code

```
pachctl enterprise activate <activation-code>
```

### Options

```
      --expires string   A timestamp indicating when the token provided above should expire (formatted as an RFC 3339/ISO 8601 datetime). This is only applied if it's earlier than the signed expiration time encoded in 'activation-code', and therefore is only useful for testing.
```

### Options inherited from parent commands

```
      --no-metrics           Don't report user metrics for this command
      --no-port-forwarding   Disable implicit port forwarding
  -v, --verbose              Output verbose logs
```

