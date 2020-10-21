---
title: "EYE SEE YOU, Interactive Installation, in a 3m*3m space"
description: "We explore a lot in the virtual world, but ignore ourselves. People's sneak peeks are also very ridiculous. We are snoopers, but also being snooped. We are people who ignore real world, and being ignored."
tags: ["EYE"]
lastmod: 2019-08-06
date: 2019-08-06
categories:
  - "EYE"
---

[1] Workshop “Mirror In Our Hands”

{{<figure src="/img/IMG_5557.png" title="Workshop" height="500" width="1080px">}}

Mentor:
 Katrin Leitner-Peter, Germany, Kunsthochschule, Kassel (Professor Kartrin is currently teaching at the Kunsthochschule Kassel in Germany, focusing on exploring the relationship between painting, installation, performance and digital media art and conducting experiments. Her research on digital media art are widely disseminated in the industry and are regarded as classics.)

Question:
 How does our online life and digital existence affect our reality and material existence?
 What has changed in our consciousness?
 How do we change our perception of the world inside and outside? Our posture, sense of direction and self-perception?

---



[2] My thoughts:

Smartdivices let us explore a lot in the virtual world, but ignore ourselves. People's sneak peeks are also very ridiculous. We are snoopers, but also being snooped. We are people who ignore real world, and being ignored.
 Whether people can jump out of theexisting relationship of human and machine, observe our relationship with the machine from a new perspective? Or separate the different parts of our individual?

"Petrochemical": the body without the soul -I made a hand, after the soil dried, the action of touching the screen became eternal, but become fragile.

---



[3] Exploring

William-Adophe Bouguereau (1825~1905, French): “There is only one kind of painting, that is, the painting that can bring the flawless beauty and perfection to people's eyes, just like the works of Venezuese and Titian. ”(1895)
 Bouguereau advocates nature, the ultimate aestheticism, the spirit of persisting in love and restoring natural beauty in the era of the rise of avant-garde art. The feeling of his paintings for me has always been: “Very beautiful, very sacred, very natural. "I think those in stark contrast to what I wanted to express in my work.

{{<figure src="/img/2-mind note.png" title="Mindnote about Bouguereau" height="500" width="1080px">}}

\#Video#
 "BEAUTIFUL BEAUTIFUL EYES" Duration: 1'20''
 Medium: Computer editing

{{<figure src="/img/屏幕快照 2019-05-24 下午2.44.13.png" title="Bouguereau's painting" height="500" width="1080px">}}

I extracted the eyes of Adolf Bouguera's oil paintings as the basis of the creation, made a video, added heavy black circles and red blood to these eyes, I hope that the picture can show contrast.

\#Kaleido#
 "Reflection_You&Me"
 How has the Internet and smart divice changed our lives?

{{<figure src="/img/屏幕快照 2019-08-27 上午9.46.38.png" title="Kaleido" height="500" width="1080px">}}

We want to see the world of others through the magic screen on our hands, and others want to see ours. The online world is like a colorful kaleidoscope, it looks magical, this two side are actually same.
 The short film on the screen records the real state of others: Staring at the screen tirelessly, blinking and wearing dark circles.
 The mirror is also the "screen". The other side of this space is someone else. This side is you, how do you look like in the mirror?

Invisible network: You always want to see some private world through the scareen,but what you see is that others are also watching the screen, it is actually yourself.

(Mindmap)

{{<figure src="/img/1-mind note 2.jpg" title="Mindmap of Kaleido" height="500" width="1080px">}}

---



[4] Case Study

\#Interactive Installation# "Penguins Mirror"

Medium: Entity Interaction

AUTHOR-Daniel Rozin:

As an interactive artist Rozin creates installations and sculptures that have the unique ability to change and respond to the presence and point of view of the viewer. The viewer becomes the contents of the piece or be invited to take an active role in the creation of the piece. Even though computers are often used in Rozin's work, they are seldom visible.

