[DWDM21](https://github.com/moneypitak/DWDM21)

#ชื่อกลุ่ม : วากาเมะ

#สมาชิกกลุ่มประกอบไปด้วย

623020528-4	นายปริชญา หงส์ทองคำ  SC-SI

623020532-3	นายมันนี่ พิทักษ์	 SC-SI

623020541-2	นายสิทธัตกะ จรัสแสง	 SC-SI

623021045-9	นายชณะชัย อิสระกูล	 SC-SI

623021048-3	นางสาวทอฝัน พงษ์พิเดช	 SC-SI

#สารบัญเนื้อหา

* บทที่1 [Introduction](https://github.com/moneypitak/DWDM21/blob/main/HW1.pdf)
  * Data Warehouse คืออะไร
  * Data Mining คืออะไรส่วนต่างๆของ Data 
* บทที่ 2 [Getting to Know Your Data](https://github.com/moneypitak/DWDM21/blob/main/%E0%B8%AA%E0%B8%A3%E0%B8%B8%E0%B8%9B%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1%E0%B8%A3%E0%B8%B9%E0%B9%89-2.1.pdf)
  * ขนาดของข้อมูล
  * ชนิดของข้อมูล
  * คุณสมบัติ
  * ลักษณะสำคัญของข้อมูล
  * ข้อมูลที่เป็นตัวเลข
* บทที่ 3 Data [Preprocessing](https://github.com/moneypitak/DWDM21/blob/main/Chap%203.pdf)
  * Data Cleaning คืออะไร
  * Data Integration คืออะไร
  * Data Reduction and Tranformation คืออะไร
  * Dimensionality Reduction คืออะไร
* บทที่ 4 Data [Warehousing and On-line Anaalytical Processing](https://github.com/moneypitak/DWDM21/blob/main/Chap%204.pdf)
  * Data Warehousing คืออะไร
*OLTP & OLAP
  * ทำไมถึงต้องแยก Data Warehousing
  * โมเดล ทั้ง 3 แบบของ Data Warehousing
  * Meta Data
  * การสร้างแบบจำลองแนวคิดของ Data Warehousing ว่ามีแบบไหนบ้าง แต่ละแบบเป็นอย่างไร
  * ลักษณะข้อมูลในหลายมิติเป็นอย่างไร
  * การใช้ data warehouse ทั้งหมด 3 ประเภท
* บทที่ 5 [Data Cube Technology](https://github.com/moneypitak/DWDM21/blob/main/Chap%205.pdf)
  * ความหมาย
  * Besic Concepts
  * Efficient Pattern Mining Methods
* บทที่ 6 [Mining Frequent Patterns, Association and Correlations:Basic Concepts and Methods]
  * Basic Concepts
  * Patterns หมายถึงอะไร ทำไมมันถึงสำคัญ
  * ตัวอย่าง K-Itemsets
  * การหาค่าต่าง ๆ ของ K-Itemsets
  * The Apriori Algorihm
  * ตัวอย่าง The Apriori Algorihm
* บทที่ 7 [Advanced Frequent Pattern Minning]
* บทที่ 8 [Classification:Basic Concepts]
  * ลักษณะการสร้างโมเดลแบบมีผู้สอน
  * ลักษณะการสร้างโมเดลแบบไม่มีผู้สอน
  * การทำนายปัญหา ระหว่าง Classification กับ การใช้ทำนายตัวเลข
  * การสร้างโมเดลแบบจำลอง
  * Decision Tree ต้นไม้ตัดสินใจ
  * หลักการสร้างตาราง
  * ตัวอย่างในการหาค่าต่าง ๆ
  * Naive Bayes Classfier
  * Linear Regreesion
 ## ภาคปฏิบัติ (Google Colab)
* บทที่ 2 [Data101(Chapter2)](https://github.com/moneypitak/DWDM21/blob/main/Data101(Chapter2).ipynb)
  * ไฟล์ .csv (cav คือ comma separated values) เป็นไฟล์หลักที่เราได้ใช้เรียนกันในวิชานี้
  * Basic Python
  * Casting int () float () str ()
  * Data Structure
  * วิธีสร้าง list ว่าง
  * เติมค่าลงไปใน list ใช้ (.append)
  * การชี้ค่าใน list (indexing)
  * list slicing การตัดลิสต์
  * จุดเริ่มต้น:จุดสุดท้าย :step
  * list + list
  * format string
  * Loop
  * Nested loop ลูบซ้อนลูบ
  * Condition (if statement)
  * Quiz 1 หา max
  * การบ้านที่ 3 หาเกรด
  * Function*
  * ลักณะตัวอย่าง (ไม่มี input)
  * ลักษณะตัวอย่างที่ (ไม่มี output)
  * ลักษณะตัวอย่าง (ไม่มี input และ output)
  * ลักษณะของ input (พารามิเตอร์)
  * Quiz 2
* บทที่ 2 [Data102_(Chapter2)](https://github.com/moneypitak/DWDM21/blob/main/Data102(Chapter2).ipynb)
  * Nan = not a Number (ช่องว่าง)
  * คำสั่ง .head() .tail()
  * Box plot
  * Time Series Plot
* บทที่ 3 [Data_Preprocessing_(Chapter_3)](https://github.com/moneypitak/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb)
  * Meta Data (Data ที่ใช้อธิบาย Data)
  * ชี้ข้อมูลในตาราง
  * ชี้แบบ .iloc[] (มองข้อมูลแบบ matrix)
  * Missing Values
  * Handling Misiing Value 1 (ลบค่า missing ออกไป)
  * Quiz 3 ให้หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
  * Handling Misiing Value 1.5 (ลบค่า missing เฉพาะในคอลัมม์ที่เราสนใจออกไป)
  * Quiz 3.1 ให้หาว่าการทำ dropna() แบบเลือก drop เฉพาะคอลลัมม์ที่เราสนใจ (age) ทำให้ข้อมูลหายไปกี่ %
  * Handling Misiing Value 2 (แทนค่าด้วย class ใหม่ (unknown))
  * Handling Misiing Value 3 (แทนค่าด้วย class ใหม่ (ค่าที่เหมาะสม)
  * Handling Misiing Value 4 (แทนค่าด้วย ค่ากลาง)
  * Handling Misiing Value 5 (แทนค่าด้วย ค่ากลางของ sample ใน class เดียวกัน)
  * Select data by values [PD] คำสั่งแพนด้า
  * ขั้นตอนสร้าง list ของ boolen
  * สร้าง list ของ boolen
  * Quiz 4 + การบ้าน
  * ต่อตารางแนวแกน Y [PD]
  * การเรียงข้อมูล [PD]
  * Outlier
  * Quiz 5
  * Quiz กลุ่ม
  * การรวมตาราง (ต่อตารางในแนวแกน x) Data Integration
  * รวม 2 ตาราง (.merge())
  * เอาเฉพาะคอลลัมม์ที่เราต้องการมาแปะ (.map())
  * Project กลุ่ม
  * Group by (pandas)
  * การบ้าน + Quiz
  * save ตารางเอาไปใช้ที่อื่น
  * การสร้างตาราง
* บทที่ 6 [Chapter_6_Association_Rules](https://github.com/moneypitak/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
  * ลบ records ที่ถูก cancel ออกไป
  * การบ้านครั้งที่ 13 วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
  * เตรียม Data สำหรับ (Fequence Pattern) Association Rules
  * Apriori
  * Quiz 7
* บทที่ 7 [Chapter7_Classification_(Decision_Tree)](https://github.com/moneypitak/DWDM21/blob/main/Chapter_7_Classification_(Decision_Tree).ipynb)
  * Load Data
  * train (ฝึกสอนตัวแบบ)
  * plot tree
  * Evaluation
  * Random
  * Advanced Tree
  * TEST
  * Start here
  * Train - Test
  * Train - Validation
  * การบ้านครั้งที่ 16
* บทที่ 7 [Chap7_Classification_(KNN_NN)](https://github.com/moneypitak/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
  * Load data
  * Split Data
  * Train Model
  * knn1
  * knn2
  * knn3
  * Retrain & Evaluate
  * Neural Network
  * Train - Test
  * ANN 2
  * ANN 3
* บทที่ 7 [Chapter_7_Classification_(Evaluation)](https://github.com/moneypitak/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
  * Load data
  * แบ่ง data
  * สร้าง model ทำนาย
  * Train - Test
  * Evalution
* บทที่ 8 [Chap_8_Clustering](https://github.com/moneypitak/DWDM21/blob/main/Chap8Clustering.ipynb)
  * K-means
  * Generat Data
  * Explole data
  * Clustering
  * นับจำนวนสี
  * จัดกลุ่มสีให้เหลือ 16 สี
  * ใช้ centroid เป็นตัวแทนของสี
  * แทนสีคืนลงไป
* Data Visualization [Data_Visualization](https://github.com/moneypitak/DWDM21/blob/main/Data_Visualization.ipynb)
  * Visuliazation
  * Scatter plot
  * Plot
  * Quizกลุ่ม
  * Bar chart
  * Stacked Barchart
  * Histrogram
* Distance Numpy [Distance_Numpy](https://github.com/moneypitak/DWDM21/blob/main/Distance_Numpy.ipynb)
  * Numpy Array
  * สร้าง numpy array
  * สร้าง matrix เริ่มต้น (zeros,ones)
  * สร้าง matrix random ค่าเเบบมั่ว ๆ
  * matrix transpose
  * Indexing & Slicing
  * Useful Function
  * วนลูปเอง
  * Summation
  * Quiz กลุ่ม
  * Distance Matrix
  * Euclidean Distance (L2-norm)
  * คำนวณระยะห่าง dist(P1,P2)
  * คำนวณระยะห่าง dist(P2,P4)
  * Distance function
  * Quiz 6
  * การบ้านครั้งที่ 11
  * Distance of Binary Value
* สอบมิดเทอม [Mini_Exam](https://github.com/moneypitak/DWDM21/blob/main/MiniExam.ipynb)
* [FinalProject]
  * การนำเข้าข้อมูล , แหล่งที่มาข้อมูล
  * ดูว่าข้อมูลมี data missing
  * สรุปข้อมูลเป็นรายคอลลัมม์ว่ามี missing
  * Drop missing value
  * ตรวสจสอบเมื่อลบออกไปแล้วตรวจสอบว่ายังไม่ข้อมูลที่หายไปหรือไม่
  * Percent of missing data from dropna
  * รวมตาราง
  * ตรวจสอบดูการลบข้อมูลที่ซ้ำกัน
  * Data Mining
  * สร้างตารางที่ใช้ในการดู challenge
  * สร้างตารางที่ค่าเฉลี่ยนประชากรมากกว่า 40
  * แปลงให้ข้อมูลอยู่ในรูปแบบเป็น transaction
  * apyori
  * ขั้นตอนติดตั้ง apyori
  * เป็นการเรียกใช้ฟังก์ชัน apriori
  * ผลลัพธ์ที่ได้จากการทำ Associantion ซึ่งรายละเอียดจะอยู่ที่ summary
  * SUMMARY
  * Plot กราฟ เพื่อดุค่าของข้อมูลผลเฉลี่ยในแต่ละจังหวัด
  * Classification
  * ทำการดูว่าประเภทของระบบใดในแต่ละภาคมีการใช้มากสุด
  * กำหนดค่า X และ Y
  * Decision Tree
  * KNN
  * Neural Network
  * วาดกราฟต้นไม้
  * Visulization
* [Slide Project]
