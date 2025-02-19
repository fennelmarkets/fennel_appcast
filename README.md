📢 Deprecation Notice: `appcast_prod.xml` & `appcast_test.xml`
The files appcast_prod.xml and appcast_test.xml are now ⚠️ DEPRECATED.

🚀 New Update Process

To upgrade versions, you must now update the following files separately in their respective folders:

✅ Production
`prod/appcast_android_prod.xml`
`prod/appcast_ios_prod.xml`

🛠 Test
`test/appcast_android_test.xml`
`test/appcast_ios_test.xml`


❗ Why Aren’t We Deleting the Old Files?
We are NOT removing appcast_prod.xml and appcast_test.xml because:
📌 If a user opens the app after 6 months, it may still try to fetch these files.
📌 Removing them would cause an error in older app versions.
