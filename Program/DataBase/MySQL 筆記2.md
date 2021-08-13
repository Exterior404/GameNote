# 筆記2
語法練習

配合 Anaconda3 再使用 SQLite處理

#### INSERT 新建資料
```sql
INSERT INTO customer
(cid, name, cellphone, address, describe)
VALUES ('c04', 'D', '0912112233', '新北', '一千五');
```

```SQL
INSERT INTO customer (cid, name, cellphone, address, describe) VALUES ("c05", "E", "0123456789", "台南", "六千五")
```

#### UPDATE 更新
```SQL
UPDATE product SET price=45 WHERE item="(二手書)魔物獵人：魂之繼承者（2）"
```

```SQL
UPDATE product SET price = price * 1.05 WHERE shop = "PChome線上購物";
```

#### DELETE刪除
```SQL
DELETE FROM product WHERE shop="台灣樂天市場";
```

```SQL
DELETE FROM product WHERE price >= 5000;
```

#### SELECT 選擇
```SQL
SELECT * FROM product //顯示多少筆資料
SELECT shop FROM product //抓出該欄位資料
SELECT DISTINCT shop FROM product //抓出該欄 且不重復
SELECT * FROM product WHERE price>=300 AND price <=1000;//抓出一個範圍
SELECT * FROM product WHERE price between 300 and 3000

SELECT * FROM course WHERE score IS NULL;//找缺失口
SELECT * FROM course WHERE score IS NOT NULL;//找非缺口

SELECT * FROM product WHERE shop in("森森購物網") //查找有沒有
SELECT * FROM product WHERE shop not in("森森購物網")

select * from product
where item like "%攻略%"
and price>=500 and price <=800

SELECT count(*), avg(price), sum(price) 
FROM product WHERE shop = "東森購物";

SELECT shop, count(*), avg(price), 
sum(price), max(price), min(price)
FROM product GROUP by shop
```