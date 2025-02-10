- waiting for device -
--------- beginning of main
I/lowmemorykiller(  120): Using in-kernel low memory killer interface
I/auditd  (  117): type=1403 audit(0.0:2): policy loaded auid=4294967295 ses=4294967295
W/init    (    1): type=1400 audit(0.0:3): avc: denied { sys_module } for capability=16 scontext=u:r:init:s0 tcontext=u:r:init:s0 tclass=capability
W/init    (  104): type=1400 audit(0.0:4): avc: denied { execute } for name="pvrsrvctl" dev="mmcblk0p6" ino=30302 scontext=u:r:init:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
W/init    (  104): type=1400 audit(0.0:5): avc: denied { execute_no_trans } for path="/system/vendor/bin/pvrsrvctl" dev="mmcblk0p6" ino=30302 scontext=u:r:init:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
W/sysinit (  115): type=1400 audit(0.0:6): avc: denied { search } for name="vendor" dev="mmcblk0p6" ino=30273 scontext=u:r:sysinit:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/lmkd    (  120): type=1400 audit(0.0:7): avc: denied { search } for name="vendor" dev="mmcblk0p6" ino=30273 scontext=u:r:lmkd:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/logd    (  117): type=1400 audit(0.0:8): avc: denied { search } for name="vendor" dev="mmcblk0p6" ino=30273 scontext=u:r:logd:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/servicemanager(  121): type=1400 audit(0.0:9): avc: denied { search } for name="vendor" dev="mmcblk0p6" ino=30273 scontext=u:r:servicemanager:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/surfaceflinger(  123): type=1400 audit(0.0:10): avc: denied { search } for name="vendor" dev="mmcblk0p6" ino=30273 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/logd    (  117): type=1400 audit(0.0:12): avc: denied { read } for name="tzdata" dev="mmcblk0p6" ino=45482 scontext=u:r:logd:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
W/logd    (  117): type=1400 audit(0.0:13): avc: denied { open } for name="tzdata" dev="mmcblk0p6" ino=45482 scontext=u:r:logd:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
I/cm      (  131): ____ _   _ ____ _  _ ____ ____ ____ _  _ _  _ ____ ___
--------- beginning of system
I/Vold    (  122): Vold 2.1 (the revenge) firing up
D/Vold    (  122): Volume sdcard0 state changing -1 (Initializing) -> 0 (No-Media)
D/Vold    (  122): Volume sdcard1 state changing -1 (Initializing) -> 0 (No-Media)
D/Vold    (  122): Volume usbdisk0 state changing -1 (Initializing) -> 0 (No-Media)
I/Cryptfs (  122): Check if PFE is activated on Boot
E/Cryptfs (  122): Unexpected value for crypto key location
E/Cryptfs (  122): Error getting crypt footer and key
W/surfaceflinger(  123): type=1400 audit(0.0:14): avc: denied { read } for name="egl" dev="mmcblk0p6" ino=30289 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/surfaceflinger(  123): type=1400 audit(0.0:15): avc: denied { open } for name="egl" dev="mmcblk0p6" ino=30289 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=dir
W/surfaceflinger(  123): type=1400 audit(0.0:16): avc: denied { read } for name="libEGL_mtk.so" dev="mmcblk0p6" ino=30290 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
W/surfaceflinger(  123): type=1400 audit(0.0:17): avc: denied { open } for name="libEGL_mtk.so" dev="mmcblk0p6" ino=30290 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
W/surfaceflinger(  123): type=1400 audit(0.0:18): avc: denied { getattr } for path="/system/vendor/lib/egl/libEGL_mtk.so" dev="mmcblk0p6" ino=30290 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
W/surfaceflinger(  123): type=1400 audit(0.0:19): avc: denied { execute } for path="/system/vendor/lib/egl/libEGL_mtk.so" dev="mmcblk0p6" ino=30290 scontext=u:r:surfaceflinger:s0 tcontext=u:object_r:unlabeled:s0 tclass=file
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
I/cm      (  142): |     \_/  |__| |\ | |  | | __ |___ |\ | |\/| |  | |  \
I/SurfaceFlinger(  123): SurfaceFlinger is starting
I/SurfaceFlinger(  123): SurfaceFlinger's main thread ready to run. Initializing graphics H/W...
W/linker  (  123): libEGL_mtk.so: unused DT entry: type 0xf arg 0x5a4
I/cm      (  144): |___   |   |  | | \| |__| |__] |___ | \| |  | |__| |__/
W/linker  (  123): libIMGegl.so: unused DT entry: type 0xf arg 0x8d2
W/linker  (  123): libsrv_um.so: unused DT entry: type 0xf arg 0x17be
D/libEGL  (  123): loaded /vendor/lib/egl/libEGL_mtk.so
W/linker  (  123): libGLESv1_CM_mtk.so: unused DT entry: type 0xf arg 0xeec
W/linker  (  123): libusc.so: unused DT entry: type 0xf arg 0x22d
I/cm      (  151): Welcome to Android 5.1.1 / CyanogenMod-12.1-20200516-UNOFFICIAL-me173x
W/linker  (  123): libGLESv2_mtk.so: unused DT entry: type 0xf arg 0x103d
W/linker  (  123): libGLESv1_CM_mtk.so: unused DT entry: type 0xf arg 0xeec
W/linker  (  123): libusc.so: unused DT entry: type 0xf arg 0x22d
D/libEGL  (  123): loaded /vendor/lib/egl/libGLESv1_CM_mtk.so
W/linker  (  123): libGLESv2_mtk.so: unused DT entry: type 0xf arg 0x103d
D/libEGL  (  123): loaded /vendor/lib/egl/libGLESv2_mtk.so
W/linker  (  123): libpvrANDROID_WSEGL.so: unused DT entry: type 0xf arg 0x185
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
D/IMGSRV  (  123): PVRSRVEnumerateDevices:561: retry=0/10
E/IMGSRV  (  123): :0: PVRSRVEnumerateDevices: BridgeCall failed
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
D/IMGSRV  (  123): PVRSRVEnumerateDevices:561: retry=0/10
E/IMGSRV  (  123): :0: PVRSRVEnumerateDevices: BridgeCall failed
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
D/IMGSRV  (  123): PVRSRVEnumerateDevices:561: retry=0/10
E/IMGSRV  (  123): :0: PVRSRVEnumerateDevices: BridgeCall failed
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
D/IMGSRV  (  123): PVRSRVEnumerateDevices:561: retry=0/10
E/IMGSRV  (  123): :0: PVRSRVEnumerateDevices: BridgeCall failed
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
D/IMGSRV  (  123): PVRSRVEnumerateDevices:561: retry=0/10
E/IMGSRV  (  123): :0: PVRSRVEnumerateDevices: BridgeCall failed
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
E/IMGSRV  (  123): :0: PVRSRVBridgeCall: Failed to access device.  Function ID:3223086849 (ret=-1, 14:strerror returns no value.).
