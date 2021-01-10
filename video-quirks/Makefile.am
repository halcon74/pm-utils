quirksdir = $(libdir)/pm-utils/video-quirks

quirks_SCRIPTS =			\
	20-video-quirk-pm-acer.quirkdb	\
	20-video-quirk-pm-dell.quirkdb		\
	20-video-quirk-pm-ibm.quirkdb		\
	20-video-quirk-pm-samsung.quirkdb	\
	20-video-quirk-pm-apple.quirkdb	\
	20-video-quirk-pm-fujitsu.quirkdb	\
	20-video-quirk-pm-lenovo.quirkdb	\
	20-video-quirk-pm-sony.quirkdb	\
	20-video-quirk-pm-asus.quirkdb	\
	20-video-quirk-pm-hp.quirkdb		\
	20-video-quirk-pm-misc.quirkdb	\
	20-video-quirk-pm-toshiba.quirkdb	\

EXTRA_DIST=$(quirks_SCRIPTS)

install-exec-local:
	-mkdir -p $(DESTDIR)$(sysconfdir)/video-quirks

clean-local :
	rm -f *~
