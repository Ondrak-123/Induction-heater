Macondo link: https://macondo.hackclub.com/projects/6495
# Induction heater
- **This project is an Induction heater based on oscillation (ZVS-Zero Voltage Switching).**
- **The journal can be found at https://stasis.hackclub.com/dashboard/projects/cmmuu5lqf00kx01ns6pu1y2ej (project was started on Statis and now will be finished on Macondo!**
- **The journal features all guides, progress, explanations on how ZVS works and why it is the best way.**
  
**Why am I using softswitching and what is it?**

- Soft switch makes sure that the circuit is not powered instantly but after some time, when connecting an aligator clip or other power source you connect and disconnect the power supply multiple times which can fry the mosfets.

**Why is it called "Zero Voltage Switching"?**

- If one side of the circuit reaches zero volts, it triggers one MOSFET to turn on, while the other stays off and this cycle continues on and on.

**Why is it so efficient?**

- It is efficient thanks to the zero voltage switching, as you can probably tell by the name the mosfets switch at zero volts, thanks to this there is not as much heat generated.

_**Pictures:**_

<img width="1228" height="541" alt="image" src="https://github.com/user-attachments/assets/c6b14349-c095-47d8-a065-b4256c72ea10" />



<img width="797" height="792" alt="image" src="https://github.com/user-attachments/assets/4f14feee-bc7d-4030-924d-f5326a7db9ec" />


<img width="793" height="800" alt="image" src="https://github.com/user-attachments/assets/0d1c5250-86f1-4c01-bfb3-64961b2842e8" />



<img width="882" height="867" alt="image" src="https://github.com/user-attachments/assets/69db1c0f-746f-40e5-b2ec-396d9d2dd843" />



<img width="882" height="882" alt="image" src="https://github.com/user-attachments/assets/50c3abb7-47a7-4809-822a-4516716d7130" />


<img width="865" height="690" alt="image" src="https://github.com/user-attachments/assets/c330a3fa-7833-4d4b-ae50-9d3d749192f4" />



<img width="934" height="614" alt="image" src="https://github.com/user-attachments/assets/841e6934-75f4-4297-b8ff-3bbeb92c320a" />



Created a completely new BOM!:

