### OrionOS OTA repo
In order for a device to be officially supported by OrionOS, OTA information needs to be added.
Please refer to the following "Readme" to get started

### Introduction
In order for a device to be OTA compliant, there are a few things to know.

### JSON structure
```
{
  "response": [
    {
        "maintainer": "Name/Nickname",
        "oem": "Xiaomi",
        "device": "ginkgo",
        "filename": "OrionOS-Cosmic-blabla.zip",
        "download": "https://sourceforge.net/projects/orionos/files/A14/<filename>.zip/download",
        "timestamp": 0000000000,
        "md5": "abcdefg123456",
        "size": 123456789,
        "version": "Cosmic"
    }
  ]
}
```
