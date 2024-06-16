# chirp-flatpak-uvk5

An unofficial flatpak for the [CHIRP radio programming software](https://chirpmyradio.com/), based on [the work of reesericci](https://git.sr.ht/~reesericci/chirp-flatpak).

> :warning: **Warning** <br>
This version includes the Quansheng UV-K5 driver for [F4HWN Armel's firmware](https://github.com/armel/uv-k5-firmware-custom) directly, no need to enable developper mode and load [uvk5_egzumer_f4hwn_ver_X_Y_Z.py](https://github.com/armel/uv-k5-chirp-driver) at every launch.

> :memo: I am using this flatpak on [Fedora Kinoite](https://fedoraproject.org/atomic-desktops/kinoite/), running flatpak-builder inside a Fedora 40 toolbox.

## How to build

- Clone repo

- Run `flatpak-builder --user --install --force-clean --disable-rofiles-fuse build-dir com.danplanet.chirp.chirp_next.yml`

- Enjoy!
