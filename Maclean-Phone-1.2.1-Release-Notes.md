# Maclean Phone 1.2.1

## New color and text-window settings

- Added an app-wide **Letter and word color** setting.
- Added black, white, Maclean green, dress blue, tartan red, heritage gold,
  and silver palette choices.
- Added a custom hexadecimal field for manually choosing any letter and word
  color.
- Added **Automatic** text color so the app can continue following its light,
  dark, or system theme.
- Added optional **Text windows** directly behind app text.
- Added **Clear** and **Colored** text-window modes.
- Added warm white, black, pale blue, pale green, soft gold, and charcoal
  text-window palette choices.
- Added a custom hexadecimal field for manually choosing any text-window
  color.
- Added a separate text-window opacity slider covering every whole percentage
  from **1% through 100%**.
- High Contrast mode temporarily uses protected automatic colors to preserve
  readability.

## Installation and compatibility

Install version 1.2.1 directly over Maclean Phone 1.2.0. Do not uninstall the
existing app first, because uninstalling may erase saved SIP and appearance
settings.

The application ID remains `com.macleanofduartenterprises.phone`, version code
8 is newer than version 1.2.0's version code 7, and the APK is signed with the
same Maclean Phone certificate. Existing appearance settings migrate without
being reset. The new text color defaults to **Automatic**, and text windows
default to **Clear**, until changed by the user.

## Verification

- Conventional clean Gradle build completed successfully.
- 23 unit tests passed with no failures.
- Release lint completed with zero errors.
- The clean unsigned APK reproduced the signed release input byte-for-byte.
- APK Signature Schemes v2 and v3 verify successfully.
- ZIP integrity, duplicate-entry, four-architecture, and 16 KB native-library
  alignment checks passed.
- Private signing material is excluded from the source archive.
