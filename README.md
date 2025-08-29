Amnezia 1.5 ipk's files for OpenWRT-24.10.2 Released Mediatek Filogic

Check kernel information befor compilating
by "opkg info kernel" and edit env matrix in "openwrt-awg.yml" file

    strategy:
      matrix:
        tag: ['24.10.2']
        build_env:
          - pkgarch: aarch64_cortex-a53
            target: mediatek
            subtarget: filogic
            vermagic: 2ccac7a75355327cb6dfb4df1ecb575e
