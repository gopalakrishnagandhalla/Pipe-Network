# Pipe-Network
# Dependencies for WINDOWS & LINUX & VPS
```
sudo apt update
sudo apt upgrade -y
```

# Install
```
curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"

```

#
```
chmod +x pop
```
# Make Directory

```
mkdir download_cache
```

# Sign-up With Command

```
./pop --signup-by-referral-route b903c8bfac75ec63
```

# Start The Node

```
sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <KEY>
```
🚩 Note: Put your `ram` , `disk` & `pubkey` with your actual Information.Retrieve the public key from your Solana wallet (e.g., Phantom, Backpack) & Replace in `<KEY>` by Solana Address

🚩**& Also Don't forget to Remove < >**



# Save the file (Very Important)  (Open a different WSL window or Ubuntu for this)

```
nano ~/node_info.json
```
**Ctrl+x to Exit**

# Node Status

```
./pop --status
```

# Check points

```
./pop --points
```

# Generate referral

```
./pop --gen-referral-route
```

# Quick Start

```
./pop
```

Docs- https://docs.pipe.network/devnet-2

Check Points & Status From Dashboard -: https://dashboard.pipenetwork.com/node-lookup

## Need to Free Your 8003 Port

### Identify the Process Using Port 8003
```
sudo ss -tulpn | grep 8003
```

### Terminate the Process by PID
```
sudo kill -9 1234
```

### Kill All Processes Using Port 8003
```
sudo fuser -k 8003/tcp
```

# Thank you for Visiting
- Done !! Feel free to ask queries in telegram channel
- Telegram - https://t.me/CryptoAcademy0616
- Youtube - https://www.youtube.com/@CryptoAcademy_Telugu
- Twitter - https://x.com/CryptoAcademy_O
