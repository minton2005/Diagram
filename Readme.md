Form1: คลาสหลักของฟอร์ม  ประกอบด้วย INStockClass และ StockUpClass เป็นสมาชิก และใช้คลาส Convert, BuyDrink1, BuyDrink2, BlackCoffee, Mocha, Latte, และ Chocolate.  มีเมธอดที่จัดการเหตุการณ์คลิกปุ่มต่างๆ (button1_Click, button2_Click, button3_Click, button4_Click, BStockUp_Click).

INStockClass: คลาสที่ใช้เก็บปริมาณส่วนผสมที่เพิ่มเข้ามา มี attributes INwater, INCof, INMilk, และ INChocolate.

StockUpClass: คลาสที่ใช้ในการจัดการสต็อก มีเมธอด StockUp1 และ properties สำหรับเก็บปริมาณสต็อกที่เหลือ StockWater, StockCof, StockMilk, และ StockChocolate.

Convert:  คลาสที่ใช้ในการแปลงค่า มีเมธอด convert.  (จากโค้ดที่ให้มา เราไม่เห็นรายละเอียดของคลาสนี้)

BuyDrink1: คลาสที่ใช้ในการคำนวณการซื้อเครื่องดื่มชนิดที่ 1 มีเมธอด BuyDrink และ properties สำหรับเก็บผลลัพธ์ OutWater และ OutCof.

BuyDrink2: คลาสที่ใช้ในการคำนวณการซื้อเครื่องดื่มชนิดที่ 2 มีเมธอด BuyDrink2 และ properties สำหรับเก็บผลลัพธ์ OutWater, OutCof, OutChocolate และ OutMike (ซึ่งอาจจะเป็น typo และควรเป็น OutMilk).

BlackCoffee, Mocha, Latte, Chocolate: คลาสที่แสดงถึงเครื่องดื่มแต่ละชนิด มี attributes ที่เก็บปริมาณส่วนผสมที่จำเป็น.

ความสัมพันธ์:

Form1 มีความสัมพันธ์แบบ "has a" (เป็นเจ้าของ) กับ INStockClass, StockUpClass, BlackCoffee, Mocha, Latte, และ Chocolate.
Form1 มีความสัมพันธ์แบบ "uses" (ใช้) กับ Convert, BuyDrink1, และ BuyDrink2.