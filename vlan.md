# Virtual Local Area Networks (VLANs)

[Profile](phatsagon.github.io/README)

- **CISSP Glossary**
  - Allow network administrators to use switches to create software-based LAN segments that can be defined based on factors other than physical location.

  - **ChatGPT**
    - ช่วยให้ผู้ดูแลระบบเครือข่ายสามารถใช้สวิตช์ในการสร้าง LAN เชิงตรรกะที่กำหนดโดยซอฟต์แวร์ ซึ่งสามารถกำหนดได้จากปัจจัยอื่น ๆ นอกเหนือจากตำแหน่งทางกายภาพ

  - **Gemini**
    - อนุญาตให้อดมินเครือข่ายใช้สวิตช์เพื่อสร้างเซ็กเมนต์ LAN แบบซอฟต์แวร์ที่สามารถกำหนดตามปัจจัยอื่นนอกเหนือจากตำแหน่งทางกายภาพ

- **Gartner**
  - A virtual LAN (VLAN) is a set of systems that, regardless of higher-layer addressing or location, is designated as a logical LAN and treated as a set of contiguous systems on a single LAN segment. Virtual LANs can be proprietary or standardized using the Institute of Electrical and Electronics Engineers (IEEE) 802.1Q. Typical grouping parameters for VLANs include the port number of the hub, switch or router, the higher-layer protocol such as Internet Protocol (IP) or Internetwork Packet Exchange (IPX), the Media Access Control (MAC) address, and the traditional subnet. The goal of VLANs is to provide simpler administration, simple moves/adds/changes to network devices, and partitioning at the MAC layer.

  - **ChatGPT**
    - VLAN (Virtual LAN) คือกลุ่มของระบบที่ได้รับการกำหนดให้เป็น LAN เชิงตรรกะ โดยไม่คำนึงถึงการกำหนดที่อยู่ของเลเยอร์ที่สูงกว่าหรือที่ตั้ง โดยถือว่าเป็นชุดของระบบที่ต่อเนื่องกันในส่วน LAN เดียว VLAN สามารถเป็นแบบเฉพาะของผู้ผลิต (Proprietary) หรือแบบมาตรฐานตาม IEEE 802.1Q
    - เกณฑ์ทั่วไปในการจัดกลุ่ม VLAN รวมถึง:
        - หมายเลขพอร์ตของฮับ, สวิตช์ หรือเราเตอร์
        - โปรโตคอลเลเยอร์สูง เช่น Internet Protocol (IP) หรือ Internetwork Packet Exchange (IPX)
        - ที่อยู่ Media Access Control (MAC)
        - ซับเน็ตแบบดั้งเดิม
    - เป้าหมายของ VLAN คือการทำให้การจัดการง่ายขึ้น การย้าย/เพิ่ม/เปลี่ยนอุปกรณ์เครือข่ายทำได้ง่าย และการแบ่งส่วนที่เลเยอร์ MAC

  - **Gemini**
    - Virtual LAN (VLAN) เป็นชุดของระบบที่ไม่คำนึงถึงการกำหนดแอดเดรสของเลเยอร์ที่สูงกว่าหรือตำแหน่ง จะถูกกำหนดเป็น LAN เชิงตรรกะและถือว่าเป็นชุดของระบบที่ต่อเนื่องกันบนเซ็กเมนต์ LAN เดียว VLAN สามารถเป็นแบบเฉพาะของผู้ผลิตหรือเป็นไปตามมาตรฐาน IEEE 802.1Q พารามิเตอร์การจัดกลุ่มทั่วไปสำหรับ VLAN ได้แก่ หมายเลขพอร์ตของฮับ สวิตช์ หรือเราเตอร์ โปรโตคอลเลเยอร์ที่สูงกว่า เช่น IP หรือ IPX แอดเดรส MAC และซับเน็ตแบบดั้งเดิม เป้าหมายของ VLAN คือการจัดการที่ง่ายขึ้น การย้าย/เพิ่ม/เปลี่ยนอุปกรณ์เครือข่ายได้ง่าย และการแบ่งส่วนที่เลเยอร์ MAC

- **สรุป**
  - VLAN (Virtual LAN) คือการสร้าง LAN เชิงตรรกะที่ไม่ขึ้นกับตำแหน่งทางกายภาพหรือเลเยอร์สูงกว่า โดยใช้เกณฑ์การจัดกลุ่ม เช่น หมายเลขพอร์ต โปรโตคอล IP, MAC Address หรือซับเน็ต ช่วยให้ผู้ดูแลระบบสามารถบริหารเครือข่ายได้ง่ายขึ้น แยกทราฟฟิก และเพิ่มความปลอดภัย โดยสามารถกำหนดได้ผ่านซอฟต์แวร์บนสวิตช์.

- **ตัวอย่างในชีวิตประจำวัน**
  - **ระบบกล้องวงจรปิด (CCTV)**
    - ในอาคารหรือบ้านพักอาศัย VLAN สามารถใช้เพื่อแยกเครือข่ายกล้องวงจรปิดออกจากเครือข่ายอินเทอร์เน็ตทั่วไป ซึ่งช่วยลดความเสี่ยงจากการถูกแฮกและทำให้การบริหารจัดการเครือข่ายง่ายขึ้น
  
  - **ร้านกาแฟ**
    - ร้านกาแฟที่ให้บริการ Wi-Fi ฟรีสามารถใช้ VLAN เพื่อแยกเครือข่ายของลูกค้าออกจากเครือข่ายภายในร้าน เช่น:
      - VLAN สำหรับลูกค้า: ให้ใช้เฉพาะอินเทอร์เน็ต
      - VLAN สำหรับพนักงาน: ใช้จัดการระบบการเงินหรือเครื่อง POS (Point of Sale)

[Witchapol VLAN Page](https://witchapolinaksorn.github.io/vlan)