<manifest versionCode="1" versionName="1.2" compileSdkVersion="29" compileSdkVersionCodename="10" package="com.kissgame.release" platformBuildVersionCode="29" platformBuildVersionName="10">
<uses-sdk minSdkVersion="19" targetSdkVersion="29"/>
<uses-permission name="android.permission.INTERNET"/>
<uses-permission name="android.permission.CHANGE_NETWORK_STATE"/>
<uses-permission name="android.permission.CHANGE_WIFI_STATE"/>
<uses-permission name="android.permission.ACCESS_NETWORK_STATE"/>
<uses-permission name="android.permission.ACCESS_WIFI_STATE"/>
<uses-permission name="android.permission.VIBRATE"/>
<uses-permission name="android.permission.READ_PHONE_STATE"/>
<uses-permission name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS"/>
<uses-permission name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission name="android.permission.ACCESS_FINE_LOCATION"/>
<uses-permission name="android.permission.ACCESS_COARSE_LOCATION"/>
<uses-permission name="android.permission.CONTROL_LOCATION_UPDATES"/>
<uses-permission name="android.permission.DELETE_CACHE_FILES"/>
<uses-permission name="android.permission.DELETE_PACKAGES"/>
<uses-permission name="android.permission.DUMP"/>
<uses-permission name="android.permission.EXPAND_STATUS_BAR"/>
<uses-permission name="android.permission.GET_PACKAGE_SIZE"/>
<uses-permission name="android.permission.GET_TASKS"/>
<uses-permission name="android.permission.INSTALL_PACKAGES"/>
<uses-permission name="android.permission.KILL_BACKGROUND_PROCESSES"/>
<uses-permission name="android.permission.NFC"/>
<uses-permission name="android.permission.READ_CONTACTS"/>
<uses-permission name="android.permission.READ_FRAME_BUFFER"/>
<uses-permission name="android.permission.SEND_SMS"/>
<uses-permission name="android.permission.STATUS_BAR"/>
<uses-permission name="android.permission.SUBSCRIBED_FEEDS_READ"/>
<uses-permission name="android.permission.SUBSCRIBED_FEEDS_WRITE"/>
<uses-permission name="android.permission.WRITE_SMS"/>
<uses-permission name="android.permission.BATTERY_STATS"/>
<uses-permission name="android.permission.BROADCAST_WAP_PUSH"/>
<uses-permission name="android.permission.BROADCAST_STICKY"/>
<uses-permission name="android.permission.CAMERA"/>
<uses-permission name="android.permission.DOWNLOAD_WITHOUT_NOTIFICATION"/>
<uses-permission name="android.permission.READ_LOGS"/>
<uses-permission name="android.permission.REORDER_TASKS"/>
<uses-permission name="android.permission.READ_SMS"/>
<uses-permission name="android.permission.READ_PHONE_NUMBERS"/>
<uses-permission name="android.permission.READ_PRIVILEGED_PHONE_STATE"/>
<application theme="AppTheme" label="918Kiss" icon="res/drawable-xhdpi-v4/icon.png" name="org.cocos2dx.lua.MyApplication" allowBackup="true" supportsRtl="true" usesCleartextTraffic="true" appComponentFactory="androidx.core.app.CoreComponentFactory">
<meta-data name="android.app.lib_name" value="cocos2dlua"/>
<meta-data name="android.max_aspect" value="2.1"/>
<activity theme="Theme.NoTitleBar.Fullscreen" label="918Kiss" name="org.cocos2dx.lua.AppActivity" screenOrientation="0" configChanges="0x80">
<intent-filter>
<action name="android.intent.action.MAIN"/>
<category name="android.intent.category.LAUNCHER"/>
</intent-filter>
<intent-filter>
<action name="android.intent.action.VIEW"/>
<category name="android.intent.category.DEFAULT"/>
<category name="android.intent.category.BROWSABLE"/>
<data scheme="lobbykiss" host="lobbykiss"/>
</intent-filter>
</activity>
<activity theme="Theme.NoTitleBar.Fullscreen" label="CrashHandler" name="org.cocos2dx.lua.CrashHandlerActivity" screenOrientation="0" configChanges="0x80"/>
</application>
</manifest>
