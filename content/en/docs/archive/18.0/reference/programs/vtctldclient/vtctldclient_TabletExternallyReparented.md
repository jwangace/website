---
title: TabletExternallyReparented
series: vtctldclient
commit: d3ff5982ddbbb04da1c9ac3c0bff9b09c904c749
---
## vtctldclient TabletExternallyReparented

Updates the topology record for the tablet's shard to acknowledge that an external tool made this tablet the primary.

### Synopsis

Updates the topology record for the tablet's shard to acknowledge that an external tool made this tablet the primary.

See the Reparenting guide for more information: https://vitess.io/docs/user-guides/configuration-advanced/reparenting/#external-reparenting.


```
vtctldclient TabletExternallyReparented <alias>
```

### Options

```
  -h, --help   help for TabletExternallyReparented
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.
