obj-$(CONFIG_USE_DIRECT_IS_CONTROL) += fimc-is-cis.o
obj-$(CONFIG_CAMERA_CIS_5E2_OBJ) += fimc-is-cis-5e2.o
obj-$(CONFIG_CAMERA_CIS_5E3_OBJ) += fimc-is-cis-5e3.o
obj-$(CONFIG_CAMERA_CIS_4H5YC_OBJ) += fimc-is-cis-4h5yc.o
obj-$(CONFIG_CAMERA_CIS_4H5_OBJ) += fimc-is-cis-4h5.o
obj-$(CONFIG_CAMERA_CIS_6B2_OBJ) += fimc-is-cis-6b2.o
obj-$(CONFIG_CAMERA_CIS_2P2_OBJ) += fimc-is-cis-2p2.o
obj-$(CONFIG_CAMERA_CIS_2P8_OBJ) += fimc-is-cis-2p8.o
obj-$(CONFIG_CAMERA_CIS_3P3_OBJ) += fimc-is-cis-3p3.o
obj-$(CONFIG_CAMERA_CIS_3L2_OBJ) += fimc-is-cis-3l2.o
obj-$(CONFIG_CAMERA_CIS_3H1_OBJ) += fimc-is-cis-3h1.o
obj-$(CONFIG_CAMERA_CIS_3H1_C3_OBJ) += fimc-is-cis-3h1.o
obj-$(CONFIG_CAMERA_CIS_4E6_OBJ) += fimc-is-cis-4e6.o
obj-$(CONFIG_CAMERA_CIS_4E6_C2_OBJ) += fimc-is-cis-4e6.o
obj-$(CONFIG_CAMERA_CIS_3M2_OBJ) += fimc-is-cis-3m2.o
obj-$(CONFIG_CAMERA_CIS_3M3_OBJ) += fimc-is-cis-3m3.o
obj-$(CONFIG_CAMERA_CIS_2L1_OBJ) += fimc-is-cis-2l1.o
obj-$(CONFIG_CAMERA_CIS_2L2_OBJ) += fimc-is-cis-2l2.o
obj-$(CONFIG_CAMERA_CIS_IMX260_OBJ) += fimc-is-cis-imx260.o
obj-$(CONFIG_CAMERA_CIS_2L7_OBJ) += fimc-is-cis-2l7.o
obj-$(CONFIG_CAMERA_CIS_IMX320_OBJ) += fimc-is-cis-imx320.o
obj-$(CONFIG_CAMERA_CIS_IMX333_OBJ) += fimc-is-cis-imx333.o

EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2/include
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2/vendor
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2/sensor/module_framework
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2/sensor/
ifeq ($(CONFIG_COMPANION_DIRECT_USE),y)
EXTRA_CFLAGS += -Idrivers/media/platform/exynos/fimc-is2/vendor/mcd/preprocessor
endif