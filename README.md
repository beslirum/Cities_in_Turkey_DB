# Turkey Cities Data

Bu repo, Türkiye'nin 81 ilinin bilgilerini içeren JSON ve CSV dosyalarını içermektedir.

## Dosyalar

- `cities_of_turkey.json`: Türkiye'nin 81 ilinin JSON formatındaki bilgilerini içerir.
- `cities_of_turkey.csv`: Türkiye'nin 81 ilinin CSV formatındaki bilgilerini içerir.

## Veri Alanları

Her bir ilin bilgileri aşağıdaki alanları içermektedir:

- `id`: İlin benzersiz kimliği.
- `name`: İlin adı.
- `latitude`: İlin enlem koordinatı.
- `longitude`: İlin boylam koordinatı.
- `population`: İlin nüfusu.
- `region`: İlin bulunduğu bölge.

## Nasıl Kullanılır

- JSON dosyasını programatik olarak kullanmak için:

  ```python
  import json

  with open('cities_of_turkey.json', 'r', encoding='utf-8') as file:
      data = json.load(file)

  # Veri kullanımı için gerekli işlemleri yapın
  
- CSV dosyasını programatik olarak kullanmak için:
  ```python
  import pandas as pd

  data = pd.read_csv('cities_of_turkey.csv')

  # Veri kullanımı için gerekli işlemleri yapın
