# JBL Quantum 910 Voice Prompt Control

A small unofficial utility for muting and unmuting the **JBL Quantum 910 voice prompts**. Because apparently adding a fucking toggle for this was too difficult.

> [!WARNING]
> This is an unofficial tool and is not affiliated with, endorsed by, or supported by JBL or Harman. It writes the relevant setting directly to the headset. Use it at your own risk.

## Why Does This Exist?

My Sony WH-1000XM5 headphones broke after the earcup hinge basically crumbled like a soft oatmeal cookie, so I went to a store to buy a new pair. After spending roughly 20-30 minutes looking at different options, I ended up buying the **JBL Quantum 910**. Almost immediately I discovered two problems: the battery life on my unit was complete fucking garbage, lasting roughly **4–6 hours from a 100% charge**, and the voice prompts were so absurdly loud that every time I powered the headset on it felt like some woman was trying to scream status messages directly through my skull. I normally put my headphones on before turning them on, which apparently makes me incompatible with JBL's brilliant design philosophy of blasting voice prompts into your ears at whatever ridiculous volume they decided was appropriate.

So I contacted JBL support and explained both problems. The headset was around three weeks old, the battery lasted only a few hours, and I wanted the voice prompts disabled because they were obnoxiously loud. I asked for an RMA so I could return the headset and replace it with something from another brand. JBL support refused. I was told that the voice prompts could not be disabled because of a **firmware limitation**, and for the battery issue I was expected to start doing troubleshooting at home before they would proceed with service.

I bought new headphones. New headphones are supposed to fucking work. I am not spending an hour of my own time swapping cables, testing chargers, waiting through charging cycles and doing diagnostic work for a multi-billion-dollar electronics manufacturer because the product I bought three weeks ago cannot manage more than a few hours on a full charge. At the time I did not even have another suitable cable that physically fit properly into the recessed connector on the headset. If I need to go buy extra shit and then spend my evening troubleshooting JBL's nearly new product for them, they can start paying me an hourly rate.

I eventually received a replacement headset through service. At the time of writing this I have not even properly tested whether the replacement has the same battery issue, although I would fucking hope not. My original plan was to get rid of the thing completely. The replacement was brand new and unopened, so I listed it on Marketplace for around **€100–120**. After a few days the listing had received something like six views.

At that point I decided: Fuck it.

Instead of practically giving the headset away, I started digging into how this piece of shit actually works. I figured out the relevant parts of the device communication, wrote the changes directly to the headset and built my own application that can **mute and unmute the voice prompts**.

JBL support told me they could not be disabled because of a firmware limitation.

Turns out I wanted them disabled more than JBL wanted to give me a useful answer.

## Compatibility

| Device          | Firmware | Status |
| --------------- | -------: | ------ |
| JBL Quantum 910 |    3.3.0 | Tested |

Other firmware versions, hardware revisions and JBL Quantum models are untested unless explicitly stated otherwise.

## Source Code

The source code is **not available**, and that is completely intentional. After the support experience that resulted in this project existing in the first place, I have absolutely zero interest in making this even one fucking inch easier for JBL. They manufacture the hardware, they write the firmware, and they presumably know perfectly well how their own device works. If they want a button for disabling voice prompts in their own software, they can figure it out themselves.

The application is available. The source code is not. Check Releases.

## Disclaimer

This software is provided **as-is**. It is an unofficial tool that modifies a setting on the headset in a way that JBL does not officially support. There is no guarantee that it works with other firmware versions, hardware revisions or JBL products, and you are responsible for anything you do with your own hardware.

**JBL**, **Quantum** and related names are trademarks of their respective owners.
