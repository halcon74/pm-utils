powerdir = $(libdir)/pm-utils/power.d

power_SCRIPTS =			\
	disable_wol	\
	harddrive		\
	intel-audio-powersave	\
	laptop-mode	\
	pci_devices	\
	pcie_aspm	\
	sata_alpm	\
	sched-powersave	\
	usb_bluetooth	\
	wireless 		\
	xfs_buffer	


EXTRA_DIST=$(power_SCRIPTS)

install-exec-local:
	-mkdir -p $(DESTDIR)$(sysconfdir)/pm/power.d

clean-local :
	rm -f *~
