# Workshop Guidelines Aug 02 2025

## Tackling Global Challenges in Plant Pathology with AI: Forecasting, Imaging, and Protein Prediction

Welcome to our workshop! We’re excited to have you join us as we explore how artificial intelligence can be applied to key challenges in plant pathology. This document provides important guidelines to help you prepare for the hands-on sections of the workshop.

---

## 🔧 General Requirements

To ensure a smooth and productive learning experience during the hands-on sessions, please review and follow the requirements below:

- **Bring Your Own Laptop**  
  Each participant is required to bring their own laptop and charger for the hands-on exercises.

- **Internet Access**  
  Internet will be provided by the hotel. However, as a precaution, please be prepared to use your mobile hotspot in case of unexpected connectivity issues.

- **Download Workshop Materials in Advance**  
  Please download and save the PDF files attached to the workshop email onto your laptop. This is a contingency in case internet access becomes unavailable. Also download this document—it contains the protein sequences needed for the AlphaFold hands-on section.

---

## 🧪 Hands-On Sessions Overview

The hands-on portion of the workshop will use **Google Colab** for running code in both **R** and **Python**. (A Google account is required.)

> **Note:** No prior programming experience is assumed. The goal is to introduce key components of machine learning workflows and show how small code changes can impact model performance.

---

## 🔗 Session Links

We will review these during the workshop, but you're welcome to try them in advance:

