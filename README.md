# gradle
Collection of some useful gradle build scripts

- For deploy tasks in `release.gradle` and `nightly.gradle` you must use `apks.gradle`.


# `apks.gradle` config:
```
# optional, defaults to project dirname
apkName=MyApkName

# optional, default=apks
apkFolder=apks
```

# `versioning.gradle` and `release.gradle` config
```
version=1.1.1-SNAPSHOT
```

# Optional for `release.gradle` and `nightly.gradle`
```
ftpServer=xyz.ftp.com
ftpUser=superFtpUser
ftpPassword=Secret!

# release only
ftpDir=/upload/myapp

# nightly only
ftpNightlyDir=/upload/nightly/myapp
```
