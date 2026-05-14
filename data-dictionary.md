# Data Dictionary - Fingo Impulsive Detector

| Column | Type | Description |
|---|---|---|
| timestamp | datetime | Waktu transaksi |
| amount | numeric | Nominal transaksi dalam IDR |
| category | string | Kategori transaksi |
| source | string | Sumber dataset |
| hour | integer | Jam transaksi |
| hour_sin | float | Encoding siklus jam menggunakan sin |
| hour_cos | float | Encoding siklus jam menggunakan cos |
| day_of_week | integer | Hari dalam minggu |
| is_weekend | integer | 1 jika Sabtu atau Minggu |
| is_night | integer | 1 jika transaksi malam |
| night_score | float | Skor transaksi malam |
| category_score | float | Skor kategori hedonic atau utilitarian |
| amount_score | float | Skor nominal transaksi |
| impulsive_score | float | Skor impulsivitas transaksi |
| label | string | AMAN / PERTIMBANGAN / IMPULSIF |
| is_impulsive | integer | 1 jika transaksi impulsif |
