GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
EXTRA_CFLAGS += -Idrivers/media/video/msm_legacy
EXTRA_CFLAGS += -Idrivers/media/video/msm_legacy/io
EXTRA_CFLAGS += -Idrivers/media/video/msm_legacy/eeprom
EXTRA_CFLAGS += -Idrivers/media/video/msm_legacy/csi
obj-$(CONFIG_MSM_CAMERA_SENSOR) += msm_sensor.o
obj-$(CONFIG_SONY_CAM_MAIN_V4L2) += sony_sensor_main_v4l2.o
obj-$(CONFIG_SONY_CAM_SUB_V4L2) += sony_sensor_sub_v4l2.o
obj-$(CONFIG_OV7692) += ov7692_v4l2.o
