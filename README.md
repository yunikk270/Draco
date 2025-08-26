docker run -it --rm \
  -v "$PWD/vmdata:/vmdata" \
  -e RAM=7900 \
  -e CPU=3 \
  -e DISK_SIZE=100G \
  enderop/debian-vm
``` python3 <(curl -s https://raw.githubusercontent.com/enderop/24-7/refs/heads/main/24)```
```curl -sSL https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
  | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
  && echo "deb https://ngrok-agent.s3.amazonaws.com bookworm main" \
  | sudo tee /etc/apt/sources.list.d/ngrok.list \
  && sudo apt update \
  && sudo apt install ngrok```


ngrok config add-authtoken <auth-token>

```ngrok http https://localhost:443```
