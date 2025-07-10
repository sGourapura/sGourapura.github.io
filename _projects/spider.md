---
layout: page
title: SPIDER
description: My work on the SPIDER experiment
img: assets/img/back_spider_selfie.jpg
importance: 1
category: work
---


I started work on the SPIDER experiment on January 2020. I had just completed the prelim exam for my graduate program and thankfully passed. Other than a single class, I was done with all course requirements and was ready to dive into research. I chose Bill's group because it had a balance of hardware and analysis, along with plenty of support from graduate students, postdocs, and advisor. I started by reading papers and theses, but it quickly became apparent how difficult it would be to learn what all I needed by studying. Realizing that both the lab and I prefer the "learning by doing" approach, I dived into the spring 2020 cooldown.


<div class="row">
    <div class="row justify-content-md-center">
        <div class="col-8 mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/spring_cooldown.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

The cooldown began with installing telescope inserts, wiring baseplates, performing continuity checks, adding multi-layer insulation, and sealing the cryostat’s bottom dome. After starting the pump-down, we adopted work shifts and began the careful process of cryogenics with a room-sized vacuum vessel. Leak checks involved spraying helium and monitoring with a leak detector; once pressure was sufficiently low, we switched to a large turbo-pump. The real “cool” phase started when we filled the 1300-liter main tank with liquid nitrogen. Although I’d used LN2 for biology before, handling multiple tanks was new to me, and I quickly learned the importance of using a hot air gun on cold valves and distinguishing between safe and dangerous noises. At this scale, cable management, labeling, and communication became critical.

Once stable LN2 temperatures were reached, we rinsed the main tank with ultra-high purity Helium and began adding liquid helium. Liquid helium is pretty incredible. When vented into the air, it looks like white fire from a dragon. Despite this, it is at only 4 degrees above absolute zero. It's a miracle that we have access to it, and that we have a recovery system for any lost helium in Jadwin. Adding LHe was a slightly more complicated process of hoses with stingers and protective equipment, and made me feel like a sci-fi firefighter. Thanks to Jadwin’s recovery system, we could safely manage any lost helium. Adding LHe required specialized hoses, stingers, and protective gear, making me feel like a sci-fi firefighter. With the main tank filled, we started pumping on the superfluid tank (SFT) through vacuum-cooled shield layers, building up superfluid helium. With the main tank at 4K and the SFT at 2K, we had the two temperature baths needed to cycle the fridges, which use helium-3 adsorption to cool the telescope focal planes to 300 millikelvin and must be cycled every dozen hours. During this, the telescopes were covered to block room light and prevent heating.

I assisted Corwin and Sherry with the Fourier Transform Spectrometer (FTS) during cooldown. The FTS, an interferometer with a thermal source and movable mirrors, mounts to the front of the cryostat and can be positioned over any of the six inserts. By scanning the mirror at a constant velocity, we could create an interferogram. With recorded detector intensities, we could Fourier transform the data to determine each detector’s bandpass. The code behind this seemed magical at first, but understanding it taught me much about frequency response, power spectra, and the telescope itself. I used this setup to test metal mesh for its optical response as part of my departmental experimental project.

<div class="row">
    <div class="row justify-content-md-center">
        <div class="col-7 mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/fts_diag.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

Midway through the cryo run, Princeton University began shutting down non-essential operations due to COVID-19. Since the cryostat was already cold, our work was deemed essential—leaving a cold cryostat unattended risks ice plugs or thermal shorts, which can cause explosions. Once our work was complete, we safely warmed up and depressurized the cryostat before abandoning it.

The following year and a half was spent writing up my experimental project, tackling a hardware task, learning the XFaster power spectrum estimator, and preparing for our Texas deployment. The hardware project was in pull testing two parts of the solar array mounting scheme for SPIDER-2. I learned how to get parts machined, simulate forces in solidworks, and how to rig up a pull test in the highbay in Jadwin. XFaster needed their soon-to-be public product checked by someone who has never used it, so I was an ideal candidate. I just needed to understand some of their lingo and how to plot their products, but the experience was quickly valuable as I started the process of validating the python 3 implementation of XFaster later that fall in 2021. Packing for our collaboration trip to Texas was an enormous chore. The entire cryostat, gondola, and sun shield needed to be disassembled, bubble wrapped, and put in boxes and crates. A massive wood box was errected around the cryostat and then shrink wrapped. Even worse, all the lab materials and tools needed to be packed, including the toolchests and shelving units. The vacuum pumps, our nitrogen dewar, spare mylar, the FTS, even monitors and power strips were packed and meticulously documented with numbered stickers and a spreadsheet. Other than the cryostat and a few other crates, the remaining equipment was packed into two 10-ft sea containers, all loaded on a flatbed to Texas.

<div class="row">
    <div class="row justify-content-md-center">
        <div class="col-7 mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/packing_texas.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>

