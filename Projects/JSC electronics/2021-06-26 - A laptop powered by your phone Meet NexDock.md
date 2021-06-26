# A laptop powered by your phone? Meet NexDock

## Hook
I... have a dream. A long-lasting dream to use my mobile phone as a Linux laptop. So wherever I go, I can just plug my phone into a dock, and have all my work with me all the time. I don't want to use multiple devices. With projects like UBPorts, my dream is slowly becoming a reality, but there's still a long way ahead of us. Today, I'll show you NexDock, which is a laptop powered by a smartphone or Raspberry Pi.

## Content
- How can I use my phone as a laptop?
  - Companies like Microsoft and Canonical worked on convergence for a long time. So when you plug your phone to a big screen, the user interface will transform itself into a desktop.
  - In 2015, I bought Lumia 950. It was a phone from Microsoft, which had a dock into which you could plug your external display, keyboard, and mouse, and which offered desktop-like Windows experience with some limitations. It was a step in the right direction, but the experience was not very good.
  - Canonical, the creator of the Ubuntu linux distribution, had a similar vision. They wanted to adapt Ubuntu to mobile phones, and to turn them into fully usable computers when connected to dock. Ultimately, they abandoned the idea, but the project still lives thanks to the community and the folks from UBPorts. And there are other groups with similar effort, like Plasma Mobile.
  - In 2018, 3-years later after Lumia 950 was released, Samsung came with their solution called DeX. For the original version you had to buy custom accessories; later a simple USB-C to HDMI adapter was enough. For quite some time, Samsung even provided a way how to run Linux on your phones. Sadly, their solution was abandoned in October 2019.
  - Samsung DeX might be a viable solution, but it is bound only to Samsung devices. But nowadays, all modern Android smartphones are capable of HDMI output through their USB-C ports. Android 10 came with a hidden desktop mode, which introduced this desktop experience to a handful of non-Samsung phones. Back in the day, this mode was highly experimental. You could turn it on only through Developer options. But this mode is getting some care, and over time more and more upcoming mobile devices will offer decent support for it out-of-the-box.

- How does NexDock fit in?
  - And here we come to NexDock. It's just a display with a keyboard, touchpad, and its own battery. All this is packed in an aluminum chasis reminding of ultrabook laptops.
  - Sadly, my phone, OnePlus 6T, doesn't support HDMI output, so I have no experience with this desktop mode. Someone would think NexDock serves me as a paperweight, but they are wrong. NexDock supports also Raspberry Pi minicomputers, which I have plenty. Let me show you how it all works.

- NexDock showcase

- Live demo: NexDock powered by a Raspberry Pi 4
  - Show booting, Raspberry OS, volume and brightness control, touch screen

  - NexDock resembles ultrabooks in many ways. On the left side, you can find a couple of USB-C ports, and one input HDMI port. You can use that when your device can't send image over USB. On the right side is a single USB-A port and a headphone jack. I was pleasantly surprised by a keyboard, which has a nice grip, and its keys are quite big.
  - Part of the accessories is a power charger, necessary cables and adapters. All you really need to hook up your device.
  - The connection varies based on the device you have. NexDock gives you a nice brochure. Also, on their website you can find the list of all supported devices.
  - You need to connect Raspberry Pi 4 using two cables, while one of them is a special Y-splitter. However, if you add one line into the configuration file, you can use a standard USB-C cable instead of this splitter. And because the Raspberry Pi has microHDMI output, you also need an adapter to full-sized HDMI. It is also included in the accessories.
  - On the Raspberry Pi, I installed the latest Raspberry OS. Ubuntu will work also good, even Windows 10 for ARM should work just fine. I didn't test it though.
  - At the moment, I use NexDock primarily as a portable display for Raspberry Pi. It works just fine for that purpose. If there was no visible Raspberry connected to the dock, you would have a feeling that you work with a real laptop. It has working Fn keys, brightness, and volume controls. All bells and whistles you got used to.
  - Especially, if you're an embedded developer like me, such a solution saves your time tremendously. You don't have to disconnect your existing display, keyboard and mouse from your computer. Doing this repeatedly is a bummer.

- NexDock is not perfect
  - As I found out, NexDock is not perfect.
  - I wanted to use my NexDock as a monitor, which I can hook up to my digital camera
  - HDMI port is picky, and I managed to get it work only once. Also, when you connect just the HDMI, the brightness and volume controls don't work at all.
  - The microHDMI-to-HDMI adapter is bad-quality. It broke after a couple of uses. Luckily, these adapters are dirt cheap and easy to find.
  - Imperfections like this bother me, but I still think it's a valuable device for a certain niche.

## CTA
Using my mobile phone instead of my laptop makes sense to me. The performance of smartphones is more than enough for common tasks. NexDock is a decent piece of hardware, and it can serve you well on your travels.

What do you think about convergence? Does it make sense for you to use your phone instead of your laptop? Let me know in the comments below. Thanks, and see you in the next video.
