# 🚢 Employee Attrition Radar: Early Warning System using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-Latest-green.svg)
![SHAP](https://img.shields.io/badge/SHAP-Explainable%20AI-yellow.svg)

## 📌 Project Overview
Tingkat *turnover* karyawan yang tinggi ibarat kebocoran halus pada sebuah kapal; jika dibiarkan, proyek akan mangkrak dan perusahaan akan merugi secara finansial maupun kultural. Proyek ini bertujuan untuk membangun **Sistem Deteksi Dini (Early Warning System)** menggunakan Machine Learning guna memprediksi potensi *resign* karyawan *sebelum* hal itu terjadi. 

Dengan pendekatan **Explainable AI (SHAP)**, model ini tidak hanya memberikan prediksi "Siapa yang akan pergi", tetapi juga menjawab "Mengapa mereka pergi?", memberikan ruang bagi manajemen untuk melakukan intervensi kultural dan strategis yang tepat sasaran tanpa adanya bias demografis.

## 🎯 Business Value
* **Proactive Retention:** Berpindah dari pendekatan *"Exit Interview"* menjadi *"Stay Interview"*.
* **Cost Efficiency:** Menekan biaya rekrutmen ulang yang memakan 1.5x hingga 2x lipat dari gaji tahunan karyawan.
* **Fair & Unbiased:** Model murni mengevaluasi berdasarkan meritokrasi, performa, dan kesejahteraan, tanpa mempertimbangkan gender, ras, atau status pernikahan.

## 🛠️ Tech Stack & Methodology
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, XGBoost, Random Forest, SMOTE (Imbalanced Learning)
* **Explainable AI:** SHAP (SHapley Additive exPlanations), Permutation Importance

## 📊 Key Insights & Findings
Melalui analisis EDA dan SHAP *Dependence Plot*, ditemukan 3 pola utama pendorong attrition:
1. **The LOP Red Flag:** Karyawan yang mengambil program LOP (Cuti di Luar Tanggungan) memiliki probabilitas resign yang melonjak drastis hingga **53%**.
2. **The 2-6 Years Itch:** Masa kerja paling rentan berada pada rentang **2 hingga 6 tahun**, mengindikasikan krisis stagnansi karir pada level *mid-senior*.
3. **The 'Average' Illusion:** Skor kepuasan karyawan di angka 3 (Netral) tidak cukup untuk mempertahankan talenta. Angka 3 masih menyumbang tingkat *resign* sebesar **36%**. 

## 💡 Strategic Recommendations
Berdasarkan *insight* model, kami merekomendasikan:
1. **LOP as an Early Warning:** Jangan otomatis menyetujui LOP. Jadikan momen pengajuan LOP sebagai *trigger* untuk sesi diskusi 1-on-1 mendalam terkait kesehatan mental dan *workload*.
2. **Internal Mobility Program:** Rancang program rotasi antar divisi atau berikan otonomi proyek baru khusus untuk karyawan yang memasuki tahun ke-3 agar mereka tidak merasa stagnan.
3. **Elevate Satisfaction Standards:** Ubah target KPI budaya kerja. Rata-rata kepuasan harus ditargetkan minimal di angka 4 untuk memastikan loyalitas yang solid.

## 🚀 How to Run the Project
1. Clone repository ini:
   ```bash
   git clone https://github.com/fanidwii/employee-attrition-prediction.git
   ```
2. Pindah ke direktori project:
   ```bash
   cd employee-attrition-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Buka dan jalankan file Jupyter Notebook  `employee-attrition-prediction.ipynb`.
