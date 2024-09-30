# NXMeta
NX Meta Object Detection Project

# Object detection using deep learning with Edge Impulse and NX Meta
Taking an AI video solution to market through Nx AI Manager is straightforward, whether you're selling through Nx EVOS or as an OEM product. From prototyping to full deployment, Nx provides the tools and support you need to build, refine, and commercialize your AI solution. By choosing the right market route and utilizing Nx Connect for licensing and management, you can efficiently scale your solution and succeed in the marketplace. 

## Installation

Clone this repo

1. Perbarui Sistem
Pastikan sistem Ubuntu Anda diperbarui sebelum instalasi.

```
sudo apt update
sudo apt upgrade -y
```

2. Instal Dependensi yang Diperlukan
Pastikan semua dependensi dan pustaka yang diperlukan terinstal.
	
```
sudo apt install -y wget curl lsb-release

```

3. Unduh Paket Nx AI Manager
Unduh paket instalasi Nx AI Manager dari situs resmi Network Optix atau portal unduhan yang disediakan.

```
sudo bash -c "$(wget -q -O - https://artifactory.nxvms.dev/artifactory/nxai_open/NXAIPlugin/install.sh)"

```

## Training

The network can be trained using the `train.py` script. Currently, two dataloaders are available: COCO and CSV. For training on coco, use

```
web.py
```

