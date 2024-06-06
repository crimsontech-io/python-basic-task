# Sqlite task

- Make any application where it will read the sqlite db’s name noodles.db
  - Read and print the data of table weight_record and delete the first row
  - download the record of table weight_record in csv format using datepicker with following heading
    - wegiht value are string format like “ 66.0;66.0;66.0;66.0;66.0;66.0” it need to be kept in separate column with heading w1, w2, w3 …. w6
    | s.n | product name | veg_non veg | weighing material | w1  | w2  | w3  | w4  | w5  | w6  | timestamp |
    | --- | ------------ | ----------- | ----------------- | --- | --- | --- | --- | --- | --- | --------- |
    | 1   |              |             |                   |     |     |     |     |     |     |           |
    | 2   |              |             |                   |     |     |     |     |     |     |           |
  - additional feature:
    - download by product name
    - download in excel format
    - add column name range ( maximum - minimum ) of the 6 weight
    - add max column
    - add min column
