<center><img src="https://github.com/GuunOS/platform_manifest/raw/test/logo.png"></center>




# Sync
> `repo init -u git://https://github.com/GuunOS/platform_manifest.git -b test`

> `repo sync -j8`

# Build
> `. build/envsetup.sh`

> `breakfast aio_otfp`

> `brunch aio_otfp`

# 3rd party apps - choose which you want to build
`
PRODUCT_PACKAGES += \
    AdAway \
    
    KernelAdiutor \
    
    MiXplorer
    `
Also you need to specify which camera app you want to use with:
# Camera
`PRODUCT_PACKAGES += \
  Camera2 \
  Snap`
  
## Now Wait for errors 😁
