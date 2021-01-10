powerdir = $(libdir)/pm-utils/power.d

power_SCRIPTS =			\
	disable_wol	\
	hal-cd-polling	\
	harddrive		\
	intel-audio-powersave	\
	journal-commit		\
	laptop-mode	\
	pci_devices	\
	pcie_aspm	\
	readahead	\
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
