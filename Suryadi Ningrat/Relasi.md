# PEMBUATAN DataBase (CompanyAde)
![[Pasted image 20240925190428.png]]

### Hasil:
![[Screenshot 2024-09-12 091404.png]]

### Code:
![[Pasted image 20240925190557.png]]

### Hasil:
![[Screenshot 2024-09-12 091417.png]]
### Code:
![[Pasted image 20240925190823.png]]
![[Pasted image 20240925190845.png]]

### Hasil:
![[Screenshot 2024-09-12 091440.png]]

### Code:
![[Pasted image 20240925191045.png]]

### Hasil:
![[Screenshot 2024-09-12 091454.png]]

### Code:
![[Pasted image 20240925191138.png]]

### Hasil:
![[Screenshot 2024-09-12 091521.png]]

### Code:
![[Pasted image 20240925191227.png]]

### Hasil:
![[Screenshot 2024-09-12 091536.png]]

### Code:
![[Pasted image 20240925191328.png]]

### Hasil:
![[Screenshot 2024-09-12 091624.png]]

### Code:
![[Pasted image 20240925191453.png]]
![[Pasted image 20240925191514.png]]

### Hasil:
![[Screenshot 2024-09-12 091648.png]]


### Code:
![[Pasted image 20240925191610.png]]

### Hasil:
![[Screenshot 2024-09-12 091659.png]]

### Code:
![[Pasted image 20240925191711.png]]
![[Pasted image 20240925191727.png]]

### Hasil:
![[Screenshot 2024-09-12 091715.png]]

###  Code:
![[Pasted image 20240925191821.png]]

### Hasil:
![[Screenshot 2024-09-12 091731.png]]

# SELECT LANJUTAN
### Code:
![[Pasted image 20240925210657.png]]

### Penjelasan:
SELECT = untuk memilih kolom mana saja Yanu ingin ditampilkan dan dari tabel mana kolom tersebut diambil. orders. 
Order ID = orders merupakan nama tabel Yang ingin ditampilkan kolomn Ya Yaitu orderID. Jadi kolom orderID Pada tabel orders ingin ditampilkan. dalam orders, 
order Date = kolom orderDate Pada tabel orders insin ditampilkan. orders. CustID= kolom CustID dalam tabel orders dipilih untuk ditampilkan. Customers. company Name = kolom company Name dalam tabel customers dipilih untuk ditampilkan.
customers.contactName = kolom contactName dalam tabel customers dipilih untuk ditampilkan. customers. city kolom city dalam tabel customers dipilih untuk ditampilkan. 
Customers. Phone = kolom Phone dalam tabel customers dipilih untuk ditampilkan. 
FROM orders, customers = untuk memilih dari tabel mana saja yang kolomnya insin dipilih untuk ditampilkan. Orders adalah nama tabel Pertama yang dipilih dan customers adalah nama tabel kedua Yang dipilih. WHERE Kondisi Yang harus dipenuhi oleh suatu kolom data avar bisa ditampilkan (orders. custID = customers.customerID) = kondisi dari WHERE Yan's harus dipenuhi. Jadi, data Pada kolom custID dalam tabel orders harus sama dengan data Pada kolom customerID dalam tabel customers avar masing-masing datarik bisa ditampilkan..
Hasilnya = Jadi Yang tampil adalah kolom orderID, Order Date dan custID dati tabel orders dan kolom companyNume, contact Name, city, dan Phone dati tabel astomers

### Hasil:
![[Screenshot 2024-09-19 092401.png]]
![[relasi1 2.png]]

