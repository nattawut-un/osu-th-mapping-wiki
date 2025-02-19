---
label: Mapping Tools
icon: tools
order: 4
author:
  - name: Pado
    link: https://osu.ppy.sh/users/11942151
    avatar: https://a.ppy.sh/11942151
---

# Mapping Tools

![Sex](./images/mapping-tools/header.png)
(เชียน by โดยเขียนโดย written by by [Nagabi](https://osu.ppy.sh/users/10352099))

Mapping Tools เป็นโปรแกรมที่ทำโดย [OilBomby](https://osu.ppy.sh/users/6573093) ในปี 2019 และเป็นการร่วมงานกันระห่วาง [Karoo13](https://osu.ppy.sh/users/1882522) และ JPK314 . โปรแกรมตัวช่วยนี้จะช่วยในทางการทำแมพง่ายขื้น (หรือยากขึ้นวะ) ไม่ว่าจะเป็นการทำ Slider ให้น่าสนใจและช่วยในด้านต่างๆ ด้วยเครืองมือที่มีอยู่. เครื่องมือนี้ได้รับความสนใจอย่างมากจากชุมชนตั้งแต่นั้นเป็นต้นมา,_and one of its features have made its way into osu!lazer as an official feature. So, keep yourself updated with osu!lazer features because there may be more._

### Slider Merger

เครื่องมือนี้จะช่วยให้เราสามารถรวมหลายๆ slider/circle ให้เป็น Slider เดียว. เป็นหนึ่งในเครืองมือทีใช้ง่ายและตรงไปตรงมา, สามารถหาวิธีการใช้เครืองมือนี้โดยทำตาม [คำแนะนำของ OliBomby’s](https://www.youtube.com/watch?v=zK6ozJK0lc4). _(This got a great amount of attention and Oli has made a counterpart feature exclusively made for the lazer editor, splitting slider.)_

![การต่อสไลเดอร์ 2 อันแบบง่ายๆ](./images/mapping-tools/slider-merger.png)

### Geometry Dashboard

เครืองมือนี้เปรียบเหมือนไม้บรรทัดในการสร้าง pattern ที่ซับซ้อน เครื่องมี่นี้ใช้งานได้ค่อนข้างยากจะอธิบาย และยากที่จะทำความเข้าใจ และส่วนใหญ่ก็ได้ใช้แค่นานๆทีเท่านั้น (เป็นเครื่องมือที่ช่วยได้มากสำหรับมือใหม่แต่กูสมองเล็ก :skull:), [so here’s a tutorial on how to use the tool.](https://youtu.be/BgKMavhSz8k)

![Geometry Dashboard เพิ่มเส้นต่างๆ ขึ้นมาเพื่อให้ง่ายต่อการหา axis, blanket ต่างๆ](./images/mapping-tools/geometry-dashboard.png)

### Sliderator
![](./images/mapping-tools/sliderator.png)

เป็นเครื่องมือที่จะสามารถทำให้ Slider ของเรามีความเร็วที่หลากหลายภายในตัวเดียว ซึ้งตรงข้ามกับ slider แบบทัวไปที่มีความเร็วของ slider เท่ากันตลอดของทั้งตัวมัน. ความเร็วของ Slider นั้น ด้วยประสบการณ์ของ Mapper และการลองผิดลองถูก จะสามารถสร้างสรรค์ Slider ได้อย่างเป็น เอกลักษณ์เลย.
ตัวอย่างของ **Sliderator** นั้นส่วนใหญ่จะใช้กันในพวกเพลง Electronic ต่างๆ เช่น

<img
  src={require('./images/mapping-tools/sliderator-ex1.png').default}
  alt="Example banner"
  width="300"
/>
<img
  src={require('./images/mapping-tools/sliderator-ex2.png').default}
  alt="Example banner"
  width="400"
/>
<img
  src={require('./images/mapping-tools/sliderator-ex3.png').default}
  alt="Example banner"
  width="700"
/>

#### วิธีการใช้
![Sliderator](./images/mapping-tools/sliderator-t1.png)

จากภาพ
 **แกน X** แสดงถึงความยาวของ Slider ที่แสดงใน Timeline (หรือในเกม เช่น 1/2 3/4 etc. etc.),
 **แกน Y** ในกราฟนี้ คือ ความเร็วของ slider ball ในตัว slider body เลขข้างๆช่างแม่มัน มันยาก


เริ่มแรกเลย, เราสามารถคลิกขวาตรงเส้นกราฟ เพื่อสร้าง anchor (ในการทำ slider จุดแดงๆเรียกว่า anchor ในที่นี้จึงนำเปรียบเทียบจุดหักของเส้นกราฟ)ขึ้นในกราฟ (จุดสีฟ้า).

จุดสีฟ้า จะเป็นจุดที่สามรถส่งผลต่อความเร็วของ Slider Ball ได้. ซึ้งสามารถปรับได้ดังนี้:
- **ถ้ากราฟสูงขึ้น**, ความเร็วจะเพิ่มขึ้น
- **ถ้ากราฟต่ำลง**, ความเร็วจะลดลง

และถ้าหากอยากนำจุด anchor ออก, ให้คลิกขวาที่จุด velocity curves อีกครั้ง

และหากสังเกตเห็น จะมีจุดที่เล็กกว่าปกติ, จุดนั้นจะทำให้ปรับความเร็วของ Slider แบบโค้งได้ *(velocity curves)*. ซึ้งสามารถปรับได้ดังนี้:
- **ถ้ากราฟนูนขึ้น**, ความเร็วจะเพิ่มขึ้น
- **ถ้ากราฟแบนลง**, ความเร็วจะลดลง

ถ้าหากเราต้องการ velocity curves ในรูปแบบอื่น เราสามารถคลิกขวาที่จุด anchor point และเราจะเห็น curves ในรูปแบบต่างๆดังภาพ:


![](./images/mapping-tools/sliderator-t2.png "menu")

แต่จริงๆแล้ว curve แบบค่าเริ่มต้น เอาจริงๆก็สามารถใช้ได้ทุกแมพแล้วแต่ก็สามารถทดลองรูปแบบอื่นได้เหมือนกัน, ไอตัวที่ดูจะเป็นไปไม่ได้ที่จะใช้เลยคือ **"Wave"**. มันเหมือนเป็น feature ที่มีใว้แค่ให้รู้ว่ามีเฉยๆ แล้วแม่งฮามากเวลาดู.

:::danger คำเตือน
  อย่างไรก็ตาม หาก Sliderator กินทรัพยากรของเครื่องมากเกินไป. คุณอาจจะจำเป็นต้องลดจุดของ Sliderator เนื่องจากมันอาจจะเยอะเกืนความจำเป็นนั้นเอง
:::

### Pattern gallery
![](./images/mapping-tools/pattern-gallery.png)

Pattern gallery สำหรับผมไม่ค่อยได้ใช้เท่าไหร่เนื่องจากผมค่อนข้างไม่ค่อยอยากใช้ Pattern เดิมๆ เพราะส่วนตัวผมตอนนี้ก็ยังหา Style ใหม่ๆอยู่เรี่อยๆ แต่สำหรับใครที่มี Style ที่ชอบ pattern ที่เคยใว้อยู่แล้วเครื่องมือนี้ก็จะช่วยประหยัดเวลาได้มากโขเลย

### Hitsound Preview Helper
![](./images/mapping-tools/hitsound-preview-helper.png)

สำหรับใครที่อยากเพิ่มระดับการทำ [Hitsound](/hitsound/basic.md) เครื่องมือนี้จะเป็นใบเบิกทางสู่นรกที่ลึกกว่าที่เคย สำหรับผมที่ใช้บ่อยเอามากๆ เพราะผมทำ Hitsound มากกว่าทำแมพซะอีก. ถ้าใครเคยเห็น Hitsound ที่มีหลายๆ Layer อย่าง Hitsounder ดังๆเช่น [Midorijeon](https://osu.ppy.sh/users/10969875) , [Nagaraia](https://osu.ppy.sh/users/13673790) และพวก Keysound ก็สามารถทำในนี้ก็ได้นะแต่ก็มีวิธีที่ดีกว่าแหละ

### Slider Picturator
![](./images/mapping-tools/slider-picturator.png)
ผมจะไม่สอนวิธีใช้เพราะมันโคตรจะไม่จำเป็น
**SHIT POST**
:::danger คำเตือน
![](./images/mapping-tools/urmom.png)
:::

[เอาไปทดลองฟัง](https://prophet-launchpad.netlify.app/)
