####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += system_top.v
M_DEPS += system_project.tcl
M_DEPS += system_constr.xdc
M_DEPS += system_bd.tcl
M_DEPS += ../common/m2k_spi.v
M_DEPS += ../common/m2k_bd.tcl
M_DEPS += ../../scripts/adi_project.tcl
M_DEPS += ../../scripts/adi_env.tcl
M_DEPS += ../../scripts/adi_board.tcl
M_DEPS += ../../../library/xilinx/common/ad_iobuf.v
M_DEPS += ../../../library/axi_ad9963/axi_ad9963.xpr
M_DEPS += ../../../library/axi_adc_decimate/axi_adc_decimate.xpr
M_DEPS += ../../../library/axi_adc_trigger/axi_adc_trigger.xpr
M_DEPS += ../../../library/axi_dac_interpolate/axi_dac_interpolate.xpr
M_DEPS += ../../../library/axi_dmac/axi_dmac.xpr
M_DEPS += ../../../library/axi_logic_analyzer/axi_logic_analyzer.xpr
M_DEPS += ../../../library/axi_rd_wr_combiner/axi_rd_wr_combiner.xpr
M_DEPS += ../../../library/util_extract/util_extract.xpr
M_DEPS += ../../../library/util_var_fifo/util_var_fifo.xpr

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += *.runs
M_FLIST += *.srcs
M_FLIST += *.sdk
M_FLIST += *.hw
M_FLIST += *.sim
M_FLIST += .Xil
M_FLIST += *.ip_user_files



.PHONY: all lib clean clean-all
all: lib m2k.sdk/system_top.hdf


clean: 
	rm -rf $(M_FLIST)


clean-all:clean
	$(MAKE) -C ../../../library/axi_ad9963 clean
	$(MAKE) -C ../../../library/axi_adc_decimate clean
	$(MAKE) -C ../../../library/axi_adc_trigger clean
	$(MAKE) -C ../../../library/axi_dac_interpolate clean
	$(MAKE) -C ../../../library/axi_dmac clean
	$(MAKE) -C ../../../library/axi_logic_analyzer clean
	$(MAKE) -C ../../../library/axi_rd_wr_combiner clean
	$(MAKE) -C ../../../library/util_extract clean
	$(MAKE) -C ../../../library/util_var_fifo clean


m2k.sdk/system_top.hdf: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) system_project.tcl >> m2k_vivado.log 2>&1


lib:
	$(MAKE) -C ../../../library/axi_ad9963
	$(MAKE) -C ../../../library/axi_adc_decimate
	$(MAKE) -C ../../../library/axi_adc_trigger
	$(MAKE) -C ../../../library/axi_dac_interpolate
	$(MAKE) -C ../../../library/axi_dmac
	$(MAKE) -C ../../../library/axi_logic_analyzer
	$(MAKE) -C ../../../library/axi_rd_wr_combiner
	$(MAKE) -C ../../../library/util_extract
	$(MAKE) -C ../../../library/util_var_fifo

####################################################################################
####################################################################################