### Code:
![[Pasted image 20240925210730.png]]
### Penjelasan:
SELECT = untuk memilih kolom mana saja yang ingin ditampilkan dan dari tabel mana kolom tersebut diambil. o. orderID = o merupakan Singkatan dari tabel orders, kolom order ID merupakan kolom dari tabel orders Yang dipilih untuk ditumpilkan. 0.
order Date = kolom order Date merupakan kolom dari tabel o Yaitu orders Yon dipilih untuk ditampilkan, 1.
custID=tolom custID merupakan kolom dari tabel o Yaitu orders yang dipilih untuk ditampilkan
C. Company Name = C merupakan singkatan dari tabel customers. kolom company Name merupakan kolom dari tabel customers Yang dipilih untuk ditam- -Pilkan.
C. Contact Name = kolom contact Name merupakan kolom dari tabel c Yaitu customer Yang dipilih untuk ditampilkan.
C. city = kolom city merupakan kolom dari tabel a Yaitu customers Yang dipilih untuk ditampilkan, 
C. Phone kolom Phone merupakan kolom dari tabel e Yaitu customers Yang dipilih untuk ditampilkan. FROM orders o,
customers c = untuk memilih dari tabel mang saja yang kolomnia ingin dipilih untuk ditampilkan. Orders adalah nama tabel yang dipilih untuk ditampilkan tapi disingkat Jadi O, asar lebih mudah dan cepat. customers adalah nama tabel yang dipilih untuk ditampilkan tapi disingkat Jadi C. - 
WHERE = kondisi yang harus dipenuhi oleh suatu kojom data avar bisa ditampilkan.
(O.CustID= costumer ID) = data Pada kolom custID dalam tabel o (orders) hans Sama dengan data Pada kolom customer ID dalam tabel c (customers). AND = untuk menyeloksi dua data atau lebih Pada Perintah WHERE. 
C.city = "London") = kondisi tambahan yang harus dipenuhi Juga. Jadi Pada kolom

### Hasil:
![[Screenshot 2024-09-19 092435.png]]
![[Screenshot 2024-09-19 092454.png]]

### Code:
![[Pasted image 20240925210801.png]]

### Penjelasan:
SELECT = untuk memilih kolom mana saja Yan's insin ditampilkan dan dari tabel mana kolom tersebut diambil. o.orderID, o. 
order Date = kolom orderID dan order Date dati tabel o (orders) dipillh untuk ditampilkan 
C.companyName, c.contactName, c. Phone = kolom-kolom companyName, Contact Name dan Phone dari tabel c(cocustomers) dipilih untuk ditampilkan. e. Last Name, e. Title = kolom Lostname dan Title dari tabel e (employees) dipilih untuk ditampilkan.
From orders o, customers c, employees e = untuk memilih dari tabel mana saja Yang kolomnya dipillh untuk ditampilkan. orders disingkat Jadi o adalah nama tabel Yang dipilih. customers disingkat Jadi C adalah nama tabel yang dipilih employees disingkat Jadi e adalah nama tabel Yang dipilih untuk ditampilkan. 1-WHERE = kondisi Yang harus dipenuhi oleh suatu data ayat bisa ditampilkan. 4. 
AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE 
(0. emPID = e.EmPID) = data Pada kolom EMPID dalam tabel o(orders) harus Sama dengan jata Pada kolom EmpID dalam tabel elemployees). Hasilnya Yang tampil adalah kolom Yang memenuhi semua kondisi dari WHERE

### Hasil:
![[Screenshot 2024-09-25 154755.png]]

### Code:
![[Pasted image 20240925210828.png]]

### Penjelasan:
SELECT=untuk memilih kolom mana saja Yang ingin ditumpilkan dan dari tabel mana kolom tersebut diambil. 
o. order ID, o. order Date = kolom orderID dan orderDate dari tabel o (orders) dipilih untuk ditampilkan. 
c.companyName, c.contuctilame, c. Phone = kolom company Name, ContactName dan Phone dari tabel c (customers) dipilih untuk ditampilkan. e. Lastname, e.Title = kolom LastName dan Title dari tabel e (employees) dipilih. untuk ditampilkan. 
From orders o, customers c, employees e = untuk memilih dari tabel mana saja Yang kolomnya dipilih untuk ditampilkan. orders atau o adalah nama tabel Yang dipilih untuk ditampilkan. customers atau c adalah nama tabel Yang dipilih untuk ditampilkan employees atau e adalah nama tabel yang dipilih untuk ditampilkan. WHERE kondisi Yang harus dipenuhi 1% suatu kolom data avar bisa ditampilkan. 
(O.CustID = c. customerID) = data Pada kolom astID dalam tabel o (orders) harus Sama denson data Pada kolom customerID davam table (customers). AND = untuk menyereksi dua data atau lebih Pada Perintah WHERE. 
(0.EmPId=e.EmPID) = data Pada kolom EmpId dalam tabel (orders) hatus sama dengan data Pada kolom EmPID dalam tabel e (employees).
AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE. Le.FirstName = "Margaret") = data Pada kolom Firstivame dalam tabel e(emploke) harus berisi data "Margaret" avar bisa tampil... Hasilnya Jadi barisan data yang sudah memenuhi kondisi WHERE akan tampil. tentama kolom firstname dari tabel employees Yang isinya "Mardanet

