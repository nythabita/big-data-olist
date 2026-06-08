# big-data-olist

Dataset: olist_marketing_qualified_leads_dataset

- Total rows: 8000
- Missing value:
  - origin: 60 (0.75%)
- Duplicate mql_id: 0
- first_contact_date converted from String to Date


Dataset: geolocation, customers, and closed deals
- total rows output around 99k ish
- i forgot how many i reduce the row but its kinda diff with group 3 dataset
- so many missing val, i handle it with mean, fix value (UNKNOWN i fogot)
- remove all duplicates, including all unique details
- string to date done


progress 9 june 2026
- already join ORDER MASTER TABLE
- should join CUST MASTER TABLE, and we can start EDA
- im afraid mismatch of order id or redundancy bcs i just roughly joining 3 diff tables w/o seeing which column should be included/excluded
- question to ask -> cek apakah udah clean, tanya apakah ada risiko datanya redundan? krn meskipun kita udah no redundan each table, tp kl digabungin takutnya ga align. trs model prediktif itu sbnrnya kek gmn kek belum kebayang. ingat tujuan kita tuh RFM, CLV, dan prediksi segmentasi pelanggan
