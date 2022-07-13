## information    

- Title: Arche-scripture: a speculative archeological experiment
- Category: Semesterarbeit
- Students: Alberto Harres
- Course Title: Master Project 2021-22
- Lecturers: Ralf Baecker, Dennis Paul
- Year: WS 2021/22

## Resarch Abstract

Arche-scriptures researches the usage of ceramics as a possible medium for storing of digital information.  

This project investigates the multiple possible and impossible relationships between ceramic as a digital medium, the audio data to be stored in it, and the methods to transmit and translate the message back to the viewer (or listener). This investigation includes multiple failues and dead-ends until it reached the final exhibiting format of a real simuation of an archeological site.

## Ancestro-futurism

>"Ancestor + Futurism are two terms that apparently emerge from an impossibility, from the ambivalence between two disparate realms: archaism and future. [...] ancestrofuturism requests concepts that work with other notions of time and resignify the assumed linearity between past and future, i.e., concepts that deconstruct the idea of vertical time and history — from archaism pointing towards the future — and that horizontalize this perspective." - Fabi Borges

## Research

### Initial references

The initial interest of this research was a convergence of multiple vectors which combined themselves 

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

![](/images/_MG_5399.png)

![](/images/_MG_5443.png)

![](/images/_MG_5410.png)

![](/images/_MG_5428.png)

---------

## Narration 

The initial traces of this project go back to the end of 2020, when during the lockdown period "the pandemic archive of voices" was created, which was an archiving project which attempted to record the voices of the people sorrounding my community, where each person recorded a word of expresstion that could translate their personal experience of the pandemic. From that project multiple iterations were made, and the archive was structure as an API.

But from this Archiving initiative I was then concerned with on how this information was being stored, how and where these digital traces of our subjectivity were being stored in some sort of material - where were these memories actually being materialized, how were they engraved. Since 

Argumentation:

-> Pandemic archive of voices
-> Materialization of memory
-> Found in ceramic as a material that could make this memory tangile and also bend the notions of technology and time, as a material that could in theory outlast divices of digital memory
-> from this research I was attempting to materialize this archive   