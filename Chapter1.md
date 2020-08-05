# บทที่ 1 Introduction
### ทำไม Data Mining ถึงมีความสำคัญ
#### Data is a new oil เปรียบได้ว่า ใครมีน้ำมันเยอะก้รวย เหมือนข้อมูล ใครมีข้อมูลเอะก้รวย
#### Internet of Things (IOT) คือ "อินเตอร์เน็ตในทุกสิ่ง"
#### Data mining คือ การทำเหมืองข้อมูล ทำเพื่อให้ได้ความรู้ออกมา
#### Data Base จุดมุ่งหมายคือการเก็บข้อมูล ให้ไม่มีการซ้ำซ้อน ไม่หายไป
#### Query คือ การค้นคืนข้อมูล
#### Mining การทำเหมือง
#### Data Base ข้อดีคือ เก็บข้อมูลแล้วข้อมูลไม่หาย
#### หลังจากมี Data แล้ว ถัดมา ทำ Data cleaning ( เพราะอาจมีการกรอกข้อมูลผิด) 
#### Noisie เช่นการกรอกผิดช่อง
#### Data integration คือ การรวมข้อมูลโดยการเอา Data จากหลายๆ แหล่งมารวมกัน เช่น การใช้เลขบัตรประชาชนในการเชื่อมข้อมูลเข้าหากัน (จัดให้ข้อมูลเป็น ฟอร์แมทเดียวกัน)
#### Data Warehouse ที่เก็บข้อมูลที่เอาไว้ตอบโจทย์ทางธุรกิจโจทย์นึง และโชว์ข้อมูลในมุมมองต่างๆ
#### Data mining คือการสกัดความรู้ที่มีอยู่ในองค์ข้อมูล ดูจากพทเทิร์นที่เกิดซ้ำในองค์ข้อมูล เช่นข้อมูลการวิเคราะห์การซื้อของในตระกร้า ของซุปเปอร์มาร์เก็ต 
#### Data Base – clean ทำความสะอาดข้อมูล – intregreat รวมข้อมูล  – tramsform แปลงข้อมูล เช่น ชาย หญิง เป็น 0 1 – load  - refresh รันใหม่หมดเลย – Data Warehouse – client ผู้ใช้งาน(ลูกค้า)
#### นำเสนอ อาจเป็นในรูปแบบกราฟ ข้อมูลเกี่ยวกับการเรียน 
#### หลังจากนั้นก้จะกลายเป็นองค์ความรู้
#### ในมุมมองขององค์กร แบ่งหน้าที่งานออกเป็นหลายๆหน่วย 
#### DBA คนที่อยู่ใกล้ชิดกับ DATA มากที่สุด (คนที่สร้างฐานข้อมูล)
#### Data Analysis - Data Mining 
#### Business Analysis - Data Presentation
#### End User - Decision Making 
#### Patern discovery หาแพทเทิร์นที่อยู่ใน Data 
#### Classification คือ ทำนายโดยที่เรารู้ผลในข้อมูลที่เรามีอยู่แล้ว
#### Clustering คือ เราจะจัดกลุ่มที่มีลักษณะเหมือนกันให้อยู่ด้วยกันโดยที่ไม่รู้ว่าชื่อกลุ่มคืออะไร 
#### Pos Processing - Patern Evaluation การประมาลผลว่าแพทเทิร์นที่เราได้ออกมามีความน่าเชื่อถือมากน้อยแค่ไหน 
#### Patern Selection หลักการในการเลือกแพทเทิร์น
#### Patern Interpre ... การแปรผลของแพทเทิร์นนั้น
#### การประมาลผลข้อมูล
#### Data Streams คือ ข้อมูลที่มาเรื่อยๆ เก็บเรื่อยๆ เช่น sensor 
#### Times series Data คือ Data ที่มีเวลาเข้ามาเกี่ยวข้อง เช่น หุ้น 
#### Structure Data Data ในรูปแบบ กราฟ เช่น การมีเพื่อนใน Facebook 
#### Spacial Data คือ Data เชิงพื้นที่ เช่น แผนที่ รูปภาพ \\\  Speciotemporal Data คือ Data ที่เกี่ยวกับทั้งเชิงพื้นที่ และ เวลา เช่น วิดีโอ 
#### Multimedia Data คือ ข้อมูลของ วิดีโอยูทูป ไลฟ์ ต่างๆ 
#### Text Data คือ เป็นข้อมูลที่เป็นข้อความ เช่น คำว่าสถิติ มีคำอธิบายอะไรบ้าง 
####  Web 
#### Data Cube การมองข้อมูลที่มองในมุมมองต่างๆได้
#### Patern discovery รูปแบบที่เกิดขึ้นบ่อยๆ
#### Classification รู้อยู่แล้วว่าอยู่กลุ่มไหนแล้วเราจะแยกว่า Data ว่ากลุ่มนี้ต้องจัดกลุ่มอย่างไร
#### Clustering จัดกลุ่มตามความสัมพันธ์ใน Data 
#### Outlier หา Data ที่ไม่เกี่ยวกับกลุ่มข้อมูล อาจเกิดจากการกรอกข้อมูลผิด 
![picture](https://76a4dad0-a-d64c9f8f-s-sites.googlegroups.com/a/bumail.net/data-mining/khwam-hmay/etl.jpg?attachauth=ANoY7cpKlIsiM3uIhJ8fGxVEqqSMPa_9t-tnPxt-h0o2PXu3U4LstioM1DzWUQ3T1TU3zFDmzyIBXyqiWwkFkJV12SPa_uJs4Wst4xWH06bezxYhb3VqhkXQx-egOxQJAYq-ZupcyHq0hI6pwxSjzrAoLEH02wkHvx3TzGmJhT55VVj6QX0CeeGI5s7bojV7vR2mMW31xq9OPG8s125lw_iQ_Fm0q52YyQ%3D%3D&attredirects=0)

