.PHONY: add-android
ionic-add-android: exec				##@ionic Add Android platform
	@echo -n "Add Android platform:"
	@$(eval CMD=$(CMD)"ionic platform add android")
	@echo -e "$(OK_STRING)";

ionic-add-ios: exec				##@ionic Add IOS platform
	@echo -n "Add IOS platform:"
	@$(eval CMD=$(CMD)"ionic platform add ios")
	@echo -e "$(OK_STRING)";

ionic-build-android: exec				##@ionic Build Android
	@echo -n "Build Android:"
	@$(eval CMD=$(CMD)"ionic build android")
	@echo -e "$(OK_STRING)";

ionic-build-ios: exec				##@ionic Build IOS
	@echo -n "Build IOS:"
	@$(eval CMD=$(CMD)"ionic build ios")
	@echo -e "$(OK_STRING)";

ionic-emulate-android:				##@ionic Emulate Android
	@echo -n "Build Android:"
	ionic emulate android
	@echo -e "$(OK_STRING)";

ionic-emulate-ios:				##@ionic Emulate IOS
	@echo -n "Build IOS:"
	ionic emulate ios
	@echo -e "$(OK_STRING)";