## Equipment 
* Manual multi-channel pipettor 
* Magnetic particle concentrator (MPC) for 1.5mL tubes (Promega Z5332). **Keep magnets away from computers, memory sticks, calculators, pacemakers, etc.** 
* MPC for PCR tubes (Promega V8351)
* Thermocycler capable of 0.1C/second ramp rate (Bio-Rad C1000 or S1000)
* nutator (orbital shaker/rocker)
* Electrophoresis equipment for agarose gels
* Non-UV based gel illuminator (blue-light screen to cover UV)
* Invitrogen QuBit DNA spectrophotometer (for concentrations ≤ 1 ng/uL)
* Illumina Genome Analyzer sequencing access – [Tufts TUCF](http://genomics.med.tufts.edu/)

## Reagents

* Qiagen DNeasy kit, buffer EB.  
* Q5 polymerase (New England Biolabs, Cat. No. M0491L)
* dNTPs, 10 mM/each (Invitrogen, Cat. No. 18427-013)
* Dynabeads M-280 Streptavidin (Invitrogen, Cat. No. 112-06D)
* Hexanucleotide Mix (Roche, Cat. No. 11277081001)
* Klenow Fragment (3’ - 5’ exo-; 5 U/µL) (New England Biolabs, Cat. No. M0212S)
* 1M NaCl (5.84 g in 100 ml, filter-sterilized in 0.22 µm filter).
* MmeI (New England Biolabs, Cat. No. R0637S)
* T4 DNA ligase (2,000,000 U/mL) (New England Biolabs, Cat. No. M0202T)
* Agarose (BioExpress, Cat. No. E-3120-500)
* 10bp DNA Ladder (Invitrogen, Cat. No. 10821-015)
	* can be substituted with a ladder that has a range from 10 – 300 bp.
* SYBR Safe (Invitrogen, no. S33102)
* 10x xylene cyanol DNA dye (20% Ficoll 400, 0.1M disodium EDTA, 0.25% xylene cyanol) "Dye-XC"
* 10x bromophenol blue DNA dye (20% Ficoll 400, 0.1M disodium EDTA, 0.25% bromophenol blue) "Dye-BB"
* QIAquick Gel Extraction Kit (Qiagen, Cat. No. 28706)
* Tween (optional; for long-term storage of INSeq libraries).

### Buffers:
#### Sodium Borate (SB) electrophoresis buffer:
* Filter sterilize and store at room temperature.
* Prepare 20x (100 mM) stock: 38.137g in 1 L. 
  * 5 mM Na<sub>2</sub>B<sub>4</sub>O<sub>7</sub>·10H<sub>2</sub>O final for Sodium Borate (SB) buffer.  

#### 2X B&W buffer:
* Filter sterilize and store at 4°C .
* Concentration (amount per 50 ml) :
	* Tris-HCl pH 7.5, 10 mM (0.5 ml of 1 M stock) 
	* EDTA 1 mM (100 ul of 0.5 M stock) 
	* NaCl 2 M (20 ml of 5 M stock) 
	* ddH<sub>2</sub>O to 50 ml

#### LoTE buffer:
* Filter sterilize and store at 4°C.
* Concentration (amount per 1 liter):
	* Tris-HCl pH7.5, 3 mM (3 ml of 1M stock)
	* EDTA 0.2 mM (0.4 ml of 0.5 M stock)
  * ddH<sub>2</sub>O to 1 liter

  --- 
## Primers

| Primer Name              | Primer Sequence                                          | Step                        | Purpose                                           |
|--------------------------|----------------------------------------------------------|-----------------------------|--------------------------------------|
| BioSamA (HPLC purified)  | 5’-Bio-TEG-CAAGCAGAAGACGGCATACGAAGACC                    | Linear PCR                  | Linear PCR, biotin to bind to streptavidin beads  |
| M12\_top                  | 5'-CTGTCCGTTCCGACTACCCTCCCGAC                            | MmeI Digestion              | dsDNA adapter with second MmeI site               |
| M12\_bot                  | 5’-GTCGGGAGGGTAGTCGGAACGGACAG                            | MmeI Digestion              | dsDNA adapter with second MmeI site               |
| LIB\_PCR\_5                | 5’-CAAGCAGAAGACGGCATACGAAGACCGGGGACTTATCATCCAACCTGT      | PCR and Final Purification  | release from beads                                |
| LIB\_PCR\_3                | 5’-AATGATACGGCGACCACCGAACACTCTTTCCCTACACGACGCTCTTCCGATCT | PCR and Final Purification  | release from beads                                |
| LIB\_AdaptT\_A             | 5’-TTCCCTACACGACGCTCTTCCGATCTTTTTNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_B             | 5’-TTCCCTACACGACGCTCTTCCGATCTACCANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_C             | 5’-TTCCCTACACGACGCTCTTCCGATCTACGTNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_D             | 5’-TTCCCTACACGACGCTCTTCCGATCTAGGANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_E             | 5’-TTCCCTACACGACGCTCTTCCGATCTAGTCNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_F             | 5’-TTCCCTACACGACGCTCTTCCGATCTATCGNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_H             | 5’-TTCCCTACACGACGCTCTTCCGATCTCATGNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_I             | 5’-TTCCCTACACGACGCTCTTCCGATCTCCAANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_J             | 5’-TTCCCTACACGACGCTCTTCCGATCTCCCCNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_K             | 5’-TTCCCTACACGACGCTCTTCCGATCTCGATNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_O             | 5’-TTCCCTACACGACGCTCTTCCGATCTGCTANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_P             | 5’-TTCCCTACACGACGCTCTTCCGATCTGGAANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_Q             | 5’-TTCCCTACACGACGCTCTTCCGATCTGGGGNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_R             | 5’-TTCCCTACACGACGCTCTTCCGATCTGTACNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_S             | 5’-TTCCCTACACGACGCTCTTCCGATCTGTCANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_U             | 5’-TTCCCTACACGACGCTCTTCCGATCTTATANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_V             | 5’-TTCCCTACACGACGCTCTTCCGATCTTCAGNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_W             | 5’-TTCCCTACACGACGCTCTTCCGATCTTCGANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_Y             | 5’-TTCCCTACACGACGCTCTTCCGATCTTTAANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_Z             | 5’-TTCCCTACACGACGCTCTTCCGATCTAAAANN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_AA            | 5’-TTCCCTACACGACGCTCTTCCGATCTGAAGNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_CC            | 5’-TTCCCTACACGACGCTCTTCCGATCTCCTTNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_DD            | 5’-TTCCCTACACGACGCTCTTCCGATCTAACCNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptT\_EE            | 5’-TTCCCTACACGACGCTCTTCCGATCTTTGGNN                      | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_A             | 5’-AAAAAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_B             | 5’-TGGTAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_C             | 5’-ACGTAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_D             | 5’-TCCTAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_E             | 5’-GACTAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_F             | 5’-CGATAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_H             | 5’-CATGAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_I             | 5’-TTGGAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_J             | 5’-GGGGAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_K             | 5’-ATCGAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_O             | 5’-TAGCAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_P             | 5’-TTCCAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_Q             | 5’-CCCCAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_R             | 5’-GTACAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_S             | 5’-TGACAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_U             | 5’-TATAAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_V             | 5’-CTGAAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_W             | 5’-TCGAAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_Y             | 5’-TTAAAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_Z             | 5’-TTTTAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_AA            | 5’-CTTCAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_CC            | 5’-AAGGAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_DD            | 5’-GGTTAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |
| LIB\_AdaptB\_EE            | 5’-CCAAAGATCGGAAGAGCGTCGTGTAGGGAA                        | Linker Ligation             | Adapter barcode                                   |

## Protocol Overview: 

1.	DNA isolation
2.	Linear PCR (LPCR)
3.	Bind LPCR product to beads
4.	Second strand synthesis
5.	MmeI digestion
6.	Linker ligation
7.	PCR and Final Purification
8.	Gel loading and extraction

## 1. DNA isolation 

Use the Qiagen DNeasy kit (or other method) to extract gDNA. You will need 1 µg of DNA for the each sample in a 50 µl volume.

Measure the DNA concentration of each sample using the NanoDrop (use 1.5 μl). 

Store the DNA at -20˚C. 
When ready, pull DNA from the -20˚C, thaw on ice, re-read the samples and perform dilutions in ddH<sub>2</sub>O to 20 ng/µl.


## 2. Linear PCR (LPCR)

Note: Dilute BioSamA to 1 pmol/µl.

| Linear PCR               | Reaction | Master (n=20)    |
|--------------------------|----------|------------------|
| dH<sub>2</sub>O                     | 17       | 540              |
| Q5 buffer (10X)          | 20       | 200              |
| dNTPs (10 mM)            | 2        | 40               |
| BioSamA (1 pmol/µl)      | 10       | 200              |
| Q5 polymerase            | 1        | 20               |
| DNA prep (1 µg in 50 µl) | 50       | --               |
| Total                    | 100      | 50 µl per sample |

Note: This uses 2x the amount of BioSamA than the 2011 Nature protocol for a better yield.

**Split reactions into 2 x 50 µl in 0.2 ml strip tubes.**

The reaction is approximately 1.5 hours.

**Program: LPCR**

| Temperature | Seconds | Cycles |
|-----| -------| -----|
| 94°C | 2 min | 1x |
| 94°C | 15 sec | 50x |
| 68°C | 1 min | 50x |

Note: the 68°C is annealing and extension.

Pool like samples, run over QiaQuick PCR cleanup column, and elute in **50 µl EB.**

## 3. Bind LPCR product to beads. 
**Step 1. Wash beads in batch**
* Resuspend streptavidin-coated beads by shaking.
* Add beads (32 µL/sample) to a new microcentrifuge tube (1 mL maximum; use multiple tubes if greater volume is required).
* Place tube on MPC for 1 - 2 min.
* Carefully remove supernatant with a pipette.
* Remove tube from MPC, add 1000 µL of 1x B&W buffer; gently resuspend by pipetting.
* Wash again 2x for a total of 3 washes.
* Remove final wash and add 2X B&W buffer (52 µL/sample). 
* Aliquot into PCR strip tubes (1 tube/sample, 50 µL/tube).

**Step 2. Bind LPCR product to beads**
**Bind LPCR to beads in PCR striptubes.  Samples remain in the striptubes for remainder of protocol.  For incubations, transfer striptubes to thermal cycler.  For washes, transfer striptubes to MPC 96-well magnet -- place every other column for ease in washing (beads will all move in the same direction).**
* Add one DNA sample (column-purified from above) to each bead aliquot.
* Incubate at RT 30 min w/gentle mixing (place on nutator and flick gently every 10 - 15 min).
* Place tubes on MPC 2 min.
* Wash 1x w/ 100 µl 1X B&W buffer (carefully remove supernatant with pipette, remove tube from MPC, then add buffer).
* Carefully remove supernatant with a pipette. 
  * _Tip: to avoid disturbing the beads, set the electronic multichannel pipettor to its slowest setting, place the end of the tip against the opposite side of the tube from the beads, and slowly move the tip downward as the supernatant is removed. See Supplemental Movie #1 for a demonstration._ 

* Place beads on MPC 2 min.
* Wash 1x w/ 100 µl LoTE.
* Place beads on MPC 2 min.
* Resuspend in 100 µl LoTE.

**Optional: store at 4°C O/N** 
  
## 4. Second strand synthesis
Make sure DNA is fully denatured: Heat 95°C 2 min and chill quickly to 4°C (Program: DENATURE).

* **Ok to perform on thermal cycler; stand there and remove samples after completion of program, and ensure that thermal cycler does not remain at 4°C for longer than necessary. Use the 96-well block if possible.**

Prepare Second Strand Mix on ice: 

| Second strand mix        | Reaction | Master (n=20)      |
|--------------------------|----------|--------------------|
| dH<sub>2</sub>O                     | 16       | 320                |
| Hexanucleotide mix (10X) | 2        | 40                 |
| dNTPs (10 mM)            | 1        | 20                 |
| Exo– Klenow (5 U/µl)     | 1        | 20                 |
| Total                    | 20       | 20 ul per reaction |

Collect beads w/ MPC, carefully remove supernatant.  Remove tubes from MPC and gently resuspend each sample in **20 µl** second strand mix: 
* 37°C 30 min EXACTLY, gently mix every 10 - 15 min.
* Add 100 µl LoTE to each sample. 
* Collect beads in MPC.  
* Wash x1 with 100 µl LoTE, then carefully discard supernatant. 
* Collect beads in MPC.  
* Resuspend in 100 µl LoTE. 

**Optional: store at 4°C O/N**

## 5. MmeI digestion 
**Prepare M12 dsDNA stock**
* Dilute M12\_top, M12\_bot to 100 µM in EB
* Combine in 0.2 mL microfuge tube:
  * 15 µL M12\_top (100 µM)
  * 15 µL M12\_bot (100 µM)
  * 1.5 µL 1M NaCl (50mM final)
* Heat 95°C for 5 min, cool slowly to 4°C at 0.1 deg/sec (Program: ANNEAL).
* Store 5 µl aliquots in PCR tubes (50 µM each oligo) at -20°C.  Only thaw aliquots one time.

Prepare MmeI Buffer Mix on ice: 

| MmeI Buffer Mix    | Reaction | Master (n=20) |
|--------------------|----------|---------------|
| dH<sub>2</sub>O               | 16.8     | 336           |
| 10x NEBuffer 4     | 2        | 40            |
| SAM (32 mM)        | 0.08     | 1.6           |
| M12 dsDNA (50 µM)  | 0.2      | 4             |
| Total | 19 µl/reaction | |

Collect beads with MPC and gently resuspend in **19 µl** MmeI buffer mix. 

* Add 1 µl MmeI to each reaction. 
* Incubate at 37°C 1 h (Program: MMEI).  Gently mix every 10 - 15 min. 
* Add 100 µl LoTE to each sample.  
* Collect beads in MPC, and carefully discard supernatant. 
* (repeat wash:) Add 100 µl LoTE to each sample.  
* Collect beads in MPC, and carefully discard supernatant. 
* Resuspend beads in 100 µl LoTE. 

**Optional: store at 4°C O/N**

## 6. Linker ligation 
**Prepare 50 µM barcoded, double-stranded sequencing adapters (1 barcode sequence/sample) by combining in a new PCR tube for each:**
* Dilute LIB\_AdaptT, LIB\_AdaptB to 100 µM in EB
* Combine in 0.2 mL microfuge tube:
  * 15 µL LIB\_AdaptT_(barcode) (100 µM)
  * 15 µL LIB\_AdaptB_(barcode) (100 µM)
  * 1.5 µL 1M NaCl (50mM final)
* Heat 95°C for 5 min, cool slowly to 4°C at 0.1 deg/sec (Program: ANNEAL).
* Store 5 µl aliquots in PCR tubes (50 µM each oligo) at -20°C.  Only thaw aliquots one time.
* **Thaw aliquots on ice and dilute 1:10 in 1x T4 ligase buffer before use for 5µM final (1 barcode/sample).**
  * Add 45 µl of 1X T4 ligase buffer to the 5 µl adapter aliquot.

**Assign barcodes to each sample.**

| Ligation Mix             | Reaction | Master (n=20) |
|--------------------------|----------|---------------|
| dH<sub>2</sub>O                     | 16.4     | 328.0         |
| 10x T4 DNA Ligase Buffer | 2.0      | 40.0          |

* Collect beads with MPC.  Carefully discard supernatant. 

* Remove tubes from MPC and gently resuspend each sample in **18.4 µl** ligation mix. 
* Add 0.6 µl of 5 uM dsDNA sequencing adapter containing a unique barcode to each sample. 
* Add 1 µl T4 DNA ligase (high concentration enzyme) to each reaction. 

* Incubate at 16°C for 1 h (Program: LIGATION).  Gently mix every 10 - 15 min. 

* Add 100 µl LoTE to each sample. 
* Collect beads in MPC.  Wash x1 with 100 µl LoTE, then carefully discard supernatant.
* Collect beads in MPC.  Resuspend in 100 µl LoTE. 


**Optional: store at 4°C O/N** 

## 7. PCR and Final Purification

Dilute primers to 5 µM working concentration.

Prepare PCR Mix on ice: 

| PCR                | Reaction | Master (n=20)      |
|--------------------|----------|--------------------|
| dH<sub>2</sub>O               | 33      | 660                |
| Q5 buffer (5X) | 10       | 200                |
| dNTPs (10 mM)      | 2        | 40                 |
| LIB-PCR5 (5 µM)    | 2        | 40                 |
| LIB-PCR3 (5 µM)    | 2        | 40                 |
| Q5 polymerase   | 1        | 20                 |
| Total              | 50       | 50 µl per reaction |

Collect beads with MPC. Carefully discard supernatant. 


**Program: FINALPCR**


| Temperature | Seconds | Cycles |
|-----| -------| -----|
| 98°C | 2 min | 1x |
| 98°C | 10 sec | 19x |
| 60°C | 30 sec | 19x |
| 72°C | 2 min | 19x |
| 72°C | 2 min | 1x |

This reaction is approximately 1 hour and 15 minutes.


# DO NOT TOSS SUPERNATANT!

* Collect supernatant on MPC.
* Transfer samples to new striptubes.


## 8. Gel loading and extraction


Run samples on a 2% agarose gel (use 1x NaBorate buffer, SYBR SAFE dye).
* The SYBR-Safe dye is 10,000X; use 15 µl if making a 150 ml gel.
* Add 10X Xylene cyanol dye to samples and 10x Bromophenol Blue dye to the ladder.
  * Ladder: 2 µl 10 bp ladder, 7 µl water, 1 µl dye.
* Load samples every other lane.
* Run for 30 minutes at 200V.
* Extract each 125 bp band from the gel .

Gel purify with Qiagen Gel Extraction Kit (include isopropanol step) and elute in 35 µL EB.

**Optional: store at 4°C O/N**

Assess samples with QuBit, following the instructions in box (use 2 µL of sample in 198 µL of working reagent). 
* Use high sensitivity dsDNA setting. 
Normalize samples based on Qubit readings. 
* All samples should be represented equally: add the same amount of ng of each sample or normalize each sample to the same pmol and mix together equal volumes. If possible, try to obtain a 10 nM sample mix. 

Place samples at -20°C. Send for sequencing on dry ice. 



