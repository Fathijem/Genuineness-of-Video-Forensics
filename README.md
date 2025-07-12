# Genuineness Study on Video Using Cyber Forensics

This project aims to analyze and verify the authenticity of digital videos using cyber forensic tools and techniques. With the rise of deepfakes and forged media, ensuring the integrity of video evidence has become critical for legal, journalistic, and social media domains.

## 🔍 Objective

To identify whether a video has been tampered with by analyzing:
- Metadata information
- Hash values
- Editing traces (e.g., scene cut, copyleft)
- Frame-by-frame differences

## 📁 Tools Used

| Tool        | Purpose                                      | License     |
|-------------|----------------------------------------------|--------------|
| **Autopsy** | Metadata and forensic analysis of media      | Open Source |
| **FTK Imager** | Imaging and hash generation               | Open Source |
| **Encase**  | In-depth forensic examination                | Licensed    |
| **WinMD5**  | Integrity check via hash verification         | Open Source |

## 🧪 Methodology

1. **Video Acquisition** – Video sourced via social media.
2. **Hashing** – MD5 calculated using WinMD5.
3. **Imaging** – Video copied and imaged using FTK Imager.
4. **Analysis** – Conducted using Autopsy and Encase for:
   - Hex dumps
   - Metadata timestamps
   - Codec detection
   - Scene cut and editing patterns
5. **Frame Conversion** – Video broken into frames and analyzed individually.

## 📊 Results

- Forged video revealed usage of editing tools like **Scene Cut** and **Intra-refresh**.
- Genuine video (MP4 format) showed no suspicious indicators.
- Detected differences in hash values, frame sizes, and metadata inconsistencies.

## ✅ Conclusion

Analyzing metadata and hash values is crucial to detecting video forgery. This project highlights the importance of verifying video authenticity before accepting or forwarding digital content, especially on social platforms.

## 📌 Use Cases

- Legal investigations
- Cyber crime forensics
- Fake news detection
- Video evidence validation

## 📚 References

- [Autopsy Documentation](https://www.autopsy.com/)
- [FTK Imager](https://www.exterro.com/ftk-imager)
- [Encase](https://encase-forensic.software.informer.com/)
- [WinMD5](https://www.winmd5.com/)
- [Video Forensics Articles & Metadata Analysis](#)

---



