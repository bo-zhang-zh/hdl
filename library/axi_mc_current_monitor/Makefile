####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += ../common/ad_rst.v
M_DEPS += ../common/up_adc_channel.v
M_DEPS += ../common/up_adc_common.v
M_DEPS += ../common/up_axi.v
M_DEPS += ../common/up_clock_mon.v
M_DEPS += ../common/up_delay_cntrl.v
M_DEPS += ../common/up_xfer_cntrl.v
M_DEPS += ../common/up_xfer_status.v
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += ad7401.v
M_DEPS += axi_mc_current_monitor.v
M_DEPS += axi_mc_current_monitor_constr.xdc
M_DEPS += axi_mc_current_monitor_ip.tcl
M_DEPS += dec256sinc24b.v

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += component.xml
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += *.ip_user_files
M_FLIST += *.srcs
M_FLIST += *.hw
M_FLIST += *.sim
M_FLIST += .Xil



.PHONY: all clean clean-all
all: axi_mc_current_monitor.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


axi_mc_current_monitor.xpr: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) axi_mc_current_monitor_ip.tcl  >> axi_mc_current_monitor_ip.log 2>&1

####################################################################################
####################################################################################
