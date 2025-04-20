# iOS-13.4.1-Investigation
# 📱 iOS 13.4.1 Digital Forensics Case Study

This repository documents my forensic investigation of an iPhone 11 disk image running iOS 13.4.1 (Build 17E262). The image was created by Joshua Hickman and is hosted by [DigitalCorpora](https://digitalcorpora.org). This case study is part of my hands-on learning in mobile device forensics.

## 🕵️‍♂️ Objective
To analyze the iOS filesystem, extract meaningful artifacts, and understand user behavior by examining system logs, backups, and application data.

## 🔍 Work Done So Far

- ✅ Explored the iOS root filesystem using Kali Linux and navigated through key directories including `/private`, `/var`, and symbolic links.
- ✅ Investigated iTunes backup and sysdiagnose logs to identify user activity and device metadata.
- ✅ Utilized tools like `tar`, `libplist-utils`, and standard UNIX commands to parse, extract, and analyze files from the forensic image.

## 🧰 Tools & Environment

- **OS:** Kali Linux
- **Disk Image:** iOS 13.4.1 (iPhone 11), Build 17E262
- **Tools:** `tar`, `libplist-utils`, `ls`, `file`, `strings`, `grep`

## 📂 Dataset

The original image and associated documentation are publicly available:

- 📥 [Joshua Hickman's iOS Test Images](https://digitalcorpora.org/corpora/misc/hickman-ios-images/)
- 📝 Includes: Full disk image, sysdiagnose logs, iTunes backup, and image creation documentation

## 📌 Next Steps

- Analyze application data and user interaction logs
- Correlate timestamps with user behavior
- Create a detailed timeline of activity

---

> 📣 **Note:** This case study is for educational purposes only and follows responsible disclosure and ethical forensic guidelines.

