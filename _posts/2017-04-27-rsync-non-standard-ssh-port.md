---
title: Rsync with a non-standard ssh port
tags: rsync linux how-to
---

It's so simple:

```bash
rsync -avz -e "ssh -p $portNumber" user@remoteip:/path/to/files/ /local/path/
```
