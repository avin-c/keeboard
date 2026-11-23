![Keyboard Final Render](https://cdn.hackclub.com/01a1fc4f-e8b8-7b2f-92d8-fe807563cc1f/Keyboard-Small.png)
# Keyz
My custom 65% mechanical keyboard as part of [Hack Club's Keeb/Fabricate YSWS](https://keeb.hackclub.com/).

## Description

My keyboard "Keyz" is a 65% mechanical keyboard powered by a Raspberry Pi Pico microcontroller. It uses the classic Gateron Quinn switches for a subtle tactile click, and is intended to be minimalistic with a compact layout while also providing the full functionality that an average keyboard user would need. It uses a sandwich mount to house the PCB, and features a rotary encoder to be used as volume control.

## Why I made it

I made this keyboard not because I percisely needed one, but because I had always dreamed of having a mechanical keyboard, but having a laptop did not pose a need to purchase one. Instead, I decided to create one instead. Another reason I chose to create this keyboard is because I am very interested in learning more about electronics and hardware, so I thought making a keyboard would be one of the best ways to get my feet wet. Anyways, this keyboard inspired me to make more projects, because it was so satisfying to go through the steps and end up with a full keyboard (at least in Onshape, I haven't actually built it yet). 

## Learning process

I learnt so much through the process of making this keyboard. I started off this project knowing absolutely nothing about keyboards at all, and know I have learnt how they work, the inner mechanisms, different types of casing, and how they are wired. In addiition, I also didn't know anything about KiCad before this project, but making this keyboard gave me a chance to learn how making a PCB works from the schematic to wiring up all the connections. It kinda surprised me how crazy the initial schematic to PCB stage was (it was VERY messy), and I was completely overwhelmed by the number of wires and connections. However, I managed to get through it and would consider myself having a solid beginner-level understanding of KiCad! I already knew about Onshape, but I definitely explored some new features in this project, like editing in context. 

Another thing this project taught me was how iterative the engineering process is, because I had a major hiccup when I thought I was almost done and got to buying keycaps, I realized that my switch sizes were not standard, and would entail 3d printing custom keycaps, which I didnt like the quality of. So I had to basically repeat the whole project with the schematic and the PCB to change the layout so that my keycap sizes were standard and fit the keycap set I was buying. 

Overall, this project was incredibly fun and taught me so much that I hope to apply in future projects. 

## Bill Of Materials 

[Link](https://docs.google.com/spreadsheets/d/1fL_IQgmIi_XlOX9ydgWSfowry5usrP5Ks7BfyhSlTqM/edit?gid=0#gid=0) to the BOM in Google Sheets with most updated info. 

| Category | Item | Quantity | Unit Cost (CAD) | Total Cost (CAD) | Total Cost (USD) | Supplier |
|---|---|---:|---:|---:|---:|---|
| Electronics | EC11 Rotary Encoder | 1 | $4.44 | $4.44 | $3.10 | [DigiKey](https://www.digikey.ca/en/products/detail/bourns-inc/PEC11R-4215K-S0024/4499662) |
|  | 1N4148 Diode | 100 | $0.54 | $5.43 | $3.79 | [DigiKey](https://www.digikey.ca/short/thzf78m3) |
|  | Raspberry Pi Pico | 1 | $3.49 | $3.49 | $2.43 | [AliExpress](https://www.aliexpress.com/item/1005007104120926.html) |
| PCB | PCB | 5 | $5.74 | $28.70 | $20.02 | JLCPCB |
| Case accessories | M2.5 Heatset Insert | 6 | $0.29 | $1.74 | $1.21 | [DigiKey](https://www.digikey.ca/short/qzncdpv7) |
|  | M2.5 Screw | 6 | $0.18 | $1.10 | $0.77 | [DigiKey](https://www.digikey.ca/short/h5w2dz84) |
| Keyboard | Gateron Chocolate Smoothie | 1 | $37.15 | $37.15 | $25.91 | [Amazon](https://www.amazon.ca/Chocolate-Smoothie-Mechanical-Switches%EF%BC%8CRGB-Pre-lubed/dp/B0FQHZD596) |
|  | MX Stabilizers | 1 | $12.39 | $12.39 | $8.64 | [AliExpress](https://www.aliexpress.com/item/1005011961905061.html) |
|  | Keycaps | 1 | $33.89 | $33.89 | $23.64 | [Amazon](https://www.amazon.ca/KBDiy-Keycaps-Percent-Mechanical-Keyboard/dp/B0CT5C2B8F) |
| Shipping | JLCPCB Shipping | — | $21.44 | $21.44 | $14.95 | JLCPCB |
|  | DigiKey Shipping | — | $15.00 | $15.00 | $10.46 | DigiKey |
|  | AliExpress Shipping | — | $9.03 | $9.03 | $6.30 | AliExpress |
| **Subtotal** | | | | **$173.80 CAD** | **$121.22 USD** | |