| I will be using a seller based in the EU. (TME.EU). to avoid new tariff for the EU. I also included AliExpress link so everyone can do this project. I will have 2 orders one from JLCPCB that costs 8.44$. second one from TME.EU. all costs calculated in the total. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Name | Symbol/TME Code: | Purpose | Link: | Quantity needed: | Total Cost (CZK): | Total cost (USD): |  |  |  |  | Link | Distributor |  |  |  |  |  |  |  |  |  |
| PCB |  | From JLCPCB | * | 1 | *0* | $8.44 |  |  |  |  | https://jlcpcb.com/ | JLCPCB |  |  |  |  |  |  |  |  |  |
| IN4007 Diode |  | For soft starter. | * | 1 | *0* | *0* |  |  |  |  | https://www.aliexpress.com/item/1005010128860199.html?spm=a2g0o.productlist.main.13.321cVeUsVeUsDv&algo_pvid=5d1dc292-8c1d-47fc-b26f-221b35f9f573&algo_exp_id=5d1dc292-8c1d-47fc-b26f-221b35f9f573-31&pdp_ext_f=%7B%22order%22%3A%22320%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.35%211.24%21%21%219.26%218.51%21%40211b61d017747780040114660e2416%2112000051243238520%21sea%21CZ%216063877758%21X%211%210%21n_tag%3A-29919%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895%3BpisId%3A5000000203375670&curPageLogUid=wIl4TFkDRmTA&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010128860199%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Resistor 100KR |  | For soft starter. | * | 1 | *0* | *0* |  |  |  |  | https://www.aliexpress.com/item/1005007539842999.html?spm=a2g0o.productlist.main.13.77d7zj23zj23DF&algo_pvid=1429645b-4a36-4119-a7b3-98d736dedff9&algo_exp_id=1429645b-4a36-4119-a7b3-98d736dedff9-12&pdp_ext_f=%7B%22order%22%3A%2220994%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005007539842999%22%2C%22orig_item_id%22%3A%221005006898731441%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.01%211.50%21%21%2120.72%2110.36%21%402103849717747778049343615ed4db%2112000041212987998%21sea%21CZ%216063877758%21X%211%210%21n_tag%3A-29919%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=Yploor7BfNi6&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007539842999%7C_p_origin_prod%3A1005006898731441 | Aliexpress |  |  |  |  |  |  |  |  |  |
| Power cable |  | For power. HIGH AWG. | * | 1 | *0* | *0* |  |  |  |  | https://www.aliexpress.com/item/1005005203646529.html?spm=a2g0o.productlist.main.3.2506vKL4vKL4H0&algo_pvid=1ff6970a-e554-417a-9736-11d1abc39dd8&algo_exp_id=1ff6970a-e554-417a-9736-11d1abc39dd8-20&pdp_ext_f=%7B%22order%22%3A%223659%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.47%210.42%21%21%210.47%210.42%21%40211b813b17747164515903870eec0a%2112000032140706915%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=I0lyyNmGkllr&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005203646529%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Freewheeling diode SB1100 | SB1100-DIO | 100V 1A | https://www.tme.eu/cz/details/sb1100-dio/diody-schottky-tht/diotec-semiconductor/sb1100/ | 2 | 7.020 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005007349885370.html?spm=a2g0o.productlist.main.1.6f9059c6bqkyBC&algo_pvid=39d6c1ab-6498-423b-9c55-4e7187bf4bcb&algo_exp_id=39d6c1ab-6498-423b-9c55-4e7187bf4bcb-0&pdp_ext_f=%7B%22order%22%3A%2266%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.32%210.99%21%21%2115.91%216.83%21%4021038da617740285924222759ed468%2112000040372339094%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895%3BpisId%3A5000000197850273&curPageLogUid=PDHqQEwCMyGC&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007349885370%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Resistor 47R 5W | 5W-47R |  | https://www.tme.eu/cz/details/5w-47r/rezistory-tht/royalohm/mor05sj0470afi/ | 1 | 23.86 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005007330288041.html?spm=a2g0o.productlist.main.46.767211fb70dwNG&aem_p4p_detail=202603201035359611494668413260001781554&algo_pvid=670cf7c4-ff83-4457-ae64-fbd872d743d6&algo_exp_id=670cf7c4-ff83-4457-ae64-fbd872d743d6-39&pdp_ext_f=%7B%22order%22%3A%22534%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.66%210.54%21%21%214.49%213.68%21%4021038e1e17740281354252687e86c1%2112000040294719771%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=U4fOPbpAK6XU&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007330288041%7C_p_origin_prod%3A&search_p4p_id=202603201035359611494668413260001781554_10 | Aliexpress |  |  |  |  |  |  |  |  |  |
| Zener diode 15V 1W | 1N4744ATR |  | https://www.tme.eu/cz/details/1n4744atr/zenerovy-diody-tht/onsemi/ | 2 | 8.480 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005006886308114.html?spm=a2g0o.productlist.main.12.763565e2VxvOFJ&algo_pvid=1daef451-8bd2-46a3-bdec-a26d66933992&algo_exp_id=1daef451-8bd2-46a3-bdec-a26d66933992-37&pdp_ext_f=%7B%22order%22%3A%2238%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.83%210.99%21%21%211.83%210.99%21%402103956b17740280088897737e333c%2112000038620719183%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895%3BpisId%3A5000000197850273&curPageLogUid=5Mdrg3XuXAoh&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006886308114%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Resistor 150R 5W | AC05-150R-5% |  | https://www.tme.eu/cz/details/ac05-150r-5%25/vykonne-rezistory/vishay/ac05000001500jac00/ | 2 | 43.86 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005003645133625.html?spm=a2g0o.productlist.main.16.338e1d45dktWii&algo_pvid=601066ed-8d9a-4710-bbdd-b970ac96d48e&algo_exp_id=601066ed-8d9a-4710-bbdd-b970ac96d48e-8&pdp_ext_f=%7B%22order%22%3A%2256%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.29%210.90%21%21%218.85%216.19%21%40211b80e117740277498711473ed231%2112000026631349304%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=fSkWTN76PRrU&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005003645133625%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Thermal paste | QOLTEC-51630 | Better heat transfer. | https://www.tme.eu/cz/details/qoltec-51630/teplovodni-pasty/qoltec/51630/ | 2 | 45.02 | *0* |  |  |  |  | https://www.aliexpress.com/item/32833422141.html?spm=a2g0o.productlist.main.1.154ethvKthvKIr&algo_pvid=386a2713-dae7-4a0d-9e44-34a7fa4773e2&algo_exp_id=386a2713-dae7-4a0d-9e44-34a7fa4773e2-0&pdp_ext_f=%7B%22order%22%3A%22228%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.79%210.52%21%21%210.79%210.52%21%40210391a017740270953226446ea508%2165038750325%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=HXpijeaxpZ5p&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A32833422141%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Capacitor 220uF | CE-220/16PHT-Y | For soft starter. MOQ: 20 | https://www.tme.eu/cz/details/ce-220_16pht-y/elektrolyticke-kondenzatory-tht/aishi/ewh1cm221e11ot/ | 1 | 32.74 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005007322240823.html?spm=a2g0o.productlist.main.3.4e4e6b597IeBnf&algo_pvid=02edfb23-74d5-47b3-b85f-622b369b29b5&algo_exp_id=02edfb23-74d5-47b3-b85f-622b369b29b5-2&pdp_ext_f=%7B%22order%22%3A%222020%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.23%210.86%21%21%211.23%210.86%21%40211b61bb17740248918105586ea653%2112000040256770954%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=mx3EbfFRgrpO&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007322240823%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Capacitor 1.5uF/2uF | C4AF9BU4150A1XK | ZVS switching. | https://www.tme.eu/cz/details/c4af9bu4150a1xk/kondenzatory-foliove-tht/kemet/ | 2 | 157.16 | *0* |  |  |  |  | https://www.tme.eu/cz/details/c4af9bu4150a1xk/kondenzatory-foliove-tht/kemet/ | Aliexpress |  |  |  |  |  |  |  |  |  |
| Resistor 10KR 5W | CRL5W-10K | ZVS switching. MOQ: 10 | https://www.tme.eu/cz/details/crl5w-10k/vykonne-rezistory/sr-passives/ | 2 | 28.46 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005006363058219.html?spm=a2g0o.productlist.main.11.45e51d57BhhODY&algo_pvid=e61700af-3e94-40c6-837f-8b9eb99a6b25&algo_exp_id=e61700af-3e94-40c6-837f-8b9eb99a6b25-10&pdp_ext_f=%7B%22order%22%3A%22475%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.76%210.66%21%21%210.76%210.66%21%402103834817740246522776895e1674%2112000036899412422%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=xUFUBN3jZzu6&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006363058219%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Transistor 2N7000 | 2N7000-DIO | For soft starter. | https://www.tme.eu/cz/details/2n7000-dio/tranzistory-s-kanalem-n-tht/diotec-semiconductor/2n7000/ | 3 | 18.13 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005007206189883.html?spm=a2g0o.productlist.main.10.52b815e34eyS3k&algo_pvid=1b9e943d-a183-49b7-ac1c-45ea658339a3&algo_exp_id=1b9e943d-a183-49b7-ac1c-45ea658339a3-48&pdp_ext_f=%7B%22order%22%3A%2225%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%210.94%210.94%21%21%210.94%210.94%21%40211b629217740244743261900e83ca%2112000039805368214%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=WkHDqQGZD8lz&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007206189883%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Inductors | DPT220A5 | Inductors 220uH. | https://www.tme.eu/cz/details/dpt220a5/tlumivky/ferrocore/ | 2 | 107.3 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005009049853632.html?spm=a2g0o.productlist.main.31.774bojbOojbOFw&algo_pvid=b89a5244-83fa-4ea0-8365-d1b630e0f499&algo_exp_id=b89a5244-83fa-4ea0-8365-d1b630e0f499-30&pdp_ext_f=%7B%22order%22%3A%22147%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%215.02%214.32%21%21%2134.38%2129.57%21%40210384b217740241582097454e3e8a%2112000047712666401%21sea%21CZ%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=ZMnsTrP83ZAj&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009049853632%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Heatsink | SK104-38STS | Mosfet Cooling. | https://www.tme.eu/cz/details/sk104-38sts/chladice/fischer-elektronik/ | 2 | 129.23 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005002711238683.html?spm=a2g0o.productlist.main.50.477a4914euPoik&algo_pvid=c910c5e1-95dc-480b-b3f9-444ed5662ba6&algo_exp_id=c910c5e1-95dc-480b-b3f9-444ed5662ba6-49&pdp_ext_f=%7B%22order%22%3A%22145%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%213.88%211.88%21%21%213.88%211.88%21%40211b813b17739477792101402edb6e%2112000021815358235%21sea%21CZ%210%21ABXZ%211%210%21n_tag%3A-29910%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895%3BpisId%3A5000000200562567&curPageLogUid=QgMZjcoePbgO&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005002711238683%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Mosfet IRFB7730 | IRFB7730PBF | ZVS switching. | https://www.tme.eu/cz/details/irfb7730pbf/tranzistory-s-kanalem-n-tht/infineon-technologies/ | 2 | 159.04 | *0* |  |  |  |  | https://www.aliexpress.com/item/1005011844869795.html?spm=a2g0o.productlist.main.6.331aK3nTK3nTPQ&algo_pvid=cbc9dd74-dd5a-4a77-907d-66a1834d7ddf&algo_exp_id=cbc9dd74-dd5a-4a77-907d-66a1834d7ddf-5&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%214.54%214.54%21%21%2131.23%2131.23%21%40210388c917747806068723055e2327%2112000056762259380%21sea%21CZ%216063877758%21X%211%210%21n_tag%3A-29919%3Bd%3A1803c9ff%3Bm03_new_user%3A-29895&curPageLogUid=CfFBsAtcuWCR&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005011844869795%7C_p_origin_prod%3A | Aliexpress |  |  |  |  |  |  |  |  |  |
| Coil |  | Few turns of solid copper wire. | * | 1 | *0* | *0* |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| TME Shipping |  |  | * |  | 169.41 | *0* |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  | 929.71 CZK | 8.44USD |  |  |  | I will not be using these links. but I included them so you cam do this project even if you are not in EU. |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | 929.71CZK = | 44.97 USD |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  | ´+8.44 USD |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  | TOTAL: | 53.41 USD |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  | REQUESTING AMOUNT: |  | 58 USD |  | SCREENSHOTS/CARTS BELOW!! |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  | TME.EU |  |  |  |  |  |  |  |  |  |  |  |  |  |  | LCSC.COM |


<img width="1687" height="670" alt="image" src="https://github.com/user-attachments/assets/0fc959c1-8449-49c5-aaf7-aaf2be7b9e52" />



<img width="1424" height="632" alt="Snímek obrazovky 2026-08-20 191143" src="https://github.com/user-attachments/assets/ce8a07cb-ff36-42ab-a8d9-c55f5e3dd758" />
<img width="1309" height="680" alt="Snímek obrazovky 2026-08-20 190943" src="https://github.com/user-attachments/assets/62ee1f60-91d7-4683-86c4-776b170ba3ec" />

