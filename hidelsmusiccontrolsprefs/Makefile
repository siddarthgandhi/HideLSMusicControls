include theos/makefiles/common.mk

BUNDLE_NAME = HideLSMusicControlsPrefs
HideLSMusicControlsPrefs_FILES = HideLSMusicControlsPrefs.mm
HideLSMusicControlsPrefs_INSTALL_PATH = /Library/PreferenceBundles
HideLSMusicControlsPrefs_FRAMEWORKS = UIKit
HideLSMusicControlsPrefs_PRIVATE_FRAMEWORKS = Preferences

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/HideLSMusicControlsPrefs.plist$(ECHO_END)
