# 🏠 House Price Prediction (Tabular ML — Linear/KNN/SVR)

این پروژه با استفاده از داده‌های جدولی (Kaggle) و الگوریتم‌های **Linear Regression**، **KNN Regressor** و **Support Vector Regression** قیمت خانه را پیش‌بینی می‌کند. نوت‌بوک در Google Colab/لوکال قابل اجراست و شامل پیش‌پردازش، تقسیم داده، آموزش مدل‌ها و ارزیابی است.

---

## 📂 ساختار پروژه
- `Predict_House_Price.ipynb`: نوت‌بوک اصلی شامل:
  - دانلود و بارگذاری دیتاست (Kaggle)
  - بررسی اولیه داده و بصری‌سازی‌های پایه
  - پیش‌پردازش (Imputation/Encoding/Scaling)
  - تقسیم داده (Train/Test Split)
  - آموزش مدل‌ها: Linear Regression, KNN, SVR
  - بهینه‌سازی ابرپارامترها (Grid Search)
  - ارزیابی مدل‌ها (MAE/MSE/RMSE/R²)

> 📌 توجه: این نوت‌بوک در **Google Colab** نوشته شده؛ اگر مسیرهایی مثل `/content/...` وجود دارد، هنگام اجرا متناسب با محیط خود تنظیم کنید.
> برای دانلود خودکار از Kaggle به `kaggle.json` در مسیر `~/.kaggle/` نیاز دارید (آن را عمومی نکنید).

---

## 🧰 تکنولوژی‌ها
- Python 3.x
- NumPy, Pandas
- scikit-learn
- Matplotlib, Seaborn
- (اختیاری) Google Colab

---

## 📥 نصب و اجرا
1. مخزن را کلون کنید:

```bash
git clone https://github.com/evi-data-vision/House-Price-Prediction-ML.git
cd House-Price-Prediction-ML
pip install -r requirements.txt
```

---