{{<figure src="/img/maxresdefault.jpg" title="Penguins" height="500" width="1080px">}}

{{<figure src="/img/dr_penguins_2-w.jpg" title="Overview" height="500" width="1080px">}}

The Penguins Mirror is an interactive mirror constructed with 450 stuffed penguins atop rotating motors.As with many of his other kinetic mirrors, Rozin makes use of the black and white color tones found on the stuffed animals to generate moving silhouettes in response to movements captured by video cameras.

---



[5] Inspiration

When I think about the role of our eyes alone, I think they become a "machine of reading information." They are like labors were over-squeezed. They are no longer bright because they are tired of staring at the screen for a long long time. They are dry, just like clay, they have no soul, just do simple “following movements”.
 But our eyes are used to be the windows that convey the feelings and reflect the state of minds. Most people continue to stay up late at night to play mobile phones and watch computers. Therefore, they all wear dark circles, red blood, affect their vision after a long time. And this is very common, because everyone spends a lot of time on this matter.

("Late Sleep Obsession "-Many people are sick without knowing it. Like me, and many paople around me.

The patient repeatedly has obsessive and compulsive behaviors in his life. The patient's self-knowledge is in good condition. These people will indulge in the Internet at night, watch online videos, forums, chats, hang out nightclubs, or evacuate pressure in fast-paced and powerful music; do things until the night is quiet, such as Clean up the room, read magazines, write articles, etc. Knowing that this is not necessary, even painful, but can not get rid of.)

Initial idea: rotating eyeball

\- Mechanical control, follow-point movement.

{{<figure src="/img/IMG_0457.jpg" title="Initial idea" height="500" width="1080px">}}

---



[6] Interactive Design:

11 * 11=121 eyes formed a square matrix, they can rotate by following the displacement of people who were in front of them, the rotation angle is dispersed into rays. I use clay pinched nearly two hundred eyes, every eye fixed on the servo, servos are used for turning, the front is a device of infrared identification device, attached to the Arduino, behind is the input code to make the rotation of the steering gear, when it reads to the face of the infrared position after simplified as a abscissa value, this value is transmitted to the Arduino calculation, output 121 rotation Angle command to 121 steering gear, respectively.

{{<figure src="/img/apple-macbook-pro的副本.jpg" title="Logical analysis" height="500" width="1080px">}}

---



[]Angle Calculation& Time Delay:

(Each eye ball rotates one by one in sequence, plus a time delay, the effect is like a wave.)

{{<figure src="/img/eye_cal_time.png" title="Interactive Design" height="500" width="1080px">}}

---



[8]Connection diagram:

(Arduino, PCA, Power, Servo)

{{<figure src="/img/eye.png" title="Component" height="500" width="1080px">}}

{{<figure src="/img/IMG_0716.png" title="Spatial structure" height="500" width="1080px">}}

---



[9] Difficulties:

The most difficult part:

Deploy the signal position of each servo;
 Check the fault one by one (when the effect is not alright, it is difficult to find out what went wrong); The power distribution is uneven;
 Mathematics calculation.

{{<figure src="/img/屏幕快照 2019-11-18 下午8.10.27.png" title="Eteballs" height="500" width="1080px">}}

{{<figure src="/img/屏幕快照 2019-11-18 下午8.10.02.png" title="Servos" height="500" width="1080px">}}

{{<figure src="/img/IMG_4322.jpg" title="Final exhibition" height="500" width="1080px">}}

{{<figure src="/img/IMG_4327.jpg" title="Final exhibition" height="500" width="1080px">}}

{{<figure src="/img/IMG_4347.jpg" title="Working" height="500" width="1080px">}}

{{<figure src="/img/IMG_4367.jpg" title="Working" height="500" width="1080px">}}

---



[10] Final work & Exhibiton

{{< youtube c4cA5mbXrAY >}}