### Hasil:
![[Screenshot 2024-09-25 154932.png]]

### Code:
![[Pasted image 20240925210852.png]]

### Penjelasan:
SELECT untuk memilih kolom mana sata Yang ingin ditampilkan dan dari tabel mana kolom tersebut diambil. C.CustomerID, C. company Name = kolom customerID dan companyName dari tabel C (customers) dipilih untuk ditampilkan. 1-0. order ID, o, order Date = kolom orderID dan orderDate dari tabel o(orders) difilih od. ProductID, ad. Quantity, od. unit Price = kolom ProductID, Quantity dan unitPrice dari tabel od (orderdetails) dipilih uritur ditampilkan. P.ProductName = kolom ProductName merupakan kolom dari tabel P(Products) Yang dipilih untuk ditampilkan. od. Quantity AS Qty = kolom Quantity ditampilkan sebagai nama sementaranya Yaitu aty. As untuk menjubah nama suatu kolom Secara sementara. FROM customers c. orders o, orderdetails od, products p = untuk memilih dari tabel mana saja yang kolomnya dipilih untuk ditampilkan, customers atav C adalah nama tabel Yang dipilih untuk ditampilkan. Orders atau o adalah nama tabel Yang dipilih untuk ditampilkan. orderdetails atau ad adalah nama tabel yang dipilih untuk ditampilkan. Products atau P adalah nama tabel yang dipilih untuk ditampilkan. WHERE = Kondisi Yang harus dipenuhi oleh suatu kolom data avar bisa ditampilkan test) (c.customerID = 0.CustID) = data Pada kolom customerID dari tabel customers atau a harus sama dengan data Pada kolom custID dari tabel orders atau 0. 00 AND = Untuk menyeleksi dua data atau lebih Pada perintah WHERE. (der) (o. orderID = Od. orderID) = data Pada kolom order ID dari tabel orders atau o harus sama dengan data Pada kolom orderId dati tabel orderdetails atau od. AND untuk menyeleksi dua data atau lebih Pada Perintah WHERE. (Products) (P.ProductID = od. ProductID) = data Pada kolom Productio dari tabel Products atau P harus sama dengan data Pada kojom ProductID dari tabel ordendetails atau d..

### Hasil:
![[Screenshot 2024-09-25 155256.png]]

### Code:
![[Pasted image 20240925210918.png]]

