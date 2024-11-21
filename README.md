# personal-health-analysis
Analyzing personal health data from Apple Health.

## Project Description
This project aims to analyze step count, heart rate, and sleep patterns using data collected from the Apple Health app.

## Data Source
The data is exported from the Apple Health app in `export.xml` format.

## Technologies Used
- Python
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

## Instructions
1. Place the data file in the `data` folder.
2. Open the `analysis.ipynb` file and run the cells to view the analyses.

## Contact
If you have any questions about the project, feel free to reach out to me: [Email](revna.demirkale@sabanciuniv.edu).
personal-health-analysis/
│
├── data/
│   └── export.xml         # Ham veriler (örneğin, Apple Health'ten alınan XML dosyası).
│
├── notebooks/
│   └── analysis.ipynb     # Analiz sürecini içeren Jupyter Notebook dosyası.
│
├── scripts/
│   └── data_processing.py # Veriyi işlemek için kullanılan Python script'leri.
│   └── visualization.py   # Grafikleri oluşturmak için kullanılan Python script'leri.
│
├── README.md              # Proje açıklamalarını içeren dosya.
│
└── .gitignore             # Git'e yüklenmeyecek dosyaları belirtmek için (örneğin, büyük veri dosyaları).
