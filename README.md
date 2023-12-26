# comfyui-provisions
basic provision script to install

# running under RunPod:
docker image: 
```
ghcr.io/ai-dock/comfyui:latest
```

environments:
```
COMFYUI_PORT="3000"
COMFYUI_FLAGS="--gpu-only --highvram"
PROVISIONING_SCRIPT="<provision script url>"
```

## Provision scripts:

### 1. ComfyUI + Manager + AnimateDiff + ControlNet + Models
https://raw.githubusercontent.com/denisix/comfyui-provisions/main/provision-manager-animatediff-controlnet-models.sh
