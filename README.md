# bulk-silent-sms

This tools intended to verification if phone number is online, offline, or airplane by sending Silent SMS (SMS that not pop up notification to destination phone number) but in programmable bulk through API Ktor 

---

# Permissions

Grant manually, app permissions otherwise it didn't work.

---

# Payload

Send the payload through your ip addres that appear in the `MainActivity` with `phone` have prefix country number otherwise it didn't work.

```
{"phone": "+628123456789"}
```

---

# Note

There's chance that this silent sms payload could pop up in certain device condition, like maybe modern Iphone with using eSIM or older device that is not Android.
