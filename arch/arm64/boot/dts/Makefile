# SPDX-License-Identifier: GPL-2.0

subdir-y += exynos
subdir-y += samsung

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
