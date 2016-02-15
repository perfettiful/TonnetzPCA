#TonnetzPCA

<p>In this project I will investigate the harmonic patterns of digitally rendered musical compositions using exploratory statistical analyses. I intend on developing a more generalized method of mining the score data of a musical composition using R statistical programming software.  Such an analysis could be used discover important harmonic relationships within a composition as well as classify its tonal content.</p>
 
<p>Working data files available here:</p>

(https://docs.google.com/spreadsheets/d/1MrluQZSDnaSbIXlp3h5GT3UZuZx_Ccw7rOY7n_UA-cY/edit?ts=5653647d#gid=756955444)

>Key Words: Tonnetz, tonal networks, Principal Component Analysis, PCA, harmonic, visualization. R
 

##I. INTRODUCTION AND BACKGROUND

<p>The inspiration for this project comes from the researcher Dan Chitwood,who through a series of videos on his Youtube channel demonstrates the prospect of using analytical techniques on digital renderings of musical compositions. Here is an example of his work wherein he applies the exploratory data analysis technique of PCA to a collection of variables defining the composition “Fugue No. 5, D Major ” by J.S. Bach.
Principal Component Analysis (PCA) is a procedure used “to describe the variation of a set of multivariate data in terms of a set of uncorrelated variables, each of which is a particular linear combination of the original variables” (Everitt and Dunn, 48). Chitwood’s analysis 
each note is analyzed for 1) duration, 2) voice, 3-4) 2D position in a Tonnetz lattice, 5) absolute pitch, and 6) relative pitch.</p>

##II. CURRENT WORK

<p>For the current project, I am interested in streamlining Chitwood’s process in order to generalize his method for analyzing the harmonic connections in a musical composition. The compositions I will attempt to analyze for this project are a selection of three pieces from the composer J.S.Bach, available freely on Musedata.org:</p>

Prelude and Fugue in C-sharp Major (http://www.musedata.org/encodings/bach/bg/keybd/wtc-i/0848/)

Prelude and Fugue in D Major (http://www.musedata.org/encodings/bach/bg/keybd/wtc-i/0850/)

Brandenburg Concerto No. 4 in G Major (http://www.musedata.org/encodings/bach/bg/orch/1049/),
 
<p>In order to extract extract and build a dataset of the score information of a given composition, I will utilize the software program MusicScore (https://musescore.org/en).  The key challenge at this step will be developing a script to automate the process of translating the score information from the kern format available on Musedata to a .txt format readable to R.</p>
 

##Data Acquisition Methodology


##REFERENCES

Cohn, Richard (1998). "Introduction to Neo-Riemannian Theory: A Survey and a Historical Perspective". Journal of Music Theory 42 (2 Autumn): 167–180.

Eric J Humphrey, Taemin Cho, and Juan Pablo Bello. Learning a robust tonnetz-space transform for automatic chord recognition. In Proceedings of the International Conference on Acoustics, Speech and Signal Processing (ICASSP), pages 453–456. IEEE, 2012.

Euler, Leonhard 1926 (1739) Tentamen Novae Theoriae Musicae. Leonhardi Euleri opera Omniae, Series III, Vol. 1. Leipzig and Berlin. (drew a tonnetz) and 1926 (1739) De Harmoniae Veris Principis per Speculum Musicum Repraesentatis.  Leonhardi Euleri opera Omniae, Series III, Vol. 1. Leipzig and Berlin. 

Everitt, Brian S., and Graham Dunn. "Principal Components Analysis." Applied Multivariate Data Analysis. London: Arnold, 2001. 48-74. Print.

Lee, Gilliean, Ph.D. Associate Professor of Computing, Lander University, Greenwood, SC, and Robert Kelley, Ph.D., Associate Professor of Music, Lander University, Greenwood, SC. Ptolemaic: A Computer Application for Music Visualization and Analysis. Computer software. Lander University, n.d. Web. <http://ptolemaic.lander.edu/>.

Temperley, David. "Applications of the Polyphonic Key-Finding Model." Music and Probability. Cambridge, MA: MIT, 2007. N. pag. Print.

Tymoczko, Dmitri. "Appendix A: Measuring Voice-Leading Size." A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice. New York: Oxford UP, 2011. N. pag. Print.

Tymoczko, Dmitri. "Appendix B: Chord Geometry." A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice. New York: Oxford UP, 2011. N. pag. Print.

Tymoczko, Dmitri. "Appendix D: The Interscalar Interval Matrix." A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice. New York: Oxford UP, 2011. N. pag. Print.

Tymoczko, Dmitri. "Appendix E: Scale, Macroharmony, and Lerdahl's "Basic Space"" A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice. New York: Oxford UP, 2011. N. pag. Print.

Tymoczko, Dmitri. "Discrete Voice-Leading Lattices." A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice. New York: Oxford UP, 2011. N. pag. Print.



http://www.ccarh.org/

http://www.tonalsoft.com/enc/t/tonnetz.aspx

http://quod.lib.umich.edu/s/spobooks/bbv9810.0001.001/1:18/--algorithmic-composition-a-gentle-introduction-to-music?rgn=div1;view=fulltext

http://cm.bell-labs.com/cm/ms/what/shannonday/shannon1948.pdf

http://mdecks.com/mapharmony.html
 
http://www.musiccog.ohio-state.edu/Music829C/statistics.html
 
http://www.ehu.es/cs-ikerbasque/conklin/papers/jnmr95.pdf
 
http://music.stackexchange.com/questions/18936/tonnetz-algorithms

http://dmitri.mycpanel.princeton.edu/tonnetzes.pdf
 
http://www.robertkelleyphd.com/justtonnetz.htm
 
http://www.music.mcgill.ca/~dsears1/New_Site/Coursework_files/math%20models%20paper.pdf

http://www.ccarh.org/publications/cm/15/cm15-05-purwins.pdf




