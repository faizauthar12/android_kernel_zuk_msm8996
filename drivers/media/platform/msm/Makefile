#
# Makefile for the QCOM specific video device drivers
# based on V4L2.
#
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifneq ($(CONFIG_ZUK_CAMERA),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
obj-$(CONFIG_MSM_AIS) += ais/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2z/
endif
obj-y += sde/
