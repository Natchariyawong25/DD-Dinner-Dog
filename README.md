# DD-Dinner-Dog
โปรเจ็คนี้เป็นส่วนหนึ่งของรายวิชา __CPE327 Software Engineering__ 
### Developer Team
Member in team : 'Cap Moo Developer Team' :dog:
> * :woman: Ms.Nasiree Suchartsunthorn 60070501095
> * :woman: Ms.Natchariya Wongamnuayporn 61070507204
> * :man: Mr.Natchapol Patamawisut 61070507205
> * :woman: Ms.Thanaporn Cheentada 61070507209
> * :man: Ms.Rungwigrai Payakkanuwat 61070507219

# Project Description 
:guide_dog: DD Dinner Dog เป็นระบบหาเพื่อนและหาคู่ให้กับสุนัข โดย DD Dinner Dog ถูกสร้างในรูปแบบ
Web Application ซึ่งทุกคนที่เป็นเจ้าของสุนัขและเลี้ยงสุนัขสามารถเข้าไปใช้งานได้ง่ายและสะดวก เจ้าของ
สุนัขที่ต้องการให้สุนัขมีเพื่อนเล่น และต้องการให้สุนัขได้สนุกสนานกับสุนัขตัวอื่น หรือแม้กระทั่งต้องการให้
สุนัขของตนมีคู่และผสมพันธุ์ในช่วงเป็นสัตว์ สามารถหาเพื่อนให้สุนัขได้ในทั้งระยะใกล้และไกลขึ้นอยู่กับการ
กำหนดระยะทางในระบบ  

#### Proposal Project
> DD Dinner Dog เป็นแอพพลิเคชั่นที่เหมาะสำหรับคนเลี้ยงสุนัข โดยมีขอบเขตของการทำงาน 
> และ วัตถุประสงค์ดังนี้ 
> 1. เพื่อตอบสนองคนเลี้ยงสุนัขที่มีความกังวลว่าสุนัขของตนจะเหงาและอยากมีเพื่อน
> 2. เพื่อเป็นตัวกลางในการจับคู่ให้สุนัข
> 3. ผู้ใช้งานสามารถกำหนดลักษณะของสุนัขที่อยากเลือกได้

# Product Perspective
:wolf: DD Dinner Dog เป็น Application ที่หาคู่ให้กับสุนัขจะมีผู้ใช้อยู่ 2 ประเภทคือ USER ที่เป็นเจ้าของสุนัข 
เเละ สัตวแพทย์ที่จะให้คำปรึกษากับเจ้าของสุนัข ซึ่งเจ้าของสุนัขสามารถหาเพื่อนหรือหาคู่ให้กับสุนัขได้ 

:dog: User จะสามารถเลือกตำเเหน่งที่อยู่บริเวณใกล้เคียงกันได้ หรือ พันธุ์สุนัขที่สนใจได้ตามใจเจ้าของสุนัข โดยการหาเพื่อนและหาคู่ให้สุนัขบนแอพพลิเคชั่นนี้มีระบบการทำงาน คือ 
> 1. ผู้ใช้งานสามารถปัดหน้าจอ like หรือ nope สุนัขที่ระบบสุ่มมาให้ในระยะทางที่กำหนด หรือจะ ปัดเเบบ super like ได้ 
> 2. ผู้ใช้สามารถเลือกที่จะเป็นสมาชิก premium ได้ โดยสมาชิก premium สามารถดูได้ว่าใครปัดเลือกและไม่เลือกสุนัขของเรา รวมถึงสามารถทำการสุ่มสุนัขใหม่
> 3. เมื่อผู้ใช้งานปัดเลือกตรงกัน ก็จะสามารถใช้งานช่องแชทเพื่อติดต่อแลกเปลี่ยนข้อมูลสุนัขผ่านทางข้อความ โทรด้วยเสียง และ วิดีโอคอล ก่อนการนำสุนัขมานัดเจอกันได้ 
> 4. เจ้าของสุนัขสามารถรายงานเจ้าของสุนัขคนอื่นที่ก่อกวนได้ 
> 5. เจ้าของสุนัขสามารถเเชท เพื่อติดต่อกับสัตวเเพทย์ได้ตลอดเวลา 

:dog::heart::dog2: 

# Installation and Setup Instructions
Clone down this repository. You will need `node` and `npm` installed globally on your machine.  
> :exclamation::exclamation: Please install only first time (install npm เเละ node.js ครั้งเเรกเท่านั้น) :exclamation::exclamation:

Installation:
### backend 
Install __npm__  
`$ npm install `

Install __sequelize-cli__ เพื่อการเชื่อมต่อกับ database   
`$ npm install -g sequelize-cli`

Create Database  
`$ sequelize-cli db:create`  

To Run Server:  
`$ node index.js`

***

### frontend
Install __npm__  
`$ npm install`  

To Start Server :  
`$ npm start`

To Visit App :  
`localhost:3000/...` 

# Running the tests 
เวลา run program ต้อง run ทั้ง 2 ส่วน backend เเละ frontend พร้อมกัน
###  backend
To Run Server:  
`$ node index.js`

***

###  frontend
To Start Server :  
`$ npm start`

To Visit App :  
`localhost:3000/...` 
  
# Deployment  
Tools : 
- [X] Azure PostgreSQL 
- [X] Azure app service 

:globe_with_meridians: :desktop_computer: Web Application Link : `https://banknatchapol.github.io/SEFE` :wolf: 
> :exclamation::exclamation: ตอนนี้ DD Dinner Dog ได้ปิดกิจการลงเเล้ว สามารติดตาม Product ใหม่ ๆ ได้เร็ว ๆ นี้ :exclamation::exclamation:
  
# Built With 
- [X] Django ในการสร้าง Database ใน PgAdmin  
- [X] React ทำ frontend 
- [X] Robot Framework ทำ Automating testing
- [X] Azure app service ในการ Deploy ขึ้น cloud server  
  
# Versioning 
> :dog: DD-Dinner-Dog base on version 1.0.0 in 11/12/2563 
  

