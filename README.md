# M490G Mic Input Module · Input Pre Amps

Ward-Beck Systems M490G, 1978|11. Wiki page: [M490G on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M490G.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 25 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 20 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 210 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 9 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 33 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Circuit description

From [1978 - M490G - Mic Input Module (2).pdf](MANUALS/1978%20-%20M490G%20-%20Mic%20Input%20Module%20(2).pdf) pages 2-7 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Parts List 3-1 103-9

CO.016 Circuit Dete 14C76 Circuit Date 14C221 Circuit Oala

O&lt;&quot;a... I&quot;' 9S:

M.9OG Front Panel 849Q....04-016 &quot;&quot;. 9OG functlone l 8490-01_008 M. 9QG Schematic 8490-02_008 &quot;&quot;.9QG Component Layout 8490-06-018 &quot;&quot;. 9QG Connector Layout 8490-M_015

MANUAL ISSUE '2.

WAR CBECKS YSTEM S LTC.

**TECHNICAL DATA**

M4gOG Ml e INPUT MODULE

Input Sen sill v i t y: -60 10 -30 dBm (ref. 150 ohms ou rce).

F&quot;requency ResPonse: +/-0.5 dB from 30 Hz to 20 kHz.

1 25 dBm ElM lit maximum SENSITIVITY (20 Hz 10 20 kHz).

HarmoniC: O; sl o.t ion: Le u Ih ll n 0.3 5S THD from 30 Hz 10 20 kHz III 20 d B llbo ve nominlll OPe r all n g level or rees, Le u than O. l S III I kHz lit 20 dB ll bo venom ina l opera lin g level or less.

Len lken 0.5 S 1111kHz through cue c:hannel lit 20 d B llbove nominal opera lin g level or less.

Source I mpe dance: 150 ohms, b ll lll n ced/ u nba l ll n c ed.

Input Imp e dance: 750 ohms, minimum.

30,000 ohm., b ll l ll nc ed (p.... g rllm c ircu il s). 60,000 ohm., balanced (cue ci rcu il s).

OUIPU I Level: o dBm nominlll, +25 dBm maximum (equi vll len i vOl lll g e 600 ohms).

P h ll sing: Inp ul and ou tpu l le..... ina l s design al ed b y number. lire in phase, 0.lo wer number of numbered p a,r;. in phase w ' l h lower number of olher numbered plli r.

Logic In p u l Levels: fT o operate CH ON, CH OF&quot;F&quot; Ct CUE).

Logic 0: 0 to +13 volts.

Logic 1: +16 to +24 vol l s.

Ext e r n ll l Control Output: l Open collector currents in k).

Minimum reee Impedll nc:e:

600 ohms.

Mllxlm um 10 ll d current: 40 rnA.

Maximums u p ply vol l &quot;,g e: +24 volts.

Sa lurat edc:o ll ec tor volt llg e: +2 volts m llxi mum lit 40 mA load.

**TECHNICAL DATA**

Power Req u i r emenl s, &quot; / -25 volts oc, 40 mA &quot;omi nal, 80 &quot;'&quot;

o 10 60 degrees Celsius.

