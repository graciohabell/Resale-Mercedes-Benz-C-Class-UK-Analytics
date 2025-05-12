## Visualisasi Data Hubungan antara tahun pennjualan, ukuran mesin, dan harga unit Mercedes-Benz C Class UK 

### Persebaran Harga Berdasarkan Tahun Penjualan

```python
sns.scatterplot(data=df, x='year', y='price', hue='model')
