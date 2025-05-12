```python

import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import pandas as pd

sns.set(style="whitegrid")
plt.figure(figsize=(10, 6))
sns.scatterplot(data=df, x='year', y='price', hue='model')
plt.title('Persebaran Harga Unit Berdasarkan Tahun Jual Unit')
plt.xlabel('Tahun Penjualan')
plt.ylabel('Harga Unit (GBP)')
plt.show()

plt.figure(figsize=(10, 6))
sns.boxplot(data=df, x='engineSize', y='price')
plt.title('Distribusi Harga Berdasarkan Ukuran Mesin')
plt.xlabel('Ukuran Mesin (L)')
plt.ylabel('Harga Mobil (GBP)')
plt.grid(True)
plt.tight_layout()
plt.show()
