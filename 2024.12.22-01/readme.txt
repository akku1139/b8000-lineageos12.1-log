- waiting for device -
--------- beginning of main
I/lowmemorykiller(  120): Using in-kernel low memory killer interface
I/auditd  (  117): type=1403 audit(0.0:2): policy loaded auid=4294967295 ses=4294967295
W/init    (    1): type=1400 audit(0.0:3): avc: denied { sys_module } for capability=16 scontext=u:r:init:s0 tcontext=u:r:init:s0 tclass=capability
I/cm      (  137): ____ _   _ ____ _  _ ____ ____ ____ _  _ _  _ ____ ___
I/cm      (  139): |     \_/  |__| |\ | |  | | __ |___ |\ | |\/| |  | |  \
I/cm      (  143): |___   |   |  | | \| |__| |__] |___ | \| |  | |__| |__/
--------- beginning of system
I/Vold    (  122): Vold 2.1 (the revenge) firing up
D/Vold    (  122): Volume sdcard0 state changing -1 (Initializing) -> 0 (No-Media)
D/Vold    (  122): Volume sdcard1 state changing -1 (Initializing) -> 0 (No-Media)
D/Vold    (  122): Volume usbdisk0 state changing -1 (Initializing) -> 0 (No-Media)
I/Cryptfs (  122): Check if PFE is activated on Boot
E/Cryptfs (  122): Unexpected value for crypto key location
E/Cryptfs (  122): Error getting crypt footer and key
W/DirectVolume(  122): Deprecated implied prefix pattern detected, please use '/devices/platform/mtk-msdc.0/mmc_host*' instead
D/Vold    (  122): Volume sdcard0 state changing 0 (No-Media) -> 1 (Idle-Unmounted)
W/Vold    (  122): Duplicate state (1)
D/Vold    (  122): Volume sdcard0 state changing 1 (Idle-Unmounted) -> 2 (Pending)
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 1, PARTN 1
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 2, PARTN 2
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 3, PARTN 3
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 4, PARTN 4
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 5, PARTN 5
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 6, PARTN 6
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 7, PARTN 7
D/DirectVolume(  122): DirectVolume::handlePartitionAdded -> MAJOR 179, MINOR 8, PARTN 8
D/Vold    (  122): Volume sdcard0 state changing 2 (Pending) -> 1 (Idle-Unmounted)
W/Vold    (  122): Duplicate state (1)
W/Vold    (  122): Duplicate state (1)
I/cm      (  148): Welcome to Android 5.1.1 / CyanogenMod-12.1-20200516-UNOFFICIAL-me173x
I/SurfaceFlinger(  123): SurfaceFlinger is starting
I/SurfaceFlinger(  123): SurfaceFlinger's main thread ready to run. Initializing graphics H/W...
W/linker  (  123): libEGL_mtk.so: unused DT entry: type 0xf arg 0x543
W/linker  (  123): libIMGegl.so: unused DT entry: type 0xf arg 0x7d4
W/linker  (  123): libsrv_um.so: unused DT entry: type 0xf arg 0xc66
D/libEGL  (  123): loaded /vendor/lib/egl/libEGL_mtk.so
W/linker  (  123): libGLESv1_CM_mtk.so: unused DT entry: type 0xf arg 0xc3e
W/linker  (  123): libusc.so: unused DT entry: type 0xf arg 0x1d9
W/linker  (  123): libGLESv2_mtk.so: unused DT entry: type 0xf arg 0xd96
W/linker  (  123): libGLESv1_CM_mtk.so: unused DT entry: type 0xf arg 0xc3e
W/linker  (  123): libusc.so: unused DT entry: type 0xf arg 0x1d9
D/libEGL  (  123): loaded /vendor/lib/egl/libGLESv1_CM_mtk.so
W/linker  (  123): libGLESv2_mtk.so: unused DT entry: type 0xf arg 0xd96
D/libEGL  (  123): loaded /vendor/lib/egl/libGLESv2_mtk.so
W/linker  (  123): libpvrANDROID_WSEGL.so: unused DT entry: type 0xf arg 0x119
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: Couldn't connect to services
W/libEGL  (  123): eglInitialize(0x1) failed (EGL_BAD_ALLOC)
W/linker  (  123): gralloc.mt6589.so: unused DT entry: type 0xf arg 0x559
W/linker  (  123): libpvr2d.so: unused DT entry: type 0xf arg 0x75c
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: OpenPVRServices: Failed to open services connection (0) : 4
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: OpenPVRServices: Failed to open services connection (20) : 4
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086860 (Bad address).
E/IMGSRV  (  123): :0: OpenServices: PVRSRVBridgeCall failed.
E/IMGSRV  (  123): :0: PVRSRVConnect: Unable to open connection.
