# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos3830.dtb

dtbo-y += samsung/a13/exynos850-a13_eur_open_00.dtbo
dtbo-y += samsung/a13/exynos850-a13_eur_open_rev02b.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