### Penjelasan:
SELECT = untuk memilih kolom mana saja Yang ingin ditampilkan dan divabundkon serta dari tabel mana kolom tersebut dipilih. c. customerID, C.Company Name = kolom customerID dan company Name dari tabel c(customers) dipilih untuk ditampilkan. o.order ID AS ordID, O.order Date = kolom orderID dan order Date dari tabel o(orders) dipilih untuk ditampilkan. As merupakan Perintah untuk mengubah nama Suatu kolom Secara sementara. Dalam hal ini kolom orderID diubah namanya sementara mentid ordID. CONCAT (e-Lastrome,,, e. FirstName) AS EmployeeName = CONCAT adalah Perintah untuk menggabungkan beberapa kolom data menjadi satu kolom data. (e. Lastname, e. First Name) merupakan kolom-kaom Yang ingin digabun LastName dan First Name merupakan kolom dari tabel e(employees) Yand indin digabung. ('.') merupakan separator atau Pemisah dari kedua kolom Yang ingin divabungkan. anform As EmployeeName untuk mengubah hasil concat tadi menjadi Employeenoor (namanya) untuk sementara. od. Product ID AS ProdID, od. Quantity AS Qty = kolom ProductID dan quantity dari tabel od (orderdetails), dipilih untuk ditampilkan, kolom ProductID namanya diubah sementara Jadi ProdID. kolom Quantity namanya diubah Sementara Jadi Qty. P. ProductName = kolom ProductName dari tabel P(Products) dipilih untuk ditampilkan. From customers c. orders o, orderdetails od, Products P, employees e = untuk memitt dari tabel mana saja yang kolomnya dipilih untuk ditampilkan customers atau C adalah nama tabel Yang dipilih. orders atau o adalah nama tabel Yang dipilih order details od adalah nama tabel Yang dipilih. Products atau P adalah nama tabel yang dipilih. employees atau e adalah nama tabel Yant dipilih. WHERE kondisi Yang harus dipenuhi oleh suatu kolom data avar bisa ditampilkan (C CustomerID = o. CustID) = data Pada kolom customerID dari tabel c(customers) harus sama dengan data Pada kolom CustIO dari tabel o(orders). AND= untuk menyeleksi dua data atau lebih pada Perintah WHERE. 6.OrderID = od.orderID) = data pada kolom orderID dari tabel o(orders) harus Sama dengan data Pada kolom orderID dari tabel od (orderdetails). AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE. (P.ProductID=od. ProductID) = data Pada kolom ProductID dari tabel PCProductID) harus sama dengan data Pada kolom ProductID dari tabel od (orderdetail AND = untuk menyeleksi dua data atau lebih Pada Perintah WHERE. (e. EmPID = 0. EmPID) = data Poda kolom EmPID dari tabel e(employees) harus sama dengan data Pada kolom EmPID dati tabel o(orders). order BY o. orderID = untuk mengurut data berdasarkan kolom orderID dari tabel orders. Hasilnya kolom LastName dan FirstName dari tabel e(employees) digabung dengan Concat dan hasil kolomnya namanya diubah sementara Jadi EmployeeName

### Hasil:
![[Screenshot 2024-09-25 180356.png]]

### Code:
![[Pasted image 20240925211824.png]]

### Penjelasan:
CREATE VIEW Custorder Emp = merupakan tabel virtual Yang dibuat dendan Nama custorderEmp AS SELECT = untuk memilih kolom-kolom mana Sava Yang ingin dipilih untuk dimasukkan ke tabel virtual. C. CustomerID, c.companyName, c.contactName = kolom customerID, company Name dan contactinome dari tabel c(customers) dipilih untuk dimasukkan ke dalam tabel virtual. 0.order ID, o. order Date = kolom order ID dan orderlate dari tabel (orders) dipilih untuk dimasukkan ke dalam tabel virtual. e-EmPID, e.Lastname, e. FirstName = kolom EmPID, LastName, dan firstName.dati tabel e(employees) dipilih untuk dimasukkan ke dalam tabel virtual. FROM customers c, orders o, employees e = untuk memilih dari tabel mana Sara Yang kolomnya dipilih untuk dimasukkan. customers, orders dan employees merupakan nama tabel yang kolomnya dipilih. WHERE kondisi yang harus dipenuhi oleh suatu data adar bisa dimasukkan ke dalam tabel virtual. (c.customerID = a custID) = data Pada kolom customerID dari tabel c(costumers) harus sama dengan data pada kolom custID dari tabel (orders) adar bisa dimasukkan. AND = untuk menyeleksi dua data atau lebih Pada WHERE. (O. EMPID = e.EmPID) = data Poda kolom EmPID dari tabel ocorders) harus Sama dengan data Pada kolom EmPID dari tabel e(employees) avar bisa dimasukkan. Hasilnya sebuah Tabel virtual telah dibuat dengan nama custorder Emi Yang berisi kolom kolom dari 3 Tabel customers, orders, employees dan telah memenuhi semua kondisi.

### Hasil:
![[Screenshot 2024-09-25 185555 1.png]]
![[Screenshot 2024-09-25 185606.png]]
![[Screenshot 2024-09-25 185624.png]]

### Code:
![[Pasted image 20240925211859.png]]

### Penjelasan:
CREATE VIEW od Products = untuk membuat tabel virtual dengan nama od products. AS SELECT = untuk memilih kolom-kolom mana saja Yand ingin dipilih untuk dimasukkan ke tabel virtual. od.orderID, od. ProductID, od. unitPrice, od. quantity = kolom order ID, ProductID, unit Price dan Quantity dari tabel od (orderdetails) dipilih untuk dimasukkan. P. ProductName = kolom Productivame dari tabel P(Products) dipilih untuk dimasukkan. - From orderdetails od, Products P = untuk memilih dari tabel mana saja yang kolomnya dipilih untuk dimasukkan. Orderdetails dan Products adalah nama tabel Yang dipilih. WHERE kondisi Yang harus dipenuhi oleh suatu data agar bisa dimasukkan ke dalam tabel virtual.-(P.ProductID = od. ProductID) = data Pada kojom productID dari tabel P(Products) hans sama dengan kolom ProductID dari tabel od (orderdetails). avar bisa dimasuktin Hasilnya Tabel virtual yang bernama odproducts yang terbuat dari kolom dalam

