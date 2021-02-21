
HQ_PROJECT_NAME ?= a2010

$(warning "CONFIG_TABLET_PROJECT:$(CONFIG_TABLET_PROJECT)")
ifeq ($(CONFIG_TABLET_PROJECT),y)
# is tablet project
obj-y				+= tb_kd_camera_hw.o
else
# not tablet project
	ifeq ($(HQ_PROJECT_NAME),a2010)
		obj-y				+= kd_camera_hw_a2010.o
	else
		obj-y				+= kd_camera_hw.o
    endif
endif
