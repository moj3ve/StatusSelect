include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = StatusSelect
StatusSelect_FILES = CSSSPreferencesController.m
StatusSelect_INSTALL_PATH = /Library/PreferenceBundles
StatusSelect_FRAMEWORKS = UIKit
StatusSelect_PRIVATE_FRAMEWORKS = Preferences
StatusSelect_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/StatusSelect.plist$(ECHO_END)
