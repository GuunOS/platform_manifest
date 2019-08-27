> repo init -u https://github.com/guuntest/platform_manifest.git -b test

> repo sync

. build/envsetup.sh

breakfast aio_otfp

brunch aio_otfp

# 3rd party apps - choose which you want to build
PRODUCT_PACKAGES += \
    AdAway \
    KernelAdiutor \
    MiXplorer