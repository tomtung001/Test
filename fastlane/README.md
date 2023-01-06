fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios script_version

```sh
[bundle exec] fastlane ios script_version
```



### ios build_ipa

```sh
[bundle exec] fastlane ios build_ipa
```



### ios deleteCert

```sh
[bundle exec] fastlane ios deleteCert
```



### ios all

```sh
[bundle exec] fastlane ios all
```



### ios first_upload

```sh
[bundle exec] fastlane ios first_upload
```



### ios first_submit

```sh
[bundle exec] fastlane ios first_submit
```



### ios update_info

```sh
[bundle exec] fastlane ios update_info
```



### ios connectAppStoreWithAPIKey

```sh
[bundle exec] fastlane ios connectAppStoreWithAPIKey
```



### ios createCert

```sh
[bundle exec] fastlane ios createCert
```



### ios arch

```sh
[bundle exec] fastlane ios arch
```

Build and archive APP

### ios upload_testflight

```sh
[bundle exec] fastlane ios upload_testflight
```

upload to testflight

### ios submit_review

```sh
[bundle exec] fastlane ios submit_review
```

上傳ipa，更新送審資料，送審一氣呵成

### ios submit_pure

```sh
[bundle exec] fastlane ios submit_pure
```

上傳ipa，不更新送審資料，送審一氣呵成

### ios Update_Submit

```sh
[bundle exec] fastlane ios Update_Submit
```

上傳送審資料兼送審

### ios submit_cancel

```sh
[bundle exec] fastlane ios submit_cancel
```

取消送審

### ios submit_only

```sh
[bundle exec] fastlane ios submit_only
```

只送審

### ios send_privacy

```sh
[bundle exec] fastlane ios send_privacy
```

發布privacy

### ios ac

```sh
[bundle exec] fastlane ios ac
```

用 adHoc 打包上傳 AppCenter

### ios arch_adhoc

```sh
[bundle exec] fastlane ios arch_adhoc
```

打包 adhoc 的 ipa

### ios upload_appcenter

```sh
[bundle exec] fastlane ios upload_appcenter
```

Upload ipa and dsym to AppCenter

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