### Hasil:
![[Screenshot 2024-09-25 185637.png]]
![[Screenshot 2024-09-25 185646.png]]
![[Screenshot 2024-09-25 185657.png]]

### Code:
![[Pasted image 20240925212013.png]]
### Penjelasan:
SELECT untuk memilih Kolom mana saja Yang ingin ditampilkan dan dihitung. c. customerID, C. company Name = kolom customerID dan company Name dari tabel c(customers) dipilih untuk ditampilkan. 0. orderID = kolom orderID dari tabel o (orders) dipilih untuk ditampilkan. Od. Product ID, od.unitPrice, od. quantity, od. Discount = kolom ProductID, unit Price, Quanti dan Discount dari tabel Od (orderdetails) dipilih untuk ditampilkan dan dibulatkan. ROUND (od unitprice, 2) = untuk membulatkan bilangan dari kojom unitPrice Sampai Jumlah digit tertentu. sesuai dengan pilihan yang dibuat Yaitu 2. ROUND (CC1-od. Discount) ad.unitPrice od. Quantity), 2) AS Jumlah = untuk membulatkan bilangan dari kolom hasil dari (1 dikurang kolom discount lalu dikali @unitprice dan kali Quantity) sampai jumlah digit Yaitu 2... As Jumlah untuk menJubah kolom hasil tersebut nama sementaranya Jodi Jumlad From customers c, orders o, orderdetails od untuk memilih dari tabel mona Sara yang kolamnya dipilih untuk ditampilkan dan dibulatkan. customery, orders, orderdetails merupakan nama-nama tabel yang dipilih. WHERE kondisi yang harus dipenuhi oleh suatu data agar bisa ditampilkan. (C. customer ID = o. cust ID) = data Pada kolom CustomerID M. dari tabel ccoustomers) harus sama dengan data Poda kolom custID dari tabel o(orders). AND = untuk menyeleksi dua data atau lebih Pada kondisi WHERE. (O.order ID = od-order ID) = data Pada kolom orderID dari tabel o(orders) hotus Sama dengan data Pada kolom OrderID dari tabel od (orderdetails). ORDER BY c.customerID = untuk mengurut data berdasarkan kolom customers dari tabel c(customers). Hasil akan tampil hasil Pembulatan dari kotom-kolom Yang telah memenuhi kondisi dari WHERE
### Hasil:
![[Pasted image 20240925212049.png]]

### Code:
![[Pasted image 20240925212117.png]]

### Penjelasan:
SELECT = untuk memilih kolom mana saja yang ingin ditampilkan dan dibulatk C.CustomerID, 
C.Company Name = kolom customerID dan companyName dati tabel (customers) dipilih untuk ditampilkan. 
ROUND (Sum((1-od.discount) od. unit Price od. quantity), 2) AS Total Jumlah = untuk membulatkan hasil sum dari ((1 dikurang kolom Discount) dikali unitPrice Kali Quantity) sampai 2 digit. 200 Dan nama kolom hasilnya diubah sementara Jadi TotalJuinlah.
FROM customers c, orders o, orderdetails od = untuk memilih dari tabel mana Saja Yang kolomnya dipilih untuk ditampilkan dan dibulatkan. customers, Orders dan orderdetails, adalah nama, tabel yang dipilih.
WHERE = kondisi Yand harus dipenuhi oleh suatu data alar bisa ditampilkan. 
(c.customerID=0.custID) = data Pada kolom customerID dati tabel c(customers) harus sama dengan data Pada kolom CustID dari tabel o (orders).
AND = untuk menyeleksi dua data atau lebih lada kondisi WHERE. 
(o.orderID) = od.orderID) = data Pada kolom orderID dari tabel o (orders). horus Sama dengan data Pada kolom orderID dari tabel od(orderdetails). 
GROUP BY c.customerID, C.CompanyName = untuk mengelompokkan data sesuai dengan kolom customerID dan company Name dari tabel c(customers). ORDER BY c.customerID = untuk mengurut data berdasarkan kolom customerID dari tabel c(customers) 
Hasilnya = tadi, Kolom Yang dikelompokkan adalah customerID dan company Name dan tampilannya diurutkan berdasarkan kolom customerID.

### Hasil:
![[Screenshot 2024-09-25 202359.png]]
