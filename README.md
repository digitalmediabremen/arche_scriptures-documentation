## information    

- Title: Arche-scripture: a speculative archeological experiment
- Category: Semesterarbeit
- Students: Alberto Harres
- Course Title: Master Project 2021-22
- Lecturers: Ralf Baecker, Dennis Paul
- Year: WS 2021/22

## Arche-scriptures

ARCHE-SCRIPTURES revolves around understanding ceramics as a possible medium to store digital information. It "emerges from an impossibility, from the ambivalence between two disparate realms: archaism and future" - it proposes an archaic digital medium, a paradox of fragility and permanence, which seeks to "resignify the assumed linearity between past and future, deconstruct the idea of vertical time, history and technology".

During the Hochschultage 2022, ARCHE-SCRIPTURES presents itself as a speculative archeological dig-site. At the courtyard of HfK Speicher XI building, a ceramic artifact is being scanned by an decrypting machine, through which the visitor is invited to listen as the original audio data engraved onto the ceramics is slowly retrieved and sonified. The experience offers a glimpse on a possible future past, it speculates on the future of our digital traces through an ancestro-futuristic perspective, provoking a discussion about continuity, preservation and archiving.

## Ancestro-futurism

>"Ancestor + Futurism are two terms that apparently emerge from an impossibility, from the ambivalence between two disparate realms: archaism and future. [...] ancestrofuturism requests concepts that work with other notions of time and resignify the assumed linearity between past and future, i.e., concepts that deconstruct the idea of vertical time and history — from archaism pointing towards the future — and that horizontalize this perspective." - Fabi Borges

## Research

This project investigates the multiple possible relationships between ceramic as a digital medium, the audio data to be stored in it, and the methods to transmit and translate the message back to the viewer (or listener). This investigation includes multiple failues and dead-ends until it reached the final exhibiting format of a real simuation of an archeological site.

### Starting point

The starting point of this research lies on the matter of digital archives, and how they are in fact materialized. After the development of the project "Pandemic Archive of Voices", a concern was made present: onto what and where are our digital traces being materilized? wheather shifting on metal-oxide semiconductors or in spinning magnetic cores at data centres unevenly spread across the globe, they belong to opaque structures to which we have minimal agency.

### Abandoned method of Optical Character Recognition

In the initial phase of the research, I attempted to expriment with a system of Optical Character Recognition (OCR) in order to store bit data into to plate. With this approach it was expected to have a flexible method which would also be aethetically fitting to aethetics of archeology.

![](/images/detections.png)

### Laser engraving ceramics

![](/images/placas_ceramica.png)

The process of creating the laser engraved slabs of ceramics:

1. Make the clay slabs using flatning tool (forgot the name)
2. Put the clays to dry on a flat surface. To make sure that they don't naturally bend, leave a weighted flat object on top of the clay piece.
3. After they are flat enough not to bend any longer, bring them to the laser engraving.
4. The following laser engraving parameters work well for red-clay.
5. Bring the lasered clay piece to be fired. In order for the engraving to be uniform across the plate, the heat during the firing process needs to also be more-or-less uniform across the piece. 

### Plattengestaltung

To make the process of generating the sound image data more streamlined, I created this online tool which automatically converts the audio data to bits and exports it in .svg, which can be later directly used bu the laser cutting software.

![](/images/platten_gestaltung.png)

### Encoding the audio data

For the audio file to be encoded into a bit-image that is ready to be laser-engraved, there are multiple steps of conversion, compression and formating that are necessary.

- convert .wav audio file to the minimal compression possible (8bit, 4000 samplerate)
- extract the raw waveform data out of the wavefile
- convert the 8bit numbers into 8 bits of `0` or `1`
- render the bit list into a grid of white and black squared.
- shape the bit grid to the dimentions of the clay piece which will be lasered

There are multiple ways in which this process can be greatly improved, certain approaches are intentionally avoided, such as more "abstract" modes of compression, which would make the data smaller but more fragile.

For cases in which the reading process needs to have a higher level of confidence, redundance of data should be implemented, but that would required a much greater ammount of space for the same ammount of information.

### Machinic reading process



## Installation 

The installation concept proposes to incorporate the pragmatic failures of the research as an audible experience of   

### Initial installation sketches



### Abstract

Arche-scripture speculates a post-technological state of digital information through an ancestro-futuristic perspective. The laser  engraved ceramics proposes an archaic digital medium, a paradox of  fragility and permanence made tangible and audible. 

The data stored in the ceramic pieces consists of voice recordings extracted from the Pandemic Archive of Voices. In the headphones one can listen to the software attempting to read back the engraved information. The central surviving piece engraves the sound of the word “dalijna”, meaning “distance”.

### Learning to Draw Exhibition - Nebenflut



### Master Project Exhibition - Dauerwelle

![](/website/P1022200_v2.JPG)

![](/images/P1022195.JPG)

![](/images/P1022350.JPG)

![](/images/P1022281.JPG)

![](/images/P1022314.JPG)

![](/images/P1022308.JPG)

## Hochschultage

For the Hochschultage exhibition at Hfk, the installation evolved from the previous setting into simulating a real archeological dig-site on the Speicher XI courtyard area.

![](/images/arche-scriptures_big.gif)

![](/images/arche-scriptures_Capture_big.gif)

![](/images/_MG_5399.png)

![](/images/_MG_5443.png)

![](/images/_MG_5410.png)

![](/images/_MG_5428.png)