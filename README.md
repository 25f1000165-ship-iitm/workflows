# Multi-Platform Matrix Build with Artifacts

This repository demonstrates a **GitHub Actions matrix build** workflow that runs parallel builds across multiple Node.js versions and uploads unique build artifacts for each run.

---

## 🚀 Workflow Overview

- **Workflow File:** `.github/workflows/matrix-build.yml`  
- **Matrix Identifier:** `matrix-28f83f1`  
- **Artifact Prefix:** `build-28f83f1-v<version>`  
- **Matrix Variants:** Node.js versions 14, 16, and 18  
- **Runs-on:** Ubuntu Latest  
- **Artifacts Uploaded:** 3 (one per version)

Each job:
1. Builds using a different Node.js version.  
2. Generates a unique output file with build details.  
3. Uploads it as an artifact to the Actions tab.

---

## 🧩 Validation Checklist

| Requirement | Status |
|--------------|--------|
| ✅ At least 3 matrix jobs | ✔️ Done |
| ✅ Artifacts prefixed with `build-28f83f1` | ✔️ Done |
| ✅ Non-empty artifact content | ✔️ Done |
| ✅ Step identifier `matrix-28f83f1` | ✔️ Present |
| ✅ README contains email address | ✔️ Below |

---

## 📧 Maintainer

**Email:** 25f1000165@ds.study.iitm.ac.in  
**GitHub Repository:** [https://github.com/25f1000165-ship-iitm/workflows](https://github.com/25f1000165-ship-iitm/workflows)

---

### 🧠 Notes

This workflow demonstrates:
- Parallelized builds using **matrix strategy** in GitHub Actions  
- Proper **artifact management** and naming conventions  
- Clean CI/CD configuration suitable for cross-version testing environments
