#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

obj-$(CONFIG_MTK_LEDS) := mtk_leds.o
obj-$(CONFIG_KTD3136_SUPPORT) += ktd3136_bl.o

obj-$(CONFIG_LM3697_SUPPORT) += ti-lmu-backlight-core.o
obj-$(CONFIG_LM3697_SUPPORT) += ti-lmu-backlight-data.o

ccflags-y += -I$(srctree)/drivers/misc/mediatek/video/include
