Least Privilege เป็นกลยุทธ์ความปลอดภัยที่ประยุกต์ใช้ได้หลากหลาย โดยอาศัยการจำกัดการอนุญาตเพื่อสร้างประสิทธิภาพสูงสุดให้แต่ละกิจกรรม
ก่อนหน้านี้ในการพูดคุยกับฝ่ายวิเคราะห์การตลาดที่ ESET Mexico กับนาย Juan Carlos Fernández เราพูดคุยเกี่ยวกับเหตุการณ์เมื่อตอนเขายังเป็นนักศึกษามหาวิทยาลัย มีบริษัทปลอมแห่งหนึ่งเปิดรับสมัครนักศึกษา เพื่อหลอกเอาข้อมูลจาก résumés (ประวัติย่อ) ที่นักศึกษาส่งเข้ามา
จริงๆแล้วไม่มีนักศึกษาคนไหนถูกว่าจ้าง และข้อมูลที่ส่งมาให้กับทางบริษัทก็เป็นการส่งโดยสมัครใจ ภายใน résumés มักมีข้อมูลส่วนตัวเขียนอยู่ซึ่งมากพอที่จะไปถึงตัวเจ้าของได้ อย่าง รูปภาพ ที่อยู่ รายละเอียดติดต่อ บัญชีโซเชี่ยลมีเดีย และข้อมูลอื่นๆ
แต่เราก็ปฏิเสธไม่ได้ว่าข้อมูลเหล่านี้ก็จำเป็นต่อผู้ว่าจ้างเช่นเดียวกัน นี่เป็นจุดเริ่มต้นของแนวคิดที่ว่า หากเราสามารถจำกัดการเข้าถึงข้อมูลที่จำเป็นได้และดีแค่ไหน
Least Privilege: ทฤษฎีความปลอดภัยที่ดี
ในด้าน Cybersecurity ทฤษฎี Least Privilege หมายถึงการอนุญาตให้ผู้ใช้เข้าระบบหรือเข้าถึงข้อมูลแตกต่างกันตามภาระหน้าที่ความรับผิดชอบ โดยการอนุญาตขึ้นอยู่กับกิจกรรมที่พวกเขาทำ เพื่อความปลอดภัยของข้อมูล ระบบ และความเป็นส่วนตัวที่ดีขึ้น
ความจำเป็นการเข้าถึงข้อมูลเพื่อทำกิจกรรมต่างๆ เป็นพื้นฐานของการอนุญาต อย่างเช่น การเข้าถึง การใช้งาน และการดัดแปลงข้อมูล ทั้งหมดนี้จะต้องไม่รุกรานความปลอดภัยและความเป็นส่วนตัว
Least Privilege สามารถใช้กับโซเชี่ยลมีเดียได้หรือไม่?
เหตุการณ์ที่ Facebook นำข้อมูลลูกค้าไปแบ่งปันกับองค์กรอื่นเป็นกรณีศึกษาของการดูแลข้อมูลและความรับผิดชอบขององค์กร
ความเป็นส่วนตัว (Privacy) มีการเปลี่ยนแปลงตลอดเวลาอย่างหลีกเลี่ยงไม่ได้ เนื่องจากเราอยู่ในยุคดิจิตอลที่ๆกฎหมายใหม่ๆจะมอบสิทธิให้ผู้ใช้สามารถควบคุมข้อมูลของตัวเองได้ดียิ่งขึ้น
ในโลกของโซเชี่ยลมีเดียการปกป้องข้อมูลขั้นพื้นฐานเลยก็คือ ไม่แบ่งปันข้อมูลส่วนตัวของตัวเองให้กับผู้อื่น โดยเฉพาะคนที่ไม่รู้จักหรือคนที่ใช้ตัวตนปลอม
โซเชี่ยลมีทางเลือกให้เราสามารถตั้งค่าความเป็นส่วนตัวและความปลอดภัย อย่างเช่นการกำหนดคนที่สามารถเห็นโพสต์ของเรา แต่เราก็ไม่ได้หมายความว่าเราต้องอยู่อย่างหวาดระแวง แค่ระมัดระวังก็พอ
Least Privilege บนอุปกรณ์พกพา
ในอุปกรณ์พกพาอย่างโทรศัพท์มือถือและแท็บเล็ต เวลาที่เราติดตั้งแอปพลิเคชั่นจะมีหน้าต่าง Permission (การอนุญาต) ให้เราเห็นอยู่บ่อยๆ นี่เป็นตัวอย่างที่ดีสำหรับทฤษฎี Least Privilege ยกตัวอย่างแอปพลิเคชั่นถ่ายภาพ ในหน้าต่าง Permission แอปพลิเคชั่นจะขออนุญาตใช้งานกล้อง แต่ในหลายครั้งบางแอปฯกลับข้ออนุญาตเข้าถึงข้อมูลอื่นๆอย่าง รายชื่อผู้ติดต่อ (Contact) หรือการโทรเข้าโทรออกและข้อความ (Call & SMS) ซึ่งไม่จำเป็น
เพราะเป็นไปได้ที่แอปฯเหล่านั้นจะมีเจตนาอื่นแฝง เช่น การลักลอบขโมยข้อมูลธุรกรรม (Banking Trojan) ที่มักพบในแอปพลิเคชั่นปลอมต่างๆ ดังนั้นเราจึงขอแนะนำให้ผู้ใช้อ่าน Permission ทุกครั้งก่อนติดตั้งแอปพลิเคชั่นบนสมาร์ทโฟนและแท็
