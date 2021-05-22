# JetsonNANO-Setup-camera

```
sudo cp camera_overrides.isp /var/nvidia/nvcam/settings/
sudo chmod 664 /var/nvidia/nvcam/settings/camera_overrides.isp
sudo chown root:root /var/nvidia/nvcam/settings/camera_overrides.isp
```

`gst-launch-1.0 nvarguscamerasrc sensor_id=0 ! nvoverlaysink`
