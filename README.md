# ports
FreeBSD ports overlay tree for dirty mods

- `graphics/tiff`: enable WebP & ZSTD
- `graphics/vips`: use snapshot version for TIFF predictor hotfix (ZSTD)

## `/etc/make.conf`

    # checkout overlay
    git clone https://github.com/Adios/ports
    
    # set variable
    echo "OVERLAYS+= `realpath ports`" >> /etc/make.conf