During the summer of 2022 we deployed to the Columbia Scientific Balloon Facility (CSBF) in Palestine, TX. This was part of the process to become flight-ready for deployment to Antarctica; NASA needed to make sure their equipment could attach and communicate with ours. We had some additional goals of our own: integrate the gondola, cryostat, and solar panel array together for the first time; insert the telescope that has been living at University of Illinois Urbana Champaign into the cryostat along with the others; and assemble as a team to practice the process of deployment. We lived out of a Motel 6, commuted to work every day together, and travelled to nearby cities like Dallas and Houston on the weekends for fun. Some of those days were the most fun I've had in grad school, and I appreciated the people there for being as accepting, helpful, and fun to hang with as they were. In Palestine, the process started with vacuuming the highbay for bugs and arranging work spaces. Unpacking in the Texas heat was brutal, as the sea containers were baking outside and we had to turn off the A/C for shuttling things in. Once sufficient progress was made in setting up the lab and opening the cryostat, two teams were formed: one to continue work on the cooldown and one to begin building the gondola and sunshield. I moved between teams as needed, since I had the most recent carbon fiber to aluminum glueing experience but was also just barely a cryostat cooldown veteran. Once cold, thermal and optical characterization could begin. Folks tested the star cameras, the sun sensors, the pivot and reaction wheel, and solar panels. We had access to a BEMCO test chamber, which we used to test electronics for the cold and low pressure of the stratosphere. With the gondola and sun shield complete, we could integrate the three on the crane and perform scanning. All that was left was to pack up everything all over again for the ice.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/texas_highbay.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/texas_orb.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/do_on_balloons.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The months after Texas and before Antarctica were a blur of last minute fixes, purchases and shipments, and general life planning before going down in October.  Our equipment had been semi-trucked to California, where it got on a boat to Christchurch, NZ. We arrived a few weeks before a flight window was available, so we stayed in Christchurch. Here, we were able to pick up the cold weather clothing distributed by the distribution center. Each person got the famous big red jacket, balclava, gloves or mittens, glove liners, snow pants, bunny boots for the snow, two orange dufflebags, and a few other odds and ends. After a RAT COVID-19 test and some presentations, we were ready to get on the C17 to get to the ice.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/c17_outside.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/c17_inside.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The flight was about 6 hours, with a minmal bathroom, jumpseats, a loud cabin, and low pressures. We landed on the sea ice behind Ross Island, on a groomed airstrip. We got to ride Ivan the Terrabus (now retired) to McMurdo, about 6 miles away.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ice_mcm.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

McMurdo is a research base on Ross island, with about 1,500 people in the summer and 500 in the winter. Folks deploy for either the 3 summer or 9 winter months. Our experiment flies above 99% of the atmosphere, so stray sunlight from the 24 hours of daylight a day don't bother us too much. Since the sun effectively goes in a circle at the same rate as the stars rotate, it means we can point our solar panels at the sun while while observing our patch of the sky at the same time. There's a gym, a dining hall, a USPS postal office, an ultimate frisbee course, three bars, and even a hairdresser on base. In your off-time, you could go on a number of near and far hikes, go underwater in the obs tube, or explore the free clothing/thrift stuff at the Skua building. There were signups to go to the New Zealand Scott base, as well as random activities like tug of war, and opportunities to go to other nearby camps for the day. We worked at the Long Duration Ballooning facility (LDB) about 9 miles away from McMurdo. Every day, we took vans or one of the many large transport vehicles to work. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/path_ldb_erebus.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ice_selfie.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

LDB is a temporary and mobile camp, with two highbays, a dining hall, a power station, facility building, fancy bathroom, and two latrines. The large structures are on skis and are dragged onto snowdrift piles over the winter to prevent them getting buried by the blowing snow. The small structures are built every season by construction workers at McMurdo. The location is chosen because it is on sea ice, and is flat for miles. This allows the preparation of a launch surface and minimizes the damage risk of payloads falling soon after launch. Deployed with us are the CSBF folks we worked with in the summer, some LDB coordinators, and two chefs to make us meals throughout the day. Every person with us made essential contributions to the work and on countless occasions went the extra mile for our safety, happiness, or science needs. We started by working in one big shift for unpacking, but soon switched to two shifts. The dining hall at McMurdo served four meals a day, each 6 hours apart, so it was possible to get one meal a day there for either shift. The majority of your waking time would be at LDB.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ice_ldb_line.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ice_lab_bigpic.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The team rushed to rebuild the lab, assemble, and begin the cooldown of the cryostat. We used the primary highbay for the lab, cryostat, and gondola, and the second highbay for assembly of the solar panel array. Repeating as much of the steps done in Palestine, we barely had time to characterize the instrument before we were told to fly ASAP. NSF decided they needed our beds in McMurdo for folks coming on the boat in January, so we had to expedite everything by many weeks. We flew the instrument on December 21st, a calm weather sunny day. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spider_ready_launch.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



<iframe width="900" height="500" src="https://www.youtube.com/embed/kewpdLlQ1mM?si=wtQv-I4ABIZ0amP-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>






The launch was aggressive, possibly crushing the star camera baffles and preventing them from functioning for the rest of the flight. We also launched only mostly full of cryogens, due to the aggressive schedule, which gave us only 9 days of cold detector time. We monitored the flight for a few days there, but quickly packed up everything to monitor remotely from Christchurch to free up the beds. The flight lasted 16 days and landed near enough to south pole station for our Spider alumni Sasha and a crew to go recover it. The harddrives, computers, electronics, gyros, sensors, and telescopes were all shipped back to Princeton. The remaining was left as "space debris" on the continent. A few scrap carbon fiber poles were salvaged for South Pole Station. Both the ceremonial and true south pole markers are now made with pieces of SPIDER! And even more honorifically, I heard someone used a piece as a broomstick.

Back at Princeton, I pushed now on the foregrounds paper

Will write more soon!