1.6&quot; wide.. 14.1 5 &quot; high.. 6.5 &quot; deep (4 1 mm.. 360 mm.. 165 mm l.

M4 900 MIC INPUT MODULE

The M4 SOG p ~ovides complete mic~op hone channel fac il ilie s, inclusive of a slide mixing atl en&quot; ato~, sO&quot; r&lt;e setecrc rand mixing bus a sslgn menl s w i l ches, as ~eq ui~ ed fo~ a m ixi ns console inpul.

I n pu land P~e ampl ifie~

Tn &quot; m&quot; lu ally in le~ locked INPUT SELECTOR swi lc hes SWI and SW2 allow lh e select ion o f one oft wo avail a bl &quot; mic~ophon e sou~c es. An addil_ io na l c onl acl is.. &quot;ppl i&quot;d fo~ cont~ol p,, ~poses on &quot; a c n sw ilc h.

T ne Impedance pr-esented by lhe inpu l l ~an s fo ~ m e~ T l iss &quot; b Slant ia l l y highe~ than l he nominal sourc &quot; impedance o f 150 ohms. These con d a ~ y of Tl i.. conn ecled to lh e prea mplifi er con.. i.. ting of 01 IhrQ&quot;g h Q7 and Z I. In P&quot;1 sens ilivi ly of lh e mod &quot; l e maybe var ied by ad j&quot; slment of Ih e SENSITIVITY trim pOl R25, covering a range of 30 d B. R25 I sac ce.... ible I h rough I h e module fronl panel, a d ja ce n l 10 Ih e INPUT SELECTOR switches. The balanced pr.. amp l i f i.. ~ output appea ~s at mod &quot;l.. conn eClor P2, pins ofF.

Two series-con nec ted, balanced l rvse r-t points a r.. made avail a b l.. a l P2, pins 6 / F, e/r, 5/ E and 7/H, ope ~ a ting alan om ina l level of o dBm. Th&quot;y allow Ihe In.... r lion o fan c ill a r y processing &quot; q u ipmenl inlo lh &quot; mixing chan n,, 1 signal pal h..u c h a.. a com pr &quot;sso ~,..qu a liz.. r o~ fill.. r. The pro vision of Iw o s.. r l.. s-c coo ect.. dIn se ~t poi n l S p.. rmi t s lh.. utili zal ion o f I h.. module i n.. t..r..o &quot; ys l ems such asl h.. WBS R 1200 / R2 000 Con Sole... I n Ihes e and sim ila r.. p pl ic a lions, I h e f unc l lon s.... SOcial e dWi l h the left end rig hl Insertion selectors (M499) may both b.. I ns&quot;rled into I h e channel, with the left chennel i n se ~l f &quot;nCl ion p~ec.. d in9 lh e righl chen n el function.

F~om lh eIn s.. rl POinIS, l he signal is rou led 10 ATTl, a b.. lanced

slide.. tlenu a lor fe.. t &quot; ring.. conl ln u ou s mixing r.. ng e of more l hen

70 d B prior to cutoff. Th.. CUE channel f.. ed is t e ken from lhe In p&quot; l

side of Ih.. all.. nuator.

Program Channel Switch

Z2 i s a CMOS an.log switch, sl!'t&quot;\l'lng a s thea Cll ve switch ing element 01 the PROGRAM channel. The control vol lag e to ope,.ate 2 2 Is Ce,.l ved from the logic c ircult,.y within the module and is coupled to Z 2 via CRI. to,&quot;wl l c h the channel ON, Ihls control v o ll age i sin I he order of +10 volts. When the control voll aged ro p s to 0 volts, the switch will be OFF, &quot; esultlng ina signal allen u&quot; llon of more th.. n 100 d B.

Following Z2, In te g r'll ed clreuiU Z3 and Z4.. mp li f y the audio sl gn.. 1 t o a nominal level of 0 dBm (e q u Ivalen t voltage). &quot;rom thea mp li fie rout pu l, the s; g na l is routed tot h e PROGRAM ASSIGNs witches SW4, SWS, SW13, SW14 followed o y the mixing ou s outputs.

Fo u,. PROGRAM outputs PI, P2, P3 &amp; P4, are designed to feed Into four mixing buses. Operation of ASSIGNMENT SWITCHES SW4, SW5, SW13 &amp; SW14 will result In Ih • •ss l gn men t to Ih e PROGRAM of thea p p,.o p,.l ate mix ing o uses.

The CUE signal originates from a o ridging takeoff at the In p u l o f the slide e llenuator. Owing tot h e high input Impedance oft he CUE channel its operation hes noe ff ec l 0... the main PROGRAM channel. Z5 &quot;8I=I&quot;eHn IS Ih e audios witch fo,. the CUE channel. Simile r ly to Z2, the control voltage for Z5 is gene,.ated int he logic c ire u i t,. y a s cle scrioed fu,.the,. on. The output of Z5 Is followed o y Ihe booller emplif le&quot; Z6, which i n tu..... f~s the cue bus mixing network Rl 0 l through Rl 04.

The con lro l vol l...g e s requi,.ed to ope,....te the PROGRAMs witch 22 and the CUEs wItch ZS a,.e generated with Ihe aid of logic cireuil ry

utilizing integrated circuits Z7 through Z10.

28 is a CMOS dual f li p-f lcp serving a s ala tc h t o maintain the ~ l a 1U~ of 22 and 25, once they have b.... n se l toe i the r the ONo r the OFF position.

A number of individual i npu l fun clio n s govern the stat u ~ oft h e dual fl i p_flo p 2 8. A d e script ion of each input f u ncl ion follows;

When power i ~ i nit i ally applied to the system, the combination of CR9, CR 10, CRI Ian d CR40 will pull down bO l h &quot; c le ar&quot; input ~ of 26 until CAO is fully charged, thus e ns u ring that switches 22 and 25 are in the OFF position.

Momentary operation of the CHANNEL ON switch SW9 will produce a neg a t i v ego ing pulse at 26, pin 2 and &quot; preset &quot; thees ecueo of 28. Alternatively, a momentary ground closure oft h e EXTERNAL CHANNEL ON control input a t P2, pin N will result i nth e same condition.

Once the f l ip_ flop is &quot; pres et&quot;, its output a t pin 15 changes from 0 to 1 (approximate ly +10 volts). This will cause the PROGRAMs witch 22 to switch ON. Furthermore, 012 will sa lu rate resulting int h e CHANNEL ON indicator lamp DS3 to switCh o n. With 0 12 saturate d, the &quot; control common &quot; potential a p pea r$ a t thee m i tte rs of Cl13 and 014. &quot; POSi live base potential is applied to either 0 13 or 014, depending on whether INPUT SELECTORs witCh SWI o r SW2 is depressed. Eff e.:t i ve l y 0 13, and 0 14 operates i miia r ly tot wo AND gates. The collect o r s o f the two trans i s tors represent the outputs oft he AND gate $. They appear a t 1'2, pin 13 and P. Th e$ e terminals are capable of sinking ama ximum current o f 40 mAe a c h from a 24 volts our Ce and maybe used for muting purposes.

When opera ting the CHANNEL ON switch SW9, a separate contact is closed, access ib lea t P2, pin $ 15/S. This contact maybe used for control o r signaling purposes.

Pin R of 1'2 isis ola ted through diode CR3. When conn e&lt;:ted i n

parallel wilh the same output of other modules, it provides a convenient OR gate configuration, suitable tor ese t a com mon lime r

each time a CHANNEL ON button i$ depressed.

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRkxHTVpHeGNHMEk/view?resourcekey=0-KKPN-UAqHnijqFHNJbqOQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRkxHTVpHeGNHMEk&resourcekey=0-KKPN-UAqHnijqFHNJbqOQw" width="240" alt="1978 - M490G - 490-04-015 - CUE OUT RIGHT OFF TALLY.jpg"></a><br><sub>1978|11 · 490-04-015 - CUE OUT RIGHT OFF TALLY · <a href="MECHANICAL/1978%20-%20M490G%20-%20490-04-015%20-%20CUE%20OUT%20RIGHT%20OFF%20TALLY%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWtEOWVsSkEzS28/view?resourcekey=0-0KIXgdAu_eerYbJpEoOdAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWtEOWVsSkEzS28&resourcekey=0-0KIXgdAu_eerYbJpEoOdAw" width="240" alt="1978 - M490G - 490-04-015 - MIC INPUT MODULE.jpg"></a><br><sub>1978|11 · 490-04-015 - MIC INPUT MODULE · <a href="MECHANICAL/1978%20-%20M490G%20-%20490-04-015%20-%20MIC%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHo4VERLemVkOFU/view?resourcekey=0-7JS-tfW09Hfnv8j5msGbBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHo4VERLemVkOFU&resourcekey=0-7JS-tfW09Hfnv8j5msGbBg" width="240" alt="1978 - M490G - 490-04-016 - IGNA PURPOSES FROM REMOTE LOCAT ION RELATED.jpg"></a><br><sub>1978|11 · 490-04-016 - IGNA PURPOSES FROM REMOTE LOCAT ION RELATED · <a href="MECHANICAL/1978%20-%20M490G%20-%20490-04-016%20-%20IGNA%20PURPOSES%20FROM%20REMOTE%20LOCAT%20ION%20RELATED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd3ZPSWZlTWdydEk/view?resourcekey=0-NSczrThfqC8S7Toilf96Fg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd3ZPSWZlTWdydEk&resourcekey=0-NSczrThfqC8S7Toilf96Fg" width="240" alt="1978 - M490G - 490-04-016 - SWII WIL SWITCH CHE CUE CHANNE TERNATELY.jpg"></a><br><sub>1978|11 · 490-04-016 - SWII WIL SWITCH CHE CUE CHANNE TERNATELY · <a href="MECHANICAL/1978%20-%20M490G%20-%20490-04-016%20-%20SWII%20WIL%20SWITCH%20CHE%20CUE%20CHANNE%20TERNATELY%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQzVPeDEtY1doWFU/view?resourcekey=0-9ohnNeiugNaeSuKjr01nAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQzVPeDEtY1doWFU&resourcekey=0-9ohnNeiugNaeSuKjr01nAg" width="240" alt="1978 - M490G - 490-01-008 - INPUT MODULE FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1978|11 · 490-01-008 - INPUT MODULE FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1978%20-%20M490G%20-%20490-01-008%20-%20INPUT%20MODULE%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKajJONTZlN0l5dWs/view?resourcekey=0-xHrGjexpv7MrdahziD5MmQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKajJONTZlN0l5dWs&resourcekey=0-xHrGjexpv7MrdahziD5MmQ" width="240" alt="1978 - M490G - 490-01-008 - OFF ONISTART TIMER RESET OFF TALLY OFF ISTOP.jpg"></a><br><sub>1978|11 · 490-01-008 - OFF ONISTART TIMER RESET OFF TALLY OFF ISTOP · <a href="SCHEMATICS/1978%20-%20M490G%20-%20490-01-008%20-%20OFF%20ONISTART%20TIMER%20RESET%20OFF%20TALLY%20OFF%20ISTOP%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcG5GdW1kWFdrbEk/view?resourcekey=0-zGT3B0MUYtq4i94WlU1gLQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcG5GdW1kWFdrbEk&resourcekey=0-zGT3B0MUYtq4i94WlU1gLQ" width="240" alt="1978 - M490G - 490-02-008 - CAST COMPONENT DESIGNTIONS CRIC.jpg"></a><br><sub>1978|11 · 490-02-008 - CAST COMPONENT DESIGNTIONS CRIC · <a href="SCHEMATICS/1978%20-%20M490G%20-%20490-02-008%20-%20CAST%20COMPONENT%20DESIGNTIONS%20CRIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEo3VVptenZyb0E/view?resourcekey=0-u1pbodQP71rKlNdvDFE0Xg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEo3VVptenZyb0E&resourcekey=0-u1pbodQP71rKlNdvDFE0Xg" width="240" alt="1978 - M490G - 490-02-008 - MIC INPUT MODULE.jpg"></a><br><sub>1978|11 · 490-02-008 - MIC INPUT MODULE · <a href="SCHEMATICS/1978%20-%20M490G%20-%20490-02-008%20-%20MIC%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHFzUEM2b1Y5dFk/view?resourcekey=0-hLZb4tIgVjug-fq4eieJig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHFzUEM2b1Y5dFk&resourcekey=0-hLZb4tIgVjug-fq4eieJig" width="240" alt="1978 - M490G - 490-06-018 - ISSUR CSUCDITF OCISION ADO.jpg"></a><br><sub>1978|11 · 490-06-018 - ISSUR CSUCDITF OCISION ADO · <a href="SCHEMATICS/1978%20-%20M490G%20-%20490-06-018%20-%20ISSUR%20CSUCDITF%20OCISION%20ADO%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUlZ6ZFdxbmhqTGM/view?resourcekey=0-DPfxEb3tTYmlLSAUKGP9yg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUlZ6ZFdxbmhqTGM&resourcekey=0-DPfxEb3tTYmlLSAUKGP9yg" width="240" alt="1978 - M490G - 490-06-018.jpg"></a><br><sub>1978|11 · 490-06-018 · <a href="SCHEMATICS/1978%20-%20M490G%20-%20490-06-018%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M490G - RTO-144 Connections.pdf`

## RTO-144 pinout

22 contacts, 4 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | PGM | audio |  | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 3 | PGM 3 OUT | out |  | high |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | PGM 3 OUT | out |  | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 5 | PGM 2 OUT | out |  | high |
| 5 |  | unread |  | low |
| 6 | PGM 2 OUT | out |  | high |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | PGM 4 OUT | out |  | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 8 | PGM 4 OUT | out |  | high |
| 8 |  | unread |  | low |
| 9 | SHIELD | ground |  | high |
| 10 | NC | nc |  | high |
| 11 | IC | nc |  | high |
| 12 | IC | nc |  | high |
| 12 |  | unread |  | low |
| 13 | IC | nc |  | high |
| 13 |  | unread |  | low |
| 14 | IC | nc |  | high |
| 15 | CUE OUT, LEFT | out |  | high |
| 15 |  | unread |  | low |
| 16 | CUE OUT, LEFT | out |  | high |
| 17 | CUE OUT, RIGHT | out |  | high |
| 17 |  | unread |  | low |
| 18 | CUE OUT, RIGHT | out |  | high |
| 18 |  | unread |  | low |
| 19 | NC | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | NC | nc |  | high |
| 20 | COMMON | ground |  | high |
| 21 | NC | nc |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| 22 |  | unread |  | low |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |
| L | 8 CTL | control |  | low |
| M |  | unread |  | low |
| N |  | unread |  | low |
| P |  | unread |  | low |
| U |  | unread |  | low |
| V |  | unread |  | low |
| W |  | unread |  | low |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOF96VmpJMzZOM0U/view?resourcekey=0-BQ84TqAMU89qJLUWL0FWjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOF96VmpJMzZOM0U&resourcekey=0-BQ84TqAMU89qJLUWL0FWjw" width="240" alt="1978 - M490G - Mic Input Module (2).pdf"></a><br><sub>1978|11 · Mic Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKajFwdzJBM0Q1Rkk/view?resourcekey=0-xWjKk2jNBd5At6t61F6aYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKajFwdzJBM0Q1Rkk&resourcekey=0-xWjKk2jNBd5At6t61F6aYw" width="240" alt="1978 - M490G - Mic Input Module.pdf"></a><br><sub>1978|11 · Mic Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbDhtdFdWTy1MV0E/view?resourcekey=0-gF44LzVrgoLGNbxxj4UIPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbDhtdFdWTy1MV0E&resourcekey=0-gF44LzVrgoLGNbxxj4UIPA" width="240" alt="1978 - M490G - P001 - Title Page.jpg"></a><br><sub>1978|11 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmotZHB0bmhBWlE/view?resourcekey=0-KFoBTFI5CSu5DJu5UpFJmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmotZHB0bmhBWlE&resourcekey=0-KFoBTFI5CSu5DJu5UpFJmw" width="240" alt="1978 - M490G - P002.jpg"></a><br><sub>1978|11 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbWxRVTRlcEpzRWM/view?resourcekey=0-0XRfUz5ELoqNROUVpshUag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbWxRVTRlcEpzRWM&resourcekey=0-0XRfUz5ELoqNROUVpshUag" width="240" alt="1978 - M490G - P003 - 1-1.jpg"></a><br><sub>1978|11 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKemY5U1k2QXh3OEU/view?resourcekey=0-aFTLvNKBAqwWV0IPUzxVaQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKemY5U1k2QXh3OEU&resourcekey=0-aFTLvNKBAqwWV0IPUzxVaQ" width="240" alt="1978 - M490G - P004 - 1-2.jpg"></a><br><sub>1978|11 · P004 - 1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZi1GVjFrUmM2QTA/view?resourcekey=0-Cc9ZktKNEDHeck9h4fmimQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZi1GVjFrUmM2QTA&resourcekey=0-Cc9ZktKNEDHeck9h4fmimQ" width="240" alt="1978 - M490G - P005 - 2-1.jpg"></a><br><sub>1978|11 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd205WVkzUnAyVDQ/view?resourcekey=0-2HzwPmOaRx1JMuOel_R92w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd205WVkzUnAyVDQ&resourcekey=0-2HzwPmOaRx1JMuOel_R92w" width="240" alt="1978 - M490G - P006 - 2-2.jpg"></a><br><sub>1978|11 · P006 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHhyNFYxZlM5bVU/view?resourcekey=0-jqgzk82al9krwuKOl3yLTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHhyNFYxZlM5bVU&resourcekey=0-jqgzk82al9krwuKOl3yLTQ" width="240" alt="1978 - M490G - P007 - 2-3.jpg"></a><br><sub>1978|11 · P007 - 2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUdzWmFYSS1MNW8/view?resourcekey=0-y9TRYV3aISp5Fag5NLav7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUdzWmFYSS1MNW8&resourcekey=0-y9TRYV3aISp5Fag5NLav7w" width="240" alt="1978 - M490G - P008 - 2-4.jpg"></a><br><sub>1978|11 · P008 - 2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSU1MQ3dpU0Zqc3c/view?resourcekey=0-quOFd0UJhrhBWr-r6sNkew" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSU1MQ3dpU0Zqc3c&resourcekey=0-quOFd0UJhrhBWr-r6sNkew" width="240" alt="1978 - M490G - P009 - 2-5.jpg"></a><br><sub>1978|11 · P009 - 2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd01sYUpoQlpCdUk/view?resourcekey=0-07qA-RDH6feFOtdJSHtn7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd01sYUpoQlpCdUk&resourcekey=0-07qA-RDH6feFOtdJSHtn7w" width="240" alt="1978 - M490G - P010 - 3-1.jpg"></a><br><sub>1978|11 · P010 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFZEdGY5bWZpZ3M/view?resourcekey=0-zFFkPufIZ3nG0iGIQLcUfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFZEdGY5bWZpZ3M&resourcekey=0-zFFkPufIZ3nG0iGIQLcUfA" width="240" alt="1978 - M490G - P011 - 3-2.jpg"></a><br><sub>1978|11 · P011 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ2FEVC0zcDczaFE/view?resourcekey=0-GHDbc9gFAXy8IlWBq4R8zw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ2FEVC0zcDczaFE&resourcekey=0-GHDbc9gFAXy8IlWBq4R8zw" width="240" alt="1978 - M490G - P012 - 3-3.jpg"></a><br><sub>1978|11 · P012 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSXVhVkF2X1lPdzA/view?resourcekey=0-BBZQ3KU1KVNZxVbOgNMRCg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSXVhVkF2X1lPdzA&resourcekey=0-BBZQ3KU1KVNZxVbOgNMRCg" width="240" alt="1978 - M490G - P013 - 3-4.jpg"></a><br><sub>1978|11 · P013 - 3-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMlB6V2hlVlR4TUU/view?resourcekey=0-gs3zFfLHgDKPUzzIGGkkXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMlB6V2hlVlR4TUU&resourcekey=0-gs3zFfLHgDKPUzzIGGkkXw" width="240" alt="1978 - M490G - P014 - 3-5.jpg"></a><br><sub>1978|11 · P014 - 3-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcS1LSTV1eTliaVU/view?resourcekey=0-En0davKpOgsGV15wM51bxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcS1LSTV1eTliaVU&resourcekey=0-En0davKpOgsGV15wM51bxA" width="240" alt="1978 - M490G - P015 - 3-6.jpg"></a><br><sub>1978|11 · P015 - 3-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2pIUDFFVEQ2UzA/view?resourcekey=0-_fuHJeZe1XkGX5q-9pEpkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2pIUDFFVEQ2UzA&resourcekey=0-_fuHJeZe1XkGX5q-9pEpkQ" width="240" alt="1978 - M490G - P016 - 3-7.jpg"></a><br><sub>1978|11 · P016 - 3-7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYnNSWkJDRUp4STA/view?resourcekey=0-R1peN_aLJWpLl840mso99A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYnNSWkJDRUp4STA&resourcekey=0-R1peN_aLJWpLl840mso99A" width="240" alt="1978 - M490G - P017 - 3-8.jpg"></a><br><sub>1978|11 · P017 - 3-8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWdDZ0djdS1SQTg/view?resourcekey=0-_1nbaDOTo0nBvz3QrzL9AA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWdDZ0djdS1SQTg&resourcekey=0-_1nbaDOTo0nBvz3QrzL9AA" width="240" alt="1978 - M490G - P018 - 3-9.jpg"></a><br><sub>1978|11 · P018 - 3-9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0F0WXkwYXk4REE/view?resourcekey=0-JVSYK4Y_JF2LhQvjxOAs5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0F0WXkwYXk4REE&resourcekey=0-JVSYK4Y_JF2LhQvjxOAs5g" width="240" alt="1978 - M490G - P019 - CD4016.jpg"></a><br><sub>1978|11 · P019 - CD4016</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc2xtemRnNGdWVFk/view?resourcekey=0-6_FAhExcbRSEW8ysscGMYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc2xtemRnNGdWVFk&resourcekey=0-6_FAhExcbRSEW8ysscGMYQ" width="240" alt="1978 - M490G - P020 - 74C76.jpg"></a><br><sub>1978|11 · P020 - 74C76</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbi1aZTF1TUdOY0E/view?resourcekey=0-kRjVCzauA_CQ0FkoHkDfyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbi1aZTF1TUdOY0E&resourcekey=0-kRjVCzauA_CQ0FkoHkDfyA" width="240" alt="1978 - M490G - P021 - 74C221.jpg"></a><br><sub>1978|11 · P021 - 74C221</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M490G - 490-01-008 - INPUT MODULE FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1978%20-%20M490G%20-%20490-01-008%20-%20INPUT%20MODULE%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1978 - M490G - 490-01-008 - OFF ONISTART TIMER RESET OFF TALLY OFF ISTOP.kicad_sch](KICAD/1978%20-%20M490G%20-%20490-01-008%20-%20OFF%20ONISTART%20TIMER%20RESET%20OFF%20TALLY%20OFF%20ISTOP.kicad_sch)
- [1978 - M490G - 490-02-008 - CAST COMPONENT DESIGNTIONS CRIC.kicad_sch](KICAD/1978%20-%20M490G%20-%20490-02-008%20-%20CAST%20COMPONENT%20DESIGNTIONS%20CRIC.kicad_sch)
- [1978 - M490G - 490-02-008 - MIC INPUT MODULE.kicad_sch](KICAD/1978%20-%20M490G%20-%20490-02-008%20-%20MIC%20INPUT%20MODULE.kicad_sch)
- [1978 - M490G - Mic Input Module (2) p25.kicad_sch](KICAD/1978%20-%20M490G%20-%20Mic%20Input%20Module%20(2)%20p25.kicad_sch)
- [1978 - M490G - Mic Input Module p25.kicad_sch](KICAD/1978%20-%20M490G%20-%20Mic%20Input%20Module%20p25.kicad_sch)
- [1978 - M490G - Mic Input Module p27.kicad_sch](KICAD/1978%20-%20M490G%20-%20Mic%20Input%20Module%20p27.kicad_sch)
- [M490G.kicad_sym](KICAD/M490G.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
