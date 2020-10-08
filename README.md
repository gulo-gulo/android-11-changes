# android-11-changes
Android 11 Changes that are not explicitly documented

### TelephonyManager
- `TelephonyManager.getNetworkType()` methods now throw a `SecurityException` if `READ_PHONE_STATE` is not granted  
