obj-$(CONFIG_OPPO_COMMON_SOFT)	+=  device_info/
obj-$(CONFIG_OPPO_DEVICE_IFNO)	+=  project_info/
obj-$(CONFIG_RECORD_MDMRST)	+=  mdmrst/
obj-$(CONFIG_OPPO_HYPNUS)     +=  oppo_hypnus/
obj-$(CONFIG_OPPO_SHUTDOWN_DETECT)	+=  oppo_shutdown_detect/
#xjun@ODM_LQ@BSP.Bringup,2020/05/27,modified for sensor folder build -start
ifeq ($(CONFIG_MSM_206B1),y)
obj-y += sensor/
else
obj-y +=  oppo_als_cali_value/
endif
#xjun@ODM_LQ@BSP.Bringup,2020/05/27,modified for sensor folder build -end
obj-y +=  oppo_criticallog/
