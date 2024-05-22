
# Commands

### Config

```bash
nixos-rebuild switch
```

### Packages

**Install**

```bash
nix-env -i <package>
```

**Uninstall**

```bash
nix-env -e <package>
```

**List**

```bash
nix-env -q
```

### Search

```bash
nix-env -qaP <package>
```

### Update

```bash
nix-channel --update
```

### Upgrade

```bash
nixos-rebuild switch --upgrade
```

### Rollback

```bash
nixos-rebuild switch --rollback
```