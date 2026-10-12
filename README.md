# 📄 Hosted Resume

This repository securely hosts and auto-deploys my professional resume to a clean, live URL using GitHub Pages.

> 🚀 [**Click Here to View My Live Resume (PDF)**](https://adamhoportfolio.github.io/resume/resume.pdf)

---

## 🛠️ How to Update Manually

When you modify your resume on Overleaf, follow these quick steps to update the live link:

1. **Download:** In Overleaf, click the **Menu** button (top left) or the **Download PDF** icon and grab the compiled PDF.
2. **Rename:** Ensure the file is named exactly `resume.pdf`.
3. **Commit & Push:** Replace the old file in this repository and push the changes.

```bash
# Quick terminal method if you use Git locally:
cp ~/Downloads/your_downloaded_file.pdf ./resume.pdf
git add resume.pdf
git commit -m "update: sync latest resume changes from overleaf"
git push origin main
```

*GitHub Pages will detect the new file instantly and update the live URL within 30 seconds.*
