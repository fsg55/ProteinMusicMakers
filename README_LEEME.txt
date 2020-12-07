README.txt

These programs are a simple musicalization of the amino acid sequences
what make up proteins.

These .zip files contain the executables ".EXE", ".JAR", and the necessary elements to
execute them and write the .WAV and .MP3 of the musicalization of the protein sequences
that want to listen.

The sequence files used can be files in FASTA format, or those provided in my repository 
https://github.com/fsg55/The-Rhythm-of-each-Human-Model_Protein-Encyclopedia, or simply 
any sequence of amino acids that you type in. 

I have made three types of ProteinMusic executables:

type 1: they translate the amino acid (AA) sequence of a protein into music, depending 
on the type amino acid, based on a set of "samples" in .wav format, single channel, PCM 16bits signed, or 2 channels, as samples packs used.

those of type2: they add a rhythm of percussion instruments to the previous one, which is a
function of the length of the amino acid chain and the amino acid that is currently being 
processed at the time of rhythm change.

those of type2D: add to the format of type1 a percussion that depends on the type of
secondary structure formed by the processed amino acids, according to software STRIDE, 
a program with prediction criteria of secondary structure, extracted from the 3D data of PDB files
(Protein Data Bank) . My sincere thanks, and credits due, for authors for 
giving disinterested access to their data.

For programs to work they must also have all the components that are provided
in these ".zip" files, since without all of them they will not work.

The ".zip" files can be unpacked in the directory that the user wants.

Over time in the subfolder "samples" I will provide different "packs" of sounds
that can be changed by those provided at source with the executables.

An important point is that the names of the "samples" must be exactly the same as
are provided, because otherwise the programs will not work.

My thanks and credits due to the programming and software development community
ffmpeg that allows me to make the copy of the .wav files in .mp3, much more compact.

These programs are free, as specified in the LICENSE, and users can substitute
the "/ sonidos" folder with the samples of your choice, taking into account that type1 programs
"samples" of different sizes can be used, while in type 2 and 2D the "samples" must be of the
same size, whatever it is, between 3 and 60 seconds, per "sample", since the programs are adapted
to the size of the "samples" provided, so as not to break.

Due to "memory Heap" limitations, for samples of 4 seconds, the limit of letters (AA) to be processed 
is 2500 for type2 and 2D, while for type1 programs it is 1700 letters with mixed samples from 1 to 
16 seconds.


You can search NCBI-GenBank for more information on the gene that
It is being heard. E.g. (https://www.ncbi.nlm.nih.gov/gene/?term=APOE)

To group the genes I used the functional gene grouping provided by 
the Kyoto Encyclopedia of Genes and Genomes (KEGG) in its "KEGG BRITE Database" 
(https://www.genome.jp/kegg/brite.html) which I found more interesting and appropriate 
than a simple list of genes and proteins.

One last additional and curious fact is that as what is being musicalized are sequences of letters,
You can input any text from any Western language you like, and you'll get a musical piece, taking 
into account that only the characters that correspond to the one-letter codes that identify each 
amino acid will be musicalize.

________________________________________________________________________________________________

LEEME.txt

Estos programas son una simple musicalización-sonorización de las secuencias de aminoácidos 
que componen las proteinas

Estos archivos .zip, contienen los ejecutables ".EXE", ".JAR", y los elementos necesarios para 
ejecutarlos y escribir los .WAV y .MP3 de las sonorizaciones de las secuencias proteicas que 
quieran escuchar.

Los archivos de secuencias utilizados pueden ser archivos en formato FASTA, o los proporcionados
en mi repositorio https://github.com/fsg55/The-Rhythm-of-each-Human-Model_Protein-Encyclopedia, 
o simplemente cualquier secuencia de aminoácidos que ustedes introduzcan.

He realizado tres tipos de ejecutables ProteinMusic:

los de tipo1: traducen la secuencia de aminoácidos (AA) de una proteina a música, según el tipo 
de aminoácido, basada en un set de "samples" en formato .wav, monocanal, PCM 16 bit con signo, 
o bien estereos, tal como los "samples packs" que se utilicen.

los de tipo2: añaden un ritmo de instrumentos de percusión al anterior, que está en función
de la longitud de la cadena de aminoácidos y el aminoácido que se está procesando en el momento 
del cambio de ritmo.
 
los de tipo2D: añaden al formato del tipo1 una percusión que está en función del tipo de 
estructura secundaria que forman los aminoácidos procesados, según el programa STRIDE, un software 
de predicción de estructura secundaria extraidos a partir de los datos 3D de ficheros PDB 
(Protein Data Bank). Mi agradecimiento más sincero, y los créditos debidos, para sus
autores por dar acceso desinteresado a sus datos.

Para que los programas funcionen también deben de tener todos los componentes que se proporcionan
en los archivos .zip, ya que sin todos ellos no funcionarán.

Los archivos .zip pueden ser desempaquetados en el directorio que el usuario quiera.

Con el tiempo en la subcarpeta "samples" iré proporcinando distintos "packs" de sonidos 
que se pueden cambiar por los proporcionados en origen con los ejecutables.

Un punto importante es que los nombres de los "samples"  deben de ser exactamente los mismos que 
se proporcionan, porque de otra manera los programas no funcionarán.

Mi agradecimiento y los creditos debidos, para la comunidad de programación y desarrollo del software
ffmpeg que me permite hacer la copia de los archivos .wav en .mp3, mucho más compactos.

Estos programas son gratuitos, como se especifica en la LICENCIA, y los usuarios pueden sustituir
la carpeta "/sonidos" con los samples de su elección, teniendo en cuenta que los programas tipo1
pueden usar samples de distintos tamaños, mientras que en los de tipo2 y 2D los "samples" deben de ser del
mismo tamaño, sea este cual sea, entre 3 y 60 segundos, por "sample", ya que los programas se adaptan
al tamaño de los "samples" proporcionados, para no romperse.

Debido a limitaciones "memory Heap", para samples de 4 segundos, el límite de letras(AA) a procesar está en 2500 
para los programas de tipo2 y 2D, mientras que para los programas de tipo1 está en 1700 letras con "samples"
de 1 a 16 segundos mezclados.

En el repositorio https://github.com/fsg55/The-Rhythm-of-each-Human-Model_Protein-Encyclopedia, pueden 
encontrar todas las proteinas humanas modelo en el formato utilizado por estos programas.

Se puede buscar en NCBI-GenBank para obtener más información sobre el gen que 
se está escuchando. P.e. (https://www.ncbi.nlm.nih.gov/gene/?term=APOE)

Para agrupar los genes he utilizado la agrupación funcional de genes
proporcionada por la Kyoto Encyclopedia of Genes and Genomes (KEGG) en su
"KEGG BRITE Database" (https://www.genome.jp/kegg/brite.html)
que me ha parecido más interesante y adecuada que una lista simple de genes y proteinas.

Un último dato adicional y curioso, es que como lo que se está musicalizando son secuencias de letras, se
puede usar como entrada cualquier texto de cualquier idioma occidental que se quiera, y se obtendrá una 
pieza musical, teniendo en cuenta que sólo se utilizarán para su elaboración, las letras que 
correspondan a los códigos de una letra que identifica a cada aminoácido.


