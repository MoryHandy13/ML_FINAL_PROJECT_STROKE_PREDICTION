# ML_FINAL_PROJECT_STROKE_PREDICTION
-- Case
Stroke merupakan penyebab ke dua yang menyebabkan kematian global, yang bertanggung jawab terhadap sekitar 11% total kematian di dunia. Dampak negatif dari stroke tersebut meningkatkan kebutuhan untuk inovasi dasi sisi diagnosis dan managemen terhadap penyakit stroke. Peluang untuk meningkatkan ketepatan hasil diagnosis terhadap potensi seseorang akan menderita penyakit stroke terbuka dengan menggunakan analisis terhadap data medis pasien terdahulu. Report ini berisi analisis terhadap hubungan antara faktor faktor yang dapat mempengaruhi kemungkinan seseorang menderita penyakit stroke. Input permasalahan ini adalah beberapa fitur seperti gender, umur, Riwayat hipertensi dan serangan jantung, status pernikahan, tipe pekerja, tipe residental, rata-rata tingkat kadar glukosa darah, bmi, dan status perokok. Kemudian kita gunakan beberapa model prediksi Classification yaitu KNN, Logistic Regression, Decision Tree, dan Random Forest. Output akhir dari penelitian ini adalah analisis terhadap fitur apa saja yang berkolerasi terhadap meningkatkan penyakit stroke dan model prediktif yang dapat memprediksi potensi seseorang menderita penyakit stroke sehingga diharapkan dengan adanya penelitian ini dapat membantu tenaga medis untuk menentukan langkah lanjutan dalam treatment terhadap pasien.

-- Objective
Tujuan utama dari task ini adalah untuk memprediksi seseorang terkena stroke berdasarkan variable yang ada
Metode yang berguna untuk task ini adalah model klasifikasi yaitu Logistic Regression, K-Nearest Neighbor, Decision Tree, Random Forest dan Support Vector Machine.

-- Dataset & Description :
- id: unique identifier

- gender: "Male", "Female" atau "Other"

- age: Umur dari pasien

- hypertension:

“No” if : pasien tidak menderita hipertensi

Normal dengan tekanan darah sistolik < 120 mmHg dan diastolic < 80 mmHg

Pre-hipertensi dengan tekanan darah sistolik 120-139 dan diastolic 80-89)

“Yes” if : pasien menderita hipertensi

Hipertensi derajat 1 dengan tekanan darah sistolik 140-159 mmHg dan diastolic 90-99 mmHg

Hipertensi derajat 2 dengan tekanan darah sistolik >160 mmHg dan diastolic >100 mmHg

- heart_disease: “No” if : pasien tidak pernah menderita penyakit jantung, 

“Yes” jika pasien pernah menderita penyakit jantung

- ever_married: "No" atau "Yes"

- work_type: "children", "Govt_jov", "Never_worked", "Private" atau "Self-employed"

- Residence_type: "Rural" atau "Urban"

-  avg_glucose_level: rata-rata glukosa dalam darah (mg/dL)

- bmi: body mass index

Underweight

Batas Normal

Overweight

Pre-obese

Obese I

Obese II

- smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*

- stroke: 1 if the patient had a stroke or 0 if not
