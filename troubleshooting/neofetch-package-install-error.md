# Neofetch Package Installation Error

## Objective
Install the `neofetch` package on Ubuntu Linux using the APT package manager.

---

## Command Attempted

```bash
sudo apt install neofetch
```

---

## Error Encountered

```text
E: Unable to locate package neofetch
```

---

## Troubleshooting Steps

### 1. Updated Package Lists

```bash
sudo apt update
```

Result:
- Package lists updated successfully.

---

### 2. Searched Available Packages

```bash
apt search neofetch
```

Result:
- `fastfetch` was available instead of `neofetch`.

---

## Resolution

Installed `fastfetch` instead.

```bash
sudo apt install fastfetch
```

Verified successful installation by running:

```bash
fastfetch
```

---

## Skills Learned

- Linux package management
- Using APT repositories
- Package searching
- Basic Linux troubleshooting
- Software installation workflow
