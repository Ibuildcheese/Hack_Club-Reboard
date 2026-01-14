# The ReBoard
This is an 87 key custom ANSI mechanical keyboard with a Raspberry Pi Pico microcontroller using QMK Software to program the Pico. All keys in the firmware are 100% ANSI since i did not want any miscommunications or things not working. Also, i am using Cherry MX Blue switches.

## Why/how i made this
---YAP WARNING---
Firstly, i want to say that this will be the first PCB that i have ever made and it was all because i thought making a new keyboard would be easier than cleaning my old one. My dell keyboard, sk-8125, my dad bought before i was born, and it was discontinued 10 yrs ago, and because of that i comitted myself to making a keyboard better than something from that time period by myself. first I looked up a bunch of tutorial videos but since they didnt help me at all i decided to just get started and go from there. this took multiple weeks to complete, even though the journal says it was a few hours, there was a lot of time in between from waiting on a friend to answer a question i had to having to completely scrapping my initial 100% keyboard i had in mind because of some fatal errors i made during the schematic. It's crazy even to me how i even began to design this keyboard, even though to others it may see this as a single day of work, because with the amount of issues and redos i encountered, i never would have thought i'd finish in time, let alone ~20 days before the deadline. Even though all this inexperience did come at a cost (i.e. spending 3 whole days to find a 3d-model of a cherry MX switch) i still cant thank Hack Club enough for giving me the opportunity to actually get started making amazing projects like these and being able to learn and problem solve along the way.





Screenshots of Design: 
| PCB - Front - Rendered | PCB - Back Rendered |
| :-: | :-: |
| ![PCB-Front-Rendered](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/Kicad-Stuff/Screenshots_PCB/Screenshot%202026-01-10%20144238.png) | ![PCB-Back-Rendered](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/Kicad-Stuff/Screenshots_PCB/Screenshot%202026-01-10%20144326.png) |
| PCB - Editor - No-Silk | PCB - Editor - Silk |
| ![PCB-Editor-No-Silk](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/Kicad-Stuff/Screenshots_files/Screenshot%202026-01-09%20203002.png) | ![PCB-Editor-Silk](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/Kicad-Stuff/Screenshots_files/Screenshot%202026-01-09%20203247.png) |


| Schematic | 
| - |
| ![Schematic-Img](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/Kicad-Stuff/Screenshots_files/Screenshot%202026-01-01%20163216.png) |


| CAD - Render - Main |
| - |
| ![CAD-Render-Main](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/CAD-Stuff/Screenshot%202026-01-10%20143353.png) |


| CAD - Render - Top | Cad - Render - Bottom |
| - | - |
| ![CAD-Render-Top](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/CAD-Stuff/Screenshot%202026-01-10%20143416.png) | ![CAD-Render-Bottom](https://github.com/Ibuildcheese/Hack_Club-Reboard/blob/7343492319bec55ae462279876c31e415d880496/CAD-Stuff/Screenshot%202026-01-10%20143404.png) |


| Amt | Name | Price | Link | Extra |
| - | - | - | - | - |
| x90 | Cherry MX Blue Switches | $35.10 | [Link](https://mechanicalkeyboards.com/products/cherry-mx2a-blue-60g-clicky?_pos=2&_sid=bf2bd6148&_ss=r) | --- |
| x98 | Cherry Profile Keycaps | $1.30 | [Link](https://www.aliexpress.us/item/3256808041449227.html?) | color: beige |
| x5 | Stabilizers | $0.99 | [Link](https://www.aliexpress.us/item/2251832533420646.html?spm=a2g0o.productlist.main.5.7b6577e2Yscqyc&algo_pvid=c163669a-a44a-4b97-9e21-d23b1fda5f76&algo_exp_id=c163669a-a44a-4b97-9e21-d23b1fda5f76-4&pdp_ext_f=%7B"order"%3A"17"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&pdp_npi=6%40dis%21USD%216.77%210.99%21%21%216.77%210.99%21%40210328df17678377393013546e1a13%2165420166339%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A182e906%3Bm03_new_user%3A-29895%3BpisId%3A5000000197821809&curPageLogUid=zKsTUTlgY3SV&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A32719735398%7C_p_origin_prod%3A#nav-specification) | --- |
| x100 | Diodes | $0.55 | [link](https://www.aliexpress.us/item/3256807350544438.html?) | 100pc option |
| 1x | PCB | --- | [link](JLCPCB.com) | --- |
| 1x | 3d Printed Case | --- | --- | I will print it myself |
| 1x | Raspberry Pi Pico | $0.99 | [Link](https://www.aliexpress.us/item/3256806652932348.html?spm=a2g0o.productlist.main.8.44ffuTLKuTLKsE&aem_p4p_detail=2026010718244013304767345269600011022831&algo_pvid=491d9255-221c-4dfd-ad03-dacfc034d7d2&algo_exp_id=491d9255-221c-4dfd-ad03-dacfc034d7d2-7&pdp_ext_f=%7B"order"%3A"257"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&pdp_npi=6%40dis%21USD%213.75%210.99%21%21%2126.04%216.86%21%402101ea8c17678390808077217e18be%2112000038471919200%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A715067b2%3Bm03_new_user%3A-29895%3BpisId%3A5000000197827679&curPageLogUid=cVG8WUSqI175&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006839247100%7C_p_origin_prod%3A&search_p4p_id=2026010718244013304767345269600011022831_2&_gl=1*11bd334*_gcl_aw*R0NMLjE3Njc2NzA0MjQuQ2p3S0NBaUEzLTNLQmhCaUVpd0EyeDdGZEFBaGpWenhGb3o1c0NHWmVUbjdBRTVpWGpJSkRzd1dDSWdHanBCTC1wNl8xd2lnMlpEN2d4b0NCRUFRQXZEX0J3RQ..*_gcl_dc*R0NMLjE3Njc2NzA0MjQuQ2p3S0NBaUEzLTNLQmhCaUVpd0EyeDdGZEFBaGpWenhGb3o1c0NHWmVUbjdBRTVpWGpJSkRzd1dDSWdHanBCTC1wNl8xd2lnMlpEN2d4b0NCRUFRQXZEX0J3RQ..*_gcl_au*Mjc0MDIyNDQyLjE3NjIyOTgzNzU.*_ga*MTg3Mzg2ODk5LjE3Njc2NzA0MjQ.*_ga_VED1YSGNC7*czE3Njc4MzY4NzgkbzIkZzEkdDE3Njc4MzkwODIkajU2JGwwJGgw#nav-specification) | --- |
| --- | Total | --- | --- | --- |

Screenshots of BOM
