## information    

- Title: Arche-scripture: a speculative archeological experiment
- Category: Semesterarbeit
- Students: Alberto Harres
- Course Title: Master Project 2021-22
- Lecturers: Ralf Baecker, Dennis Paul
- Year: WS 2021/22

## __ARCHE-SCRIPTURES__

![](/images/arche-scriptures_big.gif)

__ARCHE-SCRIPTURES__ revolves around understanding ceramics as a possible medium to store digital information. It _"emerges from an impossibility, from the ambivalence between two disparate realms: archaism and future"_ - it proposes an archaic digital medium, a paradox of fragility and permanence, which seeks to _"resignify the assumed linearity between past and future, deconstruct the idea of vertical time, history and technology"_.

During the [Hochschultage 2022](https://www.hfk-bremen.de/hochschultage2022), __ARCHE-SCRIPTURES__ presents itself as a speculative archeological dig-site. At the courtyard of HfK Speicher XI building, a ceramic artifact is being scanned by an decrypting machine, through which the visitor is invited to listen as the original audio data engraved onto the ceramics is slowly retrieved and sonified. The experience offers a glimpse on a possible future past, it speculates on the future of our digital traces through an ancestro-futuristic perspective, provoking a discussion about continuity, preservation and archiving.

The data stored in the ceramic pieces consists of voice recordings extracted from the [Pandemic Archive of Voices](http://pandemic-archive-of-voices.herokuapp.com/). In the headphones one can listen to the software attempting to read back the engraved information. The surviving piece being decrypted by the machine has engraved the sound of the word _“dalijna”_, meaning _“distance”_.


![](/images/_MG_5399.png)

![](/images/_MG_5443.png)

![](/images/_MG_5410.png)

![](/images/_MG_5428.png)

![](/images/arche-scriptures_Capture_big.gif)

## Research

__ARCHE-SCRIPTURES__ investigates the multiple possible relationships between ceramic as a digital medium, the audio data to be stored in it, and the methods to transmit and translate the message back to the viewer (or listener). This investigation includes multiple failues and dead-ends until it reached the final exhibiting format. 

### Starting point

The research's starting point lies on the matter of digital archives, and how they are in fact materialized. After the development of the project "Pandemic Archive of Voices", a concern was made present: onto what and where are our digital traces being materilized? wheather shifting on metal-oxide semiconductors or in spinning magnetic cores at data centres unevenly spread across the globe, they belong to opaque structures to which we have minimal agency. 

### Initial references

Attempting to overcome these contradictions while facing archiving as a political and poetical problem, I decided to then look back in history, to the earlier forms in which language and memory was stored/materialized.

![babilonian scripts](https://ras.ac.uk/sites/default/files/styles/media_demo_full_cropped/public/2021-05/cuneiform%20tablet%20from%20the%20British%20Museum.jpg?itok=nupb9h29)

*Cuneiform tablet from the British Museum which contains Babylonian eclipse tables.*

![oracle bone scripts](https://blogs.bl.uk/.a/6a00d8341c464853ef01b8d184cabb970c-580wi)

*Shang dynasty characters on fragments of an oracle bone dating between 1600 and 1050 BC. British Library, Or. 7694/1516*
  
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

### Optical Character Recognition

In the initial phase of the research, I attempted to expriment with a system of Optical Character Recognition (OCR) in order to store bit data into to plate. With this approach it was expected to have a flexible method which would also be aethetically fitting to aethetics of archeology.

![](/images/results.gif)


![](https://camo.githubusercontent.com/3273f9c505aa5d244c78f3576b32156f2631295d55f7392ccdfd51515caec1a0/68747470733a2f2f6c68352e676f6f676c6575736572636f6e74656e742e636f6d2f4a6a57656a35504b50506f5a45705661774451324a537a6975596a38363577574244535967684c574f54564a4b7966784c7645735f547169386f674f44766630423131655a67764f6e2d48656a34464d7a50524b6e415470364a6a38646d64617130324a33635444306c5650384f71367a71564b35686548704a745559324b6c69674f6c617856475841534b)


### Encoding the audio data

For the audio file to be encoded into a bit-image that is ready to be laser-engraved, there are multiple steps of conversion, compression and formating that are necessary.

- convert .wav audio file to the minimal compression possible (8bit, 4000 samplerate)
- extract the raw waveform data out of the wavefile
- convert the 8bit numbers into 8 bits of `0` or `1`
- render the bit list into a grid of white and black squared.
- shape the bit grid to the dimentions of the clay piece which will be lasered

There are multiple ways in which this process can be greatly improved, certain approaches are intentionally avoided, such as more "abstract" modes of compression, which would make the data smaller but more fragile.

For cases in which the reading process needs to have a higher level of confidence, redundance of data should be implemented, but that would required a much greater ammount of space for the same ammount of information.

## Initial installation sketches



## Master Project Exhibition - Dauerwelle

![](/website/P1022200_v2.JPG)

![](/images/P1022195.JPG)

![](/images/P1022350.JPG)

![](/images/P1022281.JPG)

![](/images/P1022314.JPG)

![](/images/P1022308.JPG)

## Links

### References:


### Open Source Softwares:
- Processing/Arduino Code for the Hochscultage software version [mneunomne/archeReaderController](https://github.com/mneunomne/archeReaderController)
- Python/OpenCV Code for the software used in Master Project Exhibition [mneunomne/fiducial_marker](https://github.com/mneunomne/fiducial_marker)
- Browser display software for the Master Project Exhibition [mneunomne/archeology](https://github.com/mneunomne/archeology)
- Fork from the YOLOv5 library to work on the abandoned OCR part of the project [mneunomne/YOLOv5](https://github.com/mneunomne/yolov5)