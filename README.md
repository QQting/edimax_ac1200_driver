# EDIMAX AC1200 Linux Driver

## Prepare required packages

```bash
sudo apt install -y build-essential dkms git 
```

## Download driver source codes
```bash
mkdir -p ~/edimax_ac1200_driver/src
cd ~/edimax_ac1200_driver/src
git clone https://github.com/morrownr/88x2bu-20210702.git
```

## Build & Install driver
```bash
cd ~/edimax_ac1200_driver/src/88x2bu-20210702
sudo ./install-driver.sh
```

## Remove driver
```bash
sudo ./remove-driver.sh
```

## Reboot
```bash
sudo reboot
```
