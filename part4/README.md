Apply the changes using:
```bash
kubectl apply -f < name-of-the-file >.yaml
```
navigate to the host file and update it:
```bash
notepad C:\Windows\System32\drivers\etc\hosts
.\scripts\add-to-hosts.ps1 widgetario.local 127.0.0.1
.\scripts\add-to-hosts.ps1 api.widgetario.local 127.0.0.1
```
for Ubuntu use:
```bash
/etc/hosts
```