# Building EXCEPTIONAL speakers using MODERN TECHNIQUES


## [Introduction](https://youtu.be/XEspOD1NHr0)

Building homemade speakers that can compare favorably to Manufactured units that have all manner of built-in Digital Signal processes precisely tuned ports and computer calculated internal air volumes is hard.  
Simple boxes just aren't going to cut at anymore.


## [3D Printers and Sound Quality](https://youtu.be/XEspOD1NHr0?t=18)

However, 3D printers might be able to help here.

Their ability to make complex shapes with millimeter precision is perfect for making computer aided designs. But, there's a bit of a problem in that thin extruded plastic is acoustically not that great.

As it's low in mass, it vibrates and resonates easily, which is awful for sound quality. If this basic enclosure, for example, is measured with a calibrated microphone, we can see this resonance appearing in the 100 to 500 Hertz range and it presents as distortion.

[\<frequency graph>](https://youtu.be/XEspOD1NHr0?t=47)

Making the chamber walls thicker would of course help here, but it would require a lot of filament and take days to actually print.


## [Using a Filler Material](https://youtu.be/XEspOD1NHr0?t=58)

However, what if we print only a hollow shell and then use it as a form mold 
instead. Doing it this way results in speedy print times, as the filament only has to be deposited for the shell, with a large internal gap left for a a filler material.


### [Plaster of Paris](https://youtu.be/XEspOD1NHr0?t=74)

A cheap and readily available option for this filler material is of course plaster of Paris, which can be added to water to make a paste that sets hard.

It does have a problem for sound applications though, in that it's a very brittle material, giving it a ringing quality, a bit like a teacup. This has the potential to sound worse than the plastic alone.


### [Mixing PVA to Plaster of Paris](https://youtu.be/XEspOD1NHr0?t=96)

But, there is a way to fix it by adding PVA glue during the mixing process, which changes this quality entirely and the difference between the two is night and day.

I believe the addition of PVA creates a microscopic level of flexibility, reducing its brittle nature and making it behave like a much duller sounding material, perfect for using in our 3D printed mold, which once dried is way more solid than our previous version.


## [Damping Internal Reflections](https://youtu.be/XEspOD1NHr0?t=132)

These new thick chamber walls reduce the 100 to 500 Hz distortion significantly, which is great, but as the enclosure is so much stiffer now there's a new problem to contend with: *Internal Reflections*.

[\<frequency graph>](https://youtu.be/XEspOD1NHr0?t=134)

You see when a speaker driver moves back and forth it sends sound wav not only forwards towards the listener, but also backwards into the enclosure.

An ideal enclosure is supposed to prevent these sound waves from escaping, which our solid enclosure now does a decent job of, but as these sound waves have nowhere else to go, they bounce around and eventually hit the back of the speaker driver again, coloring its output due to the time delay.

This is less than ideal but, adding soft materials to the inside of the enclosure is a good way to dampen these reflections.

Here I'm going with some some soft automotive acoustic pads, followed by a folded layer of cotton towel and then some sheep's wool, which will all act together to stop the sound waves from being reflected back. And overall compared to our original thin enclosure we've gone from this to this.

[\<frequency graph>](https://youtu.be/XEspOD1NHr0?t=192)

Further improvements can be had by utilizing higher quality drivers, which we'll be diving into later. 


## [Improving Subwoofer Frequencies](https://youtu.be/XEspOD1NHr0?t=202)

But, essentially this forming technique has made 3D printing a viable option for Hi-Fi sound quality, which is really exciting because we can now use their ability to make complex shapes to our advantage and one area in particular that's going to benefit a lot from this, is the subwoofer frequencies.


### [The Bass Reflection Tube](https://youtu.be/XEspOD1NHr0?t=222)

You see if we replace the enclosure with a long tube, it will keep the rear sound waves contained only until they exit at the other end.

Due to the time that this takes, it essentially delays the audibility of these rare sound waves, just enough for them to become additive, rather than some attractive to the driver's forward sound waves, which makes far more use of the speaker's energy. 


### [Tang Band W3-1876S Subwoofer](https://youtu.be/XEspOD1NHr0?t=246)

One notable subwoofer that's become somewhat of a legend in this configuration, mostly thanks to fellow YouTuber hexy base, is [this 3-in unit from Tang Band](https://www.tb-speaker.com/products/w3-1876s).  
Despite its diminutive size, it should go down to the low 40 Hz range, which is insane for such a small driver. 

![Tang Band W3-1876S 3" Mini Subwoofer](https://www.tb-speaker.com/uploads/images/cache/29740ba259c4df56ae4cbddc02776810-224-224-0-1-1.png)


### [Calculating the Bass Reflection Tube Dimensions](https://youtu.be/XEspOD1NHr0?t=264)

Calculating the required dimensions for this to be done properly can be done with a piece of software called [Hornresp](https://www.diyaudio.com/community/threads/hornresp.119854/), which can map out the predicted response, allowing us to get two key measurements: the tube length and the area of its cross-section. 

The 1.4 M length required for this is rather long, so it can be made into a folded configuration to make it more compact so that we can actually print it off with the 3D printer.

Again in an effort to reduce print times, I'm making this design entirely hollow. With the goal being to fill it with our special PVA and plaster of paris mix.


## [Initial Prototype](https://youtu.be/XEspOD1NHr0?t=298)

As it approaches 60 cm in height, it's necessary to split it up into three individual sections so that it can be printed with the widest variety of printers and as you can see, I've included a sealed enclosure above it all, for a dedicated mid-tone driver, as the subwoofer isn't really very good at reproducing these tones.

Filling this whole thing with plaster of Paris can be done through a hole at the top. Though it does need to be knocked repeatedly to make sure that there are no air pockets.

This makes thick walls around the subwoffer port and the midtone chamber and it makes the unit extremely heavy for its size. But, it does feel high quality for it and very solid. 


### [Evaluating the Subwoofer Performance](https://youtu.be/XEspOD1NHr0?t=338)

During testing though I found that subwoofer notes while extremely deep, weren't as loud as I'd like.

Now being me, I'm not satisfied with this yet I want to take this design as far as we can possibly go, to make it the ultimate 3D printed speaker. And to do this my conclusion, is to add yet another subwoofer driver. This doubles the surface area that's going to be providing base and should hopefully solve the issue.

But it does come with its own challenges, namely that we not only need to find space for the driver itself, but also the port has to literally double in dimensional volume. And if I want this thing to remain the same size, that's going to be a massive challenge. 

But uh to be honest, the solution is annoyingly obvious.


## [A Second Attempt With a New Concept](https://youtu.be/XEspOD1NHr0?t=390)

You see in an effort to have enough room for the plaster of Paris to form good solid boundary walls throughout the speaker, including those surrounding the subwoofers port, I forgot to ask myself whether they were all necessary. 

You see the whole point of this subwoofer tube, is to redirect energy, not contain it, as the end is open, its walls really don't have to be as thick as I've made them, because they don't have to hold in any energy, they merely direct it through. 

With this in mind for the second attempt, I've decided to remove the need for plaster of Paris for the subwoffer port entirely and instead have gone with 4mm 3D printed boundaries, which saves just enough space for the now much wider and longer Port. 

The downside is that it consumes twice as much filament and takes twice as long to print, compared to the original. So let's hope it's all worth it. 

So a few days of print time later and we've got everything printed off, ready to be mounted together. Now this is a relatively simple process due to the way it's been designed and divided up, but we do need some glue now. This isn't actually for anything structural, it's just to form an airtight seal between the different layers so let's get to it. 

```[NordVPN Ads]```


## [Build Instructions](https://youtu.be/XEspOD1NHr0?t=537)

Now, time to get gluing.


### [Printing the Parts](https://youtu.be/XEspOD1NHr0?t=541)

As you can see the biggest change from the original design is how it's been divided up for the printing process, with smaller individual parts rather than three big ones. This has been done to reduce the likelihood of printing failure by them popping off the build plate before they complete.

Though if you do want to print a set of these yourself do note that it's still important to clean the build plate and apply some school glue for the best adhesion.


### [Glueing all the Pieces Together ](https://youtu.be/XEspOD1NHr0?t=566)

Once everything's successfully printed, build platforms one and two can be glued together, first utilizing a couple of **H Clips**, to make sure that they're nice and tight.  
As you can see, the glue has a tendency to squeeze all over the place but it's easy enough to wipe away any excess.

Now you'll have probably noticed that these pieces **have many small discs on them**. 

These are actually centering guides which line up with the subsequent pieces making them easy to position accurately. Here I'm adding the bottom part of the subwoofers chamber and if we flip it over we can see that there are four holes beneath it.  
These are for **2 mm diameter self-tapping screws**, which allow us to clamp the pieces together. 

From here, the internal air guides can now be added starting with piece **A**.  
This just needs a **thin bead of glue along the bottom as well as any vertical seams** it touches. The guides help a lot in positioning it correctly, after which **the screws take over**.

It's important to ensure adequate glue here for a tight seam, keeping in mind that **any spillover can be easily wiped away**. 

This process needs to be continued with all of the internal air guides, which completes the subwofer tuning Port, allowing us to move on to the midtone chamber. 


### [Cable Wiring](https://youtu.be/XEspOD1NHr0?t=637)

As you can see this is the only section that is carried over the hollow forming technique, as it's proven so effective for mid-tone use. For a nice strong length this final platform can get extra support from the subwoofer exit port, which as you can see **has a wiring guide in its top half**. 

There are **a total of four pairs of wires** that need to be rooted through this. **A pair for the top chamber**, **a pair for the middle Chamber** and **two pairs for the lowest subwoofer chamber**.  
The holes for these, of course, **all need to be sealed up so that no air can pass through**.


### [Setup of the Midtone Chamber](https://youtu.be/XEspOD1NHr0?t=670)

With that done the hollow cavity below the midtone chamber can now be covered, ready for the PVA and plaster of Paris mix, in just a moment. 

But before we do that, we might as well **add the chambers dampening materials** at this stage, while we have easy access to it. Again this is just a layer of **15 mm thick automotive acoustic foam**, followed by a **folded layer of cotton towel** and then **some sheep's wool**. 

> If you can't find any sheep's wool by the way it's worth noting that loosened rock wall can also be used here, which is something that you can find in most hardware stores. 


### [Closing the Speakers](https://youtu.be/XEspOD1NHr0?t=703)

All this being done, means that we can finally cap the unit off with **its top lids**, as well as the **brackets for the speakers** themselves. 

It's worth noting that these being separate is intentional, as it means that the design can be easily adapted to different speaker drivers.


### [Filling the Chamber](https://youtu.be/XEspOD1NHr0?t=718)

So to finish things off it's time to make what will hopefully be our last batch of **PVA and plaster of Paris**. 

> While plaster of Paris is generally safe, it does need to be respected as it can set quickly and generate some heat while doing so. Make sure you read the safety notes in the video's description before attempting to use it.

The quantity required for our pour is **750 mL of water** that's already been **mixed with PVA**, at a **ratio of about 10 to 20%**. This can be followed with **1 kg** of plaster of Paris powder, which needs to be mixed in gradually. 

Once a smooth consistency has been achieved, it can be poured into the chamber at the back, which completely surrounds the midtone chamber with a solid 16 mm thick wall. 

It doesn't take too long for this to set, after which the rear can be closed up with a little cap. 


### [Painting](https://youtu.be/XEspOD1NHr0?t=769)

Now technically the enclosure is ready for the various drivers to be mounted. 

But, aesthetically I think there's room for improvement, especially as not everyone is fond of the 3D printed look, particularly when there are joins that are still visible.  
But thankfully there are loads of different techniques that we can utilize to make this thing look really special. 

To make the joins less of an issue, they can simply be filled and then thoroughly sanded down. While this can be done by hand, it's worthwhile borrowing a Disc Sander, as it saves so much time and it gives a really smooth finish, ready in fact, for some paint. 

Some plastic primer can be used here first, as it gives a good key for the top coat. There are loads of cool finishes available these days and I'm going with a textured paint, that looks a little bit like metal. A far cry from the original printed plastic that's for sure. 


### [The Wood Veneer](https://youtu.be/XEspOD1NHr0?t=820)

Now if you look closely at the sides of mine you'll see that I've masked them off. What's underneath some beautiful wood veneer.

I added this before the painting process by spreading around a load of glue and **sticking the veneer on top**. Veneer for those who don't know is a very slim slice of real Hardwood. Mine being **Rosewood**.  
It gives the enclosure a really high-end appearance, particularly when it's oiled as it brings out the richness of the wood.

Lovely!

The rapid transformation of how this looks, is really quite remarkable and it's only going to get better from here.


### [Speaker Drivers Mounting](https://youtu.be/XEspOD1NHr0?t=856)

To prepare for the mounting of the speaker drivers the holes for them need some little **M3 threaded inserts**, which are for screwing them in place.

When wiring them up it's worth noting that the **polarity of each speaker** needs to be correct with the **red wires going to the positive terminals**. 

One often overlooked but very vital addition is to **add a rim of blue tack around the edge** before the driver gets screwed in place, as this makes an airtight seal for it. 

As you can see they are slightly proud rather than flush, so to make them aesthetically more pleasing, they can be tied together visually with a little bracket. 

Very nice!


### [Midtone Driver](https://youtu.be/XEspOD1NHr0?t=892)

So with the two subwoofer drivers now installed, it's time to tackle the midtone driver. 

Choosing a suitable one is somewhat daunting as there are literally hundreds of different models available, each with wildly varying performance characteristics.  
In an effort to select the best possible driver for this project I spent literally days testing various drivers, ultimately settling [on this one](https://www.tb-speaker.com/products/w3-1364sa), which is again a Tang Band unit. 

![W3-1364SA 3" Paper Full Range](https://www.tb-speaker.com/uploads/images/cache/6da1b17fb1e663b6f76d84b135beace8-224-224-0-1-1.png)

It's got a nice smooth character to its sound output with plenty of mid-range detail and it looks really smart to boot. An amazing feature of this driver, is that it can actually cover high frequencies as well, so it can pull double duty as a tweeter, which is great for those on a tighter budget. 


### [Optional High Frequency Driver](https://youtu.be/XEspOD1NHr0?t=934)

For those who want the absolute best high frequency detail however, the design does cater for [dedicated tweeters](https://sbacoustics.com/product/sb26stcn-c000-4/). Though they'll only likely be appreciated by the most demanding of listeners.  
So it's your call whether to include one or not as the speaker can be printed without the hole. 

![SB26STCN-C000-4 / Fabric](https://sbacoustics.com/wp-content/uploads/2022/11/SB26STCN-C000-4-main-photo-product.jpg)

Either way with all of the drivers added it looks really elegant and it's easy to forget that it is in fact 3D printed.


### [Front Grill](https://youtu.be/XEspOD1NHr0?t=956)

Now some people might prefer the drivers to be covered which is why I've included these holes. 

They're for a grill which can be made by gluing some threaded steel rods to some mesh, which can in turn be held in front of the speaker with some 3D printed pegs. You could even Paint It Black, for a different look. 


### [Hi-Fi Side Baffles](https://youtu.be/XEspOD1NHr0?t=973)

An optional extra I've included for Hi-Fi Buffs by the way, are some side baffles. I embedded magnets for these before the painting process, which allows them to be easily added or removed.  And the idea is to provide a smooth surface for the sound waves to spread out on. 

To describe the effect is like the sound gets projected forward slightly with them, but it's only a tiny difference. Still the options there for those of you who want it.


## Electrical Setup

### [DSP](https://youtu.be/XEspOD1NHr0?t=998)

Now to get the very best possible sound from this thing, we're going to need some help from our secret ingredient: A digital signal processor.

![ADAU1701](https://ae01.alicdn.com/kf/Sa61086175f97411c95b596c4d91c013cc.jpg)

Shockingly these are really cheap to buy now and can provide four fully programmable sound outputs, allowing it to function as an advanced crossover.

To make use of it we can simply mount it into a little 3D printed box, along with **a voltage regulator for power**. It's going to get its audio signal from a phono socket, that can be inserted here, alongside a **DC Barrel plug**.

This essentially takes the audio signal from the phone socket and internally splits it up into four separate signals with specific processing for each. 


### [Amplifier](https://youtu.be/XEspOD1NHr0?t=1038)

As the board can't do any amplification though it needs to send these signals to a [4 channel amplifier](https://ebay.us/ZWlpBh).

The one I have here is a **class AB type** which uses slightly more power than class D amplifiers but it has a very low level of output hiss, which can be at annoying levels on so many other amps. 

There is of course a ready-made chamber for it on the back of the speaker and each driver wire pair needs to be hooked up to it, being careful of polarity.


### [Cooling](https://youtu.be/XEspOD1NHr0?t=1065)

To Aid in cooling a little shroud can be fitted on top that features **a slow-moving fan**.

The amp can run passively, but when listening to loud content for an extended period of time, it's likely to get quite hot and the tiny amount of of air movement that the fan provides, is all that's required to keep it nice and cool, so is well worth it. 


### [Connecting Amplifier and DSP](https://youtu.be/XEspOD1NHr0?t=1084)

The signal processor can be added just below this and wide up to the amplifier input wires. Their order doesn't really matter, as we can configure them digitally later.

The last thing to do, is add a cap to cover everything up which completes the build. 


### [Stereo Application](https://youtu.be/XEspOD1NHr0?t=1099)

Now for stereo I've made an identical pair. And they look way better than I thought that they ever would, particularly for 3D printed speakers. But do they have the audio quality to match their looks. 

Let's find out!


## [Programming the DSP](https://youtu.be/XEspOD1NHr0?t=1114)

After giving them power, the first thing we need to do is program the signal processor.


### [Sigma Studio Software](https://youtu.be/XEspOD1NHr0?t=1118)

This can be done with a free piece of software called [SigmaStudio](https://www.analog.com/en/resources/evaluation-hardware-and-software/software/ss_sigst_02.html), which has loads of different filters and algorithms. I've spent many hours making a profile that gets the most from this design. And you can find it with the Project's 3D printable files.  
[Link in the description](https://payhip.com/b/dhJrS).


### [Connecting the USB Programmer](https://youtu.be/XEspOD1NHr0?t=1135)

To upload it to the DSP we can simply use a [cheap USB programmer](https://ebay.us/i8U1fC). This has three pins: **GND**, **SCL** and **SDA**, that corresponds to ones labeled on the DSP.  
So merely need to be connected together.

![USBi](https://ae01.alicdn.com/kf/S30bc4658ac2d485994ccc0a8917fdb98p.jpg)

This allows the profile to be compiled and tested live. 

Though to save it to the DSP itself, the **WP** pin needs to be bridged to ground, after which the profile can be written to its internal memory. 


## Applications

### [Frequency Response](https://youtu.be/XEspOD1NHr0?t=1161)

Now if you're wondering what the frequency response looks like, I've tuned it to be extremely 
flat right down to 50 Hz, where it then tapers slightly to 40 Hz. This measurement is without any boundary reinforcement, as it's been done in the open air.  
But in a typical indoor location with a wall behind them, they measure flat right down to 35 Hz.

This is incredibly deep for such small speakers and this level of performance is usually only found in floor standing units or external subwoofers. 


### [Computer Gaming](https://youtu.be/XEspOD1NHr0?t=1192)

As these would make excellent gaming speakers it's a perfect opportunity to show you how Vivid their Sound Stage can be.

```[Music]```


### [Alternative to a Soundbar](https://youtu.be/XEspOD1NHr0?t=1228)

As they're tall and elegant having them sit either side of TV is a great alternative to a soundbar. Particularly as they'll sound significantly better as - well here's an example against a much more expensive Bose unit:

```[Music]```


### [Comparing to High End Bookshelf Speakers](https://youtu.be/XEspOD1NHr0?t=1258)

They can even trade blows with high-end bookshelf speakers as well.

```[Music]```


## [Conclusion](https://youtu.be/XEspOD1NHr0?t=1290)

If you'd like to build a pair for yourself, you can find the principal components for them, in the video's description. Though do note that they take about 5 days to print. 

Now I can't offer any warranty or support for them, but as you've seen from the video, they're easy enough to put together and they're well worth building.

It's taken many weeks of prototyping to evolve the design to where it's ultimately ended up. And I'd say it's a massive success! We've made them very competitive to manufactured units and they look good to boot.

Now for my next video I'm actually going to be doing the first PC build I've done in ages and it's going to be going underwater. So make sure you're subscribed so you don't miss it and I'll
see you there.

