####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += system_top.v
M_DEPS += system_project.tcl
M_DEPS += system_bd.tcl
M_DEPS += ../common/ccbox_constr.xdc
M_DEPS += ../common/ccbox_bd.tcl
M_DEPS += ../common/adrv9364z7020_constr_lvds.xdc
M_DEPS += ../common/adrv9364z7020_constr.xdc
M_DEPS += ../common/adrv9364z7020_bd.tcl
M_DEPS += ../../scripts/adi_project.tcl
M_DEPS += ../../scripts/adi_env.tcl
M_DEPS += ../../scripts/adi_board.tcl
M_DEPS += ../../../library/xilinx/common/ad_iobuf.v
M_DEPS += ../../../library/common/ad_adl5904_rst.v
M_DEPS += ../../../library/axi_ad9361/axi_ad9361_delay.tcl
M_DEPS += ../../../library/axi_ad9361/axi_ad9361.xpr
M_DEPS += ../../../library/axi_dmac/axi_dmac.xpr
M_DEPS += ../../../library/axi_i2s_adi/axi_i2s_adi.xpr
M_DEPS += ../../../library/util_clkdiv/util_clkdiv.xpr
M_DEPS += ../../../library/util_cpack/util_cpack.xpr
M_DEPS += ../../../library/util_rfifo/util_rfifo.xpr
M_DEPS += ../../../library/util_tdd_sync/util_tdd_sync.xpr
M_DEPS += ../../../library/util_upack/util_upack.xpr
M_DEPS += ../../../library/util_wfifo/util_wfifo.xpr

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
all: lib adrv9364z7020_ccbox_lvds.sdk/system_top.hdf


clean: 
	rm -rf $(M_FLIST)


clean-all:clean
	$(MAKE) -C ../../../library/axi_ad9361 clean
	$(MAKE) -C ../../../library/axi_dmac clean
	$(MAKE) -C ../../../library/axi_i2s_adi clean
	$(MAKE) -C ../../../library/util_clkdiv clean
	$(MAKE) -C ../../../library/util_cpack clean
	$(MAKE) -C ../../../library/util_rfifo clean
	$(MAKE) -C ../../../library/util_tdd_sync clean
	$(MAKE) -C ../../../library/util_upack clean
	$(MAKE) -C ../../../library/util_wfifo clean


adrv9364z7020_ccbox_lvds.sdk/system_top.hdf: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) system_project.tcl >> adrv9364z7020_ccbox_lvds_vivado.log 2>&1


lib:
	$(MAKE) -C ../../../library/axi_ad9361
	$(MAKE) -C ../../../library/axi_dmac
	$(MAKE) -C ../../../library/axi_i2s_adi
	$(MAKE) -C ../../../library/util_clkdiv
	$(MAKE) -C ../../../library/util_cpack
	$(MAKE) -C ../../../library/util_rfifo
	$(MAKE) -C ../../../library/util_tdd_sync
	$(MAKE) -C ../../../library/util_upack
	$(MAKE) -C ../../../library/util_wfifo

####################################################################################
####################################################################################
