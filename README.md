<div align="center">

# Baibhav Kumar
### Software Developer · B.Tech CSE @ NIT Durgapur

</div>

---

<table>
<tr>
<td width="370" valign="top">

<!-- ASCII portrait (types itself in like a terminal on load) -->
<img src="avi-ascii.svg" width="370" alt="Baibhav Kumar ASCII portrait" />

</td>
<td width="490" valign="top">

<!-- Info card (neofetch-style panel, fades in alongside the portrait) -->
<img src="info-card.svg" width="490" alt="DSBaibhav info card" />

</td>
</tr>
</table>

<!-- Contribution heatmap (rebuilds every night via GitHub Actions) -->
<img src="contrib-heatmap.svg" width="860" alt="DSBaibhav contribution graph" />

---

<div align="center">

**📬 Connect with me**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Baibhav_Kumar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/baibhav-kumar-541642332)
[![GitHub](https://img.shields.io/badge/GitHub-DSBaibhav-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/DSBaibhav)
[![Instagram](https://img.shields.io/badge/Instagram-@_vaibhav0__8-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/_vaibhav0_8?igsh=MXhybHg1YWV1cHB3aw==)
[![Gmail](https://img.shields.io/badge/Email-baibhavsingh473@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:baibhavsingh473@gmail.com)
[![Resume](https://img.shields.io/badge/Resume_%26_CV-Google_Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1wBocrvmhNGzy5XtUTxyDehjEgg_HF-sz)

</div>

---

<details>
<summary><b>🔧 To retune the portrait</b></summary>

```bash
# Adjust clipLimit (more = more contrast), then re-run ascii+preview:
nano scripts/prep_photo.py          # tweak clipLimit= in line 33
python3 scripts/prep_photo.py /path/to/photo.jpg source-prepped.png
STATIC=1 python3 scripts/make_ascii_svg.py && qlmanage -t -s 900 -o . avi-ascii.svg
# Tune CONTRAST / GAMMA / WHITE_FLOOR in make_ascii_svg.py for face brightness
```

</details>

<details>
<summary><b>📝 To edit the info panel</b></summary>

```bash
nano scripts/make_info_card.py      # edit the ROWS list at the top
python3 scripts/make_info_card.py
STATIC=1 python3 scripts/make_info_card.py && qlmanage -t -s 900 -o . info-card.svg
```

</details>
