# Comandos HA Supervisor

### Acessar terminal para comandos HA
```powershell
has
```

### Listar interface de rede
```powershell
ha network info
```

### update interface de rede para DHCP
```powershell
ha network update INTERFACE_NAME --ipv4-method auto --ipv6-method auto
```

### Reniciar instancia HA
```powershell
ha host reboot
```

### Reiniciar Add-on samba
```powershell
ha addons restart core_samba
```
