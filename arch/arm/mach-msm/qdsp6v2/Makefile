obj-y += rtac.o

ifdef CONFIG_ARCH_MSM8X60
obj-y += audio_dev_ctl.o
ifdef CONFIG_USA_MODEL_SGH_I717
obj-y += board-msm8x60-audio-Q1.o
else ifdef CONFIG_USA_MODEL_SGH_I577
obj-y += board-msm8x60-audio_a2.o
else ifdef CONFIG_USA_MODEL_SGH_T769
obj-y += board-msm8x60-audio-APEX40.o
else ifdef CONFIG_USA_MODEL_SGH_I757
obj-y += board-msm8x60-audio-CELOXHD.o
else ifdef CONFIG_EUR_MODEL_GT_P7320
obj-y += board-msm8x60-audio-P5LTE.o
else ifdef CONFIG_USA_MODEL_SGH_I957
obj-y += board-msm8x60-audio-P5LTE_ATT.o
else ifdef CONFIG_KOR_MODEL_SHV_E140S
obj-y += board-msm8x60-audio-P5LTE.o
else ifdef CONFIG_KOR_MODEL_SHV_E140K
obj-y += board-msm8x60-audio-P5LTE.o
else ifdef CONFIG_KOR_MODEL_SHV_E140L
obj-y += board-msm8x60-audio-P5LTE.o
else ifdef CONFIG_KOR_MODEL_SHV_E150S
obj-y += board-msm8x60-audio-P8LTE.o
else ifdef CONFIG_JPN_MODEL_SC_01E
obj-y += board-msm8x60-audio-P8LTE.o
else ifdef CONFIG_JPN_MODEL_SC_01D
obj-y += board-msm8x60-audio-P5LTE_ATT.o
else
obj-y += board-msm8x60-audio.o
endif
obj-$(CONFIG_TIMPANI_CODEC) += snddev_icodec.o
obj-y += snddev_ecodec.o snddev_mi2s.o snddev_virtual.o
obj-y += pcm_out.o pcm_in.o fm.o
obj-y += audio_lpa.o
obj-y += q6voice.o
obj-y += snddev_hdmi.o
obj-y += audio_mvs.o
obj-$(CONFIG_FB_MSM_HDMI_MSM_PANEL) += lpa_if_hdmi.o
endif
obj-$(CONFIG_MSM_QDSP6_APR) += apr.o apr_tal.o q6core.o dsp_debug.o
obj-y += audio_acdb.o
obj-y += aac_in.o qcelp_in.o evrc_in.o amrnb_in.o audio_utils.o
obj-y += audio_wma.o audio_wmapro.o audio_aac.o audio_multi_aac.o audio_utils_aio.o
obj-$(CONFIG_MSM_ULTRASOUND) += ultrasound/
obj-y += audio_mp3.o audio_amrnb.o audio_amrwb.o audio_evrc.o audio_qcelp.o amrwb_in.o
