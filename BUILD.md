
# Steps

1. Clone this repo (to $SRC, for example)
2. cd `mkdir nerves_build`
3. `git clone https://github.com/nerves-project/nerves_system_br.git`
4. `./nerves_system_br/create-build.sh ../adsb-nerves-rpi3/nerves_defconfig adsb_nerves_rpi3_out`
5. `cd adsb_nerves_rpi3_out`
6. `make` (for about 30 minutes)
7. `make system` (to package it up)

# References

https://hexdocs.pm/nerves/0.4.0/systems.html
https://hexdocs.pm/nerves/customizing-systems.html
