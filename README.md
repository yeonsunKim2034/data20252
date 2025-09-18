def get_year_months():
  year_months = []
  for year in range(2015, 2024+1):
   for month in range(1, 12+1):
    year_months.append(f’{year}{month:02d}’)
  return year_months

responses = []

for year_month in get_year_months():
  # 데이터를 수집하고 responses에 추가
  