1. **Applying ML to Multidimensional Epidemiological Data**  
   👉 [Open in Google Colab](https://nam10.safelinks.protection.outlook.com/?url=https%3A%2F%2Fcolab.research.google.com%2Fdrive%2F1AeSFSa-6CD0oLyhwG8bUnATs_fPSKB-O%3Fusp%3Ddrive_link&data=05%7C02%7Cjacoborobledobur%40ufl.edu%7Cb9e907d47b78408c86df08ddd1df5668%7C0d4da0f84a314d76ace60a62331e1b84%7C0%7C0%7C638897479561052765%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=txSAsxXnX3N7KHJFV2%2FVjTLqYMHpf%2FA8nmO71s4hZNA%3D&reserved=0)

2. **Building Neural Networks for Image Classification**  
   👉 [Open in Google Colab](https://nam10.safelinks.protection.outlook.com/?url=https%3A%2F%2Fcolab.research.google.com%2Fdrive%2F1VkmFzryPIrEwpzSH5HjfMoTDOHl9F81I%3Fusp%3Dsharing&data=05%7C02%7Cjacoborobledobur%40ufl.edu%7Cb9e907d47b78408c86df08ddd1df5668%7C0d4da0f84a314d76ace60a62331e1b84%7C0%7C0%7C638897479561080639%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=J%2Fti%2FhpoyxetU1C6GN22xLPmOb6B9rIpgThJfry21wI%3D&reserved=0)  
   ⚠️ Be sure to enable **GPU**:  
   Go to `Runtime > Change runtime type > Hardware accelerator > GPU (T4)`

3. **Exploring AlphaFold 3 for Protein Prediction**  
   - 👉 [Open AlphaFold Server](https://nam10.safelinks.protection.outlook.com/?url=https%3A%2F%2Falphafoldserver.com%2Ffold%2F6a4c9bf165fe51e9&data=05%7C02%7Cjacoborobledobur%40ufl.edu%7Cb9e907d47b78408c86df08ddd1df5668%7C0d4da0f84a314d76ace60a62331e1b84%7C0%7C0%7C638897479561100881%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=mk0kZq6x23UuBzd%2FWMxHCjZzJ5i41WzRjWJWtw6wy3k%3D&reserved=0)  
   - 👉 [Open UniProt Protein Structure Database](https://nam10.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.uniprot.org%2F&data=05%7C02%7Cjacoborobledobur%40ufl.edu%7Cb9e907d47b78408c86df08ddd1df5668%7C0d4da0f84a314d76ace60a62331e1b84%7C0%7C0%7C638897479561116116%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=8pS%2FgaovJ8Z3xH5V3IiY6fsUi6Tn56R884%2FWFTcMpAA%3D&reserved=0)

---

## 🧬 Sequence Showdown!

Below are 5 amino acid sequences—but only **two** interact!  
Use **AlphaFold Server** and confidence scores to figure out which pair it is.

> 💡 Copy-paste sequences into AlphaFold Server, label jobs clearly (e.g., `Seq1-Seq2`, `Seq3-Seq5`) to keep track.

### 🔹 Sequence 1
```

MRLAIMLSATAVAINFATCSAIDQTKVLVYGTPAHYIHDSAGRRLLRKNEENEETSEERAPNFNLANLNEEMFNVAALTKRADAKKLAKQLMGNDKLADAAYIWWQHNRVTLDQIDTFLKLASRKTQGAKYNQIYNSYMMHLGLTGY

```

### 🔹 Sequence 2
```

MRYLATLLLSLAVLITAGCGWHLRDTTQVPSTMKVMILDSGDPNGPLSRAVRNQLRLNGVELLDKETTRKDVPSLRLGKVSIAKDTASVFRNGQTAEYQMIMTVNATVLIPGRDIYPISAKVFRSFFDNPQMALAKDNEQDMIVKEMYDRAAEQLIRKLPSIRAADIRSDEEQTSTTTDTPATPARVSTTLGN

```

### 🔹 Sequence 3
```

MIVLSVGSASSSPIVVVFSVALLLFYFSETSLGAPCPINGLPIVRNISDLPQDNYGRPGLSHMTVAGSVLHGMKEVEIWLQTFAPGSETPIHRHSCEEVFVVLKGSGTLYLAETHGNFPGKPIEFPIFANSTIHIPINDAHQVKNTGHEDLQVLVIISRPPIKIFIYEDWFMPHTAARLKFPYYWDEQCIQESQKDEL

```

### 🔹 Sequence 4
```

MQGRLSAWLVKHGLVHRSLGFDYQGIETLQIKPEDWHSVAVILYIYGYNYLRSQCAYDVAPGGLLASVYHLTRIEYGVDQPEEVCIKVFAPRSNPKIPSVFWVWKSANFPERESYDMLGILYDNHPRLKRILMPESWIGWPLRKDYIAPNFYEIQDAY

```

### 🔹 Sequence 5
```

MKKRIPTLLATMIATALYSQQGLAADLASQCMLGVPSYDRPLVQGDTNDLPVTINADHAKGDYPDDAVFTGSVDIMQGNSRLQADEVQLHQKEAPGQPEPVRTVDALGNVHYDDNQVILKGPKGWANLNTKDTNVWEGDYQMVGRQGRGKADLMKQRGENRYTILDNGSFTSCLPGSDTWSVVGSEIIHDREEQVAEIWNARFKVGPVPIFYSPYLQLPVGDKRRSGFLIPNAKYTTTNYFEFYLPYYWNIAPNMDATITPHYMHRRGNIMWENEFRYLSQAGAGLMELDYLPSDKVYEDEHPNDDSSRRWLFYWNHSGVMDQVWRFNVDYTKVSDPSYFNDFDNKYGSSTDGYATQKFSVGYAVQNFNATVSTKQFQVFSEQNTSSYSAEPQLDVNYYQNDVGPFDTRIYGQAVHFVNTRDDMPEATRVHLEPTINLPLSNNWGSINTEAKLLATHYQQTNLDWYNSRNTTKLDESVNRVMPQFKVDGKMVFERDMEMLAPGYTQTLEPRAQYLYVPYRDQSDIYNYDSSLLQSDYSGLFRDRTYGGLDRIASANQVTTGVTSRIYDDAAVERFNISVGQIYYFTESRTGDDNITWENDDKTGSLVWAGDTYWRISERWGLRGGIQYDTRLDNVATSNSSIEYRRDEDRLVQLNYRYASPEYIQATLPKYYSTAEQYKNGISQVGAVASWPIADRWSIVGAYYYDTNANKQADSMLGVQYSSCCYAIRVGYERKLNGWDNDKQHAVYDNAIGFNIELRGLSSNYGLGTQEMLRSNILPYQNTL

```

---

## 📬 Questions?

If you have any questions or run into issues ahead of the workshop, feel free to reach out to:

📧 **Jacob Robledo**  
📨 jacoborobledobur@ufl.edu

We look forward to a great session together!
