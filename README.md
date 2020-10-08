# android-11-changes
Android 11 Changes that are not yet explicitly documented. You should be able to protect against these thrown exceptions by only updating your `targetSdkVersion` after having done extensive testing on the api level you want to update to (i.e. Android 11 / api 30). 

### TelephonyManager
- `TelephonyManager.getNetworkType()` methods now throw a `SecurityException` if `READ_PHONE_STATE` is not granted  
