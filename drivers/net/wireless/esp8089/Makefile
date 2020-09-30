# SPDX-License-Identifier: GPL-2.0-only

EXTRA_CFLAGS += -DP2P_CONCURRENT -DESP_USE_SDIO
#EXTRA_CFLAGS += -DDEBUG -DSIP_DEBUG -DFAST_TX_STATUS \
#				-DKERNEL_IV_WAR -DRX_SENDUP_SYNC \
#				-DSIF_DSR_WAR -DHAS_INIT_DATA -DHAS_FW

esp8089-y := esp_debug.o sdio_sif_esp.o spi_sif_esp.o esp_io.o \
    esp_file.o esp_main.o esp_sip.o esp_ext.o esp_ctrl.o \
    esp_mac80211.o esp_debug.o esp_utils.o esp_pm.o

obj-$(CONFIG_ESP8089) := esp8089.o
