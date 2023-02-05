# Table des matières

- [Le modèle standard de la cosmologie](#Le-modèle-standard-de-la-cosmologie)
- [Le modèle standard à l'épreuve des observations](#Le-modèle-standard-à-lépreuve-des-observations)
- [La cosmologie quantique](#La-cosmologie-quantique)
- [Matière noire](#Matière-noire)
- [Energie sombre](#Energie-sombre)
- [L'inflation cosmique](#Linflation-cosmique)
- [Le problème de la hiérarchie](#Le-problème-de-la-hiérarchie)
- [Le problème du lithium cosmique](#Le-problème-du-lithium-cosmique)
- [Le principe cosmologique](#Le-principe-cosmologique)
- [La tension de Hubble](#La-tension-de-Hubble)
- [L'asymétrie entre matière et antimatière](#Lasymétrie-entre-matière-et-antimatière)
- [La nucléosynthèse primordiale](#La-nucléosynthèse-primordiale)
- [La croissance des trous noirs supermassifs](#La-croissance-des-trous-noirs-supermassifs)
- [L'ajustement fin de l'univers](#Lajustement-fin-de-lunivers)

# Le modèle standard de la cosmologie

*Sources*

- [Dark matter and cosmic structure](https://arxiv.org/abs/1210.0544) - White et Frenk (2012)
- [The origin of cosmic structure](https://cds.cern.ch/record/935628/files/p239.pdf) - Frenk

---

## L'univers s'étend

*Vitesse de récession des galaxies en fonction de leur distance. Crédit : Hubble (1929). [Source](https://www.pnas.org/doi/10.1073/pnas.15.3.168)*

![Hubble1929](https://www.pnas.org/cms/10.1073/pnas.15.3.168/asset/3c4ab7f0-0cf6-43b7-afdf-2b7066aa0260/assets/graphic/pnas.168fig01.jpeg)

## L'univers se refroidit

*Carte du CMB par le satellite Planck (2018). Crédit : Collaboration Planck. [Source](https://wiki.cosmos.esa.int/planck-legacy-archive/index.php/CMB_maps)*

![CMBPlanck2018](https://wiki.cosmos.esa.int/planck-legacy-archive/images/thumb/8/84/Cmb_inpaint_T_commander_v1.png/1200px-Cmb_inpaint_T_commander_v1.png)

*Evolution de la résolution de la cartographie du CMB. Crédit : le Figaro [Source](https://www.researchgate.net/figure/Temperature-fluctuations-observed-in-the-CMB-using-COBE-WMAP-Planck-data-Gold-et-al_fig1_328474806)*

![CMBevol](https://i.imgur.com/6v0Tqdu.png)

## L'univers est en grande partie invisible

## L'univers se structure

The mapping of 2,400 galaxies by the CfA Redshift Survey (Huchra et al. 1983), the first
systematic survey of this kind, revealed that the spatial distribution of galaxies was far from
random: at the scale of several tens of Mpcs, they were lying on the "surfaces of bubble-like
structures" surrounding vast cosmic voids (De Lapparent et al. 1986). The invention of charge
coupled devices (CCDs) marked the beginning of the golden age of extragalactic astronomy in
the mid-1980s. Astronomical surveys such as the Sloan Digital Sky Survey (York et al. 2000),
the first fully digital map of the local universe, provided astronomers with an unprecedented
wealth of data that only recently allowed to make reliable, quantitative statements on the distribution
of dierent galaxy populations.

In parallel with the development of astronomical surveys, cosmological simulations allowed
us to model the non-linear dynamics of large-scale structures and their interplay with
the small scale physics of galaxy evolution with ever-increasing complexity. Starting from the
tiny density fluctuations of the early universe observed in the CMB (now tightly constrained
thanks to the results of the WMAP and Planck satellites), these simulations replayed the history
of the universe, according to our best theoretical models. The numerical simulation method in
the field of galaxy evolution dates back to the first N-body simulations of interacting galaxies
of Holmberg (1941) performed on an analog computer7, and its use has become ubiquitous
since the late 1970’s, with the pioneering simulation of Miyoshi and Kihara (1975) performed
on 400 “galaxies” (particles) in an expanding universe8, achieving the prediction of the spatial
distribution of the large-scale structures with remarkable accuracy, and ushering us in the era
of “precision cosmology” (Primack 2005).

For a long time, large-scale cosmological simulations such as the Millenium run (Springel
et al. 2005) or the Bolshoi simulation (Klypin et al. 2011) were limited to N-body simulations
involving only dark matter, and therefore could not trace the evolution of baryonic matter
(i.e. gas and stars), due to computational limitations. Only recently does computational power
(along with more ecient numerical methods) allow for the complexity of fluid dynamics
to enter the picture, and to simulate statistically significant populations of galaxies. Following
Moore’s law9, cosmological simulations have been doubling in size every  16:5 months
(Springel et al. 2005). The last generation of cosmological hydrodynamic simulations such as
Illustris (Vogelsberger et al. 2014), EAGLE (Crain et al. 2015) and Horizon-AGN (Dubois et al.
2014) are finally able to simulate cosmological volumes (boxes of hundreds of Mpc in comoving
size) with enough precision to resolve the internal structure of individual galaxies (of kpc
size). But up to now the dierences in numerical implementations of unresolved (“sub-grid”)
physical processes make the comparison of the results of these simulations dicult (Scannapieco
et al. 2012). The direct comparison between cosmological hydrodynamical simulations
and observations has also been seen as a hazardous undertaking, as they trace dierent physical
phenomena (light for astronomical surveys and mass for simulations). The advent of synthetic
observatories built from the results of simulations, mimicking the eects of telescope resolution
and noise, such as, e.g., the work of Snyder et al. (2015) on the Illustris simulation (cf
Figure 1-7), might have a role to play to better estimate the reliability of simulations

Cosmological simulations follow explicitly the evolution of dark matter and gas in the
non-linear regime of a CDM universe. In these simulations, dark matter is modeled
as a collection of collisionless massive particles whose dynamics follows the Vlasov-
Poisson equations in a box of cosmological (comoving) volume with periodic boundary
conditions. To reproduce the conditions of the early universe, they use a Gaussian
random field of density perturbations with a power spectrum constrained by the CMB
(e.g., Aghanim et al. 2016) as their initial conditions. These N-body simulations can
be completed with the much more computationally intensive baryonic physics, which
in practices comes down to solving the Euler equations on a collisional ideal fluid12 via
Lagrangian or Eulerian methods. In this scheme these simulations are referred to as
cosmological hydrodynamical simulations. Sub-grid models that reproduce the eects
of star formation, turbulence, supernovae and AGN feedback on the surrounding gas,
supermassive black hole growth, chemistry of heavy elements and dust are unavoidable
because galaxy evolution span a wide range of scales. These sub-grid models usually
consist in a mix of empirical (or ad hoc) rules whose calibration is open to fine tuning to
fit the data, as the detailed physics of these processes are not yet well understood. Stateof-
the-art cosmological hydrodynamical simulations include Illustris (Vogelsberger et al.
2014), EAGLE (Crain et al. 2015) and Horizon-AGN (Dubois et al. 2014).

The Sloan Digital Sky Survey (SDSS, York et al. 2000), an on-going spectro-photometric
survey that started in 1998, conducted using the 2.5m telescope of the Apache Point observatory
in New Mexico. The SDSS covers an area of  14; 555 deg2 on the sky (over
1/3 of the celestial sphere) in five optical bands (ugriz, Fukugita et al. 1996). The last
data release (DR12, Alam et al. 2015) contains  4:7  108 cataloged objects (detected
in the optical r-band) and more than 1:8  106 galaxy spectra.

Toutes les DR jusqu'au DR17 (2021):
Total spectra
    5,789,200
Useful spectra
    4,846,156
Galaxies
    2,863,635
    
  Galaxies cataloguées
    208,478,448

*Première observation de la distribution à grande échelle des galaxies (structure dite "en bulles") par le CfA Redshift Survey. Le graphe représente environ un millier de galaxies. Crédit : De Lapparent et al (1986), SAO. [Source](http://tdc-www.harvard.edu/zcat/)*

![cfa1998](http://tdc-www.harvard.edu/zcat/cfa2.n30.gif)

## L'univers s'accélère

The model
describes the geometry and material content of the Uni-
verse, explaining how structure - galaxies of various sizes
and types, groups and clusters of galaxies, the entire cos-
mic web of filaments and voids - emerged from a hot and
near-uniform Big Bang. This astonishing richness appears
to have grown from quantum zero-point fluctuations pro-
duced during a period of cosmic inflation occurring very
soon after the beginning of our Universe. Over the sub-
sequent 13.7 billion years, these small density perturba-
tions were amplified by the relentless action of gravita-
tional forces due predominantly to dark matter, but illumi-
nated by complex astrophysical phenomena involving ordi-
nary matter. In the standard model, the dark matter, which
makes up five sixths of all matter, is hypothesised to be a
weakly interacting non-baryonic elementary particle, cre-
ated in the early stages of cosmic evolution.

Although mas-
sive neutrinos had already been suggested as a dark matter
candidate by Cowsik and McClelland [8,9] and Szalay and
Marx [10], White and Rees considered an early population
of low-mass stars as the most plausible identification for
the dark matter in their theory.
The evolution of the halo population in this theory was
based on Press and Schechter’s [11] analytic model for the
growth of cosmic structure from a Gaussian initial density
field. To test this model, Press and Schechter carried out
computer N-body simulations. This was the first time nu-
merical experiments were used for quantitative exploration
of nonlinear structure formation in an expanding universe.

The direct N-body integrators of the
1970’s could follow ∼ 1000 particles within an expanding
spherical volume (N = 4000 in two simulations by Aarseth,
Gott and Turner [13]) so small particle numbers and edge
effects seriously limited the conclusions which could be
drawn. 

Today’s standard model of cosmology arose through the
confluence of three distinct disciplines: particle physics, as-
tronomy and computing. In the early 1980s, new develop-
ments in each of these areas coalesced to establish the phys-
ical foundations and methodology of what, twenty years
later, would become the standard model.

From particle physics came two fundamental new ideas.
The first was Guth and Linde’s theory of cosmic inflation
[27, 28] and the realisation that it could give rise to quan-
tum fluctuations that might seed the universe with adia-
batic, scale invariant density perturbations [29–32]. The
second was the proposal that the dark matter (DM) could
be composed of non-baryonic particles. This idea took cen-
tre stage after Lubimov et al. [33] measured a ∼ 30eV mass
for the electron neutrino, enough to provide the critical
density needed to close the universe [8]. Such light par-
ticles would remain relativistic until relatively late times,
but it was soon recognized that other (hypothetical) parti-
cles which were more massive and decoupled earlier could
also be dark matter. This led to the convenient classification
of candidate dark matter particles into three families: hot,
warm and cold dark matter, names that reflect their typical
velocities at some early time, for example at the epoch of
recombination [21]. Light neutrinos are the prototype for
hot dark matter (HDM) and are the only DM candidates
that are proven to exist from earth-bound experiments; a
supersymmetric particle [34] or an axion [35] emerged as
plausible candidates for cold dark matter (CDM); a non-
standard gravitino was the initially suggested candidate for
warm dark matter (WDM) [36], but more recently, a sterile
neutrino has seemed a more attractive possibility

For the first time, there was a plausible physical mech-
anism to generate small density irregularities in the very
early universe and several concrete proposals for the iden-
tity of the dark matter which would drive their late-time
amplification. Thus, the ingredients were in place for de-
tailed linear calculations of the evolution of structure in the
universe, from its initial generation until the formation of
the first nonlinear objects. 

Inflation seeds the universe with nearly scale invari-
ant, adiabatic density perturbations of very small (and tun-
able) amplitude and a simple power-law power spectrum,
P(k) ∝ k n , where n is close to, but smaller than unity.
As the universe expands, the growth of these perturba-
tions is regulated initially by the dominant radiation com-
ponent and later by the dark matter. 

the smallest structure which can
form directly is radically different in each case: for HDM,
superclusters form first and must fragment to make galax-
ies; for WDM and CDM, small objects form first and grow
by merging and accretion to make bigger systems. Dark
matter objects significantly smaller than galaxies can form
in CDM, but not in WDM.
The proposal of inflationary fluctuation generation and
the rise of interest in particle dark matter coincided with the
publication of the first extensive 3D survey of galaxies, the
CfA redshift survey [39]. Lilliputian by today’s standards,
this survey gave the first clear picture of the richness of
the large-scale distribution of galaxies, offering a glimpse
of what would later be called the “cosmic web” 

N-body simulations had been used
in previous years to study the growth of nonlinear structure
in an expanding universe, and the size of feasible calcula-
tions was increasing rapidly through developments in both
hardware and algorithms. 

the ex-
clusion of a neutrino-dominated universe was a major suc-
cess for the then new cosmological methodology: a light
neutrino mass in the ∼ 30 eV range was conclusively ruled
out by a combination of N-body simulations and astronom-
ical observations. Attention then shifted to the alternative
possibility of a universe dominated by cold dark matter.
The first simulations of structure formation in such a uni-
verse [44] (hereafter DEFW), illustrated in Fig. 2, revealed
that this hypothesis gave far better results when compared
to the CfA data. 

following the formation and evo-
lution of the galaxies within each dark halo in the simu-
lated volume. It might seem that this would best be accom-
plished by direct inclusion of the baryonic component and
all the astrophysical processes affecting it. Unfortunately,
this is far beyond current computational capabilities. The
difficulty is that the relevant baryonic processes are not
only much more diverse and complex than the purely gravi-
tational processes which affect the dark matter, but are also
sensitive to much smaller length- and time-scales than can
be followed in a cosmological simulation (related, for ex-
ample, to star formation and evolution or black hole ac-
cretion). Although this is currently a very active area of
computational astrophysics and progress is rapid, such hy-
drodynamic galaxy formation simulations are still far from
reproducing basic properties of the galaxy population such
as their abundance as a function of stellar mass or their spa-
tial clustering [85–88].
An alternative approach takes the assembly history and
structure of each dark halo from a large cosmological simu-
lation and calculates the growth of galaxies within it using
simplified phenomenological treatments of baryonic pro-
cesses. The latter are typically based on physical insights
gained from simulations of individual systems and from
observation [89–91]. Uncertain parameters such as the ef-
ficiencies of star formation, of black hole growth or of
feedback from stars and black holes can be adjusted to re-
produce the properties of the observed galaxy distribution,
thus providing a practical and empirical route to measure
these efficiencies and their dependence on galaxy mass and
epoch.

Recent semi-analytic galaxy formation simulations fol-
low the evolution of millions of galaxies throughout vol-
umes comparable to those of new very large redshift sur-
veys like the SDSS. In particular, several generations of
publicly available models based on the Millennium Sim-
ulatio [96, 98–101] have produced ever closer matches
to the observed galaxy population and have been widely
used by the community4. This success reflects the fact
that simulations of this kind make it possible to construct
mock surveys where the simulated galaxy population is
"observed" with a virtual telescope to produce a sample
in which galaxy properties and the large-scale structure
can be compared directly with those observed in real sur-
veys

Dark matter halos are the fundamental nonlinear units of
cosmic structure and galaxies condense in their cores. As
a result, halos have a special status in cosmology. Under-
standing their basic properties – formation histories, inter-
nal structure and abundance – is an important step in devis-
ing astronomical tests of the ΛCDM paradigm and in ex-
ploring how galaxies form. Halos are also the prime hunt-
ing ground for dark matter detection. Direct detection ex-
periments target dark matter particles at the Earth’s posi-
tion within our own Galactic halo; indirect detection exper-
iments target the radiation from decaying or annihilating
dark matter particles, and this is also strongly affected by
the structure of halos.

The idea that dark matter is made of free elementary par-
ticles of some new type will likely be fully accepted by
the scientific community only once non-gravitational ef-
fects of these particles have been unambiguously measured.
Two routes to making such measurements are being ac-
tively pursued. Direct detection experiments attempt to
measure the effects of dark matter particles in a laboratory.

The second route to non-gravitational detection is by
searching for annihilation or decay products from dis-
tant dark matter concentrations. In typical supersymmetric
models WIMPS can decay and can annihilate with each
other. Both processes can have a significant branching ra-
tio into photons which would then be detectable with γ-
ray telescopes. Since particle decay is independent of en-
vironment, it would produce γ-ray images of dark matter
halos which trace their mass distribution, just as optical
images of galaxies trace their star distribution. 

The evidence that the universe conforms to the expecta-
tions of the CDM model is compelling but not decisive.
Current observational tests span a very wide range of
scales. Fluctuations in the microwave background probe
from the whole observable universe down to the scale of
rich galaxy clusters. Galaxy and quasar clustering probe
scales between one and a few hundred megaparsecs. Gravi-
tational lensing measurements constrain the detailed struc-
ture of galaxy and cluster halos. Observations of the Ly-
α forest at z ∼ 2 probe down to scales far below those
responsible for forming bright galaxies like the Milky
Way, putting severe constraints on warm dark matter and
on any subdominant contribution from massive neutrinos
[194, 208, 209]. Nevertheless, new data are needed to test
the model on even smaller scales. Currently, warm dark
matter remains possible if the particles are sufficiently mas-
sive to evade the Ly-α forest constraints. More exotic pos-
sibilities such as self-interacting dark matter may also be
possible, provided their properties are carefully tuned. Ex-
perimental searches for such alternative types of dark mat-
ter would need to be quite different than those for WIMPS
or axions, so it is imperative that astrophysicists continue
to test the standard model and to evaluate possible evidence
for alternatives. Dwarf galaxies are a prime source of such
evidence, both in the field and as satellites of larger galax-
ies.
On subgalactic scales, currently viable hypotheses for
the dark matter can produce strikingly different structure.

There are three aspects of small-scale structure where
potential conflicts with the cold dark matter model have
been identified: (i) the luminosity function of galactic satel-
lites, (ii) the abundance of galactic substructures as a func-
tion of mass or circular velocity and (iii) the structure of the
halos that host faint satellites or field dwarfs. Problem (ii)
was the first to be clearly identified in the late 1990s when
N-body simulations revealed a large number of subhalos
within galactic halos, vastly exceeding the number of satel-
lites then known to be orbiting in the halo of the Milky Way
[136, 175]. In its original form, the problem was expressed
as an excess of subhalos as a function of their circular ve-
locity or mass but it was soon re-expressed as an excess of
subhalos as a function of their galaxy luminosity. Although
closely related, these two statements are conceptually dis-
tinct and the solutions that have been proposed differ for
the two cases.
The small number of visible satellites in the Milky Way
compared to the large number of subhalos in N-body simu-
lations of galactic halos is often referred to as “the satellite
problem”. Soon after it was first formulated, a new popu-
lation of ultra-faint dwarf satellites was discovered in the
Milky Way [211–215], but they are too small and too few
to alter the argument. 

The three problems mentioned at the beginning of this
section remain a subject of lively debate and suggest clear
avenues for astrophysical progress, both theoretical and ob-
servational. Higher resolution N-body simulations will fur-
ther explore predictions for warm and self-interacting dark
matter. More realistic N-body and hydrodynamic simula-
tions should clarify whether baryonic effects are indeed vi-
able explanations for the apparent discrepancies with pre-
dicted halo structure. 

Most searches are focused on cold dark matter. This is
entirely justified: the cold dark matter model has been the
catalyst for the momentous developments of the past thirty
years. The statistical properties of the large-scale distribu-
tion of galaxies, the form and amplitude of the microwave
background temperature fluctuations and many aspects of
galaxy formation were predicted (in advance!) by theoret-
ical models that had cold dark matter at their heart. Time
and again when astronomical data seemed to conflict with
the model (for example, the clustering of galaxy clusters,
large-scale streaming data, galaxies at very high redshift)
the conflict has been resolved either by revisions of the data
or by refinments of the theory. Nevertheless, even the most
ardent supporters of the cold dark matter idea must remain
sceptical until the dark matter particles are finally and con-
clusively discovered.

1970-1980 Prehistory
Dark matter (DM) halos are proposed to surround all galaxies
Massive neutrinos are suggested as a dark matter candidate
Large-scale structure is characterized through the measurement of galaxy correlation functions
First analytic models and computer simulations are built for nonlinear structure formation in an expanding universe
Simulations from idealized initial conditions contrast the “isothermal” case where structure grows by hierarchical merging
with the "adiabatic" case where galaxies form by fragmentation of large-scale structure

1980-83 The breakthrough years
The CfA redshift survey provides a first representative picture of the cosmic web
A claimed measurement of a 30eV mass for νe galvanizes research into elementary particle dark matter
Quantum fluctuations during an early inflationary era are suggested as a physical model for the initial generation of density
fluctuations
Improved calculations of early linear evolution provide accurate initial conditions for late-time growth, dividing particle
candidates into Hot, Warm and Cold Dark Matter (HDM, WDM, CDM respectively)
Simulations from these initial conditions exclude HDM (and hence all known particle species) for the bulk of the DM

1983-2002 Establishment of the standard model
Simulations from CDM initial conditions produce large-scale structure resembling that seen in redshift surveys
Galaxies are shown to trace the DM distribution in a biased way depending strongly on galaxy type and on epoch
The first direct detection experiments and the first searches for DM annihilation radiation are set up
The COBE measurement of temperature fluctuations in the cosmic microwave background (CMB) indicates an amplitude
too small for a universe without particle DM, but too large for a universe with a closure density of such DM
Large-scale correlations of galaxies and the baryon fraction of rich clusters prove inconsistent with a high-density universe
Simulations establish the detailed structure expected for DM halos in a CDM universe
Supernova measurements rule out a high density universe and strongly suggest accelerated expansion
Boomerang and Maxima convincingly localize the first acoustic peak in the CMB, showing our universe to be flat
WMAP convincingly measures the second acoustic peak also, excluding many alternatives to the standard model and giving
precise estimates of the baryon and dark matter densities

2002-present Pushing to new frontiers
Simulations explore the predictions of the standard model at higher precision and on both larger and smaller scales
Gravitational lensing measurements check the detailed structure predicted for dark halos
Large redshift surveys give precise measures of galaxy biasing, and of the Gaussianity and power spectrum of the initial
conditions, detecting weak baryon-induced features
Simulations and observations explore constraints on the nature of the dark matter based on the inner structure of dark halos
and on structure in the intergalactic medium
Both direct detection experiments and the Fermi satellite begin to exclude parts of the parameter space expected for WIMPs

## Le modèle standard aujourd'hui

- Depuis les années 2000
- Lambda-CDM
- 6 paramètres libres
- l'ère de la "cosmologie de précision"

# Le modèle standard à l'épreuve des observations

*Sources*

- [Anomalies in Physical Cosmology](https://arxiv.org/abs/2208.05018) - Peebles (2022)
- [Cosmology Intertwined: A Review of the Particle Physics, Astrophysics, and Cosmology Associated with the Cosmological Tensions and Anomalies](https://arxiv.org/abs/2203.06142) - Abdalla et al (2022)
- [SMALL-SCALE CHALLENGES TO THE ΛCDM PARADIGM](http://ned.ipac.caltech.edu/level5/Sept18/Bullock/Bullock2.html) - Bullock et Boylan-Kolchin (2017)
- [The Core-Cusp Problem](https://arxiv.org/abs/0910.3538) - de Block (2009)
- [Dwarf galaxies yesterday, now and tomorrow](https://sazabi4.github.io/DwarfGalaxies2021_NatAst.pdf) - Crnojević et Burçin Mutlu-Pakdil (2021)
- [The Planes of Satellite Galaxies Problem, Suggested Solutions, and Open Questions](https://arxiv.org/abs/1802.02579) - Pawlowski (2018)
- [Satellite Galaxies Live In A Single Plane, Defying Dark Matter Predictions](https://www.forbes.com/sites/startswithabang/2018/02/01/satellite-galaxies-live-in-the-same-plane-as-their-hosts-defying-dark-matter-predictions/?sh=7abf95ad2971) - Ethan Siegel (2018)
- [The coherent motion of Cen A dwarf satellite galaxies remains a challenge for ΛCDM cosmology](https://hal.archives-ouvertes.fr/hal-03104420/document) - Muller et al (2021)
- [Un plan de galaxies satellites en rotation autour de Centaurus A défie le modèle cosmologique standard](https://www.ca-se-passe-la-haut.fr/2021/01/un-plan-de-galaxies-satellites-en.html) - Ca se passe là-haut (2021) 
- [A Solution to “Too Big to Fail”](https://aasnova.org/2016/10/03/a-solution-to-too-big-to-fail/) - AAS Nova (2016)
- [Galaxies That Are Too Big To Fail, But Fail Anyway](https://www.preposterousuniverse.com/blog/2014/07/18/galaxies-that-are-too-big-to-fail-but-fail-anyway/) - Preposterous Universe (2014)
- [Small Scale Problems of the ΛCDM Model: A Short Review](https://www.mdpi.com/2075-4434/5/1/17) - Del Popolo et Le Delliou (2016)
- [satellite plane problem](http://astro.vaporia.com/start/satelliteplaneproblem.html)

---

## À l'échelle des galaxies

- Le modèle ΛCDM fonctionne très bien pour prédire la formation et la distribution des grandes structures cosmiques. Par contre, il ne parvient pas encore à reproduire les propriétés observées des différentes familles de galaxies. 
> * Dans les simulations informatiques (N-corps) réalisées dans le cadre du modèle standard, les particules de matière noire (froide) ont tendance à s’accumuler au centre des galaxies de faibles masses. Or, les courbes de rotation observées dans ce type de galaxies ne montrent pas un tel pic de densité. C’est le ***problème de la concentration du halo*** (core-cusp problem). Il est possible de résoudre ce problème dans les simulations en faisant appel à des supernovæ et à des noyaux actifs de galaxies (AGN) qui transmettent leur énergie aux particules de matière noire froide (baryonic feedback). Il est aussi possible de résoudre ce problème hors du cadre du paradigme ΛCDM en faisant appel à de la matière noire « tiède » ou « auto-interagissante » (self-interacting), ie où les particules entrent en collisions entre elles, ce qui aurait pour effet de les disperser. 
> * Les simulations cosmologiques dans le modèle standard prédisent aussi l’existence de milliers de petites galaxies satellites entourant les galaxies massives comme la Voie Lactée, qui se formeraient dans autant de « sous-halos » de matière noire. Or, on n’observe aujourd’hui qu’une soixantaine de galaxies naines orbitant autour de notre Galaxies. C’est le ***problème des galaxies satellites manquantes*** (missing satellites problem). Les futurs relevés astronomiques permettront probablement de détecter des centaines de galaxies naines ultra-pâles (ultra-faint dwarfs), c’est-à-dire de très faible luminosité, mais quoi qu’il en soit il est très improbable que l’on en découvre des milliers. On peut  notamment résoudre le problème des satellites manquants en faisant appel à de la matière noire « tiède », ce qui a pour effet d’éviter l’apparition de nombreuses structures à petite échelle.
> * Les simulations prédisent aussi que les galaxies satellites doivent être distribuées en un vaste halo sphérique autour des galaxies massives. Or, lorsqu’on observe la distribution des galaxies naines autour de la Voie Lactée, de la galaxie d’Andromède ou encore de Centaurus A (une galaxie lenticulaire), on remarque que ces satellites sont plutôt distribués dans une structure plane (autrement dit, un disque), inclinée par rapport au disque galactique. C’est le ***problème des plans de satellites*** (plane-of-satellites problem). Il n’a pour le moment aucune explication viable à ce phénomène dans le cadre de ΛCDM.
> * Une solution au problème des satellites manquants consiste à affirmer que les galaxies naines autour de la Voie Lactée sont bien plus nombreuses que celles que l’on observe, mais que la plupart de ces satellites ont été déshabillées de leurs étoiles et de leur gaz à cause des interactions gravitationnelles avec la Voie Lactée. Les galaxies naines que l’on observeraient seraient celles issues des sous-halos de matière noire les plus massifs. Malheureusement, cette solution cause un nouveau problème : de nombreuses galaxies satellites prédites par ΛCDM sont si massives qu’il est impossible qu’elles aient perdues ainsi leurs étoiles. Une autre manière de formuler ce problème est de pointer le fait que les satellites observés de la Voie Lactée sont trop peu massifs par rapport aux satellites prédits par ΛCDM. C’est le ***problème des galaxies « trop grosses pour échouer »*** (too big to fail problem). 

*Problème de la concentration du halo. Le profil en "cusp" est prédit par ΛCDM, mais c'est le profil en "core" qui est observé dans les galaxies naines. Crédit : Del Popolo et Le Delliou (2021). [Source](https://www.mdpi.com/2075-4434/9/4/123/htm)*

![corecusp](https://i.imgur.com/xEETZrX.jpg)

*Problème des satellites manquants. Crédit : Bullock et Boylan-Kolchin (2017). [Source](http://ned.ipac.caltech.edu/level5/Sept18/Bullock/Bullock2.html)*

![missingsatellites](https://i.imgur.com/5jeQMVf.jpg)

*Plans de satellites autour de la Voie Lactée, d'Andromède et de Cenaurus A. Crédit : [Pawlowski (2018)](https://arxiv.org/abs/1802.02579). [Source](https://astro.uni-bonn.de/~pavel/CONFERENCES/MOND2019/website/Talks/Thursday/Pawlowsk_BonnGravity2019.pdf)*

![plan-of-galaxies](https://i.imgur.com/uDeCcwe.png)

# La cosmologie quantique

*Sources*

- [Quantum cosmology: a review](https://arxiv.org/abs/1501.04899) - Bojowald (2015)
- [Loop Quantum Cosmology: A brief review](https://arxiv.org/abs/1612.01236) - Agulo et Singh (2016)
- [Conceptual Problems in Quantum Gravity and Quantum Cosmology](https://www.hindawi.com/journals/isrn/2013/509316/) - Kiefer (2013)
- [Quantum Gravity](https://plato.stanford.edu/entries/quantum-gravity/) - Stanford Encyclopedia of philosophy
- [String Cosmology: A Review](https://arxiv.org/abs/0710.2951) - McAllister et Silverstein (2007)
- [Loop Quantum Gravity](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5567241/) - Carlo Rovelli (1998)

---

# Matière noire

*Sources*

- [A History of Dark Matter](https://arxiv.org/pdf/1605.04909.pdf) - Berton et Hooper (2016)
- [Dark matter and cosmic structure](https://arxiv.org/abs/1210.0544) - Frenk and White (2012)
- [La matière noire, une sombre affaire](https://www.refletsdelaphysique.fr/articles/refdp/pdf/2016/04/refdp201651p4.pdf) - Combes (2016)
- [Dark matter and cosmic structure](https://arxiv.org/abs/1210.0544) - White et Frenk (2012)
- [The Search for Dark Matter Is Dramatically Expanding](https://www.quantamagazine.org/physicists-are-expanding-the-search-for-dark-matter-20201123/) - Quanta Magazine
- [Axion Dark Matter: What is it and Why Now?](https://arxiv.org/abs/2105.01406) - Chadha-Day et al (2021)
- [In the hunt for dark matter, are axions our best bet?](https://www.space.com/dark-matter-axions-best-bet) - Space.com (2022)
- [Dark Matter Candidates from Particle Physics and Methods of Detection](https://arxiv.org/abs/1003.0904) - Feng et al (2010)
- [Dark Matter Candidates](https://www.slac.stanford.edu/econf/C040802/papers/L002.PDF) - Baltz (2004)
- [What is Dark Matter Made Of? These Are the Top Candidates](https://www.discovermagazine.com/the-sciences/what-is-dark-matter-made-of-these-are-the-top-candidates) - Discover Magazine
- [What could dark matter be?](https://www.symmetrymagazine.org/article/what-could-dark-matter-be) - Symmetry Magazine (2015)
- [A Brief Review on Primordial Black Holes as Dark Matter](https://www.frontiersin.org/articles/10.3389/fspas.2021.681084/full) - Villanueva-Domingo et al (2021)
- [(Just can’t get enough) primordial black holes](https://astrobites.org/2018/02/13/just-cant-get-enough-primordial-black-holes/) - Astroites (2018)
- [Exploring the high-redshift PBH-ΛCDM Universe: early black hole seeding, the first stars and cosmic radiation backgrounds](https://arxiv.org/abs/2109.08701) - Cappelluti et al (2021)
- [Neutrinos Stériles et Matière Noire font Bon Ménage](https://www.ca-se-passe-la-haut.fr/2014/05/neutrinos-steriles-et-matiere-noire.html) - Ca se passe là-haut (2014)
- [WIMPs and MACHOs](https://sites.astro.caltech.edu/~george/ay20/eaa-wimps-machos.pdf) - ENCYCLOPEDIA OF ASTRONOMY AND ASTROPHYSICS (2002)
- [Forget WIMPs, Axions And MACHOs: Could WIMPzillas Solve The Dark Matter Problem?](https://www.forbes.com/sites/startswithabang/2018/05/09/forget-wimps-axions-and-machos-could-wimpzillas-solve-the-dark-matter-problem/?sh=3a0cc9fc3a22) - Ethan Siegel
- [Supersymmetry](https://home.cern/fr/science/physics/supersymmetry) - CERN
- [WIMPZILLAS!](https://arxiv.org/abs/hep-ph/9810361) - Kolb et al (1998)
- [Wimpzillas leave tracks say astronomers](https://www.newscientist.com/article/dn2342-wimpzillas-leave-tracks-say-astronomers/) - New Scientist 
- [Superheavy dark matter through Higgs portal operators](https://arxiv.org/abs/1708.04293) - Kolb et al (2019)
- [Oh-My-God (Particle), It’s WIMPzilla!](https://mcdonaldinstitute.ca/apbites/2019-09-11-its-wimpzilla/) - AstroParticle Bites (2019) 
- [WIMPZillas: The Biggest WIMPs](https://darkmatterdarkenergy.com/2018/06/26/wimpzillas-the-biggest-wimps/) - Stephen Perrenod
- [Axion dark matter: What is it and why now?](https://www.science.org/doi/10.1126/sciadv.abj3618) - Chadha-Day et al (2022)
- [Les sym ́etries au fondement de la physique moderne](https://web.umons.ac.be/app/uploads/sites/31/2019/01/News-Complexys_J.-Fran%C3%A7ois.pdf) - Jordan François
- [Axions : l'Autre Matière Noire](https://www.ca-se-passe-la-haut.fr/2013/11/axions-lautre-matiere-noire.html) - Ca se passe là-haut (2013) 
- [The universe according to Frank Wilczek](https://www.templetonprize.org/the-universe-according-to-frank-wilczek/) - Templeton Prize
- [OSQAR](https://home.cern/fr/science/osqar) - CERN
- [Le chasseur de matière noire XENON1T détecte un signal suspect](https://www.cieletespace.fr/actualites/le-chasseur-de-matiere-noire-xenon1t-detecte-un-signal-suspect) - Ciel et Espace (2020)
- [La matière noire pointe-t-elle enfin le bout de son nez dans Xenon 1T ?](https://www.futura-sciences.com/sciences/actualites/nouvelle-physique-matiere-noire-pointe-t-elle-enfin-bout-son-nez-xenon-1t-60517/) - Ciel et Espace (2020)
- [L'asymétrie CP ou le privilège de la matière](http://www.astrosurf.com/luxorion/quantique-asymetrie-cp.htm) - Astrosurf
- [Matière noire (axions) : nouveaux résultats de deux haloscopes](https://www.ca-se-passe-la-haut.fr/2021/05/matiere-noire-axions-nouveaux-resultats.html) - Ca se passe là-haut (2021)
- [Limits on the Macho content of the Galactic Halo from the EROS-2 Survey of the Magellanic Clouds](https://www.aanda.org/articles/aa/abs/2007/26/aa6017-06/aa6017-06.html) - Tisserand et al (2007)
- [The OGLE view of microlensing towards the Magellanic Clouds – IV. OGLE-III SMC data and final conclusions on MACHOs](https://academic.oup.com/mnras/article/416/4/2949/976362) - Wyrzykowski et al (2011)
- [MACHOs](https://astronomy.swin.edu.au/cosmos/m/MACHOs) - ENCYCLOPEDIA OF ASTRONOMY AND ASTROPHYSIC
- [Introduction to Dark Matter](https://link.springer.com/chapter/10.1007/978-3-030-95852-7_1) - Derek Jackson Kimball et Dmitry Budker (2023)   
- [MaCHO Dark Matter (What is it?)](https://youtu.be/9GzB7mNWXAE) - Chris Pattison  
- [The Dark Matter Enigma](https://inference-review.com/article/the-dark-matter-enigma) - Jean-Pierre Luminet (2020)
- [Neutrinos stériles : MINOS+ contredit MiniBooNE](https://www.ca-se-passe-la-haut.fr/2019/03/neutrinos-steriles-minos-contredit.html) - Ca se passe là-haut (2019)
- [Rotation of the Andromeda Nebula from a Spectroscopic Survey of Emission Regions](http://adsabs.harvard.edu/abs/1970ApJ...159..379R) - Rubin et Ford (1970)
- [Rotational properties of 21 Sc galaxies with a large range of luminosities and radii](https://ui.adsabs.harvard.edu/abs/1980ApJ...238..471R/abstract) - Ford et Rubin (1980) 
- [1978: Vera Rubin and Kent Ford Confirm the Existence of Dark Matter](https://cosmology.carnegiescience.edu/timeline/1978.html) - Observatories of the Carnegie Institution for Science 
- [Découverte de la matière noire](https://cosmology.education/decouverte-matiere-noire/#!) - Lucas Gautheron 
- [How one person discovered the majority of the universe – The work of Vera Rubin](https://astrobites.org/2016/12/27/how-one-person-discovered-the-majority-of-the-universe-the-work-of-vera-rubin/) - AStrobites
- [Public misconceptions of Vera Rubin’s career pervade news cycle](https://miscellanynews.org/2017/02/01/opinions/public-misconceptions-of-dark-matter-pervade-news-cycle/) - Steven Park
- [Vera Rubin and Dark Matter ](https://www.amnh.org/learn-teach/curriculum-collections/cosmic-horizons-book/vera-rubin-dark-matter) - AMNH
- [How Vera Rubin broke barriers and convinced the astronomy community that dark matter exists](https://physicsworld.com/a/how-vera-rubin-broke-barriers-and-convinced-the-astronomy-community-that-dark-matter-exists/) - Physics World
- [A primer on hierarchical galaxy formation: the semi-analytical approach](https://arxiv.org/pdf/astro-ph/0610031.pdf) - Baugh (2006)
- Cosmologie moderne - James Peebles (2022)
- [The Current Status of Galaxy Formation](https://arxiv.org/abs/1207.3080) - Silk et Mamon (2012)
- [La théorie Mond marque encore des points contre la matière noire](https://www.futura-sciences.com/sciences/actualites/matiere-noire-theorie-mond-marque-encore-points-matiere-noire-41401/) - Futura Sciences (2020)
- [Les caractéristiques du CMB reproduites pour la première fois par un modèle de gravitation modifiée](https://www.ca-se-passe-la-haut.fr/2021/10/les-caracteristiques-du-cmb-expliquees.html) - Ca se passe là-haut (2021) 
- [MOND - A PEDAGOGICAL REVIEW](https://ned.ipac.caltech.edu/level5/Sept01/Milgrom2/Milgrom_contents.html) - Milgrom (2001)
- [Modified Newtonian Dynamics as an Alternative to Dark Matter](https://arxiv.org/abs/astro-ph/0204521) - Sanders et McGaugh (2002)
- [Modified Newtonian dynamics](https://en.wikipedia.org/wiki/Modified_Newtonian_dynamics#Outstanding_problems_for_MOND) - Wikipédia
- [MOND](https://ncatlab.org/nlab/show/MOND) - nLab
- [Literature relating to the Modified Newtonian Dynamics (MOND)](http://astroweb.case.edu/ssm/mond/litsub.html) - Stacy McGaugh
- [The MOND Pages](http://astroweb.case.edu/ssm/mond/) - Stacy McGaugh
- [Modified Newtonian Dynamics](https://www.sciencedirect.com/topics/physics-and-astronomy/modified-newtonian-dynamics) - ScienceDirect 
- [MODIFIED GRAVITY](https://ned.ipac.caltech.edu/level5/Sept16/Bertone/Bertone7.html) - Bertone (2016)
- [MOND avec ou sans matière noire](http://www2.iap.fr/users/blanchet/images/Recherche.pdf) - Blanchet et Combes (2009) 
- [A Feasible and Decisive Test between Newtonian and Varying-G Gravity that can be Conducted in the Oort Cloud](https://www.researchgate.net/publication/333907246_A_Feasible_and_Decisive_Test_between_Newtonian_and_Varying-G_Gravity_that_can_be_Conducted_in_the_Oort_Cloud) - Christodoulou et al (2019)
- [A modification of the Newtonian dynamics as a possible alternative to the hidden mass hypothesis](https://ui.adsabs.harvard.edu/abs/1983ApJ...270..365M/abstract) - Milgrom (1983)
- [Physique des galaxies en gravité modifiée](https://www.college-de-france.fr/agenda/cours/le-probleme-de-la-matiere-noire-galaxies-spirales/physique-des-galaxies-en-gravite-modifiee) - Cours de Françoise Combes (2015) 
- [Barred Spiral Galaxy](https://en.wikipedia.org/wiki/Barred_spiral_galaxy) - Wikipédia
- [La matière noire dans l’Univers](https://books.openedition.org/cdf/4575?lang=fr) - Cours de Françoise Combes (2014)  
- [Evolution des galaxies:Interactions, fusions, et accretion de gaz](https://theses.hal.science/tel-00079377/document) - Thèse de Frédéric Bournaud (2006)
- [A Brief History of Dark Matter](http://physics.ucsc.edu/~joel/DarkMatterHist.pdf) - Joel Primack (2007)
- [The MOND paradigm of modified dynamics](www.scholarpedia.org/article/The_MOND_paradigm_of_modified_dynamics) - Scholarpedia
- [Modified Newtonian Dynamics (MOND): Observational Phenomenology and Relativistic Extensions](https://arxiv.org/abs/1112.3960) - Famaey et McGaugh (2011)
- [Modified Newtonian Dynamics, an Introductory Review](https://arxiv.org/abs/astro-ph/0601478) - Scarpa (2006)
- [Matière noire et gravité modifiée](http://aramis.obspm.fr/~combes/fcombes/sem/MOND-21.pdf) - Françoise Combes (2021)
- [Challenges for ΛCDM and MOND](https://iopscience.iop.org/article/10.1088/1742-6596/437/1/012001/pdf) - Famaey et McGaugh (2013)
- [Matière noire : la piste de la gravité modifiée passe un test crucial](https://www.pourlascience.fr/sd/cosmologie/matiere-noire-la-piste-de-la-gravite-modifiee-passe-un-test-crucial-23353.php) - Pour la science (2022) 
- [A new relativistic theory for Modified Newtonian Dynamics](https://arxiv.org/abs/2007.00082) - Skordis et Zlosnik (2021)
- [Dark matter – Evidence and Candidates](https://www.mpi-hd.mpg.de/lin/_isapp2019/talks/ISAPP2019-Weniger_1.pdf) - Slides de Christoph Weniger (2019)
- [Physics Beyond the Standard Model and Dark Matter](https://arxiv.org/abs/0704.2276) - Murayama (2007)  
- [Dark Matter: A Primer](https://www.hindawi.com/journals/aa/2011/968283/) - Garrett et Duda (2010)
- [Dark matter in astrophysics/cosmology](https://indico.cern.ch/event/949654/contributions/4025903/attachments/2288387/3890053/2evidence.pdf) - Slides de Anne Green  
- [Astrophysical and Cosmological Probes of Dark Matter](https://www.scirp.org/html/7-7500789_23061.htm) - Roos (2012)
- [Rayonnement cosmique et détection indirecte de matière noire](https://theses.hal.science/tel-00880159/document) - Thèse de David Maurin (2013)
- [Probing the Dark Matter Content of Local Group Dwarf Spheroidal Galaxies with FLAMES](https://www.eso.org/sci/publications/messenger/archive/no.124-jun06/messenger-no124-25-29.pdf) - Wilkinson et al (2006) 
- [La dynamique interne des galaxies naines dirigée par les effets gravitationnels de la Voie Lactée et non par la matière noire](https://www.ca-se-passe-la-haut.fr/2018/06/la-dynamique-interne-des-galaxies.html) - Ca se passe là-haut (2018)  
- [Galactic forces rule dynamics of Milky Way dwarf galaxies](https://arxiv.org/abs/1805.01469) - Hammer et al (2018)
- [Plus besoin de matière sombre pour expliquer la dynamique des galaxies naines](https://www.observatoiredeparis.psl.eu/plus-besoin-de-matiere-sombre.html) - Observatoire de Paris (2018)
- [The Bullet Cluster as Evidence against Dark Matter](http://backreaction.blogspot.com/2017/01/the-bullet-cluster-as-evidence-against.html) - Back Reaction (2017)
- [Visible-light and x-ray composite image of galaxy cluster 1E 0657-556](https://esahubble.org/images/opo0639a/) - ESA
- [L'amas de la Balle a-t-il tué MOND ?](http://lapth.cnrs.fr/pg-nomin/taillet/dossier_matiere_noire/matiere_noire4_bullet.php) - Richard Taillet
- [ASTROPHYSICAL AND COSMOLOGICAL PROBES OF DARK MATTER](https://ned.ipac.caltech.edu/level5/March15/Roos/frames.html) - Roos (2012)
- [Le rayonnement fossile](https://www.pourlascience.fr/sd/cosmologie/le-rayonnement-fossile-5110.php) - Pour la science (2003)
- [Non-Baryonic Dark Matter: Observational Evidence and Detection Methods](https://core.ac.uk/download/pdf/25279293.pdf) - Bergstrom (2000)
- [Big-Bang Nucleosynthesis and the Baryon Density of the Universe](https://www.jstor.org/stable/2885889) - Copi et al (1995)
- [Intermediate Guide to the Acoustic Peaks and Polarization](http://background.uchicago.edu/~whu/intermediate/second.html) - Wayne Hu (2001)
- [Dark matter universe](https://www.pnas.org/doi/10.1073/pnas.1516944112) - Bahcall (2015)
- [A direct empirical proof of the existence of dark matter](https://arxiv.org/abs/astro-ph/0608407) - Clowe et al (2006)
- [Structure formation in warm dark matter cosmologies: Top-Bottom Upside-Down](https://arxiv.org/abs/1506.03789) - Paduroiu et al (2015)
- [Cold dark matter vs warm dark matter](http://star-www.dur.ac.uk/~csf/talks/talks_2015/cdm_vs_wdm_karlsruhe.pdf) - Slides de Carlos Frenk
- [Dark Matter - Hot and Cold](http://burro.case.edu/Academics/Astr222/Cosmo/Structure/darkmatter.html) - Chris Mihos (2018)
- [Is dark matter cold, warm or hot?](https://www.symmetrymagazine.org/article/is-dark-matter-cold-warm-or-hot) - Symmetry Magazine (2021) 
- [Un monde moins macho](https://irfu.cea.fr/Phocea/Vie_des_labos/Ast/ast.php?t=fait_marquant&id_ast=1469) - CEA (2007)

---

## Histoire

- En 1933, un astronome suisse nommé Fritz Zwicky observe les vitesses radiales de 8 galaxies à l’intérieur de l’amas de Coma (Abell 1656), et remarque un curieux phénomène : la dispersion de vitesse de ces galaxies (estimée à l’aide de leur décalage spectral) est très supérieure (de l’ordre de 1000 km/s) à celle à laquelle on s’attendrait si la masse de l’amas était entièrement constituée de matière lumineuse (de l’ordre de 80 km/s). Pour expliquer la dispersion observée, il faudrait que l’amas contienne bien plus de masse que celle qui émet de la lumière. En d’autre termes, elle devrait contenir une sorte de matière « noire » (dunkel materie) en grande quantité. Sans cette matière noire pour retenir les galaxies dans son potentiel gravitationnel, l’amas aurait dû finir par se désagréger. Il conclut son article par la phrase suivante : « Si ce résultat devait être confirmé, il conduirait à la surprenante conclusion que la matière noire est bien plus abondante que la matière visible ». Mais pendant longtemps, l’hypothèse de la matière noire de Zwicky trouve peu d’écho dans la communauté scientifique, notamment à cause des grandes incertitudes qui entachent ses estimations (il avait notamment grandement sous estimé la distance de l’amas). 
> Pour estimer la masse (lumineuse) de l’amas, Zwicky multiplie le nombre observé de galaxies (800) par la masse moyenne d’une galaxie (1 milliard de masses solaires selon Hubble). Pour estimer la dispersion de vitesse théorique de l’amas, il fait appel au ***théorème du viriel*** , un théorème de mécanique newtonienne qui relie la masse d’une structure gravitationnellement liée et la vitesse des astres qui la compose.
- Entre les années 30 et 70, de nombreux chercheurs s’intéressent à la manière dont la masse est répartie au sein des galaxies. Une manière de tracer la masse consiste à observer le mouvement de ses étoiles. Comme on l’observe quasiment par la tranche, on peut estimer la vitesse à laquelle les étoiles orbitent autour du centre galactique. Si l’on calcule la vitesse orbitale des étoiles en fonction de leur distance au centre galactique, on obtient ce qu’on appelle une ***courbe de rotation***. Elle sert à estimer la distribution de masse dans la galaxie.
> Lorsque ces étoiles s’approchent de nous, leur lumière est décalée vers le bleu, et lorsqu’elles s’éloignent de nous, leur lumière est décalée vers le rouge (effet Doppler). Ce décalage de longueur d’onde étant proportionnel à la vitesse d’éloignement ou de rapprochement des étoiles par rapport à l’observateur, on peut estimer la vitesse de rotation des étoiles. 
- À la fin des années 60, les astronomes américains Vera Rubin et Kent Ford utilisent un nouveau spectromètre développé par Ford pour étudier la courbe de rotation de la galaxie d’Andromède (la galaxie spirale la plus proche de nous) avec une précision inédite. Ils observent pour cela une soixantaine de régions HII répartis sur toute l’étendue de la galaxie.
> La vitesse orbitale de ces régions peut être mesurée par le décalage Doppler de certaines raies d'émission de l'atome d’hydrogène (ici $H_{\alpha}$ ).
- Comme la région du centre galactique contient une concentration d’étoiles plus élevée que le reste de la galaxie, les lois de la gravitation de Newton prédisent que plus l’on s’éloigne du centre, moins la vitesse orbitale des étoiles devrait être élevée (décroissance en 1/r). C’est notamment ce qui se passe dans le système solaire, où la majorité de la masse est concentrée dans le Soleil. Les planètes du système solaire externe orbitent donc beaucoup moins vite que les planètes internes. On dit qu’elles suivent des ***orbites képleriennes***.
- Or, ce n’est pas du tout ce que Rubin et Ford observent ! Au lieu d’une courbe de rotation qui diminue avec la distance, la courbe de M31 est presque plate. Autrement dit, les étoiles en périphérie de la galaxie orbitent quasiment à la même vitesse que les étoiles proches du centre. Si l’on ne prenait en compte que la masse « lumineuse » de la galaxie, les étoiles de la périphérie auraient dû être éjectées de la galaxie. Tout se passe comme si ces étoiles étaient retenues par une masse invisible.
> * Les observations radio de la raie à 21 cm de l’hydrogène permettent de tracer les vitesses orbitales des régions encore plus  éloignées  du centre galactique que les données obtenues dans le domaine optique. Les mesures radio de la galaxie d’Andromède réalisées par Roberts et Whitehurst (1975) ont grandement participé à consolider les résultats de Rubin et Ford.
> * L’interprétation des courbes de rotation plates comme signe d’une masse invisible a été proposée pour la première fois en 1973 par Morton Roberts et Arnold Rots, suite à leur propre étude de M31 et d’autres galaxies (M81 et M101)
- En 1973, James Peebles et Jeremiah Ostriker montrent, par le biais de simulations informatiques (N-corps avec quelques centaines de points de masse), qu'un halo de matière invisible est nécessaire pour garantir la stabilité des disques des galaxies de forme aplatie. Si ces galaxies n’étaient composées que d’étoiles, elles donneraient systématiquement naissance à des barres d’étoiles. Or, toutes les galaxies spirales ne contiennent pas de barres. Ils ajoutent que cette masse invisible pourrait expliquer les courbes de rotation plates observées notamment par Rubin et Ford.
> L’argument de Peebles et Ostriker était en fait faux car la plupart des galaxies spirales (deux tiers) contiennent des barres, et qu’un halo de matière noire n’empêche pas forcément la formation de barres. On ne le savait juste pas à l’époque.
- Pendant près d’une décennie, Rubin et Ford réitèrent leurs mesures sur un échantillon toujours plus élevé de galaxies spirales, et trouvent systématiquement des courbes de rotation plates. Ces courbes finissent par convaincre une grande partie de la communauté scientifique que les galaxies sont enchâssées dans un halo beaucoup plus vaste que sa contribution « lumineuse ». Ce halo serait fait d’une matière invisible qui constitue près de 90% de la masse totale de la galaxie. 
- En 1978, Simon White et Martin Rees mettent la matière noire au centre de leur scénario de formation des galaxies. Les grandes lignes de ce scénario sont aujourd’hui à la base de notre compréhension moderne des galaxies.
> Il s’agit d’un scénario en deux étapes : dans un premier temps, des halos de matière noire grandissent à partir des conditions de l’univers primordial, par effondrement gravitationnel. Dans un deuxième temps, la matière baryonique « tombe » dans les puits gravitationnels formés par les halos de matière noire, se condense en leur centre et se refroidit pour donner naissance à la composante lumineuse des galaxies.
- Si l’on en croit le modèle standard (ΛCDM), on devrait trouver de la matière noire dans toutes les galaxies, à l’exception probable des ***naines de marées***, de petites galaxies produites par les effets de marées à partir des longues queues de gaz nées lors de la fusion entre deux grosses galaxies.

*Courbe de rotation de la galaxie d’Andromède. Crédit : Rubin et Ford (1970). [Source](https://www.researchgate.net/figure/Rotation-curve-of-M31-from-Rubin-Ford-1970-Rotational-velocities-for-OB_fig1_221915312)*
![rubinford70](https://i.imgur.com/nbnKRce.png)

*Courbes de rotation de 21 galaxies spirales. Crédit : Rubin et Ford (1980). [Source](https://astrobites.org/2016/12/27/how-one-person-discovered-the-majority-of-the-universe-the-work-of-vera-rubin/)*
![rotcurves21galaxies](https://astrobites.org/wp-content/uploads/2016/12/Screen-Shot-2016-12-27-at-1.47.30-PM-768x887.png)

*Courbe de rotation de M33. Données et prédictions issues de Corbelli et Salucci (2000). Crédit : Mario De Leo. [Source](https://en.wikipedia.org/wiki/Galaxy_rotation_curve#/media/File:Rotation_curve_of_spiral_galaxy_Messier_33_(Triangulum).png)*
![M33rotationcurve](https://upload.wikimedia.org/wikipedia/commons/c/cd/Rotation_curve_of_spiral_galaxy_Messier_33_%28Triangulum%29.png)

## Matière noire chaude, tiède ou froide ?

- En 1983, à l’occasion d’une conférence, les astronomes Dick Bond et Joel Primack introduisent une terminologie pour classifier les modèles théoriques de matière noire en fonction de la vitesse des particules au moment où elles se découplent du plasma primordial et où leur abondance est "gelée", une propriété aisément modélisable par le biais de simulations numériques.
> * La ***matière noire chaude*** (HDM) correspond à des particules dont la vitesse est proche de celle de la lumière. La masse de ces particules est de l’ordre de quelques eV. Exemple : le neutrino.
> * La ***matière noire froide*** (CDM) correspond à des particules relativement lentes (non relativistes). La masse de ces particules se situe entre $10^{-5}$ eV et plus de 100 GeV. Exemples : le neutralino ou l’axion.
> * La ***matière noire tiède*** (WDM) correspond à des particules aux vitesses intermédiaires (relativistes mais moins que la matière noire chaude). La masse de ces particules se situe entre le keV et le MeV. Exemple : le neutrino stérile.
- En règle générale, la vitesse des particules de matière noire est corrélée à leur masse. À l’exception de l’axion, plus un candidat à la matière noire est léger, plus il est « chaud ».
- Ces différents modèles de matière noire ont des impacts très différents sur la croissance des structures cosmiques.
> * Les simulations cosmologiques avec de la HDM ont tendance à former des galaxies de manière « top down », c’est-à-dire par fragmentation d’immenses nuages de matière noire (aussi grands que des gros amas de galaxies). Dans ce scénario, les galaxies se forment lentement et relativement tard dans l’histoire de l’univers. Ce modèle a été invalidé dans les années 80 (cf White, Frenk, Davis 1983) car il donnait lieu à une distribution de matière à grande échelle très différente de celle observée dans les relevés astronomiques. 
> * Les simulations avec de la CDM, au contraire, forment des structures de toutes tailles de manière hiérarchique (« bottom-up »), ie par fusions successives de petits nuages. Dans ce scénario, les galaxies se forment avant les amas de galaxies. C’est aujourd’hui le scénario qui reproduit le mieux la distribution observée de la matière à grande échelle, malgré quelques problèmes (problème de la concentration du halo, problème des satellites manquants, problème des galaxies « trop grosses pour échouer »).
> * Les simulations avec de la matière noire tiède produisent des structures qui naissent via une combinaison de processus top-down (fragmentation de grosses structures) et bottom-up (fusions de petites structures). Les structures de WDM ont des profils moins concentrés que celles générées par de la CDM, et sont entourées de moins de galaxies satellites.

*Halo de matière noire d'une galaxie similaire à la Voie Lactée simulé avec de la matière noire froide (gauche) et avec de la matière noire tiède (droite). Crédit : [Lovell et al (2012)](https://arxiv.org/abs/1104.2929). [Source](https://link.springer.com/article/10.1007/s41115-021-00013-z#Fig15)*

![cdm_wdm](https://i.imgur.com/A1ZnIlj.jpg)

*Simulation de structures cosmiques formées dans un univers avec de la matière noire chaude (gauche), tiède (milieu) et froide (droite). Crédit : Ben Moore, ITC @ University of Zurich. [Source](http://burro.case.edu/Academics/Astr222/Cosmo/Structure/darkmatter.html)*

![cdm_wdm_hdm](https://i.imgur.com/Jv4bLHd.gif)

## Indices de l'existence de la matière noire 

### Galaxies

- ***Les courbes de rotation des galaxies spirales*** : cf Rubin et Ford. 
- ***Les galaxies naines sphéroïdales***  : Les galaxies naines sphéroïdales (dSph) sont les plus petites structures stellaires dont on peut inférer qu’elles contiennent de la matière noire (les amas globulaires n’en contiennent pas). Ces galaxies contiennent très peu de gaz interstellaire et ne forment plus de nouvelles étoiles depuis des milliards d’années. Elles sont donc très peu lumineuses. On les retrouve notamment autour des grosses galaxies. Ainsi, les galaxies satellites les moins lumineuses de la Voie Lactée et d’Andromède sont des naines sphéroïdales. Ces galaxies se distinguent par un ***rapport masse/luminosité*** extrêmement élevé par rapport à celui du Soleil (10 à 100 fois plus élevé), ce qui laisse suggérer que leur masse est très largement dominée par de la matière non lumineuse. Jusqu’à récemment, cette conclusion était soutenue par les valeurs anormalement élevées de dispersion interne de leurs étoiles pour des systèmes aussi stables (gravitationnellement parlant). On pensait donc que les naines sphéroïdales étaient enchâssées dans des sous-halos de matière noire qui protégeait leur structure contre les disruptions causées par les effets de marées de leur galaxie-hôte. Cela en faisait des sondes particulièrement importantes pour déterminer la nature de la matière noire : la mesure du nombre de naines sphéroïdales et de leur profil de densité pouvait en effet permettre de déterminer si la matière noire était froide (CDM prédit des cusps) ou tiède (WDM prédit des cores). Mais une étude publiée en 2018 par des chercheur.es de l’observatoire de Paris questionne ce scénario établi. En analysant la dynamique interne de 17 galaxies naines sphéroïdales autour de la Voie Lactée, ils ont en effet démontré que l’agitation désordonnée de leurs étoiles s’expliquait intégralement par l’attraction gravitationnelle de la Voie Lactée. Il n’y a donc pas besoin d’ajouter de la matière noire dans ces systèmes pour expliquer leurs propriétés dynamiques.

### Amas de galaxies

- ***L’amas de la balle*** : En 2006, une équipe d’astronomes menée par l’astronome américain Douglas Clowe a observé le résultat d’une collision spectaculaire entre deux amas de galaxies, une structure surnommée « Bullet cluster » (1E0657-56). Les deux amas se sontr traversés il y a bien longtemps à une vitesse de plus de 10 millions de km/h (3000 km/s). Quand on observe l’amas de la balle dans le domaine optique, on ne remarque rien d’inhabituel. Les amas de galaxies sont des structures si vastes que les galaxies des deux amas n’ont pas eu l’occasion d’entrer en collision (la distance typique entre deux galaxies est d’1 Mpc). Mais quand on l’observe dans le domaine des rayons X, c’est une autre composante de l’amas que l’on trace : le gaz intergalactique surchauffé (10-100 millions de degrés) qui domine la masse baryonique de la structure. Dans ces longueurs d’onde, une autre histoire émerge. Le gaz intergalactique des deux amas a été fortement ralenti par les forces de frottement (pression dynamique) et comprimé lors de la collision intergalactique, et les ondes de choc générées ont formé deux structures distinctes qui ressemblent à une balle de fusil ayant traversé un nuage. Mais le résultat le plus surprenant est encore à venir. À l’aide de ***l’effet de lentilles gravitationnel faible***, les astronomes ont pu cartographier le potentiel gravitationnel de cette structure et estimer sa masse totale. En superposant les deux cartes (rayons X et potentiel gravitationnel), ils ont alors remarqué que la majorité de la masse de l’amas ne se trouvait pas au même endroit que la distribution de matière baryonique (tracée par son émission de rayons X). Ce décalage spatial entre distribution de matière totale et baryonique s’explique très bien si l’on considère que la masse de l’amas de la balle est dominée par des particules de matière noire qui n’entrent pas en collision entre elles. Dans ce scénario, les galaxies et la matière noire des deux amas se seraient traversées sans être ralenties (parce que ces composantes sont non collisionnelles), tandis que les composantes gazeuses se seraient entrechoquées et auraient été ralenties lors de la rencontre. Pour Clowe et al, l’amas de la balle constituerait une « preuve empirique directe de l’existence de la matière noire » qui signerait la mort de l’approche de l’hypothèse MOND. Cependant, les chercheurs de l’approche MOND n’ont pas encore dit leur dernier mot, et affirment pouvoir interpréter (du moins en partie) ce type d’observations dans leur formalisme, par exemple en introduisant des neutrinos massifs.


*Image composite de l'amas de la balle. Le gaz intergalactique chaud est en rose, et la distribution de matière noire en bleu. Crédit : X-ray: NASA/CXC/CfA/M.Markevitch, Optical and lensing map: NASA/STScI, Magellan/U.Arizona/D.Clowe, Lensing map: ESO WFI. [Source](https://www.esa.int/ESA_Multimedia/Images/2007/07/The_Bullet_Cluster2).*

![bulletcluster](https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2007/07/the_bullet_cluster2/10084622-2-eng-GB/The_Bullet_Cluster_pillars.jpg)

### Grandes structures

- ***Simulations cosmologiques*** : Les simulations N-corps réalisées dans un univers sans matière noire ne reproduisent pas la structure filamenteuse de la distribution de matière à grande échelle  (toile cosmique) observés depuis les années 80 par les relevés astronomiques. À l’inverse, les simulations avec de la matière noire reproduisent avec une précision saisissante les propriétés statistiques observées des grandes structures cosmiques. 

### Rayonnement fossile

- ***Les anisotropies du CMB*** : L’amplitude des fluctuations de température du CMB est incroyablement faible (de l’ordre de $10^{-5}$ ). Si l’intégralité de la matière de l’univers était baryonique, les fluctuations observées dans le CMB n’auraient pas eu le temps de former toutes les structures à grandes échelles que l’on observe dans l’univers. En effet, avant l’époque de la recombinaison, la matière baryonique était chargée électriquement et les forces électrostatiques empêchaient cette dernière de former des amas suffisamment denses. La matière noire étant électriquement neutre, elle ne faisait pas face à cette contrainte et pouvait donc former des proto-structures dans lesquelles la matière baryonique allait pouvoir « tomber » plus tard, après la recombinaison. Dans un univers sans matière noire, le CMB aurait dû présenter des fluctuations de températures 10 fois plus grandes que celles qu’on observe (ie de l’ordre de $10^{-4}$ ) pour permettre l’existence des grandes structures cosmiques.
- ***Les paramètres cosmologiques*** : l’analyse statistique des fluctuations du CMB permettent aussi d’obtenir une estimation des paramètres cosmologiques. On se sert pour cela du ***spectre de puissance du CMB***, une représentation graphique de l'amplitude des variations de température en fonction de leur diamètre (angulaire) apparent sur la sphère céleste. La position des différents pics du spectre de puissance (en particulier du premier) est compatible avec un univers géométriquement plat (ie un univers où les rayons de lumière parallèles entre eux sont toujours parallèles au fil de leur trajet). La hauteur des autres pics du spectre de puissance nous renseigne quant à elle sur la densité de matière baryonique (2e pic) et sur la densité de matière totale (tous les autres pics). Quand on estime ces deux quantités dans le cadre du modèle ΛCDM, on se rend compte qu’elles sont très différentes, ce qui ce qui est un indice solide du fait que le contenu matériel de l’univers est dominé par la matière noire. Le spectre de puissance issus des données du satellite Planck (2018) est parfaitement interprété dans le cadre de ΛCDM dans lequel la matière baryonique représente environ 5 % de la densité énergétique totale de l’univers et la matière noire 26,8 %.

*Spectre de puissance du CMB. Crédit : NASA / WMAP science team. [Source](https://wmap.gsfc.nasa.gov/mission/sgoals_parameters_spect.html)*

![CMBanisotropiesWMAP](https://wmap.gsfc.nasa.gov/media/070950/070950b.jpg)

### Nucléosynthèse primordiale

- La théorie de la nucléosynthèse primordiale fournit une limite haute à la densité de matière baryonique dans l’univers. En effet, les abondances en deutérium et en hélium prédites par la théorie ne sont compatibles avec les observations que si la densité de matière baryonique  cosmique ne représente que 5 % de la ***densité critique*** (ie la densité de matière et d’énergie moyenne nécessaire pour que l’expansion de l’univers soit stoppée par la gravitation dans un futur infini). Quand on combine ces prédictions avec les données du CMB et de la dynamique des amas de galaxies, on arrive à la conclusion qu’il doit exister au moins 5 fois plus de matière dans l’univers que la quantité maximale de matière baryonique permise par la nucléosynthèse. 

## Les principaux candidats à la matière noire

- ***Les axions***
> L’existence de ces particules hypothétiques très peu massive (entre 1 et 1000 μeV) a été postulée en 1977 par Roberto Peccei et Helen Quinn comme solution d’une énigme du modèle standard : le ***problème CP fort***. Pour le comprendre, il faut revenir sur le concept de ***symétries de jauge***, qui est fondamental en physique des particules. Une symétrie de jauge, c’est une transformation qui laisse les propriétés d’un système physique inchangées, invariantes. Par exemple, si on tourne autour du centre d’une boule de billard, l’apparence de la boule reste inchangée. L’ensemble des rotations 3D possibles constituent donc les symétries de la boule. En physique des particules, il existe 3 transformations fondamentales : la ***symétrie C*** (conjugaison de charge), qui change le signe de la charge électrique et transforme une particule en son antiparticule, la ***symétrie P*** (transformation de parité), qui inverse toutes les coordonnées spatiales d’une particule, et la ***symétrie T*** (renversement du temps), qui inverse la flèche du temps. On peut combiner ces opérations pour créer d’autres types de symétries, comme la symétrie CP ou la symétrie CPT. Ainsi, en vertu de la symétrie CP, les particules et les antiparticules devraient obéir aux mêmes lois physiques. Autrement dit, matière et antimatière auraient dû être produits en quantités égales dans l’univers primordial. Pourtant, l’univers qu’on observe est indéniablement dominé par la matière, et l’antimatière est quasi-inexistante à l’échelle cosmique.  Cette victoire de la matière peut être expliquée en partie par la ***brisure de la symétrie CP***. Autrement dit, il y aurait des différences entre les lois qui régissent l’évolution de la matière et celles qui régissent l’antimatière. En 1964, une équipe de physiciens du laboratoire national de Brookhaven a mis en évidence expérimentalement que la symétrie CP pouvait être effectivement brisée dans le phénomène de désintégration du kaon, qui met en jeu l’interaction faible. Cette particule se désintègre en effet préférentiellement en positron plutôt qu’en électron. L’interaction faible brise donc la symétrie CP. Mais qu’en est-il de l’interaction forte ? Selon la ***chromodynamique quantique*** (la théorie qui décrit les interactions entre les quarks et les gluons qui composent les protons et les neutrons), celle-ci devrait aussi briser la symétrie CP. Or, toutes nos expériences nous montrent qu’elle semble malgré tout être préservée. Le problème CP fort consiste à se demander pourquoi les lois de la chromodynamique quantique préservent la symétrie CP. Pour résoudre ce problème, Peccei et Quinn ont postulé l’existence d’un nouveau champ quantique interagissant avec les gluons. Et les particules qui composent ce champ sont les fameux axions. Pourquoi axion ? En référence aux axes de symmétrie, mais aussi, de manière humoristique, à une marque de détergent. Frank Wilczek, qui a eu l’honneur de nommer cette particule, trouvait en effet que celle-ci permettait de « nettoyer » le problème. De nos jours, les axions font partie des candidats favoris des physicien.nes à la matière noire. Pour les détecter, ils se servent d’une étrange propriété de l’axion : lorsqu’il est  soumis à un fort champ magnétique, il se désintègre en paires de photons. On peut alors utiliser un instrument appelé ***haloscope*** pour détecter des axions du halo de matière noire galactique. Celui-ci est composé d’un électroaimant supraconducteur et d’une cavité résonnante qui amplifie le signal photonique (qui arrive dans le domaine des micro-ondes). Le plus célèbre de ces haloscopes est une expérience nommée ADMX (Axion Dark Matter eXperiment), construite à l’université de Washington. Cet instrument a permis de mieux contraindre la plage de masses de l’axion. Et en 2020, l’expérience XENON1T, située dans le laboratoire souterrain de San Grasso en Italie, aurait découvert les premiers indices sérieux de l’existence d’axions en provenance du Soleil. La découverte reste cependant à confirmer.

- ***Les WIMPs***
> Les WIMPs (accronyme de “Weakly Interacting Massive Particles”) désignent une classe de particules hypothétiques qui n’interagiraient avec la matière ordinaire que via la force nucléaire faible. Ils ont constitué le paradigme dominant dans la quête de la matière noire depuis les années 80, grâce à de solides fondations théoriques et des prédictions testables expérimentalement. Si elles existent, les WIMPs devraient être entre 1 et 1000 fois plus massifs que les protons (1-1000 GeV). Parmi les WIMPs, le candidat le plus étudié est (de loin) le ***neutralino***. L'existence de cette particule est prédite par la théorie de la ***supersymétrie***, une extension du modèle standard de la physique des particules. Celle-ci fait l’hypothèse qu’il existerait un lien fondamental (une symétrie) entre les deux grandes catégories de particules : les bosons (particules dont le spin est entier ou nul) et les fermions (particules dont le spin est demi-entier ou nul). Dans cette théorie, toutes les particules du modèle standard possèdent un « partenaire supersymétrique » (ou ***superpartenaire***) plus massif dont le spin diffère du sien de moitié. Ainsi, des bosons auraient des superpartenaires fermioniques et inversement. Les superpartenaires fermioniques des bosons ont le même nom que ces derniers, mais avec le suffixe -ino (ex : le superpartenaire du photon est le photino, et celui du Higgs est le higgsino), tandis que les superpartenaires bosoniques des fermions ont le même nom que ces derniers avec le préfixe s- (ex : les superpartenaires des quarks sont les squarks, et ceux des électrons sont les sélectrons). Dans ce cadre, le neutralino est une combinaison de 3 superpartenaires : le photino, le higgsino et le Z-ino. Selon l'extension supersymétrique minimale du modèle standard de la physique des particules, il existerait 4 neutralinos possibles, et le plus léger d’entre eux est souvent considéré comme l’un des candidats à la matière noire le plus prometteur. Pourquoi ? Les neutralinos étant leur propre antiparticules, ils sont sensés s’annihiler entre eux dans les premiers instants du cosmos. Mais à mesure que l’univers s’étend, le  taux d’anihilation devient négligeable et l’abondance des neutralinos est « gelée » à une densité relique que l’on peut calculer. Pour un neutralino de l’ordre de 100 fois la masse du proton, cette densité relique correspond à la densité de la matière noire mesurée à l’échelle cosmique ! On appelle cette coïncidence intrigante le ***miracle du WIMP***, et c’est elle qui explique en grande partie l’engouement des scientifiques sur ce candidat. Une manière de détecter des WIMPs est d’observer les flux de rayons gamma produits dans les halos de matière noire suffisamment denses lorsque des paires de ces particules fantômatiques s’annihilent entre elles. Une autre technique consiste à faire collisionner des particules à très grande vitesse (au LHC par exemple), en espérant que les débris de la collision révèlent des signes de WIMPs. Une dernière technique consiste à construire de grandes cuves souterraines (ie à l’abri des rayons cosmiques) remplies d’atomes de xénon, comme le détecteur LUX (Large Underground Xenon experiment) situé aux États-Unis, et d’attendre qu’une particule de matière noire interagisse avec les atomes de la cuve en produisant des électrons et des photons. Mais après des décennies de recherche et des expériences de plus en plus précises, aucun signe de neutralinos ou plus généralement de WIMPs n’a été détecté pour le moment. Et si leur existence n’est pas encore exclue, la communauté scientifique commence à privilégier d’autres candidats.

- ***Les WIMPZILLAS***
> Contrairement aux WIMPs, qui sont des particules très légères, les WIMPZILLAS sont des particules hypothétiques ultra-lourdes, dont la masse pourrait être comprise entre $10^9$ et $10^{16}$ GeV, et qui interagiraient très faiblement avec la matière. Elles ont été proposées à la fin des années 90 par Edward Kolb, Daniel Chung et Antonio Riotto. Ces particules auraient pu être créées dans les conditions de l’univers primordial, pendant la période de réchauffement qui fait suite à l’inflation. Si ces WIMPZILLAS existent, elles pourraient potentiellement résoudre un autre problème de l’astrophysique : la nature des rayons cosmiques d’ultra-haute énergie. En effet, les WIMPZILLAS pourraient se désintégrer en particules de hautes énergies (essentiellement des rayons gamma dont l’énergie est supérieure à $10^{9}$ GeV) qui pourraient voyager jusqu’à la Terre. Ces particules pourraient être détectées par les futurs observatoires Pierre Augier (en Argentine) et l’Extreme Universe Space Observatory (à bord de l’ISS), en ciblant le centre de la Galaxie. Mais les rayons cosmiques d’ultra-haute énergie sont des événements ultra-rares, et établir des statistiques prend du temps. En attendant, il est difficile de  distinguer les rayons cosmiques issus de la désintégration des WIMPZILLAS des rayons cosmiques issus d’autres processus astrophysiques.

- ***Les MACHOs***
> Les MACHOs (acronyme de MAssive Compact Halo Objects, nommé ainsi en opposition aux WIMPs par l’astronome Kim Griest) sont des astres constitués de matière ordinaire (baryonique) qui seraient si peu lumineux qu’ils n’auraient pas été détectés par les relevés astronomiques jusqu’à présent. Ces astres incluent des étoiles peu massives (naines rouges), des cadavres stellaires (naines blanches, étoiles à neutrons, trous noirs), des planètes errantes et des naines brunes. Les MACHOs sont des candidats intrigants à la matière noire, car ils ne font pas intervenir de matière exotique ou de nouvelle physique. Comme les télescopes ne sont pas assez sensibles pour capter leur lumière, une manière de les recenser fait intervenir ***l’effet de microlentille gravitationnelle*** : lorsqu’un MACHO passe devant une étoile lointaine en arrière plan, il courbe l’espace autour de lui et altère le trajet des photons provenant de l’étoile. Cela se traduit par une augmentation passagère de la luminosité apparente de l’étoile au moment du passage du MACHO. De tels alignements sont très rares (ils concernent environ une étoile sur un million), mais en observant de grandes quantités d’étoiles (des millions) sur des temps suffisamment longs (des années), on peut assigner une borne supérieure au nombre de MACHOs (ainsi que leur masse) dans une galaxie donnée. C’est notamment le travail qu’ont réalisé les collaborations MACHO, EROS (Expérience pour la Recherche d'Objets Sombres) et OGLE (Optical Gravitational Lensing Experiment), en observant les étoiles des nuages de Magellan pendant plusieurs années. Ces analyses ont montré que les MACHOs ne pouvaient pas représenter plus de 8 % de la masse « noire » du halo galactique. D’autres études indépendantes issues de l’analyse du fond diffus cosmologique et de l’abondance des éléments légers dans l’univers ont montré que moins de 20 % de la matière de l’univers était d’origine baryonique. Il y a donc un consensus selon lequel les MACHOs ne constituent qu’une petite fraction de la matière noire à l’échelle du cosmos. De nos jours, les seuls MACHOs qui résistent encore aux contraintes fournies par le CMB et la nucléosynthèse primordiale sont les ***trous noirs primordiaux***.

- ***Les trous noirs primordiaux***
> Les observations actuelles ont éliminé les trous noirs stellaires (issus de la mort d’étoiles massives) comme candidats à la matière noire. Il n’y en a juste pas assez pour expliquer nos observations. Mais les trous noirs stellaires ne sont pas les seuls trous noirs possibles. En 1971, Stephen Hawking a proposé l’hypothèse que la matière noire pourrait être constituée de trous noirs qui se seraient formés dans les conditions ardentes de l’univers primordial, pendant les quelques secondes qui ont suivi sa période inflationnaire (lorsque la température de l’univers est passée sous la barre de 10 milliards de de degrés), à partir de surdensités de matières qui se seraient effondrées sur elles-mêmes sous leur propre poids. Les trous noirs primordiaux représentent un candidat attrayant parce qu’ils ne requièrent pas de nouveau type de matière exotique. La masse de ces trous noirs primordiaux pourrait s’étendre de $10^{-10}$ à $10^{7}$ masses solaires, c'est-à-dire de la masse d’un astéroïde (et plus petits qu’un grain de sable) à celle d’un trou noir supermassif. Ceux plus légers que cette limite basse auraient fini par s’évaporer complètement avant nos jours. La détection des ondes gravitationnelles émises par la fusion de paires de trous noirs en 2016 a remis sur le devant de la scène l’hypothèse des trous noirs primordiaux comme candidats à la matière noire (les trous noirs détectés étaient en effet légèrement plus massifs que ce à quoi on s’attendrait pour des trous noirs stellaires). Il est aussi possible que les trous noirs primordiaux aient constitué les graines des trous noirs supermassifs que l’on retrouve aujourd’hui au centre de toutes les grosses galaxies.

- ***Les neutrinos stériles***
> Les neutrinos stériles sont un (ou plusieurs) type(s) hypothétique(s) de ***neutrinos*** très massifs, électriquement neutres, n’interagissant avec la matière que par le biais de leur gravité (contrairement aux 3 types -saveurs- de neutrinos du modèle standard de la physique des particules, qui interagissent aussi avec la matière par le biais de la force nucléaire faible), et stables sur les échelles de temps cosmologiques. Ils ont été proposés en 1977 par Benjamin Lee et Steven Weinberg. Cette hypothèse a connu son heure de gloire au milieu des années 90, lorsque l’expérience LSND (Liquid Scintillator Neutrino Detector) située au Nouveau Mexique avait montré qu’il existait un léger excès d'***(anti-)neutrinos électroniques*** par rapport aux deux autres saveurs (***muonique*** et ***tauique***). Ce résultat pouvait s’expliquer si les (anti-)neutrinos pouvaient se transformer temporairement en une quatrième saveur sur leur trajet. Si leur masse est supérieure au keV, les neutrinos stériles pourraient rendre compte de l’intégralité de la matière noire dans l’univers. La désintégration des neutrinos stériles produirait des photons qui seraient détectables sous la forme d’une raie spectrale dans le domaine des rayons X. En 2014, une telle raie d’émission à 3,55 keV a été détectée dans des amas de galaxies observées par les télescopes spatiaux XMM-Newton et Chandra. Une telle détection est compatible avec la désintégration d’un neutrino stérile d’une masse de 7 keV. Mais ce résultat fait encore débat dans la communauté scientifique. 

*Candidats à la matière noire. Crédit : Samuel Velasco/Quanta Magazine [Source](https://www.quantamagazine.org/physicists-are-expanding-the-search-for-dark-matter-20201123/)*

![DMparticles](https://d2r55xnwy6nx47.cloudfront.net/uploads/2020/11/Dark_Matter_graphic_2880x1620_Lede_final.svg)

*Liste plus exhaustive de candidats. Crédit : Alves Batista et al (2021). [Source](https://arxiv.org/abs/2110.10074)*

![DMcandidates](https://i.imgur.com/VgeZTI3.png)

## La piste de la gravité modifiée

- En 1983, le physicien israélien Moti Milgrom propose une alternative au postulat de la matière noire pour expliquer les courbes de rotation plates des galaxies. Ce modèle alternatif, nommé ***MOND*** (MOdified Newtonian Dynamics) est dit de « gravité modifiée », car il est basé sur une modification (ad-hoc) de la lois de la gravitation Newtonienne.
- Selon le modèle de Milgrom, il existerait une échelle d’accélération critique universelle ( $a_0$  ~ $10^{-10}$ m/s², soit 100 milliards de fois plus faible que le champ de gravité terrestre) en-deçà de laquelle la force de gravitation est plus faible et ne décroît plus avec la distance en 1/R² mais plus doucement, en 1/R. Ces accélérations « faibles » seraient notamment ressenties par les étoiles en périphérie des galaxies. Dans ce cadre, $a_0$ serait une nouvelle constante fondamentale de la physique.
> * Cette généralisation des lois de Newton en « champ faible » serait analogue à la relativité restreinte comme généralisation de la théorie de Newton pour des vitesses proches de celle de la lumière.
> * Ce régime d’accélération spécial ne se rencontrerait pas sur Terre, ni même dans le système solaire, parce que l’énorme champ de gravité du Soleil domine tous les processus dynamiques. Il est donc impossible de tester les prédictions de MOND en laboratoire sur Terre. 
- Cette modification de la loi de Newton permet de reproduire systématiquement et de manière très fidèle les courbes de rotation plate des galaxies (des naines aux géantes) avec un seul paramètre libre : $a_0$. Et ce, sans avoir recours à des quantités astronomiques de matière invisible.
- Le formalisme de Milgrom permet notamment d’expliquer naturellement des relations empiriques entre différentes propriétés des galaxies, comme la ***loi de Tully-Fisher*** pour les galaxies spirales (qui relie la luminosité intrinsèque d’une galaxie aux vitesses de rotation des étoiles autour de son centre) ou encore la ***relation de Faber-Jackson*** pour les galaxies elliptiques (qui relie la luminosité intrinsèque d’une galaxie à la dispersion de vitesses de ses étoiles centrales). Ces relations ne sont pas directement expliquées dans le modèle standard de la cosmologie
- Des simulations informatiques réalisées dans le cadre du formalisme de MOND permettent de reproduire avec succès de nombreuses caractéristiques observées des galaxies : fréquence des barres d’étoiles, motif en spirales, forme des galaxies en fusion etc.
- L’une des grandes faiblesses du modèle MOND est qu’il n’est pas encore associé à un cadre théorique déjà établi, comme la théorie de la relativité générale. Il faudrait donc modifier la relativité générale de telle sorte à reproduire les lois de MOND dans le régime non-relativiste, ce qui n’est pas une mince affaire, à cause de la grande cohérence mathématique de la relativité générale.
> * En 2004, Jacob Bekenstein a proposé pour la première fois une version relativiste de MOND compatible avec les principes de la relativité générale. Sa théorie nommée TeVeS (Tensor-Vector-Scalar gravity) introduit 3 champs différents associés à la gravitation (un champ tensoriel, un champ vectoriel et un champ scalaire), au lieu d’un seul champ (tensoriel) en relativité générale. Cette théorie obéit aux lois de conservation, et permet notamment de prédire les effets de lentilles gravitationnelles (faibles et forts). Mais TeVeS ne permet pas de reproduire les caractéristiques du spectre de puissance du CMB. Ce modèle a été définitivement éliminé à la suite de la première détection des ondes gravitationnelles issue de la fusion de 2 étoiles à neutrons, car il prédisait un retard d’arrivée des ondes lumineuses par rapport aux ondes gravitationnelles, et ce retard n’a pas été observé.
> * En 2021, deux chercheurs de l’Académie tchèque des sciences, Constantinos Skordis et Tom Złośnik, ont proposé un modèle dérivé de TeVeS nommé RMOND (Relativistic MOND) qui permet à la fois de reproduire la dynamique des galaxies et les propriétés du fond diffus cosmologique. C’est une avancée considérable, parce que jusqu’à présent, les fluctuations du CMB étaient uniquement reproduites dans le cadre du modèle ΛCDM. Reste à confronter ce modèle aux échelles des amas de galaxies.
- Pour le moment, la validité de MOND trouve ses limites à l’échelle des amas de galaxies. En effet, dans le cadre de ce modèle, il manque encore de la masse « invisible » pour expliquer les propriétés observées des amas de galaxies. Cette masse invisible pourrait être composée de neutrinos ou de baryons « noirs ». 
- Il serait en théorie possible de tester les prédictions du modèle MOND localement en étudiant la dynamique des comètes du nuage d’Oort (à des distances de quelques milliers à quelques dizaines de milliers d’unités astronomiques du Soleil). En effet, dans cette région, l’accélération centripète est comparable à $a_0$. Si l'on observait des comètes avec une vitesse orbitale plus élevée que celle prédite par les lois de Newton, cela constituerait un indice en faveur de MOND. MOND prédit aussi un nuage d’Oort à la structure plus compacte que celle prédite par la gravité Newtonienne. 

# Energie sombre

*Sources*

- [Dark Energy: A Short Review](https://arxiv.org/abs/1401.0046) - Mortonson et al (2013)
- [Dark Energy Versus Modified Gravity](https://www.annualreviews.org/doi/abs/10.1146/annurev-nucl-102115-044553) - Joyce et al (2016)
- [Dark energy: A brief review](https://link.springer.com/article/10.1007/s11467-013-0300-5) - Li et al (2013)
- [Changement de rythme dans l’expansion de l’Univers : Un premier rôle pour le côté obscur](https://www.refletsdelaphysique.fr/articles/refdp/pdf/2016/04/refdp201651p12.pdf) - Palanque Delabrouille (2016)
- [L'histoire de l'expansion de l'Univers dévoilée](https://www.refletsdelaphysique.fr/articles/refdp/pdf/2022/01/refdp202271p22.pdf) - Burtin (2022)
- [Avancées de la recherche Cisaillement gravitationnel et sondage de l’Univers](https://www.refletsdelaphysique.fr/articles/refdp/pdf/2006/01/refdp20061p5.pdf) - Mellier (2006)
- [La constante cosmologique : la plus grande erreur d’Einstein](https://books.openedition.org/cdf/9443?lang=fr) - Combes
- [Listening for the Size of the Universe](https://astro.ucla.edu/~wright/BAO-cosmology.html) - Edward Wright (2014)
- [Astronomy Jargon 101: Baryon Acoustic Oscillations](https://www.universetoday.com/153273/astronomy-jargon-101-baryon-acoustic-oscillations/) - Paul Sutter
- [BOSS Measures the Universe to One-Percent Accuracy](https://newscenter.lbl.gov/2014/01/08/boss-one-percent/) - Berkeley Lab (2014)
- [DESI lance un programme de 5 ans pour mieux comprendre l’univers](https://insidetheperimeter.ca/fr/desi-launches-five-year-quest-to-understand-the-universe/) - PI (2021)
- [La distribution des galaxies, une fenêtre sur l'Univers primordial](https://www.pourlascience.fr/sd/cosmologie/la-distribution-des-galaxies-une-fenetre-sur-l-univers-primordial-11827.php) - Pour la Science (2014)
- [What are baryonic acoustic oscillations?](https://sci.esa.int/web/euclid/-/what-are-baryonic-acoustic-oscillations-) - ESA
- [What the hell are Baryon Acoustic Oscillations?](https://medium.com/starts-with-a-bang/what-the-hell-are-baryon-acoustic-oscillations-cfee6d726538) - Ethan Siegel
- [Dark Energy Spectroscopic Instrument (DESI) Creates Largest 3-D Map of the Cosmos](https://www.ifae.es/news/2022/01/13/dark-energy-spectroscopic-instrument-desi-creates-largest-3-d-map-of-the-cosmos/) - IFAE (2022)
- [Listening to the sound of the universe](https://web.physics.ucsb.edu/~jatila/CMB-sounds/CMB/) - Jatila van der Veen
- [Dark matter in galaxy clusters](https://www.slac.stanford.edu/econf/C070730/talks/allen_080607.pdf) - Steve Allen
- [PROBES OF COSMIC ACCELERATION](https://ned.ipac.caltech.edu/level5/March08/Frieman/Frieman7.html) - Frieman (2008)
- [Probing Dark Energy with Galaxy Clusters](https://www.nasa.gov/mission_pages/chandra/probing-dark-energy-with-galaxy-clusters.html) - NASA (2016)
- [Probing dark energy via galaxy cluster outskirts](https://academic.oup.com/mnras/article/457/3/3266/2588928) - Morandi et Sun (2016)
- [La masse des amas déduite des rayons X](https://media4.obspm.fr/public/ressources_lu/pages_structures/massesx.html) - Observatoire de Paris
- [LES AMAS DE GALAXIES EN LUMIERE VISIBLE ET EN RAYONS X](http://www.astrosurf.com/thizy/rochelle2009/doc/2009oct27E%20Amas%20de%20Galaxies%20(Florence%20Durret).pdf) - Florence Durret (2009)
- [Studies of dark energy with x-ray observatories](https://www.pnas.org/doi/10.1073/pnas.0914905107) - Vikhlinin (2010)
- [Dark energy two decades after: Observables, probes, consistency tests](https://arxiv.org/abs/1709.01091) - Huterer et Chafer (2017)
- [Découverte de l'accélération de l'expansion de l'Univers](https://cosmology.education/decouverte-acceleration-expansion/distance-luminosite/#!) - Lucas Gautheron
- [Cosmology with cosmic shear observations: a review]( https://iopscience.iop.org/article/10.1088/0034-4885/78/8/086901) – Kilbinger (2015)
[Cisaillement cosmique](https://www.college-de-france.fr/agenda/seminaire/amas-de-galaxies-et-grandes-structures-de-univers/cisaillement-cosmique) – Collège de France
- [How Does DARK ENERGY Change the CMB Temperature? | The Integrated Sachs-Wolfe Effect](https://youtu.be/F3XOz1dR9YA) - Chris Pattison
- [Faster walk on the dark side](https://imagine.gsfc.nasa.gov/educators/programs/cosmictimes/educators/guide/2006/faster.html) - NASA
- [L’effet Sachs-Wolfe intégré ou la traversée des grandes structures](http://public.planck.fr/outils/astrophysique/effet-sachs-wolfe-integre-isw) - Planck HFI
- [RayGal : une nouvelle simulation du cosmos pour percer les secrets de l'énergie noire](https://www.futura-sciences.com/sciences/actualites/cosmologie-raygal-nouvelle-simulation-cosmos-percer-secrets-energie-noire-94917/) - Futura Sciences (2022)
- [Comment Estimer la masse des amas de galaxies?](http://physique.unice.fr/sem6/2017-2018/PagesWeb/PT/Galaxie/les_amas/comment.html) - Observatoire de la côte d'Azur
- [Gravitational Lensing in the Canary Islands](https://astrobites.org/2012/11/25/gravitational-lensing-in-the-canary-islands/) - Astrobites
- [Cosmological constant](http://www.scholarpedia.org/article/Cosmological_constant) - Scholarpedia
- [Ask Ethan: Is Einstein’s Cosmological Constant The Same As Dark Energy?](https://www.forbes.com/sites/startswithabang/2020/12/25/ask-ethan-is-einsteins-cosmological-constant-the-same-as-dark-energy/?sh=33a76ee84636) - Ethan Siegel
- [La plus grosse erreur de toute l’histoire de la physique](https://scienceetonnante.com/2012/05/14/la-plus-grosse-erreur-de-toute-lhistoire-de-la-physique/) - Science Etonnante

---

-	En 1917, alors que les observations astronomiques sont principalement limitées aux étoiles de notre Galaxie, Albert Einstein tente d’appliquer sa toute jeune théorie de la relativité générale à un modèle d’univers qu’il juge statique. Pour contrer les effets de la gravitation, il introduit un nouveau terme dans ses équations : la ***constante cosmologique*** (symbolisée par la lettre grecque Λ). 
-	En 1922, le mathématicien russe Alexandre Friedmann démontre que la solution d’univers statique d’Einstein est aussi stable qu’un stylo posé sur sa pointe, et propose de le remplacer par un modèle d’univers en expansion. Le modèle de Friedman sera corroboré par les observations de la fuite des galaxies par Edwin Hubble à la fin des années 20. Il est désormais à la base du modèle cosmologique standard.
> À partir des années 30, Einstein va rapidement renoncer à son modèle d’univers statique. Il confiera plus tard à son collègue George Gamow que l’introduction de la constante cosmologique dans ses équations était « la plus grosse erreur de sa vie » (biggest blunder).
- La constante cosmologique va gagner une seconde vie à la fin des années 90. À cette époque, la majorité des cosmologistes sont persuadés que l’expansion de l’univers est en train de ralentir. Mais en 1998, deux équipes indépendantes d’astronomes des collaborations High-Z supernova Team et Supernova Cosmology Project découvrent que des supernovae thermonucléaires lointaines (0<z<1) sont moins brillantes que ce qu’elles devraient être dans un univers en cours de décélération (ce à quoi on s'attendrait dans un univers constitué uniquement de matière et de rayonnement). 
- La manière la plus simple d’interpréter ces observations est de considérer que l’univers se trouve dans une période d’expansion accélérée depuis environ 6 milliards d’années, qui fait suite à une période de décélération (justifiée par des supernovae thermonucléaires à z>1 plus brillantes que prévues cette fois).
- Cette découverte a valu le prix Nobel de physique en 2011 à trois chercheurs associés aux deux collaborations : Saul Perlmutter, Brian Schmidt et Adam Riess.
- De nos jours, de nombreuses observations indépendantes vont dans le sens d’une période d’expansion cosmique accélérée dans l’histoire récente de l’univers.
- Selon les données du télescope spatial Planck publiées en 2013, l’énergie sombre représenterait 68,3% de la densité énergétique totale de l’univers.
- On ne connaît pas la nature du phénomène qui cause cette expansion accélérée. 

## Comment modéliser la cause de l’expansion accélérée

- Une manière d’interpréter les observations dans le cadre du modèle cosmologique standard est d’invoquer l’existence d’une mystérieuse ***énergie sombre*** qui remplirait uniformément l’univers et qui serait dotée d’une « pression négative » qui la ferait se comporter comme une force répulsive.
> On modélise l’énergie sombre comme un fluide parfait caractérisé par son équation d’état, qui relie sa pression à sa densité d’énergie : P = wρ. (w est un nombre sans dimension)
- La modélisation la plus simple de cette hypothétique énergie sombre fait intervenir la fameuse constante cosmologique, qui pourrait être assimilée de façon élégante à une sorte d’énergie du vide dont la densité reste constante à mesure que l’univers s’étend.
> Si l’énergie sombre est une constante cosmologique, w = -1.
- Dans le langage de la théorie quantique des champs, il est possible d’assimiler cette énergie noire à l’***énergie du vide*** (vacuum energy), qui émerge à cause du ***principe d’incertitude d’Heisenberg***.
> La physique quantique ne permet pas l’existence d’états dans le vide où l’énergie est strictement nulle. L’énergie du vide est l’énergie de l’état fondamental des champs quantiques dans un espace vide de matière. Cet état est constamment fluctuant, et permet l’émergence et l’annihilation permanente de paires de particules virtuelles dans le vide quantique.
- Le problème, c’est que lorsqu’on mesure la densité de l’énergie sombre aux échelles cosmologiques, et qu’on calcule la densité de l’énergie du vide à l’aide des équations de la théorie quantique des champs, les deux valeurs sont incroyablement différentes : la densité du vide quantique excède celle de l’énergie sombre d’un facteur 10 puissance 120 ! Ce problème n’est pas encore résolu à ce jour.
> Certains appellent ce résultat « la plus grosse erreur de toute l’histoire de la physique ».
- La constante cosmologique n’est qu’une des modélisations possibles de l’énergie sombre. De nombreuses théories de gravitation quantique produisent ainsi des candidats à l’énergie sombre qui possèdent d’autres propriétés (par exemple différentes valeurs de w).
- Une autre forme hypothétique que pourrait prendre l’énergie sombre est la ***quintessence***, un champ scalaire dont la contribution varierait dans le temps, contrairement à une constante cosmologique (ie, son équation d’état évolue au fil du temps).
> Une forme particulière de quintessence est ***l’énergie fantôme***, proposé par le physicien Robert Caldwell et dont le paramètre w < -1. 
- Toutes ces propositions d’énergie sombre partent du principe que la relativité générale est la bonne théorie pour décrire l’évolution à grande échelle du cosmos. Mais il existe aussi l’option que la relativité générale doit être révisée aux échelles les plus vastes. C’est l’approche dite de ***gravité modifiée*** (ou de ***gravité sombre*** - dark gravity).
- Les modèles de gravité modifiée produisent des scénarios d’évolution des grandes structures cosmiques différents de ceux du modèle standard de la cosmologie.
- Malheureusement, il n’existe à ce jour aucun modèle de gravité modifiée qui permette d’expliquer l’accélération de l’expansion cosmique observée.

*Evolution de l'expansion cosmique dans le scénario où l'énergie sombre est une constante cosmologique (Big Freeze). [Source](https://phys.libretexts.org/Bookshelves/Astronomy__Cosmology/Big_Ideas_in_Cosmology_(Coble_et_al.)/17%3A_Dark_Energy_and_the_Fate_of_the_Universe/17.04%3A_Cosmic_Concordance_and_Cosmological_Parameters)*

![bigfreeze](https://files.mtstatic.com/site_4539/22172/0?Expires=1670329144&Signature=fQ9JJW4nsEkrF4Fve7nb~Zs5mEqLneKvkcEUfrGzn3rCgIh3RSqPvHS2cj3dqtq7VNe2bi3YByGcKNSZIVXi77diOvXv~8QhRJ96dyuC0CvO3njbvP-fPokd5ilLmylFHIr~gTd1vUYRh0L8ESPpeZwo4T3ZBTxKWnJAKipViEw_&Key-Pair-Id=APKAJ5Y6AV4GI7A555NA)

## Comment sonder les propriétés de l'énergie noire à l'aide de nos observations

- Il y a essentiellement deux classes de méthodes pour étudier les signatures observables de l'énergie sombre : les méthodes dites "géométriques", qui se concentrent sur le taux d'expansion de l'univers (à l'aide de règles ou de chandelles standards), et les méthodes se focalisant sur la croissance des grandes structures cosmiques.

### Les anisotropies du CMB

-	Le CMB a été émis à une époque où la contribution de l’énergie sombre dans l’évolution cosmique était négligeable.
-	Par contre, l’analyse statistique des anisotropies de température du CMB (à travers son spectre de puissance) permet de contraindre les paramètres du modèle standard de la cosmologie avec une précision inférieure au pourcent. En effet, l’énergie sombre affecte la distance (comobile) qui nous sépare de l’époque de la recombinaison, et donc les échelles angulaires auxquelles les fluctuations de températures du CMB sont observées. Ces échelles se traduisent dans la position horizontale des pics dans le spectre de puissance.
- L'énergie sombre laisse une autre trace, plus subtile, dans les anisotropies de température du CMB, générée cette fois-ci au cours du voyage des photons du CMB depuis leur source jusqu'à nous.
> * Les grandes structures cosmiques comme les amas de galaxies courbent l'espace-temps autour d'eux et génèrent des puits de potentiel gravitationnel. Lorsqu'un photon du CMB traverse un amas de galaxies, il tombe dans le puits de potentiel. Et à la manière d'une bille qui est accélérée lorsqu'elle roule dans une cuvette, le photon gagne de l'énergie. Autrement dit, il bleuit (sa longueur d'onde est décalée vers le bleu). Et parce qu'émerger du puits gravitationnel est coûteux en énergie, le photon perd de l'énergie lorsqu'il quitte l'amas de galaxies. Autrement dit, il rougit. En règle générale, comme l’énergie se conserve, les deux effets se compensent, et le photon à la sortie de l’amas possède la même longueur d’onde qu’avant son arrivée. Ce phénomène a été théorisé en 1967 par les astronomes Rainer Kurt Sachs et Arthur Michael Wolfe et porte aujourd'hui le nom d'***effet Sachs-Wolfe***. Dans un univers dominé par l'énergie sombre (z < 1), la situation est légèrement différente. Lorsque le photon pénètre dans l’amas de galaxies, il rougit comme avant. Cependant, la structure est si vaste (il faut des centaines de millions d’années à un photon pour la traverser) qu’elle subit les effets de l’accélération de l’expansion cosmique. Ces effets se traduisent par une inflation de l’amas de galaxies, et donc par un « aplatissement » du puits de potentiel gravitationnel. Autrement dit, la forme de la cuvette évolue dans le temps. Elle est moins profonde qu’avant. Dans ce cas de figure, le photon bleui qui émerge de l’amas est moins rougi que dans la situation précédente. Lorsqu’il arrive dans nos détecteurs, le photon sera donc légèrement décalé vers le bleu par rapport à sa longueur d’onde de départ. On appelle ce phénomène l’***effet Sachs-Wolfe intégré*** (ou effet ISW, pour Integrated Sachs-Wolfe).
> * À noter que la traversée d’un vide cosmique produit aussi un effet Sachs-Wolfe intégré, mais qu’il fonctionne dans l’autre sens. Le photon rougit en arrivant dans le vide, et bleuit à sa sortie.
- Lorsqu’on cartographie la distribution de la matière dans une région du ciel et qu’on corrèle cette carte avec la carte des anisotropies du CMB dans la même direction du ciel (on fait ce qu’on appelle une ***corrélation croisée***), on peut donc en tirer des indices sur la nature et les propriétés de l’énergie sombre (à travers son effet sur la croissance des grands structures).

*Illustration de l'effet Sachs-Wolfe intégré. Crédit : NASA's Cosmic Times [Source](https://imagine.gsfc.nasa.gov/educators/programs/cosmictimes/educators/guide/2006/faster.html)*

![ISW](https://imagine.gsfc.nasa.gov/educators/programs/cosmictimes/educators/guide/2006/images/sachs_wolfe_illustration.gif)

### Les supernovae thermonucléaires

- Les ***supernovae thermonucléaires*** (aussi appelées ***supernovae de type Ia***, ou SNIa) sont des phénomènes résultant de l’explosion de naines blanches situées dans des couples stellaires.
> Dans de tels systèmes, la naine blanche (constituée majoritairement de carbone et d’oxygène) accumule de la matière provenant de sa partenaire à sa surface. Cette accumulation a lieu jusqu’à ce que la naine blanche atteigne une masse critique de 1,4 masse solaire (la ***masse de Chandrasekhar***). À ce moment-là, on pense que des réactions de fusion du carbone se déclenchent dans son cœur et s’emballent en quelques secondes à peine, provoquant une explosion thermonucléaire qui oblitère complètement cette dernière.
- La durée de ce type d’explosion est de l’ordre d’un mois, durée pendant laquelle la luminosité de la SNIa augmente puis diminue jusqu’à disparaitre dans la nuit. À son pic de luminosité, une SNIa peut être aussi brillante qu’une galaxie tout entière.
- Les SNIa sont très utiles pour les cosmologistes puisqu’elles constituent des ***chandelles standards***, c’est-à-dire des objets (idéaux) dont la luminosité intrinsèque est toujours la même, et qui servent donc à estimer les distances dans l’univers.
> Si on connaît la luminosité intrinsèque d’un objet, il suffit de mesurer sa luminosité apparente pour en déduire la distance (de luminosité) grâce à la ***loi en carré inverse***. 
- Une fois que l’on a mesuré la distance de luminosité d’une SNIa, on peut obtenir son redshift pour un modèle cosmologique donné à l’aide de la ***relation distance-redshift***. Observer la luminosité apparente d’un échantillon de SNIa permet donc d’obtenir des informations sur l’histoire de l’expansion de l’univers.
- En pratique, les SNIa ne sont pas des chandelles standard parfaites : à leur pic, la luminosité d’un échantillon de ces explosions présente des différences de l’ordre de 10-15% (après correction de la durée de l’explosion et de sa couleur). Ces différences limitent la précision à laquelle les distances cosmiques sont inférées. 
- On recense aujourd’hui des milliers de SNIa, dont près d’un millier sont utilisées à des fins cosmologiques.
> Ce sont des événements relativement rares. En moyenne, dans une galaxie typique, il se produit une SNIa tous les 100 ans environs.

*Courbe de luminosité d'un échantillon de SN Ia. Crédit : Huterer et Schafer (2018). [Source](https://astrobites.org/2019/02/18/type-ia-supernovae-could-use-some-more-color/)*

![SNIa](https://astrobites.org/wp-content/uploads/2020/01/Screen-Shot-2020-01-03-at-3.30.49-PM-1080x469.png)

### Les oscillations acoustiques des baryons

- La méthode la plus précise actuellement utilisée pour mesurer l'histoire de l'expansion de l'univers fait appel à d'étranges motifs imprimés dans le ciel que l'on peut détecter quand on observe la distribution des galaxies dans l'univers avec une grande précision. Quand on les projette sur la sphère céleste, ces motifs ressemblent à des petits cercles entourés d'immenses anneaux, similaires à ceux créés par un caillou jeté dans un étang. Ces anneaux sont difficiles à détecter et se chevauchent, mais le plus surprenant c'est qu'ils ont tous la même taille caractéristique (que les astronomes appellent ***échelle acoustique***).
- Ces motifs sont dus à un phénomène physique assez insolite : les  ***oscillations acoustiques des baryons*** (ou BAO, pour Baryonic Acoustic Oscillations)
- La signature des BAO dans la répartition des galaxies a été mise en évidence pour la première fois en 2005 par deux équipes indépendantes d'astronomes associés aux relevés SDSS (Sloan Digital Sky Survey, au Nouveau Mexique) et 2dFGRS (2dF Galaxy Redshift Survey, en Australie).
> Ils ont montré que les anneaux ont une taille caractéristique de 500 millions d'années-lumière (150 Mpc) dans l'univers actuel. Autrement dit, si on observe une galaxie quelque part dans l’univers, on a (un peu) plus de chance de trouver une autre galaxie située à 500 millions d’années-lumière d’elle qu’une galaxie à 400 ou à 600 millions d’années-lumière. 
- Pour comprendre l'origine de ces motifs, il faut revenir aux conditions de l'univers primordial.
> Pendant les premières centaines de milliers d'années qui ont suivi le Big Bang, l'univers était un plasma chaud composé de photons, de protons, d'électrons et de matière noire qui interagissaient sans cesse. Ce plasma avait beau être extrêmement homogène, de petites surdensités de matière noire apparaissaient quand même en permanence. Attirée par la gravité de ces petits amas de matière noire, la matière ordinaire (dite "baryonique") tentait de s'accumuler, mais le rayonnement ambiant avait tendance à s'opposer à cette accumulation (à noter que la matière noire n'interagit pas avec la lumière, donc elle peut former des amas sans problème). Ces deux processus antagonistes ont généré des ondes de pressions qui se déplacent à la vitesse du son (170 000 km/s) dans ce plasma ultra-dense. Ces ondes de pression sont littéralement des ondes sonores de différentes intensités qui se déplacent dans toutes les directions. Dans cette cacophonie, certaines longueurs d'onde sont plus amplifiées que d'autres. La "note" la plus amplifiée possède une longueur d'onde d'un million d'années-lumière environ, ce qui représente une fréquence 48 octaves plus basses que la note la plus grave sur un piano ! Mais lorsque le cosmos atteint l’âge de 380 000 ans, la température du rayonnement primordial passe sous la barre des 3000 K (2700°C environ), et les électrons peuvent enfin se lier aux protons pour former les premiers atomes. Le plasma primordial est devenu un gaz d’atomes électriquement neutres. La lumière cesse alors d’interagir avec la matière et peut se balader dans l’espace à l’infini. Le cosmos, initialement opaque, devient alors transparent. C’est ***l’époque de la recombinaison***. À ce moment, la cacophonie s’arrête. Les ondes sonores sont soudainement figées à une certaine distance caractéristique des surdensités de matière noire. C’est comme si on avait soudainement gelé la surface de l’étang. Ces surdensités sont les graines à partir desquelles se formeront les premières galaxies et autres grandes structures de l’univers. Les empreintes des ondes sonores en forme de coquilles sphériques, quant à elles, vont se mettre à enfler au fil de l’expansion cosmique, à la matière d’un cercle dessiné à la surface d’un ballon de baudruche que l’on gonfle. 13,8 milliards d’années plus tard, on pourra les observer sous la forme d’un léger surnombre de galaxies au niveau  de ces coquilles, et d’une très légère tendance de ces galaxies à être alignées le long de leur surface.
- Le phénomène des BAO lie de manière quantitative les anisotropies observées dans le CMB et les motifs d'anneaux observés dans la distribution spatiale des galaxies
> En effet, les BAO sont responsables des pics observés dans le ***spectre de puissance*** (à définir) du CMB. Ces derniers correspondent aux longueurs d'onde sonores les plus amplifiées dans le plasma primordial.
- En mesurant la taille de ces anneaux à différentes époques de l’univers, à l’aide de relevés astronomiques très fins, et en liant ces anneaux aux conditions initiales fournies par les anisotropies du CMB, on peut donc reconstruire l’histoire de l’expansion cosmique avec une grande précision.
- L'empreinte des BAO sert de ***règle standard*** aux astronomes, c’est-à-dire que ces anneaux sont des objets dont on connaît la taille réelle. Quand on mesure leur diamètre apparent dans le ciel, comme on connaît leur taille on peut donc déterminer leur distance.
- Le grand relevé astronomique BOSS (Baryon Oscillation Spectroscopic Survey), qui fait partie du 3e relevé SDSS, et dont les données ont été acquises entre 2009 et 2014, constitue à ce jour la mesure la plus précise des anneaux produits par les BAO. À travers l’étude spectroscopique de plus d’un million de galaxies, les astronomes ont pu mesurer ces « règles standard » avec une précision d’1% sur une période qui couvre les 6 derniers milliards d’années de l’évolution cosmique (il y a une vingtaine d’années à peine, cette précision n’était que de 50% !).
- Un instrument fondamental pour détecter la signature des BAO dans les années à venir est DESI (Dark Energy Spectroscopic Instrument, "instrument spectroscopique pour l'énergie noire"), installé sur le télescope Mayall de 4 mètres de l'Observatoire National de Kitt Peak (Arizona) et capable de mesurer 5000 spectres de galaxies simultanément
> En 2021, une collaboration internationale de 50 institutions dirigée par le Berkeley Lab a débuté un programme d'observation de 5 ans avec DESI qui devrait l'amener à cartographier la position de plus de 30 millions de galaxies dans le ciel de l'hémisphère Nord, dont près de 2,4 millions de quasars. Couvrant les 11 derniers milliards d’années de l’histoire de l’univers, il pourra atteindre des profondeurs que BOSS ne pouvait pas atteindre, et permettra l'étude la plus fine de l'histoire de l'expansion cosmique jamais produite.      	      	      

*(Illustration des BAO. Crédit: Gabriela Secara, Institut Périmètre [Source](https://insidetheperimeter.ca/fr/desi-launches-five-year-quest-to-understand-the-universe/))*

![BAO](https://insidetheperimeter.ca/wp-content/uploads/2021/05/test-DESI_Baryon_Acoustic_Oscillation.png)

### L'effet de lentille gravitationnelle faible

-	Lorsque des rayons de lumière provenant de galaxies très lointaines traversent l’espace-temps déformé aux abords d’une grosse concentration de matière (dans ce contexte, un amas de galaxies) située entre les sources et l’observateur, on observe des images distordues des galaxies lointaines, comme si ces dernières étaient vues à travers la lentille d’une loupe. Ces distorsions sont dues à l’***effet de lentille gravitationnelle***, un phénomène prédit par la théorie de la relativité générale d’Albert Einstein.
>	La mesure de la déflexion de rayons lumineux des étoiles observées à proximité du Soleil lors d’une éclipse en 1919 constitue l’une des premières prédictions réussies de la relativité générale.
-	Dans certaines situations, l’effet de lentille gravitationnelle peut produire de multiples images de la source en arrière-plan. On parle alors de ***lentillage fort***. Celui-ci requiert un alignement particulier entre la source, la concentration de matière et l’observateur, ainsi que des distances relatives particulières entre les 3 parties. 
>	Les lentilles gravitationnelles fortes peuvent générer d’étranges mirages gravitationnels, tels que les croix ou les anneaux d’Einstein.
-	Mais dans le contexte de la traque de l’énergie sombre, l’effet qui nous intéresse particulièrement est le ***lentillage faible***, beaucoup plus fréquent, mais plus difficile à observer. Ce dernier crée un aplatissement ainsi qu’un alignement systématique des images des galaxies en arrière-plan qui forment un motif particulier.
-	On appelle ***cisaillement cosmique*** (cosmic shear) le signal statistique causé par le lentillage faible des amas de galaxies. Pour l’estimer, on mesure la forme d’un grand échantillon de galaxies lointaines dans une région du ciel donné, et on calcule la déformation moyenne de ces galaxies produite par l’effet de lentilles gravitationnelles.
>	Le cisaillement cosmique a été mesuré pour la première fois en 2000 par une équipe internationale d’astronomes incluant des chercheurs de l’IAP, grâce à l’étude des données du Canada France Hawaii Telescope (CFHT).
-	L’analyse statistique des déformations causées par l’effet de lentillage faible permet de reconstruire la distribution de matière noire dans les amas de galaxies et de suivre l’évolution de ces structures dans le temps (en observant le lentillage faible de ces galaxies lointaines à différents redshifts), ce qui permet de sonder l’influence de l’énergie sombre sur le taux de croissance des structures cosmiques.
>	* On peut comparer la cartographie de la distribution de la matière noire par cette méthode à la reconstruction des lignes de champ magnétique invisible avec de la limaille de fer
> * Lorsque l'on cartographie le cisaillement cosmique, on peut recenser les fluctuations de densité de différentes tailles qui se jouent à grande échelle dans l'univers et en déduire leur spectre de puissance. Et l'étude de ce spectre de puissance nous informe sur la nature et les propriétés de l'énergie sombre. C'est une méthode analogue à celle de l'analyse du spectre de puissance du CMB, mais qui nous informe cette fois du devenir des fluctuations de densité initiales.
-	De nombreux relevés astronomiques font de la mesure du cisaillement cosmique une priorité dans les années à venir. C’est notamment le cas du Dark Energy Survey (DES), du Hyper Suprime-Cam Subaru Strategic Program (HSC-SSP) ou encore du relevé que réalisera l'observatoire Vera Rubin (anciennement appelé LSST), qui a pour mission de mesurer plusieurs milliards (!) de formes de galaxies dans le ciel de l'hémisphère Sud. 

*Illustration de l'effet de lentilles gravitationnelles faible. Crédit : Michael Sachs. [Source](https://en.wikipedia.org/wiki/Weak_gravitational_lensing#/media/File:Gravitational-lensing-3d.png)*

![weak-lensing](https://upload.wikimedia.org/wikipedia/commons/b/b9/Gravitational-lensing-3d.png)

### Les amas de galaxies

- Les amas de galaxies sont les plus grandes structures liées par gravité dans l'Univers.
> Ils ont des tailles de l'ordre du million d'années-lumière (Mpc) et des masses de l'ordre du million de milliards de masses solaires ( $10^{15}$ Msol)
- Les galaxies ne constituent que quelques pourcents de la masse totale d'un amas. Celles-ci baignent en effet dans un gaz très chaud (comprimé à 10-100 millions de degrés sous l'action de la gravité) et très peu dense, et ce gaz représente 80-90% de la masse baryonique d'un amas. De plus, la masse totale de l'amas est largement dominée par la matière noire qui la compose (combien ?)
- Quand on observe les amas de galaxies en rayons X, ceux-ci apparaissent comme des sources diffuses et étendues. Ce qu'on voit dans ces longueurs d'onde, c'est la contribution du gaz intergalactique surchauffé. 
> On ne peut pas observer les rayons X depuis des observatoires au sol, puisque ces longueurs d'onde sont absorbées par l'atmosphère terrestre. On doit donc avoir recours à des observatoires spatiaux comme Chandra ou XMM-Newton pour ce genre d'études.
- Pour les amas dits "relaxés" (ie en équilibre dynamique), la distribution spatiale de ce gaz est très fortement corrélée avec la distribution de la matière noire qui compose en grande partie
> Les amas relaxés constituent une minorité dans la population des amas de galaxies. 
- La formation des amas de galaxies dépend à la fois de la composition de l'univers (et donc des propriétés de la matière noire : Ω_m), de l'histoire de la formation des structures cosmiques (encapsulé dans σ8, l'amplitude des fluctuations de matière) et de l'histoire de l'expansion de l'univers (et donc des propriétés de l'énergie sombre : Ω_Λ, ω)
> En recensant les gros amas de galaxies "relaxés" dans l'univers, on peut comparer les nombres d'amas observés en fonction de leur distance (redshift) et les abondances prédites par différents scénarios d'évolution et de composition cosmique (issues de simulations cosmologiques), et ainsi inférer les propriétés de l'énergie sombre qui collent le mieux aux observations (Ω_Λ, ω) 
- À partir de l'observation d'un amas en rayons X, on peut calculer sa masse baryonique (car la luminosité X est proportionnelle au carré de la densité de gaz qui émet ces rayons X) et sa température. Et à partir d'un profil de densité théorique, si l'on fait l'hypothèse que le gaz est en équilibre hydrostatique dans le puits de potentiel de l'amas (ie l'amas ne présente pas de sous-structure et n'est pas en train de fusionner avec d'autres amas), alors on peut calculer la masse totale de l'amas en fonction du rayon, puis en intégrant sur le profil la masse totale de l'amas. On peut alors obtenir la ***fraction de gaz*** des amas (notée f_gas(z)), définie comme le rapport de la masse de gaz (mesurée via l'émission de rayons X) sur la masse totale de l'amas (galaxies + gaz intergalactique + matière noire)
> * Une autre manière d'obtenir la masse totale d'un amas est d'utiliser l'effet de lentilles gravitationnelle.
- Au milieu des années 90, les astronomes se sont rendus compte qu'ils pouvaientaussi utiliser les observations en rayons X des amas comme indicateurs de distance de ces amas, ce qui leur ont permis de tester les prédictions du modèle ΛCDM et en particulier de contraindre les propriétés de l'énergie sombre
> * Il faut pour cela supposer que les amas de galaxies sont des objets si vastes et si massifs que leur composition matérielle, notamment le rapport entre matière baryonique et matière noire est représentative de la composition matérielle de l'univers tout entier.
> * La fraction de gaz est corrélée avec la distance de l'amas, et cette distance dépend elle-même de la quantité de matière noire et d'énergie sombre dans l'univers. Comme la fraction de gaz doit être à peu près la même sur tous les amas de galaxies, en mesurant la fraction de gaz dans plein d'amas on doit pouvoir trouver les paramètres cosmologiques qui donnent les distances d'amas "correctes".
- Les données actuelles issues de l'observation des amas de galaxies fournissent une confirmation indépendante que l'expansion de l'univers est bien accélérée, et elles montrent que les propriétés de l'énergie sombre sont très proches d'une constante cosmologique
- Le télescope spatial Euclid de l'ESA, qui sera lancé en 2023, a pour mission de produire dans les années à venir l'un des catalogues d'amas de galaxies les plus fournis et les plus profonds de tous les temps, ce qui permettra aux astronomes de mieux contraindre les propriétés de l'énergie sombre.  

*Emission de rayons X du gaz chaud de 4 amas de galaxies, photographiée par le télescope spatial Chandra. Crédit : X-ray: NASA/CXC/Univ. of Alabama/A. Morandi et al; Optical: SDSS, NASA/STScI. [Source](https://www.nasa.gov/mission_pages/chandra/probing-dark-energy-with-galaxy-clusters.html)*

![xraychandra](https://www.nasa.gov/sites/default/files/styles/full_width_feature/public/thumbnails/image/clusters.jpg)

### La détermination directe du taux d'expansion cosmique

Direct Determination of H0: The value of H0 sets the current value of the critical density
ρc = 3H2
0 /8πGN, and combination with CMB measurements provides a long lever arm
for constraining the evolution of dark energy. The challenge in direct H0 measurements is
establishing distances to galaxies that are far enough away that their peculiar velocities
are small compared to the expansion velocity v = H0d. This can be done by building
a ladder of distance indicators tied to stellar parallax on its lowest rung, or by using
gravitational lens time delays or geometrical measurements of maser data to circumvent
this ladder

Direct measurements of the Hubble constant offer use-
ful complementary information that helps break degen-
eracy between dark energy and other cosmological pa-
rameters. This is because precise CMB measurements
effectively fix high-redshift parameters including the
physical matter density Ωmh2; independent measure-
ments of H0 (i.e. h) therefore help determine Ωm which
is degenerate with the dark energy equation of state.
Current & 3σ tension between the most precise direct
measurements of H0 from the Cepheid distance lad-
der [355, 356] and the indirect ΛCDM determination
from the CMB [74] is partially, but not fully, relieved
by allowing phantom dark energy (w < −1) or extra
relativistic degrees of freedom

A still more ambitious period begins late in this decade and continues through the
2020s, with experiments that include the Dark Energy Spectroscopic Instrument (DESI),
the Subaru Prime Focus Spectrograph (PFS), the Large Synoptic Survey Telescope
(LSST), and the space missions Euclid and WFIRST (Wide Field Infrared Survey
Telescope). DESI and PFS both aim for major improvements in the precision of BAO,
RSD, and other measurements of galaxy clustering in the redshift range 0.8 < z < 2,
where large comoving volume allows much smaller cosmic variance errors than low
redshift surveys like BOSS. LSST will be the ultimate ground-based optical weak lensing
experiment, measuring several billion galaxy shapes over 20,000 deg2 of the southern
hemisphere sky, and it will detect and monitor many thousands of SNe per year. Euclid
and WFIRST also have weak lensing as a primary science goal, taking advantage of the
high angular resolution and extremely stable image quality achievable from space. Both
missions plan large spectroscopic galaxy surveys, which will provide better sampling at
high redshifts than DESI or PFS because of the lower infrared sky background above
the atmosphere. WFIRST is also designed to carry out what should be the ultimate
supernova cosmology experiment, with deep, high resolution, near-IR observations and
the stable calibration achievable with a space platform.

Performance forecasts necessarily become more uncertain the further ahead we
look, but collectively these experiments are likely to achieve 1–2 order of magnitude
improvements over the precision of current expansion and growth measurements, while
simultaneously extending their redshift range, improving control of systematics, and
enabling much tighter cross-checks of results from entirely independent methods. The
critical clue to the origin of cosmic acceleration could also come from a surprising
direction, such as laboratory or solar system tests that challenge GR, time variation
of fundamental “constants,” or anomalous behavior of gravity in some astronomical
environments. Experimental advances along these multiple axes could confirm today’s
relatively simple, but frustratingly incomplete, “standard model” of cosmology, or they
could force yet another radical revision in our understanding of energy, or gravity, or the
spacetime structure of the Universe.


## Que sait-on de l'énergie sombre aujourd'hui ?

- L'énergie sombre ne domine le contenu énergétique de l'univers que depuis relativement récemment (z ~ 0.5)
- Elle affecte les distances dans l'univers, ainsi que la croissance et le nombre des grandes structures cosmiques 
- Les différentes contraintes observationnelles actuelles tendent vers w ~ -1 (à 5% près).
- Les prochains relevés astronomiques vont permettre d'étudier la variation temporelle (hypothétique) de la contribution de l'énergie sombre


# L'inflation cosmique

*Sources*

- [Inflationary Cosmology: From Theory to Observations](https://arxiv.org/abs/1810.09934) - Alberto Vazquez et al (2018)
- [Introductory review of cosmic inflation](https://arxiv.org/abs/hep-ph/0304257) – Tsujikawa (2003)
- [A review on cosmic inflation](http://www.ijcrar.com/abstractview.php?ID=329&vol=5-5-2017&SNo=6) - Sapkota et Adhikari (2017)
- [Ask Ethan: How Well Has Cosmic Inflation Been Verified?](https://www.forbes.com/sites/startswithabang/2019/05/11/ask-ethan-how-well-has-cosmic-inflation-been-verified/?sh=146398421d07) – Ethan Siegel (2019)
- [Inflation and the Cosmic Microwave Background](https://arxiv.org/abs/astro-ph/0305179) - Lineweaver (2003)
- [Inflation et physique des particules](https://cosmology.education/inflation/#!) - Lucas Gautheron
- [Inflationary universe: A possible solution to the horizon and flatness problems](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.23.347) - Guth (1981)
- The Inflationary Universe: The Quest for a New Theory of Cosmic Origins. Alan Guth (Vintage, 1998)
- [Eternal Inflation](https://arxiv.org/abs/astro-ph/0101507) – Guth (2001)
- [Inflation and the New Era of High-Precision Cosmology](https://physics.mit.edu/wp-content/uploads/2021/01/physicsatmit_02_cosmology.pdf) - Guth (2002)
- [Inflation: Theory and Observations](https://arxiv.org/abs/2203.08128) – Achucarro et al (2022)
- [What is the Inflation Theory?](https://wmap.gsfc.nasa.gov/universe/bb_cosmo_infl.html) - NASA
- [Cosmologie (A)](https://encyclo-philo.fr/item/1683) – L’Encyclopédie philosophique
- [Du nouveau sur l'existence des mythiques monopôles magnétiques](https://www.futura-sciences.com/sciences/actualites/physique-nouveau-existence-mythiques-monopoles-magnetiques-44601/) - Futura Sciences (2022)
- [ATLAS, à la recherche des monopôles magnétiques](https://home.cern/fr/news/news/physics/atlas-homes-magnetic-monopoles) - CERN
- [Magnetic monopoles in field theory and cosmology](https://royalsocietypublishing.org/doi/10.1098/rsta.2011.0394) – Rajantie (2012)
- [The Friedmann Equation and the Fate of the Universe](https://phys.libretexts.org/Bookshelves/Astronomy__Cosmology/Big_Ideas_in_Cosmology_(Coble_et_al.)/17%3A_Dark_Energy_and_the_Fate_of_the_Universe/17.03%3A_The_Friedmann_Equation_and_the_Fate_of_the_Universe) – Libretexts Physics
- [Geometry of the Universe ](https://map.gsfc.nasa.gov/media/990006/index.html) - NASA
- [Inflation](https://sites.astro.caltech.edu/~ccs/Ay21/guth_inflation.pdf) – Guth (2004)
- [Une fantastique inflation](https://www.cnrs.fr/cw/dossiers/dosbig/decouv/xchrono/inflat/niv1_1.htm) - CNRS
- [Inflation et nouveaux paradigmes](https://podcastfichiers.college-de-france.fr/combes-20170130.pdf) – Slides de Françoise Combes (2017)
- [The Inflationary Universe](https://phys.libretexts.org/Bookshelves/Astronomy__Cosmology/Book%3A_Astronomy_(OpenStax)/29%3A_The_Big_Bang/29.06%3A_The_Inflationary_Universe) – Libretext Physics
- [Inflation for beginners](http://www.lifesci.sussex.ac.uk/home/John_Gribbin/cosmo.htm) - Gribbin
- [Cosmology and particle physics Lecture notes](https://www.lehigh.edu/~tiw419/files/2019S-Lecture-09.pdf) -  Timm Wrase
- [chaotic cosmic inflation](https://ncatlab.org/nlab/show/chaotic+cosmic+inflation) - nLab
- [Inflationary Theory versus Ekpyrotic/Cyclic Scenario](http://de.arxiv.org/abs/hep-th/0205259) – Linde (2002)
- [Chaotic Inflation](https://linkinghub.elsevier.com/retrieve/pii/0370269383908377) - Linde (1983).
- [Cosmology](https://pages.aip.de/pfrommer/Lectures/cosmology.pdf) – Cours de Matthias Bartelmann 
- [The Horizon Problem](https://iopscience.iop.org/article/10.1088/1742-6596/1269/1/012017/pdf) - Si Lakhal et Guezmir (2017)
- [Birth of inflationary universes](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.27.2848) – Vilenkin (1983) 
- [Eternal inflation and its implications](https://arxiv.org/abs/hep-th/0702178) - Guth (2007) 
- [Eternal inflation and its implications](https://arxiv.org/abs/hep-th/0702178) – Linde (2007)
- [Graceful exit problem (cosmology)](https://en.wikipedia.org/wiki/Graceful_exit_problem_(cosmology)) - Wikipédia
- [Eternal Inflation, Multiverse and the Measure Problem - DESY THEORY WORKSHOP SEMINAR](https://indico.desy.de/event/34374/attachments/75767/97426/Eternal_Inflation_Workshop_Seminar.pdf) - Koschnitzke  (2022)
- [Eternal Inflation](https://www.worldscientific.com/doi/suppl/10.1142/6923/suppl_file/6923_chap01.pdf) – livre de Sergei Winitzki (2009) 
- [Eternal Inflation](https://people.ast.cam.ac.uk/~stg20/cuda/eternal/index.html) – Steven Gratton
- [The Founder of Cosmic Inflation Theory on Cosmology's Next Big Ideas](https://www.scientificamerican.com/custom-media/biggest-questions-in-science/the-founder-of-cosmic-inflation-theory-on-cosmologys-next-big-ideas/) - Scientific American
- [Why Do Physicists Say A Multiverse Has To Exist?](https://www.forbes.com/sites/startswithabang/2021/02/25/why-do-physicists-say-a-multiverse-has-to-exist/?sh=113d826c4727) – Ethan Siegel (2021)
- [Universe in a bubble](https://aeon.co/essays/did-our-cosmos-emerge-from-a-sea-of-inflating-bubbles) – Richard Gott
- [Eternal Inflation](https://ncatlab.org/nlab/show/eternal+inflation) - ncatlab
- [Measure problem (cosmology)](https://en.wikipedia.org/wiki/Measure_problem_(cosmology)) - Wikipédia
- [Et l’inflation fut](https://unesdoc.unesco.org/ark:/48223/pf0000122630_fre) -  Andrei Linde, le courrier de l’UNESCO (2001)
- [Natural Inflation](https://lib-extopc.kek.jp/preprints/PDF/2000/0036/0036503.pdf) – Steinhardt (1983)
- [The birth of inflationary universes](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.27.2848) - Vilenkin (1983)
- [Inflation cosmologique et théorie des cordes : aspects multichamps et non-gaussianités primordiales](https://theses.hal.science/tel-00724157/document) – Thèse de Sébastien Renaux-Pétel (2010)

---

- Le modèle du Big Bang a connu de nombreux succès, mais il n’a pourtant pas réponse à tout. Quelques propriétés de l’univers échappent à ses prédictions et posent donc problème :
> * ***Le problème de l’horizon*** (horizon problem) : Lorsqu’on observe le CMB dans deux régions A et B diamétralement opposées du ciel (ie deux régions situées aux extrémités de l’univers observable), on remarque que ces régions ont exactement la même température (à $10^{-5}$ K près). Cette isotropie de température implique que ces deux régions étaient à l’***équilibre thermique*** par le passé. En d’autres termes, elles ont du être en contact suffisamment longtemps pour atteindre la même température. Mais dans le cadre du modèle standard, le cosmos n’étant âgé que de 13,8 milliards d’années, un photon partant de la région A au moment de l’émission du CMB et voyageant en ligne droite n’aurait jamais eu le temps d’arriver à la région B pour échanger de l’information (et inversement). A et B étant trop éloignées, le temps de voyage du photon dépasserait l’âge de l’univers. En pratique, on peut calculer, pour chaque point du CMB, avec quels autres points il a eu le temps d’être en contact depuis le début de l’expansion cosmique. L’ensemble de ces points définit son ***horizon causal***. Cet horizon forme un disque d’environ 2° de rayon. Autrement dit, des points séparés de plus de 2° sur la carte du CMB n’auraient théoriquement pas pu entrer en contact au cours de l’histoire de l’univers pour échanger de la chaleur. On dit qu’ils sont « causalement disjoints ». Le modèle du Big Bang ne permet donc pas d’expliquer l’isotropie du CMB autrement qu’en la traitant comme une condition initiale de l’expansion cosmique (ie la température et la densité de l’univers l’univers étaient homogènes et isotropes depuis le début de son histoire).
> * ***Le problème de la courbure*** (flatness problem) : dans le modèle standard de la cosmologie, les équations de Friedman régissent l’évolution du taux d’expansion cosmique dans un univers homogène et isotrope, en fonction de son contenu matériel et énergétique (en matière baryonique, en matière noire, en rayonnement et en énergie sombre). Ces équations nous disent que la densité totale de l’univers (notée $\rho$ ) détermine sa géométrie. Si cette densité dépasse une valeur critique (notée $\rho_c$ ), cela veut dire que sa géométrie est fermée (analogue à la surface d’une sphère). Dans cet univers, deux rayon laser émis parallèlement entre eux finiront par se rejoindre au bout d’un moment. À l’inverse, si la densité totale de l’univers est inférieure à la densité critique ( $\Omega$ = $\rho$ / $\rho_c$ < 1), la géométrie de l’espace est ouverte (analogue à une selle de cheval). Dans cet univers, deux rayons laser parallèles finissent par diverger. Enfin, si la densité de l’univers est égale à la densité critique ( $\Omega$ = 1), la géométrie de l’univers est dite plate (analogue à une feuille de papier). On dit aussi que sa courbure est nulle. Dans cet univers, deux rayons laser parallèles resteront parallèles pour toujours. À son tour, la géométrie de l’univers détermine son destin ultime : ainsi, si l’on élude la contribution de l’énergie sombre pour simplifier, un univers fermé finira par ralentir son expansion jusqu’à s’effondrer sur lui-même. C’est le scénario du ***Big Crunch***. Un univers ouvert quant à lui continuera son expansion pour toujours. C’est le scénario du ***Big Chill***.  Enfin, un univers plat s’étendra pour toujours mais de plus en plus lentement, et ne s’effondrera jamais sur lui-même (Big Chill aussi). Les mesures actuelles de la densité de l’univers réalisées grâce à la cartographie du CMB montrent que celle-ci est très proche de la densité critique :  0.95 < $\Omega$ < 1.05. Or, les équations de Friedman nous apprennent que la densité de l’univers a tendance à s’éloigner spontanément de sa valeur critique au fil de l’expansion cosmique. Du coup, si | $\Omega$ − 1| < 0,05 de nos jours, on peut calculer que la densité de l’univers aurait dû être encore plus proche de la densité critique à l’époque de la nucléosynthèse primordiale (| $\Omega$ − 1| < $10^{-16}$ ), et encore bien plus proche à l’ère de Planck (| $\Omega$ − 1| < $10^{-64}$ ). Il faudrait donc que la densité de l’univers primordial soit dans une gamme de valeurs extrêmement précises pour être compatibles avec les observations actuelles, sinon le cosmos s’effondrerait très tôt sur lui-même ou bien s’étendrait si vite qu’aucune structure ne pourrait se former. Un tel ***ajustement fin*** de ce paramètre est inacceptable pour beaucoup de cosmologistes (pourquoi cette valeur très spéciale et pas une autre ?).
> * ***Le problème des monopoles magnétiques*** (magnetic monopole problem) : les monopoles magnétiques sont des particules hypothétiques qui possèdent un pôle magnétique isolé « nord » ou « sud » (une « charge magnétique » analogue à la charge électrique positive ou négative), contrairement aux aimants « classiques » qui possèdent toujours 2 pôles opposés (un nord ET un sud, même si on les brise en leurs constituants élémentaires). L’existence de telles particules a été théorisée pour la première fois par Paul Dirac en 1931 et constitue une prédiction de nombreuses extensions du modèle standard de la physique des particules (GUT, supersymétrie, supercordes). Elles auraient dû être créées dans les conditions de l’univers primordial, et devraient dominer le contenu matériel de l’univers actuel. Pourtant, aucun indice de l’existence de monopoles magnétiques n’a été trouvé jusqu’à présent, que ce soit au travers d’observations ou d’expérimentations. 
> * ***L’origine des grandes structures cosmiques*** : l’univers est rempli de galaxies, d’amas de galaxies et de grandes structures cosmiques (murs, filaments , vides etc). Le modèle standard ne fournit aucun scénario pour expliquer l’origine de ces structures et de leurs propriétés. En particulier, les fluctuations de température observées dans la carte du CMB s’étalent sur des échelles si grandes que le modèle du Big Bang est démuni pour expliquer leur apparition en un temps aussi restreint que 380 000 ans (entre le Big Bang et l’époque où la lumière se découple de la matière à z ~ 1100), à moins de considérer que ces fluctuations à grande échelle étaient déjà présentes dans l’univers primordial et qu’elles ont formé les graines des structures à venir. 
> * ***L’origine de l’expansion cosmique*** : le modèle du Big Bang ne dit rien de la « pichenette initiale » qui aurait lancé les galaxies sur leur course actuelle.
- Il faut noter que tous ces problèmes sont résolus si l’on considère que ces propriétés particulières sont des conditions initiales de l’histoire de l’univers. Autrement dit, l’univers aurait débuté son histoire en expansion, parfaitement plat, avec la même température partout et avec les germes des grandes structures à venir. « C’est comme ça, un point c’est tout ». Mais de telles considérations ne sont pas satisfaisantes pour la majorité des scientifiques.

## Les scénarios d’inflation cosmique

- En 1981, le cosmologiste Alan Guth, initialement motivé par la résolution du problème des monopoles magnétiques, propose une « rustine » (un add-on !) pour pallier les différentes limitations du modèle du Big Bang : le ***scénario de l’inflation cosmique***.
> Selon ce scénario, l’univers primordial aurait connu une brève période d’expansion accélérée (quasi-exponentielle) qui l’aurait fait enfler d’un facteur phénoménal (au moins $10^{30}$ ) en une fraction de seconde infinitésimale.
- Pour justifier physiquement son scénario, Guth postule l’existence d’un nouveau champ scalaire qu’il nomme ***l’inflaton***. Ce champ scalaire est défini comme un espace vide de matière mais en tous points rempli d’une forme d’énergie exotique (jamais encore observée dans la nature). Mathématiquement, on le caractérise par un ***potentiel*** qui encapsule ses propriétés et son évolution. L’inflaton se trouve initialement dans un état dit de ***faux vide*** (ie un espace sans matière mais au niveau d’énergie plus élevé que celui du vrai vide -minimum local du potentiel-, ie dont l’état d’énergie est minimal). Cet état de faux vide est caractérisé par une pression négative qui agit comme une force répulsive, une sorte “d’antigravitation” (à proprement parler, il faudrait parler de gravitation tout court, puisqu’en relativité générale, la gravitation peut être aussi bien attractive que répulsive). C’est cette force répulsive qui propulse l’univers dans sa phase d’expansion accélérée. À mesure que le cosmos enfle de manière quasi-exponentielle, sa température diminue. Comme l’état de faux vide est ***métastable*** (c’est-à-dire que la moindre perturbation peut déclencher un changement abrupte d’état), l’inflaton finit par transitionner vers un état de vrai vide. Cette transition signe la fin de la période inflationnaire. L’énergie contenue dans le champ scalaire est alors déversée dans l’univers sous forme d’énergie thermique, et la température du cosmos augmente à nouveau. C’est la période de ***réchauffement*** (reheating). À la fin du réchauffement, l’univers est constitué d’une soupe de particules élémentaires et de rayonnement en expansion (non accélérée) telle que le décrit le modèle du Big Bang chaud. 
- Dans le scénario original de Guth (1981), à la fin de la période inflationnaire le cosmos subit une ***transition de phase***, un changement d’état résultant du passage de l’état de faux vide (minimum local du potentiel du champ scalaire) à l’état de vrai vide (minimum global) par ***effet tunnel***. Cette transition de phase (dite de « premier ordre ») est analogue à celui d’un verre d’eau en ***surfusion*** (ie liquide à des températures négatives) qui se solidifie brutalement à la moindre perturbation. Lors de cette transition de phase, des bulles de vrai vide se forment un peu partout dans l’océan de faux-vide ambiant, s’étendent et finissent par collisionner entre elles. Ces motifs de percolation servent ensuite de graines pour les grandes structures à venir.
- Le problème avec le modèle original de Guth (qu’on appelle aujourd’hui ***l’ancienne inflation***), c’est que ces bulles de vrai vide sont trop petites pour contenir notre univers. Par conséquent, la collision entre les bulles créerait des inhomogénéités à la fin de l’inflation qui seraient bien plus grandes que celles que l’on observe actuellement dans l’univers (graceful exit problem).
- En 1982, Andrei Linde ainsi que Andreas Albrecht et Paul Steinhardt introduisent indépendamment une nouvelle classe de modèles pour résoudre le problème de l’ancienne inflation. On parle aujourd’hui de ***nouvelle inflation*** pour se référer à cette classe de modèles. Dans ce cadre, au lieu de changer instantanément d’état par effet tunnel, l’inflaton passe graduellement de l’état de faux vide (ou d’un état instable situé au sommet du potentiel du champ scalaire) au vrai vide, à la manière d’une bille posée sur la pente d’un toboggan qui roule jusqu’au sol. On parle d’***inflation de roulement lent*** (slow-roll). Au lieu d’avoir des milliards de bulles qui percolent, l’univers observable tout entier est cette fois-ci contenu dans une seule bulle, et l’énergie de l’inflaton se déverse dans l’espace en tous points de cette bulle, et pas seulement au niveau de sa coquille (comme c’était le cas dans l’ancienne inflation). Les modèles de nouvelle inflation prédisent un univers homogène à grande échelle, similaire à celui qu’on observe.
- Les modèles d’ancienne et de nouvelle inflation sont basées sur l’hypothèse d’un univers primordial aux conditions initiales spécifiques, ie que l’univers était à ses débuts déjà dans un état d’équilibre thermique et que tous les points de l’Univers ont subi une même période d’inflation en même temps (l’amplitude du potentiel de l’inflaton est la même en tous points de l’espace-temps « au moment du Big Bang »). En d’autres termes ces scénarios requièrent un ajustement fin de l’univers. En 1983, Andrei Linde propose une variante de la nouvelle inflation appelée ***inflation chaotique***. 
> Dans ce scénario, les conditions initiales de l’inflaton sont distribuées de manière stochastiques (« chaotiques »), et des fluctuations quantiques peuvent pousser certaines régions locales de l’espace-temps hors de l’équilibre et déclencher de manière aléatoire des périodes d’inflation dans ces régions. L’une de ces régions constituerait aujourd’hui notre univers observable.
> Des mesures récentes réalisées entre 2013 et 2015 dans le cadre des collaborations Planck et BICEP2 ont depuis fortement défavorisé ce scénario.
- En 1983, Steinhardt, Vilenkin et Linde se rendent compte que la quasi-totalité des modèles inflationnaires (nouvelle et chaotique) présentent une étrange propriété :  ***l’inflation est un processus éternel***, qui s’auto-entretient à l’infini.
> * Cette propriété est due au fait que le champ scalaire est parcouru par des fluctuations quantiques qui retardent ou avancent aléatoirement le moment de la période de réchauffement (et donc la fin de la période inflationnaire) selon les régions de l’espace dans lesquelles il a lieu. Dans les régions où la fin de l’inflation est retardée, l’expansion exponentielle produit donc de nouvelles régions de faux vide métastables, qui génèrent à leur tour une infinité de ***poches d’univers*** (pocket universe) au fil du temps. Ces poches se dilatent et évoluent indépendamment les unes des autres au sein d’un vaste ***multivers*** comme des bulles dans une mer de champagne infinie, et sont déconnectées causalement, si bien qu’il est impossible de les observer depuis notre poche d’univers à nous (ce qui pose le problème de la testabilité de cette hypothèse). Il existerait de « rares » régions (relativement parlant, parce qu’il y en existerait une infinité) dans lesquelles le processus inflationnaire s’est arrêté et a conduit à une période de réchauffement, donnant naissance à une poche d’univers. Des êtres vivants et des cosmologistes ne peuvent émerger que dans de telles régions, et sans surprise, notre univers observable en fait partie. Mais le reste du multivers se trouve dans une phase inflationnaire sans fin. 
> * Si ce scénario est correct, alors le multivers dans sa globalité n’est pas homogène, mais présente plutôt une structure analogue à une fractale.
> * Chaque poche d’univers présente localement des propriétés physiques qui lui sont propres : intensités relatives des interactions fondamentales (constantes de couplage), valeur de la constante cosmologique, masses des différentes particules, température du CMB, etc… Si le multivers est réellement infini, alors toutes les valeurs possibles de ces paramètres physiques co-existent. En d’autres termes, tout ce qui peut arriver se produit.
> * Certains auteurs parlent parfois de « bulles d’univers » (bubble universes) pour se référer aux poches d’univers, mais cette formulation peut être trompeuse, car les « bulles » en question présentent des formes très irrégulières et sont loin d’être sphériques.
> * Si l’inflation est éternelle dans le futur, on peut montrer qu’elle n’est pas éternelle dans le passé. 
> * ***problème de la mesure*** (measure problem).
> * ***paradoxe de la jeunesse*** (Youngness Paradox)
- On ne sait pas combien de temps a pu durer la période inflationnaire. A minima, elle a pu démarrer à ***l’ère de Planck*** ( $10^{-43}$ s après le Big Bang). On pense qu’elle a eu lieu à ***l’ère de grande unification*** ( $10^{-35}$ s après le Big Bang) et qu’elle s’est probablement terminée vers $10^{-32}$ s après le Big Bang.
- Il existe à l’heure actuelle plus de 200 modèles d’inflation cosmique, mais aussi des scénarios alternatifs à l’inflation, comme les scénarios du ***pré-Big Bang*** et les ***modèles cycliques / ekpyrotiques***, mais ces derniers requièrent un ajustement fin de leurs paramètres libres pour résoudre les problèmes du Big Bang. 

*Comparaison entre l’ancienne et la nouvelle inflation. Crédit : inconnu. [Source](https://antimatter.ie/2009/03/18/the-mechanism-of-inflation/)*
![old-vs-new-inflation](https://i.imgur.com/90DWC1n.jpg)

*Représentation schématique de l’inflation éternelle. Crédit : Jared Schneidman. [Source]( https://briankoberlein.com/blog/boltzmanns-brain/)*
![inflation-eternelle]( https://i.imgur.com/70UL7S4.jpg)

## Solutions aux problèmes du Big Bang

- Le scénario inflationnaire fournit une solution au problème des monopoles :
> Selon les théories de grande unification, les monopoles magnétiques auraient été générés durant l’ère de grande unification. Or, durant l’inflation, l’univers se retrouve incroyablement dilué. La densité des monopoles magnétiques (et d’autres particules « reliques ») diminue alors très rapidement et devient négligeable. Et au moment du réchauffement, la température ambiante n’est plus assez élevée pour générer de nouveaux monopoles. C’est pour cela qu’on n’en trouve plus aujourd’hui.
- L’inflation résout aussi le problème de l’horizon :
> La région de l’espace qui correspond aujourd’hui à notre univers observable se trouvait dans un état d’équilibre thermique AVANT l’inflation. Puis, lors de l’inflation, des points initialement très proches les uns des autres (et donc en contact thermique) ont été envoyés à des distances si grandes qu’ils n’ont plus été capable d’échanger de l’information. De fait, l’homogénéité de notre univers observable est préservée. Pour fournir une solution viable au problème de l’horizon, on peut calculer que les dimensions de l’univers ont dû être multipliées au moins par un facteur $10^{30}$ pendant la période inflationnaire (60 e-folds).
- L’inflation résout également le problème de la courbure :
> Si une région de l’espace donnée se dilate suffisamment rapidement pendant la période inflationnaire, elle finira par prendre une taille beaucoup plus grande que l’univers observable (le facteur d’échelle augmente de manière exponentielle tandis que le rayon de Hubble reste quasi-constant), et sa géométrie finira forcément par nous apparaître plate localement, de la même façon qu’une fourmi posée sur un ballon de baudruche qui enfle jusqu’à prendre la taille de la Terre ne verra plus la courbure de la sphère sur laquelle elle se trouve. Dans le scénario inflationnaire, quelle que soit la valeur de $\Omega$ avant l’inflation, il finira par tendre vers 1 à la fin de cette période. Pour fournir une solution viable au problème de la courbure, on peut calculer que les dimensions de l’univers ont dû être multipliées au moins par un facteur $10^{30}$ pendant la période inflationnaire (60 e-folds).
- Le scénario inflationnaire propose un mécanisme physique qui pourrait être à l’origine des grandes structures cosmiques :
> L’inflaton était parcouru d’infimes fluctuations de densité d’énergie appelées ***fluctuations quantiques***, qui se produisent spontanément, à la manière de la désintégration radioactive d’un atome (ie elles ne sont pas causées par un phénomène antérieur). D’ordinaire, ces vaguelettes aléatoires sont évanescentes. Mais l’inflation a rapidement étiré ces fluctuations microscopiques à des échelles beaucoup plus vastes, et a figé leur empreinte dans l’espace. Ces fluctuations quantiques hypertrophiées ont introduit des grumeaux dans la soupe cosmique primordiale. À terme, ces grumeaux ont permis à la gravitation de structurer l’échafaudage du cosmos à grande échelle. Les propriétés statistiques des grumeaux prédites par le scénario inflationnaire (spectre de puissance quasi invariant d’échelle) correspondent aux propriétés des anisotropies de température observées du CMB.
- L’inflation ne résout pas tous les problèmes de la cosmologie contemporaine non plus. Ainsi, il ne dit rien sur l’origine de l’inflaton, ni sur l’état de l’univers avant l’inflation.

*Evolution de la taille de l’univers observable, avec et sans ajout du scénario inflationnaire. Crédit : Roen Kelly, d’après Alan Guth. [Source](https://astronomy.com/magazine/news/2021/01/the-beginning-to-the-end-of-the-universe-inflating-the-universe)*
![radius-observable-inflation](https://i.imgur.com/qBaFbeR.jpg)

*Illustration de la résolution du problème de la courbure. Crédit : Physics Libretext. [Source](https://phys.libretexts.org/Bookshelves/Astronomy__Cosmology/Book%3A_Astronomy_(OpenStax)/29%3A_The_Big_Bang/29.06%3A_The_Inflationary_Universe)*
![fourmi](https://i.imgur.com/lgC8OkU.jpg)

# Le problème de la hiérarchie

*Sources*

- [The Hierarchy Problem: why the Higgs has a snowball’s chance in hell](https://www.quantumdiaries.org/2012/07/01/the-hierarchy-problem-why-the-higgs-has-a-snowballs-chance-in-hell/) - Quantum Diaries
- [The Hierarchy Problem](https://profmattstrassler.com/articles-and-posts/particle-physics-basics/the-hierarchy-problem/) - Matt Strassler 
- [The Higgs, The Hierarchy Problem, and the LHC](https://www2.physics.ox.ac.uk/sites/default/files/2014-11-24/higgs_lhc_jmr_nov14_pdf_93873.pdf) - John March-Russell
- [The Mystery of the Higgs Boson's Mass](https://podcasts.google.com/feed/aHR0cHM6Ly9mZWVkcy5idXp6c3Byb3V0LmNvbS8xMTYyNjEzLnJzcw/episode/QnV6enNwcm91dC04OTE4NTUw) - Why this universe
- [Naturalness after the Higgs](https://cerncourier.com/a/naturalness-after-the-higgs/) - CERN
- [A Deepening Crisis Forces Physicists to Rethink Structure of Nature’s Laws](https://www.quantamagazine.org/crisis-in-particle-physics-forces-a-rethink-of-what-is-natural-20220301/) - Quanta Magazine
- [The Dawn of the Post-Naturalness Era](https://arxiv.org/abs/1710.07663) - Giudice (2017)
- [A Lecture on the Hierarchy Problem and Gravity](https://cds.cern.ch/record/2120792/files/CERN-2013-003-p145.pdf) - Dvali (2013) 
- [The Higgs & the Hierarchy Problem](https://www.youtube.com/watch?v=iywSF7BGhyU) - Anna Barth
- [Big Mysteries: The Higgs Mass](https://www.youtube.com/watch?v=IjCypYnBYwQ) - Fermilab
- [Naturally Speaking: The Naturalness Criterion and Physics at the LHC](https://arxiv.org/abs/0801.2562) - Giudice (2008)
- [Histoire de la cosmologie](https://cosmology.education/booklet/booklet.pdf) - Lucas Gautheron
- [Naturalness: A Snowmass White Paper](https://arxiv.org/abs/2205.05708) - Craig (2022)
- ["Particle Physics: The Higgs Boson and Beyond" by Andreas Hoecker (CERN)](https://youtu.be/XX4pL7pwl7w) - SLAC (2012)
- ["The Once and Future Higgs" by Prof. Nathaniel Craig (University of California, Santa Barbara)](https://youtu.be/GduJt1V2eNk) - TIFR (2021)

---

- Le modèle standard est constitué de 24 particules fondamentales.
- Le boson de Higgs joue un rôle fondamental dans le modèle standard
- Le boson de Higgs brise la symétrie électrofaible et donne sa masse aux bosons et aux fermions
- Les particules interagissent avec le champ de Higgs (qui remplit tout l'espace-temps), ce qui réduit leur vitesse. Et plus elles interagissent fortement, plus leur masse est grande (c'est proportionnel).
- Découvert en 2012 par le LHC, un accélérateur de particules de 27km de circonférence
- On peut sonder la composition de la matière de plus en plus profondément à mesure que l'on fait des collisions de plus en plus énergétiques
- Dans le modèle standard, le higgs est "le seul scalaire fondamental (tous les autres scalaires sont des états composites)"
- Un des problèmes les plus importants de la physique contemporaine
- coincidence spectaculaire
- Boson de Higgs prédit en 1954
- En une phrase : la masse observée du boson de Higgs est de 125 GeV (125 fois la masse du proton ?). Pourtant, des corrections quantiques issues des interactions avec d'autres particules du modèle standard prédisent une masse 17 ordres de grandeur plus grande (au niveau de la masse de Planck). C'est le problème de la hiérarchie électrofaible.
- The Higgs boson plays a key role in the Standard Model: it is related to the unification of the electromagnetic and weak forces, explains the origin of elementary particle masses
- Higgs—the last piece of the Standard Model
- Hierarchy problem. This is often ‘explained’ by saying that quantum corrections want to make the Higgs much heavier than we need it to be… say, 125-ish GeV. 
- The Higgs has a snowball’s chance in hell of having a mass in that ballpark.
- If you put a glass of water in a really hot place—you expect it to also become really hot, maybe even to off into steam.  It would be really surprising if we put an ice cube in a hot oven and 10 minutes later it had not melted. This is because the ambient thermal energy is expected to be transferred to the ice cube by the energetic air molecules bouncing off it. Sure, it is possible that the air molecules just happen to bounce in a way that doesn’t impart much thermal energy—but that would be ridiculously improbable, as we learn in thermodynamics.
- The Higgs is very similar: we expect its mass to be around 125 GeV (not too far from W and Z masses), but ambient quantum energy wants to make its mass much larger through interactions with virtual particles. While it is possible that the Higgs stays light without any additional help, it’s ridiculously improbable, as we learn from quantum physics.
- the Standard Model really, really wants the Higgs to be around the 100 GeV scale. This is because it needs something to “unitarize longitudinal vector boson scattering.” It needs to have some Higgs-like state accessible at low energies to explain why certain observed particle interactions are well behaved.
- The Hierarchy problem has been the main motivation for new physics at the TeV scale for over two decades. 
- it is possible that the Higgs mass is 125 GeV due to some miraculous almost-cancellation that set it to be in just the right ballpark to unitarize longitudinal vector boson scattering. But such miracles are rare in physics without any a priori explanation. The electron mass is an excellent example. There are some apparent (and somewhat controversial) counter-examples: the cosmological constant problem is a much more severe ‘fine-tuning’ problem which may be explained anthropically rather than through more fundamental principles.
-  What are the possible ways to solve the Hierarchy problem?
- There are two main directions that most people consider:
> * Supersymmetry. Recall in our electron analogy that the solution to the ‘electron mass hierarchy problem’ was that quantum mechanics doubled the number of particles: in addition to the electron, there was also a positron. The virtual electron–positron contributions solved the problem by smearing out the electric charge. Supersymmetry is an analogous idea where once again the set of particles is doubled, and in doing so the loop contributions of one particle to the Higgs are cancelled by the loop contributions of its super-partner. Supersymmetry has deep connections to an extension of space-time symmetry since it relates matter particles to force particles.
> * Compositeness/extra dimensions. The other solution is that maybe our description of physics breaks down much sooner than the Planck scale. In particular, maybe at the TeV scale the Higgs no longer behaves like a scalar particles, but rather as a bound state of two fermions. This is precisely what happens with the mesons: even though the pion is a scalar, there is no pion ‘hierarchy problem’ because as you probe smaller distances, you realize the pion is actually a bound state of two quarks and it starts behaving as such. One of the beautiful developments of theoretical physics in the 1990s and early 2000s was the realization that this is precisely what is being described by theories of extra dimensions through the so-called holographic principle.
- An important feature of nature that puzzles scientists like myself is known as the hierarchy, meaning the vast discrepancy between aspects of the weak nuclear force and gravity. There are several different ways to describe this hierarchy, each emphasizing a different feature of it. Here is one:
- The mass of the smallest possible black hole defines what is known as the Planck Mass. 
-     The masses of the W and Z particles, the force carriers of the weak nuclear force, are about 10,000,000,000,000,000 times smaller than the Planck Mass. Thus there is a huge hierarchy in the mass scales of weak nuclear forces and gravity.
- When faced with such a large number as 10,000,000,000,000,000, ten quadrillion, the question that physicists are naturally led to ask is: where did that number come from? It might have some sort of interesting explanation.
- But while trying to figure out a possible explanation, physicists in the 1970s realized there was actually a serious problem, even a paradox, behind this number. The issue, now called the hierarchy problem, has to do with the size of the non-zero Higgs field, which in turn determines the mass of the W and Z particles.
- The non-zero Higgs field has a size of about 250 GeV, and that gives us the W and Z particles with masses of about 100 GeV. But it turns out that quantum mechanics would lead us to expect that this size of a Higgs field is unstable, something like (warning: imperfect analogy ahead) a vase balanced precariously on the edge of a table. With the physics we know about so far, the tendency of quantum mechanics to jostle — those quantum fluctuations I’ve mentioned elsewhere — would seem to imply that there are two natural values for the Higgs field — in analogy to the two natural places for the vase, firmly placed on the table or smashed on the floor. Naively, the Higgs field should either be zero, or it should be as big as the Planck Energy, 10,000,000,000,000,000 times larger than it is observed to be. Why is it at a value that is non-zero and tiny, a value that seems, at least naively, so unnatural? This is the hierarchy problem.
- Many theoretical physicists have devoted significant fractions of their careers to trying to solve this problem. Some have argued that new particles and new forces are needed (and their theories go by names such as supersymmetry, technicolor , little Higgs, etc.) Some have argued that our understanding of gravity is mistaken and that there are new unknown dimensions (“extra dimensions”) of space that will become apparent to our experiments at the Large Hadron collider in the near future. Others have argued that there is nothing to explain, because of a selection effect: the universe is far larger and far more diverse than the part that we can see, and we live in an apparently unnatural part of the universe mainly because the rest of it is uninhabitable — much the way that although rocky planets are rare in the universe, we live on one because it’s the only place we could have evolved and survived. There may be other solutions to this problem that have not yet been invented.
- Many of these solutions — certainly all the ones with new particles and forces or with new dimensions — predict that new phenomena should be visible at the Large Hadron Collider. 
- By the way, you will often read the hierarchy problem stated as a problem with the Higgs particle mass.  This is incorrect.  The problem is with how big the non-zero Higgs field is.  (For experts — quantum mechanics corrects not the Higgs particle mass but the Higgs mass-squared parameter, changing the Higgs field potential energy and thus the field’s value, making it zero or immense.  That’s a disaster because the W and Z masses are known.  The Higgs mass is unknown, and therefore it could be very large — if the W and Z masses were very large too.  So it is the W and Z masses — and the size of the non-zero Higgs field — that are the problem, both logically and scientifically.)
- Either new particles are keeping the Higgs boson light, or the universe is oddly fine-tuned for our existence. 
- When Victor Weisskopf sat down in the early 1930s to compute the energy of a solitary electron, he had no way of knowing that he’d ultimately discover what is now known as the electroweak hierarchy problem. Revisiting a familiar puzzle from classical electrodynamics – that the energy stored in an electron’s own electric field diverges as the radius of the electron is taken to zero (equivalently, as the energy cutoff of the theory is taken to infinity) – in Dirac’s recently proposed theory of relativistic quantum mechanics, he made a remarkable discovery: the contribution from a new particle in Dirac’s theory, the positron, cancelled the divergence from the electron itself and left a quantum correction to the self-energy that was only logarithmically sensitive to the cutoff. 
-  the coupling between the Higgs boson and other particles of the Standard Model (SM) leads to yet another divergent self-energy, for which the logic of naturalness implied new physics at around the TeV scale. Thus the electroweak hierarchy problem was born – not as a new puzzle unique to the Higgs, but rather the latest application of Weisskopf’s wildly successful logic (albeit one for which the answer is not yet known). 
- History suggested two possibilities. As a scalar, the Higgs could only benefit from the sort of cancellation observed among fermions if there is a symmetry relating bosons and fermions, namely supersymmetry. Alternatively, it could be a light product of compositeness, just as the pions and kaons are light bound states of the strong interactions. These solutions to the hierarchy problem came to dominate expectations for physics beyond the SM, with a sharp target – the TeV scale – motivating successive generations of collider experiments. Indeed, when the physics case for the LHC was first developed in the mid-1980s, it was thought that new particles associated with supersymmetry or compositeness would be much easier to discover than the Higgs itself. But while the Higgs was discovered, no signs of supersymmetry or compositeness were to be found.
- In the meantime, other naturalness problems were brewing. The vacuum energy – Einstein’s infamous cosmological constant – suffers a divergence of its own, and even the finite contributions from the SM are many orders of magnitude larger than the observed value. Although natural expectations for the cosmological constant fail, an entirely different set of logic seems to succeed in its place. To observe a small cosmological constant requires observers, and observers can presumably arise only if gravitationally-bound structures are able to form. As Steven Weinberg and others observed in the 1980s, such anthropic reasoning leads to a prediction that is remarkably close to the value ultimately measured in 1998. To have predictive power, this requires a multitude of possible universes across which the cosmological constant varies; only the ones with sufficiently small values of the cosmological constant produce observers to bear witness.
- An analogous argument might apply to the electroweak hierarchy problem: the nuclear binding energy is no longer sufficient to stabilise the neutron within typical nuclei if the Higgs vacuum expectation value (VEV) is increased well above its observed value. If the Higgs VEV varies across a landscape of possible universes while its couplings to fermions are kept fixed, only universes with sufficiently small values of the Higgs VEV would lead to complex atoms and, presumably, observers. Although anthropic reasoning for the hierarchy problem requires stronger assumptions than for the cosmological-constant problem, its compatibility with null results at the LHC is enough to raise questions about the robustness of natural reasoning. 
- The success of the relaxion hypothesis in solving the hierarchy problem hinges on an array of other questions involving gravity. Whether the relaxion potential can remain sufficiently smooth over the vast trans-Planckian distances in field space required to set the value of the weak scale is an open question, one that is intimately connected to the fate of global symmetries in a theory of quantum gravity (itself the target of active study in what is known as the Swampland programme).
- the recognition that cosmology might play a role in solving the hierarchy problem has given rise to a plethora of new ideas. For instance, in Raffaele D’Agnolo and Daniele Teresi’s recent paradigm of “sliding naturalness”, the Higgs is coupled to a new scalar whose potential features two minima. In the true minimum, the cosmological constant is large and negative, and the universe would crunch away into oblivion if it ended up in this vacuum. In the second, local minimum, the cosmological constant is safely positive (and can be made compatible with the small observed value of the cosmological constant by Weinberg’s anthropic selection). The Higgs couples to this scalar in such a way that a large value of the Higgs VEV destabilises the “safe” minimum. During the inflationary epoch, only universes with suitably small values of the Higgs VEV can grow and expand, while those with large values of the Higgs VEV crunch away. A second scalar coupled analogously to the Higgs can explain why the VEV is small but non-zero. 
- Alternatively, in the paradigm of “Nnaturalness” proposed by Nima Arkani-Hamed and others, the multitude of SMs over which the Higgs mass varies occur in one universe, rather than many. The fact that the universe is predominantly composed of one copy of the SM with a small Higgs mass can be explained if inflation ends and reheats the universe through the decay of a single particle. If this particle is sufficiently light, it will preferentially reheat the copy of the SM with the smallest non-zero value of the Higgs VEV, even if it couples symmetrically to each copy. The sub-dominant energy density deposited in other copies of the SM leaves its mark in the form of dark radiation susceptible to detection by the Simons Observatory or upcoming CMB-S4 facility. 
- Finally, Gian Giudice, Matthew Mccullough and Tevong You have recently shown that inflation can help to understand the electroweak hierarchy problem by analogy with self-organised criticality. Just as adding individual grains of sand to a sandpile induces avalanches over diverse length scales – a hallmark of critical behaviour, obtained without tuning parameters – so too can inflation drive scalar fields close to critical points in their potential. This may help to understand why the observed Higgs mass lies so close to the boundary between the unbroken and broken phases of electroweak symmetry without fine tuning.
- Underlying Weisskopf’s natural reasoning is a long-standing assumption about relativistic theories of quantum mechanics: physics at short distances (the ultraviolet, or UV) is decoupled from physics at long distances (the infrared, or IR), making it challenging to apply a theory involving a large energy scale to a much smaller one without fine tuning. This suggests that loopholes may be found in theories that mix the UV and the IR, as is known to occur in quantum gravity. 
- While the connection between this type of UV/IR mixing and the mass of the Higgs remains tenuous, there are encouraging signs of progress.
- We have come a long way since Weisskopf first set out to understand the self-energy of the electron. The electroweak hierarchy problem is not the first of its kind, but rather the one that remains unresolved. The absence of supersymmetry or compositeness at the TeV scale beckons us to search for new solutions to the hierarchy problem, rather than turning our backs on it. In the decade since the discovery of the Higgs, this search has given rise to a plethora of novel approaches, building new bridges between particle physics, cosmology and gravity along the way. Despite the many differences among these new approaches, they share a common tendency to leave imprints on the Higgs boson. And so, as ever, we must look to experiment to show the way. 
-  The hierarchy problem, as the puzzle is called, asks why the Higgs boson is so lightweight — a hundred million billion times less massive than the highest energy scales that exist in nature. The Higgs mass seems unnaturally dialed down relative to these higher energies, as if huge numbers in the underlying equation that determines its value all miraculously cancel out.
-  The extra particles would have explained the tiny Higgs mass, restoring what physicists call “naturalness” to their equations. But after the LHC became the third and biggest collider to search in vain for them, it seemed that the very logic about what’s natural in nature might be wrong.
-  At first, the community despaired. “You could feel the pessimism,” said Isabel Garcia Garcia, a particle theorist at the Kavli Institute for Theoretical Physics at the University of California, Santa Barbara, who was a graduate student at the time. Not only had the $10 billion proton smasher failed to answer a 40-year-old question, but the very beliefs and strategies that had long guided particle physics could no longer be trusted. People wondered more loudly than before whether the universe is simply unnatural, the product of fine-tuned mathematical cancellations. Perhaps there’s a multiverse of universes, all with randomly dialed Higgs masses and other parameters, and we find ourselves here only because our universe’s peculiar properties foster the formation of atoms, stars and planets and therefore life. This “anthropic argument,” though possibly right, is frustratingly untestable.
-  Some of those who remained set to work scrutinizing decades-old assumptions. They started thinking anew about the striking features of nature that seem unnaturally fine-tuned — both the Higgs boson’s small mass, and a seemingly unrelated case, one that concerns the unnaturally low energy of space itself.
-  Their introspection is bearing fruit. Researchers are increasingly zeroing in on what they see as a weakness in the conventional reasoning about naturalness. It rests on a seemingly benign assumption, one that has been baked into scientific outlooks since ancient Greece: Big stuff consists of smaller, more fundamental stuff — an idea known as reductionism. “The reductionist paradigm … is hard-wired into the naturalness problems,” said Nima Arkani-Hamed, a theorist at the Institute for Advanced Study in Princeton, New Jersey.
- Now a growing number of particle physicists think naturalness problems and the null results at the Large Hadron Collider might be tied to reductionism’s breakdown. “Could it be that this changes the rules of the game?” Arkani-Hamed said. In a slew of recent papers, researchers have thrown reductionism to the wind. They’re exploring novel ways in which big and small distance scales might conspire, producing values of parameters that look unnaturally fine-tuned from a reductionist perspective.
- The Large Hadron Collider did make one critical discovery: In 2012, it finally struck upon the Higgs boson, the keystone of the 50-year-old set of equations known as the Standard Model of particle physics, which describes the 17 known elementary particles.
- The discovery of the Higgs confirmed a riveting story that’s written in the Standard Model equations. Moments after the Big Bang, an entity that permeates space called the Higgs field suddenly became infused with energy. This Higgs field crackles with Higgs bosons, particles that possess mass because of the field’s energy. As electrons, quarks and other particles move through space, they interact with Higgs bosons, and in this way they acquire mass as well.
- After the Standard Model was completed in 1975, its architects almost immediately noticed a problem.
- When the Higgs gives other particles mass, they give it right back; the particle masses shake out together. Physicists can write an equation for the Higgs boson’s mass that includes terms from each particle it interacts with. All the massive Standard Model particles contribute terms to the equation, but these aren’t the only contributions. The Higgs should also mathematically mingle with heavier particles, up to and including phenomena at the Planck scale, an energy level associated with the quantum nature of gravity, black holes and the Big Bang. Planck-scale phenomena should contribute terms to the Higgs mass that are huge — roughly a hundred million billion times larger than the actual Higgs mass. Naively, you would expect the Higgs boson to be as heavy as they are, thereby beefing up other elementary particles as well. Particles would be too heavy to form atoms, and the universe would be empty.
- For the Higgs to depend on enormous energies yet end up so light, you have to assume that some of the Planckian contributions to its mass are negative while others are positive, and that they’re all dialed to just the right amounts to exactly cancel out. Unless there’s some reason for this cancellation, it seems ludicrous — about as unlikely as air currents and table vibrations counteracting each other to keep a pencil balanced on its tip. This kind of fine-tuned cancellation physicists deem “unnatural.”
- Within a few years, physicists found a tidy solution: supersymmetry, a hypothesized doubling of nature’s elementary particles. Supersymmetry says that every boson (one of two types of particle) has a partner fermion (the other type), and vice versa. Bosons and fermions contribute positive and negative terms to the Higgs mass, respectively. So if these terms always come in pairs, they’ll always cancel.
- The search for supersymmetric partner particles began at the Large Electron-Positron Collider in the 1990s. Researchers assumed the particles were just a tad heavier than their Standard Model partners, requiring more raw energy to materialize, so they accelerated particles to nearly light speed, smashed them together, and looked for heavy apparitions among the debris.
- The fabric of space, even when devoid of matter, seems as if it should sizzle with energy — the net activity of all the quantum fields coursing through it. When particle physicists add up all the presumptive contributions to the energy of space, they find that, as with the Higgs mass, injections of energy coming from Planck-scale phenomena should blow it up. Albert Einstein showed that the energy of space, which he dubbed the cosmological constant, has a gravitationally repulsive effect; it causes space to expand faster and faster. If space were infused with a Planckian density of energy, the universe would have ripped itself apart moments after the Big Bang. But this hasn’t happened.
- Instead, cosmologists observe that space’s expansion is accelerating only slowly, indicating that the cosmological constant is small. Measurements in 1998 pegged its value as a million million million million million times lower than the Planck energy. Again, it seems all those enormous energy injections and extractions in the equation for the cosmological constant perfectly cancel out, leaving space eerily placid.
- In hindsight, the two naturalness problems seem more like symptoms of a deeper issue. “It’s useful to think about how these problems come about,” said Garcia Garcia in a Zoom call from Santa Barbara this winter. “The hierarchy problem and the cosmological constant problem are problems that arise in part because of the tools we’re using to try to answer questions — the way we’re trying to understand certain features of our universe.”
- 

# Le problème du lithium cosmique

*Sources*


- [Populating the periodic table: Nucleosynthesis of the elements](https://science.sciencemag.org/content/363/6426/474) - Johnson (2019)
- [The Primordial Lithium Problem](https://www.annualreviews.org/doi/10.1146/annurev-nucl-102010-130445) - Fields (2011)
- [The Cosmological Lithium Problem Revisited](https://arxiv.org/abs/1603.03864) - Bertulani et al (2016)
- [Etoile de population II](https://fr.wikipedia.org/wiki/%C3%89toile_de_population_II) - WIkipédia
- [Big-Bang Nucleosynthesis and the Baryon Density of the Universe](https://arxiv.org/pdf/astro-ph/9407006.pdf) - Copi et al (1995)
- [Big Bang Nucleosynthesis](https://pdg.lbl.gov/2019/reviews/rpp2019-rev-bbang-nucleosynthesis.pdf)  - Fields (2019)
- [Big Bang Nucleosynthesis (BBN)](https://www.astronomy.ohio-state.edu/weinberg.21/A5682/notes8.pdf) - Weinberg
- [The cosmological lithium problem](https://www.sciencedaily.com/releases/2018/10/181009102501.htm) - Science Daily (2018)

---

- La ***nucléosynthèse primordiale*** désigne le processus de formation des noyaux les plus légers dans les conditions ardentes de l'univers primordial, entre 1 s et 3 minutes (~180 s) environ après le Big Bang.
> À partir de 1 seconde après le Big Bang, la température du cosmos passe sous la barre des 10 milliards de degrés. Une séquence d'événements est alors initiée, qui mène à la synthèse de quelques éléments légers, comme ***le deutérium, l'hélium-3, l'hélium-4 et le lithium-7***.
- La théorie de la nucléosynthèse primordiale standard (Big Bang Nucleosynthesis) repose sur le modèle standard de la physique des particules ainsi que du modèle standard de la cosmologie (ΛCDM), qui modélise un univershomogène et isotrope en expansion selon les règles de la relativité générale contenant de la matière noire et de l'énergie sombre.
- Dans la théorie de la nucléosynthèse primordiale standard, les abondances des éléments légers sont encapsulées dans un unique paramètre, la ***densité de baryons cosmique***, noté η (les baryons dans ce contexte sont les protons et les neutrons), qui est normalisée par rapport à la densité de photons du fond diffus cosmologique (baryon-photon ratio). Ce rapport est de l'ordre de $10^{-9}$, ce qui veut dire que pour chaque baryon de l'univers, il y a environ 1 milliard de photons du CMB.
> La densité de photon du CMB est de 413 photons/cm3.
- Le ***problème du lithium cosmique*** désigne l'énorme différence entre nos théories et nos observations concernant l'abondance de lithium 7 dans l'univers.
> On observe 3 à 4 fois moins de lithium-7 dans l'univers que ce qui est prédit par la théorie. 
- Par contre, les abondances d'hélium et de deutérium sont reproduites avec beaucoup de succès
> Ces abondances constituent même l'un des quatre piliers observationnels du modèle du Big Bang chaud.
- Le problème du lithium est apparu lorsque les astronomes ont commencé à étudier les propriétés du rayonnement de fond diffus cosmologique à l'aide du satellite WMAP, et le désaccord entre théorie et observation est devenu de plus en plus plus important au fil des nouvelles observations (à l'époque de la première fournée de données de WMAP, il n'y avait qu'un facteur 2-3).

### Comment mesure t-on les abondances des éléments légers dans l'univers ?

- En analysant la carte du fond diffus cosmologique, on peut prédire la densité de baryons cosmiques avec une grande précision et ainsi tester la théorie de la nucléosynthèse primordiale.
> Les récentes données du satellite Planck donnent une prédiction de η = 6x10^-10, qui est en très bon accord avec les abondances observées de deutérium et d'hélium-4 de z=1000 à z=0.
- Les abondance en deutérium (un isotope de l'hydrogène constitué d'1 proton et 1 neutron) sont mesurées dans des nuages d'hydrogène très lointains (z~3) et très pauvres en éléments lourds qui sont observés sur la ligne de visée de quasars encore plus lointains. On ne peut pas mesurer les abondances en deutérium dans les étoiles, car il est entièrement détruit dans ces systèmes.
> À l'heure actuelle, ce sont les abondances qui sont (de loin) les mieux reproduites par la théorie.
- Les abondances en hélium-3 sont mesurées dans le milieu interstellaire dans la Voie Lactée, faute de pouvoir les mesurer dans des galaxies lointaines. Comme notre galaxie est riche en éléments lourds, on ne peut pas utiliser pour le moment les abondances en hélium-3 pour contraindre la période de nucléosynthèse primordiale.
- Les abondances en hélium-4 sont mesurées dans des régions de formation d'étoiles (appelées ***régions HII***) de galaxies voisines pauvres en éléments lourds (metal-poor)
- Les abondances en lithium sont principalement mesurées dans l'atmosphère (photosphère) de très vieilles étoiles (âgées de 11 à 13,5 milliards d'années) pauvres en éléments lourds présentes dans le halo stellaire de notre Galaxie. On connaît environ une centaine de ces étoiles dites de ***population II***. Les abondances observées sont relativement faibles, notamment parce que le lithium de l'atmosphère de ces étoiles est en permanence emporté dans les profondeurs par les mouvements convectifs de leur enveloppe, où il est détruit par la chaleur intense.
> Ce qu'on mesure en pratique ce sont les raies d'absorption dans le spectre de ces étoiles qui correspondent à la signature du lithium

### Quelles sont les solutions possibles au problème du lithium cosmique ?

- Soit nos prédictions théoriques (cosmologie+physique des particules) sont correctes, mais ce sont les observations astrophysiques qui sont incomplètes
> Grâce au LSST, on aura bientôt accès à une population bien plus grande d'étoiles pauvres en éléments lourds dans des galaxies proches et lointaines qui permettra d'avoir des statistiques plus fiables sur les abondances de lithium.
- Il pourrait aussi exister des processus encore inconnus au niveau de la physique nucléaire qui pourrait altérer nos prédictions sur les abondances du lithium
> Ces processus pourraient en particulier amplifier la destruction du béryllium-7. On peut vérifier cette hypothèse à l'aide d'expériences de physique nucléaire comme celles menées par la collaboration n_TOF (neutron-Time Of Flight) au CERN depuis 2018.
- Il pourrait enfin exister des solutions au-delà du modèle standard (comme la supersymmétrie par exemple) qui pourrait impliquer de nouveaux processus au niveau cosmologique ou de la physique des particules
> Ces solutions sont testées dans les accélérateurs de particules comme le LHC et du côté des expériences de détection de matière noire.

# Le principe cosmologique

- [Probing cosmic isotropy with a new X-ray galaxy cluster sample through the LX–T scaling relation](https://www.aanda.org/articles/aa/full_html/2020/04/aa36602-19/aa36602-19.html) - Migkas et al (2020)
- [Observation d'une anisotropie de l'Univers !](https://www.ca-se-passe-la-haut.fr/2020/04/observation-dune-anisotropie-de-lunivers.html) - Ca se passe là-haut
- [The CMB Dipole: Eppur Si Muove](https://arxiv.org/abs/2111.12186) - Sullivan et Scott (2021)
- [Cosmic Microwave Background Dipole](https://astronomy.swin.edu.au/cosmos/c/Cosmic+Microwave+Background+Dipole) - SAO Encyclopedia of astronomy
- [The Motion of the Local Group with Respect to the 15,000 Kilometer per Second Abell Cluster Inertial Frame](https://adsabs.harvard.edu/full/1994ApJ...425..418L) - Lauer et Postman (1994)
- [Testing the Cosmological Principle in the radio sky](https://arxiv.org/pdf/1905.12378.pdf) - Bengaly et al (2021)
- [Is the Observable Universe Consistent with the Cosmological Principle?](https://arxiv.org/abs/2207.05765) - Aluri et al (2022)
- [Cosmologists Parry Attacks on the Vaunted Cosmological Principle](https://www.quantamagazine.org/giant-arc-of-galaxies-puts-basic-cosmology-under-scrutiny-20211213/) - Quanta (2021)
- [Un intrigant anneau géant fait de sursauts gamma](https://www.futura-sciences.com/sciences/actualites/sursaut-gamma-intrigant-anneau-geant-fait-sursauts-gamma-59317/) - Futura Sciences (2015)
- [The dipole repeller](https://www.nature.com/articles/s41550-016-0036) - Hoffman et al (2017)
- [Testing the Cosmological Principle](https://indico.cern.ch/event/1036660/attachments/2241767/3801102/TestingCosmoPrinciple.pdf) - Subir Sarkar (2021)

---

- L'homogénéité (à grande échelle, ie au-delà de 70 h-1 Mpc) et l'isotropie (statistiquement parlant) de l'univers est à la base du modèle standard de la cosmologie. Autrement dit, il n'y a pas d'observateur privilégié ou de direction privilégiée dans l'univers. Où que l'on soit dans l'univers, et quelque soit la direction où l'on regarde, on devrait observer la même chose à grande échelle. Cette idée constitue le ***principe cosmologique***.
> The cosmological principle grew out of the Copernican principle, Nicolaus Copernicus’ 1543 realization that Earth is not the fixed center of creation. Not only is Earth not special, but nothing anywhere is special. 
- The universe is clearly not homogeneous on the human scale. Teleport a person one light-year from here and you’ll ruin their day. But drop the Hubble Space Telescope halfway across the universe, and it will return familiar-looking galaxy-filled images. 
- Theorists reconstruct the cosmos’s past and predict its future using a standard theoretical model based largely on general relativity, Albert Einstein’s theory of gravity. Einstein’s theory describes the interplay between matter and space-time — the bendy fabric of the universe. But Einstein’s treatment involves 10 interlinked equations and 20 variables, a system of equations that is generally too complicated to solve.

Cosmologists lean on the cosmological principle to restrict their focus to a universe acting as a smooth and symmetric fluid. By ignoring bumps of matter like galaxies and requiring the universe to expand in the same way along all three axes, the cosmological principle deletes parts of the equations and links some of the variables, dramatically simplifying the system of equations. Theorists can then predict the velocity and acceleration of the cosmos’s expansion with just two equations — the Friedmann equations, derived from Einstein’s by Alexander Friedmann, a Russian cosmologist, in 1922. It’s a bit like computing the volume of the Earth: You could fret over every mountain and ravine, or you could assume the planet is a sphere and call it a day.

### Le dipôle cosmologique

- Lorsque l'on cartographie le fond diffus cosmologique, on remarque qu'il n'est pas directement isotrope. La plus grande anisotropie de température qu'il présente est un dipole. On l'appelle le ***dipôle cosmologique*** (CMB dipole). Son amplitude (ΔT/T \~ $10^{-3}$) est plus grande que les autres fluctuations de température (ΔT/T \~ $10^{-5}$). 
> Afin d'étudier les anisotropies de l'ordre de 10-5, on doit donc soustraire la contribution du dipôle cosmologique.
- Son existence a été révélée pour la première fois par les mesures du satellite COBE dans les années 90.

*Dipôle cosmologique révélé par COBE ([Source](https://apod.nasa.gov/apod/ap010128.html))*

![COBE_dipole](https://apod.nasa.gov/apod/image/0101/dipole_cobe.jpg)

- On interprète généralement ce dipôle comme le résultat du mouvement combiné de la Terre autour du Soleil, du Soleil autour de la Voie Lactée, de la Voie Lactée dans le Groupe Local, et du Groupe Local vers un ***Grand Attracteur*** dans le référentiel du CMB (modèle proposé par Lynden Bell et al en 1988), qui génère un ***effet Doppler*** : on observe le CMB avec un décalage spectral vers le bleu dans la direction de notre mouvement et un décalage vers le rouge dans la direction opposée. 
> * Notre système solaire se déplace à environ 370 km/s par rapport au référentiel dans lequel le CMB est isotrope, et le Groupe Local se déplace à environ 630 (+-20) km/s (2,2 millions de km/h) par rapport au CMB dans la direction du super-amas de Shapley (à 600 millions d'années-lumière d'ici), à cause du Grand Attracteur (une région contenant une demi-douzaine d'amas de galaxies qui se trouve au coeur du super-amas Laniakea, à 150 millions d'années-lumière d'ici)
> * Ce Grand Attracteur est difficile à observer dans le domaine du visible parce qu'il est situé directement derrière le plan Galactique.
- Depuis 2017, on sait aussi qu'il existe une région relativement vide de matière (noire et baryonique) située dans la direction opposée du Grand Attracteur. Cette région, qu'on a appelé ***répulseur du dipôle*** (Dipole Repeller), agit de manière effective comme un répulseur sur le mouvement des galaxies avoisinantes. La force attractive causée par le Grand Attracteur (sur-densité de matière dans la direction de notre mouvement) ET la force "répulsive" causée par le répulseur du dipôle (sous-densité de matière dans la direction opposée) contribuent de manière équivalente au mouvement du Groupe Local dans l'espace, et donc au dipôle cosmologique.

*Le mouvement du Groupe Local dans son contexte cosmique (Source : Hoffman et al 2017)*

![dipole-repeller](https://user-images.githubusercontent.com/4954089/203095826-6f110b58-2853-4938-80f3-af813e76cfe7.png)

- Lorsque ce mouvement global est corrigé, le CMB est remarquablement isotrope.
- Cependant, l'isotropie du CMB (à l'échelle de 10-5) n'implique pas forcément l'isotropie de l'univers. Pour tester l'isotropie de l'univers, on a besoin d'autres mesures indépendantes, par exemple en étudiant la distribution statistique de matière dans l'univers. 

### Des structures plus grandes que l'échelle d'homogénéité

- Depuis les années 80, des relevés astronomiques révèlent l'existence d'une liste croissante de grandes structures dont la taille dépasse l'échelle maximale à partir de laquelle l'univers est sensé être homogène. L'estimation haute de cette échelle d'homogénéité est de ~370 Mpc (1,2 milliards d'années-lumière).
- La plupart de ces structures sont des ***amas de quasars*** (en anglais : large quasar group ou LQG). Ces collections de quasars font partie des plus grandes structures cosmiques connues. On pense qu'ils pourraient être les précurseurs des filaments galactiques que l'on observe dans l'univers proche.
- ***Liste des plus grandes structures cosmiques par ordre croissant de taille :***
> * Le ***grand mur de Sloan*** est une structure mesurant plus d'1,37 milliards d'années-lumière, découverte en 2003 dans les données du SDSS
> * Le ***Clowes–Campusano Large Quasar Group*** (CCLQG) est un amas de quasars constitué de 34 quasars et mesurant environ 2 milliards d’années-lumière de diamètre (~630 Mpc), découvert en 1991.
> * ***L'amas de quasars U1.11*** est une collection de 38 quasars dont le diamètre est estimé à 2,5 milliards d'années-lumière (~780 Mpc). Il a été découvert en 2011 à proximité du CCLQG dans les données du SDSS.
> * ***L'arc géant*** est une structure en forme de sourire mesurant 3,3 milliards d'années-lumière (1/28e du diamètre de l'univers observable), découverte en 2021 dans les données du SDSS. Sa taille apparente dans le ciel est aussi étendue que 20 pleines lunes. Elle se trouve à 9,2 milliards d'années-lumière d'ici (z~0.8).
> * Le ***Huge-LQG*** (Huge Large Quasar Group, « Immense grand amas de quasars ») est un amas composé de 73 quasars mesurant environ 4 milliards d'années-lumière de diamètre (~1240 Mpc), découvert en 2013 dans les données du SDSS
> * ***L'anneau géant de sursauts gamma*** (Giant GRB ring) est un grand anneau constitué par 9 sursauts gamma (hypernovae ou collisions entre étoiles à neutrons) qui s'étalerait sur environ 5,6 milliards d'années-lumière. Il a été découvert en 2015. Son diamètre apparent dans le ciel est équivalent à 70 pleines lunes.
> * Le ***Grand Mur d'Hercule-Couronne boréale*** est un filament cosmique mesurant 10 milliards d'années-lumière, découvert en 2013 dans les données d'un relevé de sursauts gamma. Il s'agit de la plus vaste et la plus massive structure cosmique connue de l'univers observable. Mais certaines études mettent en doute son existence.
- Le modèle standard de la cosmologie n'interdit pas complètement l'existence de telles structures, mais il les rend extrêmement rares.

### Conclusion

- Avec les données actuelles, on ne peut pas encore conclure que le principe cosmologique n'est pas valide. Mais dans les décennies à venir, 

- The isotropy of the late Universe and consequently of the X-ray galaxy cluster scaling relations is an assumption greatly used in astronomy. However, within the last decade, many studies have reported deviations from isotropy when using various cosmological probes; a definitive conclusion has yet to be made. New, effective and independent methods to robustly test the cosmic isotropy are of crucial importance.

referred axes noted in other astronomical surveys spanning the
electromagnetic spectrum were also found to be aligned with the CMB kinematic dipole, pointing towards
the Virgo cluster [73, 182]. The standard narrative says that these are coincidences
-  
Previous work has shown no statistically significant violation of isotropy in the obser-
vational data of Type Ia Supernova distances [4, 5, 6] and of gamma-ray bursts [7, 8, 9].
More stringent tests require the far higher number densities delivered by large galaxy sur-
veys. The simplest way to test consistency with the CMB is to measure the dipole of a
(sufficiently wide) galaxy survey, which should be aligned with the direction of the CMB
dipole [10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22]. For currently available data sets,
the matter dipole direction is not inconsistent with the CMB, but the amplitude is too large,
probably arising from the quality of current data sets. Forecasts predict that future all-sky
radio continuum surveys with the SKA should achieve the accuracy necessary to make a
stringent test of consistency with the CMB dipole [23, 24]
- ensions
have emerged within the ΛCDM model, most notably a statistically significant discrepancy in the
value of the Hubble constant, H0. Since the notion of cosmic expansion determined by a single
parameter is intimately tied to the CP, implications of the H0 tension may extend beyond ΛCDM
to the CP itself. This review surveys current observational hints for deviations from the expecta-
tions of the CP, highlighting synergies and disagreements that warrant further study. Setting aside
the debate about individual large structures, potential deviations from the CP include variations of
cosmological parameters on the sky, discrepancies in the cosmic dipoles, and mysterious alignments
in quasar polarizations and galaxy spins.
- If the Universe is not FLRW, but we view it through the prism of FLRW, cos-
mological tensions are inevitable. Interestingly, a host of fascinating observational tensions exist, including
the H0 tension [45, 51–58], the S8 tension [178–181], potentially a curvature tension [119, 296], and an
AISW tension 
- But our peculiar velocity might not fully explain the perceived lopsidedness of the CMB; the distortion could also include the effect of the whole universe drifting. If this is the case, gauging our motion against distant galaxies will give a different result than if we measure our speed against the CMB, since those galaxies will be moving too. 
-  we document a series of intriguing alignments that are surprising in a statistically homo-
geneous and isotropic universe. One curious aspect of some of these alignments is their observation over
large – potentially gigaparsecs – scales and axes that overlap with the CMB dipole direction. If not due to
experimental systematics or interstellar physics, one exciting possibility is that these features are cosmo-
logical in origin. 

# La tension de Hubble

*Sources*

- [La crise cosmique de la constante de Hubble](https://www.pourlascience.fr/sd/cosmologie/la-crise-cosmique-de-la-constante-de-hubble-19032.php) - Pour la Science (2020)
- [Exploring the Hubble tension](https://cerncourier.com/a/exploring-the-hubble-tension/) - CERN Courrier (2021)
- [La tension de Hubble : la cosmologie en crise ?](https://scienceetonnante.com/2022/02/04/la-tension-de-hubble/) - Science Etonnante (2022)
- [Tensions dans le modèle cosmologique : l’espoir d’une nouvelle génération de télescopes](https://www.pourlascience.fr/sd/cosmologie/tensions-dans-le-modele-cosmologique-l-espoir-d-une-nouvelle-generation-de-telescopes-23923.php) - Pour  la Science (2022)
- [Measurements of the Hubble Constant: Tensions in Perspective](https://arxiv.org/abs/2106.15656) - Freedman (2021)
- [JWST just made the "Crisis in Cosmology" WORSE](https://youtu.be/hps-HfpL1vc) - Dr Becky (2022)
- [In the Realm of the Hubble tension − a Review of Solutions](https://arxiv.org/abs/2103.01183) - Di Valentino et al (2021)
- [Cosmic Expansion: A mini review of the Hubble-Lemaitre tension](https://arxiv.org/abs/2105.09409) - Cyr-Racine (2021)
- [Is there really a 'crisis' in cosmology?](https://www.space.com/cosmology-crisis-age-of-the-universe) - Space.com
- [Why is there a 'crisis' in cosmology?](https://www.space.com/why-is-there-a-cosmology-crisis) - Space.com 
- [A Comprehensive Measurement of the Local Value of the Hubble Constant with 1 km s−1 Mpc−1 Uncertainty from the Hubble Space Telescope and the SH0ES Team](https://iopscience.iop.org/article/10.3847/2041-8213/ac5c5b/meta) - Riess et al (2022)
- [Damn You, Little h! (Or, Real-World Applications of the Hubble Constant Using Observed and Simulated Data)](https://www.cambridge.org/core/journals/publications-of-the-astronomical-society-of-australia/article/damn-you-little-h-or-real-world-applications-of-the-hubble-constant-using-observed-and-simulated-data/EB4B786F4500F897A589C3ED980C17F5) - Croton (2013) 
- [Hubble constant](https://www.britannica.com/science/Hubble-constant) - Encyclopedia Britannica 
- [THE HUBBLE CONSTANT](https://lweb.cfa.harvard.edu/~dfabricant/huchra/hubble/) - John Huchra (2008)
- [Slipher, galaxies, and cosmological velocity fields](https://arxiv.org/abs/1301.7286) - Peacock (2013) 
- [The Crisis in Cosmology](https://medium.com/predict/the-crisis-in-cosmology-aa6053c0c86c) - Astrophysics in progress
- [Crisis In Cosmology Gets Worse](https://www.forbes.com/sites/drdonlincoln/2021/01/05/crisis-in-cosmology-gets-worse/?sh=3fdb6d752826) - Don Lincoln (2021) 
- [How a Dispute over a Single Number Became a Cosmological Crisis](https://www.scientificamerican.com/article/how-a-dispute-over-a-single-number-became-a-cosmological-crisis/) - Scientific American (2020)
- [Cutting the Hubble constant down to size ](http://spiff.rit.edu/richmond/asras/hubble_const/hubble_const.html) - Michael Richmont (2020) 
- [L'échelle des distances](https://media4.obspm.fr/public/ressources_lu/pages_distance/impression.html) - Observatoire de Paris
- [Measurements of the Hubble constant](https://sci.esa.int/web/planck/-/60504-measurements-of-the-hubble-constant) - ESA 
- [Hubble time](https://www.oxfordreference.com/display/10.1093/oi/authority.20110803095948568) - Oxford Reference
- [Baryon Acoustic Oscillations BAO](https://www.ias.u-psud.fr/Dark_energy/presentations/castanderBAO_081124.pdf) - Slides de Francisco Javier Castander
- [Using the Tip of the Red Giant Branch As a Distance Indicator in the Near Infrared](https://iopscience.iop.org/article/10.3847/1538-4357/ab2627) - McQuinn et al (2019)
- [Sorry, Astronomy Fans, The Hubble Constant Isn't A Constant At All](https://www.forbes.com/sites/startswithabang/2019/08/02/sorry-astronomy-fans-the-hubble-constant-isnt-a-constant-at-all/?sh=2a3cb08c9d59) - Ethan Siegel (2019)
- [The Tension Cosmology](https://agenda.ciemat.es/event/1126/contributions/2119/attachments/1604/1919/divalentino.pdf) - Di Valentino (2019)

---

- À la fin des années 20, Edwin Hubble et Georges Lemaître ont indépendamment mis en évidence une loi de proportionnalité entre la vitesse de récession des galaxies v (mesurée par leur décalage vers le rouge) et leur distance d (mesurée par les Céphéides). C’est la ***loi de Hubble-Lemaître***.
> v = H0*d
- La constante de proportionnalité H0 qui lie ces deux variables (ie la pente de la droite) s’appelle la ***constante de Hubble***, en l’honneur de l’astronome Edwin Hubble, qui fut parmi les premiers chercheurs à calculer cette quantité en 1929. H0 correspond au taux d’expansion actuel de l’univers (à z=0). On la mesure dans une étrange unité : le km/s/Mpc. Autrement dit, elle a la dimension inverse d'un temps (1/t).
> * Hubble avait estimé H0 à environ 500 km/s/Mpc, ce qui correspondait à un âge de l’univers d’environ 2 milliards d’années. Cette valeur avait causé pas mal de controverses dans la communauté scientifique. Dans les années 30, la datation des roches terrestres par la radioactivité permettait d’inférer que l’âge de la Terre est d’au moins 3 milliards d’années, et l’étude de la dynamique des amas d’étoiles assignait à ces structures des âges de l’ordre de 1 à 10 milliards d’années. L’univers ne pouvait décemment pas être plus jeune que les objets qu’il contenait ! Des analyses ultérieures réaliséées au cours de la deuxième moitié du 20e siècle ont revu à la baisse la valeur de H0, qui tourne depuis autour de 50-100 km/s/Mpc. Depuis les années 80, plus de 1000 estimations de H0 ont été publiées dans la littérature scientifique. 
> * Techniquement, Georges Lemaître avait déjà produit une estimation de H0 en 1927, à partir des données observationnelles de distances de galaxies de Hubble.
> * La loi de Hubble-Lemaître était initialement nommée « loi de Hubble ». Elle a été renommée ainsi par l’Union astronomique internationale en 2018, en reconnaissance des travaux de l’astronome belge.
> * Attention, la constante de Hubble n’est pas réellement une constante au sens strict du terme. Si on observe des galaxies suffisamment lointaines, l’expansion cosmique n’est plus modélisable par une droite mais par une courbe. Autrement dit, le taux d’expansion cosmique varie au cours du temps. À un instant donné de l’histoire cosmique, ce paramètre est le même pour tout l’univers : il est constant dans l’espace. Par contre, il change de valeur au cours de l’histoire cosmique. Pour éviter toute confusion, certains astronomes préfèrent donc parler de « paramètre de Hubble ».
- Mesurer H0 nous permet d’obtenir une estimation grossière de l’âge de l’univers. En effet, si l’on considère que la vitesse de récession des galaxies est restée inchangée depuis le Big Bang (ce qui est faux), le temps entre le moment où la matière d’une galaxie donnée était dans notre voisinage et le moment où elle se trouve à sa distance actuelle est donné par 1/H0 : c’est ce qu’on appelle ***le temps de Hubble***. Pour une constante de Hubble de 71 km/s/Mpc, on obtient un temps de Hubble d’environ 14 milliards d’années.
> En pratique, comme le taux d’expansion cosmique varie au fil du temps, l’âge de l’univers est légèrement différent du temps de Hubble. Pour obtenir une estimation plus précise de l’âge de l’univers, il faut résoudre les équations de Friedmann dans un univers plat dominé par une constante cosmologique. 
- Il existe de nombreuses manières d’estimer la constante de Hubble. Certaines méthodes se basent sur l’observation de l’univers local, et d’autres sur l’univers primordial. Toutes ces estimations reposent sur la robustesse de nos estimations des distances absolues des astres. 
> * Les mesures basées sur l’univers primordial sont des prédictions du modèle ΛCDM étalonnées sur les données observées du CMB. Elles utilisent comme règle standard l’***horizon sonore***, c’est-à-dire la distance (comobile) maximum qu’a pu parcourir une onde sonore dans le plasma primordial entre le Big Bang et l’époque du découplage de la matière et du rayonnement, qui a eu lieu environ 380 000 ans après le Big Bang. La taille de l’horizon sonore permet de contraindre les paramètres cosmologiques du modèle standard.
> * Les mesures locales de H0 reposent quant à elles sur l’observation de certaines populations d’étoiles, comme les Céphéides ou certains types de géantes rouges (TRGB, ie des étoiles de faible masse qui démarrent à peine la fusion de l’hélium dans leur cœur), situées dans des galaxies relativement proches, ou de supernovæ thermonucléaires (SNIa) pour les galaxies plus lointaines. Dans certaines galaxies, la distance des supernovæ thermonucléaires peut être étalonnée par la distance des céphéides ou des étoiles TRGB. Les distances des Céphéides d’autres galaxies sont à leur tour calibrées sur les distances des Céphéides proches situées dans la Voie Lactée, qui sont elles estimées via la ***méthode des parallaxes***. Ces différentes méthodes imbriquées d’estimation de distances des astres forment ce que les astronomes appellent ***l’échelle des distances***. Une erreur sur le barreau le plus bas de l’échelle (ie la distance des étoiles proches via la méthode des parallaxes) peut se répercuter sur tous les autres barreaux!
- En 2014, suite à la publication des résultats du satellite Planck, différentes estimations de H0 ont commencé à diverger. D’abord un peu, puis de manière de plus en plus significative à mesure que les barres d’erreur se sont réduites dans les différentes méthodes. Ce problème a fini par être nommé ***la tension de Hubble***. 
> * Les estimations les plus récentes de la collaboration Planck (2018) prédisent une valeur de H0 de 67,27 ± 0.6 km/s/Mpc dans le cadre du modèle ΛCDM (univers plat). Autrement dit, une galaxie située à 1 Mpc de nous s’éloigne actuellement à une vitesse de 67,3 km/s environ. Une galaxie située à 2 Mpc, quant à elle, s’éloigne à une vitesse de 134.6 km/s. Etc, etc. Selon cette valeur de H0, l’univers serait âgé de 13,8 milliards d’années.
> * les estimations réalisées dans l’univers local à partir d’observation des Céphéides et des supernovæ thermonucléaires, quant à elles, fournissent une estimation de H0 environ 10 % plus grande, ie autour de 74.03 ± 1.42  km/s/Mpc. Selon cette valeur de H0, l’univers serait âgé de 14,5 milliards d’années.
> * D’autres estimations basées sur les étoiles TRGB parviennent à des estimations situées entre ces deux valeurs extrêmes.
- Il n’y a pour le moment aucune solution consensuelle à la tension de Hubble, ni de valeur de H0 qui pourrait servir de « référence ». Cette tension pourrait provenir d’erreurs dans nos observations, mais elle pourrait aussi être le signe que le modèle standard de la cosmologie est à réviser. Il est aussi possible qu’elle soit due à un comportement particulier de l’énergie sombre, dont la nature est encore inconnue (sa contribution pourrait varier dans le temps par exemple).

*Estimations de H0 depuis 1920. Crédit : Michael S. Turner (2021). [Source](https://www.researchgate.net/figure/Measurements-of-the-Hubble-constant-from-1920-to-2000-All-the-major-shifts-involved_fig1_356631453)*

![H0evolution](https://i.imgur.com/PezSFdu.png)

*Evolution de la tension de Hubble au fil des ans. Crédit : Cyr-Racine (2021). [Source](https://arxiv.org/pdf/2105.09409.pdf)*

![H0](https://i.imgur.com/AjK9qEf.png)

*L'échelle des distances en astronomie. Crédit : NASA, ESA, A. Feild (STScI), and A. Riess (STScI/JHU). [Source](https://esahubble.org/images/heic1611a/)*

![distanceladder](https://cdn.spacetelescope.org/archives/images/large/heic1611a.jpg)

# L'asymétrie entre matière et antimatière

*Sources*

- [L’apparition de la matière et la baryogénèse](https://www.astronomes.com/le-big-bang/naissance-matiere) – Astronomie et Astrophysique (2019)
- [Antimatière](https://fr.wikipedia.org/wiki/Antimati%C3%A8re#%C2%AB_Victoire_%C2%BB_de_la_mati%C3%A8re_par_violation_de_CP) - Wikipédia
- [How Do We Know Antimatter Is Absent?](http://www.slac.stanford.edu/econf/C040802/papers/L017.PDF) – SLAC Summer Institute on Particle physics (2004)
- [Antimatter : Anything out there?](https://www.nature.com/articles/nphys2308) - Georgescu (2012)
- [L’asymétrie matière-antimatière (à la recherche de l’antimatière perdue)](https://indico.in2p3.fr/event/8801/attachments/37978/46891/Justine_Serrano_Antimatiere.pdf) Conférence de Justine Serrano (2013)
- [Baryogenesis](https://en.wikipedia.org/wiki/Baryogenesis) - Wikipédia
- [BARYOGENESIS](https://arxiv.org/pdf/hep-ph/0609145.pdf) Cline (2006)
- [Baryogenesis and Leptogenesis](https://www.slac.stanford.edu/econf/C040802/papers/L018.PDF) – Trodden, SLAC Summer Institute on Particle physics (2004) 
- [Baryogenesis: A small review of the big picture](https://arxiv.org/abs/1411.3398) – Balazs (2014) 
- [What exactly is CP violation?](https://www.quantumdiaries.org/2011/11/14/what-exactly-is-cp-violation/) - Quantum diaries
- [Symétrie C](https://fr.wikipedia.org/wiki/Sym%C3%A9trie_C) - Wikipédia
- [Symétries](http://lappweb.in2p3.fr/~buskulic/cours/PHYS805/PHYS805_Chapitre4.pdf) – Cours de Damir Buskulic
- [CP violation](https://www.britannica.com/science/CP-violation) – Encyclopedia Brittanica
- [Une brève histoire de l’univers](https://books.google.com/books?id=sNHF8e7tJD8C&pg=PA102&lpg=PA102&dq=%C3%A9tat+hors+d%27%C3%A9quilibre+sakharov&source=bl&ots=8p5QVdqCEo&sig=ACfU3U1DMWsD3O3tc4jMqyuG77A07lpnig&hl=fr&sa=X&ved=2ahUKEwj66eKP8PjjAhXxAGMBHfY-DjIQ6AEwDnoECAYQAQ#v=onepage&q=%C3%A9tat%20hors%20d'%C3%A9quilibre%20sakharov&f=false) – Joe Silk
- [Madame Wu and the Holiday Experiment That Changed Physics Forever](https://gizmodo.com/madame-wu-and-the-holiday-experiment-that-changed-physi-1749319896) – Gizmodo (2015)
- [Toward a history of explanation in science communication: the case of Madame Wu experiment on parity violation](https://jcom.sissa.it/archive/16/03/JCOM_1603_2017_A10) - Bertozzi (2017)
- [Symétrie CP](http://feynman.phy.ulaval.ca/marleau/pp/10cpt/sym_cp.html) – Cours de Luc Marleau
- [Les neutrinos, la clé de l’asymétrie matière-antimatière ?](https://www.pourlascience.fr/sd/physique-particules/les-neutrinos-la-cle-de-lasymetrie-matiere-antimatiere-19318.php)

---

- Aujourd’hui on prend la matière (protons, neutrons, électrons...) comme un acquis. Mais elle n’a pas toujours existé comme tel !
- Le modèle standard de la physique des particules contient 12 particules élémentaires : 6 quarks et 6 leptons
- A chacune de ces particules de matière correspond une particule d’***antimatière*** : une particule d’antimatière a la même masse et les mêmes nombres quantiques que sa particule de matière correspondante, mais une charge électrique opposée.
> En 1928, Paul Dirac décrit le comportement des électrons dans l’équation qui porte aujourd’hui son nom. Sauf que son équation a 2 solutions ! La 2e solution correspond à une particule de charge opposée. Dirac invente alors le concept de ***positron*** (ou anti-électron) en 1930. 2 ans plus tard, on en découvre dans les rayons cosmiques (Prix Nobel 1936)
- Si l’on fait s’entrechoquer des particules de matière avec leurs antiparticules, elles s’annihilent et convertissent l’intégralité de leur masse en photons. (E=mc² ! Si on a assez d’énergie on peut créer de la matière, et toute matière de masse m contient une énergie au repos E/c²)
> 1 positron + 1 électron < - > 2 photons
- Il n’y a quasiment plus d’antimatière dans l’univers aujourd’hui. 
> On en trouve sous forme de traces dans les rayons cosmiques qui entrent en collision avec l’atmosphère. Ils sont issus de la collision entre particules comme des baryons (particules composées de 3 quarks, comme des protons et des neutrons), des leptons (particules élémentaires de spin 1/2 insensibles à l'interaction forte) ou des photons. On en produit aussi dans nos accélérateurs de particules.
- Mais ça n’a pas été toujours le cas ! Juste après l’inflation, l’énergie dans lequel l’univers baignait après le réchauffement aurait dû produire autant de matière que d’antimatière !
> Les baryons auraient du s’annihiler avec leurs antiparticules, en ne laissant qu’une abondance négligeable de baryons. Mais ce n’est pas ce qu’on observe.
- L’origine de cette asymétrie entre matière et antimatière est aujourd’hui un mystère, et un sujet de recherche très actif.
> * Toute asymétrie de baryons qui existerait avant l’inflation devrait avoir été diluée et deveniu négligeable pendant l’inflation, à cause de la production d’entropie qui a lieu pendant le réchauffement.
> * Aucun processus connu dans le modèle standard n’est capable de produire une telle asymétrie. Il faut donc étendre le modèle standard pour construire une explication.
- Si les lois de la nature traitent les particules de la matière de la même manière que les particules d’antimatière, les physiciens disent qu’elles respectent la symétrie CP (Charge-Parité). Sinon, ils disent que la symétrie CP est brisée.
> * Une symétrie en physique, c’est une transformation qui agit sur un système physique et qui laisse ce système inchangé.
> * CP est la combinaison de 2 symétries fondamentales : la conjugaison de charge (C) et la parité (P)
- La conjugaison de charge est une transformation mathématique qui change la valeur de la charge / remplace une particule par son antiparticule : Q → -Q (ex : un électron devient un positron)
> Une théorie possède la symétrie C si elle est invariante sous la conjugaison de charge. L’électromagnétisme, la gravitation et l’interaction forte obéissent à la symétrie de charge, mais l’interaction faible brise la symétrie C. 
- La parité (qu’on appelle aussi inversion de l’espace) est une transformation mathématique qui change les coordonnées spatiales d’un système en son symétrique par rapport à l’origine des coordonnées : (x,y,z) → (-x,-y,-z) 
> Une théorie possède la symétrie P si elle est invariante sous la conjugaison de parité. La parité est conservée dans l’électromagnétisme, la gravitation et l’interaction forte, mais elle est violée dans l’interaction faible. Ça veut dire que certains atomes radioactifs se désintègrent de façon asymétrique : l’électron est préférentiellement éjecté dans une direction précise par rapport au spin du noyau (montrée en 1956 sur des atomes de Cobalt 60 par l’expérience de Chien-Shiung Wu). Certaines réactions se produisent donc moins souvent que leur image dans un miroir (analogie intuitive mais limitée).
- CP transforme un électron de spin up en positron de spin down
> L’interaction faible est la seule interaction qui brise la symétrie CP
- Selon Sakharov (1967), tout modèle d’émergence de la matière (baryogénèse) doit remplir les 3 conditions suivantes pour générer une asymétrie entre matière et antimatière :
> * ***Violation du nombre baryonique B*** : certains processus physiques doivent créer plus de matière que d’antimatière 
> * ***Brisure de la symétrie CP***
> * ***L’univers doit être hors de l’équilibre thermique***, ce qui est une conséquence logique de son expansion
- Les 3 ***conditions de Sakharov*** sont satisfaites dans le modèle standard, mais l’asymétrie prédite par le modèle standard est trop faible pour expliquer les observations.
- Nos théories cosmologiques n’excluent pas la possibilité qu’il reste des régions / îlots dans l’univers constituées d’antimatière.
> La matière et l’antimatière émettent des photons de même longueur d’onde, donc la lumière des galaxies lointaines ne nous aide pas vraiment. Par contre à la frontière entre les régions de matière et les régions d’antimatière on devrait voir de l’annihilation donc un fort signal dans le domaine des rayons gamma, mais on n’a détecté aucun signal de ce type à ce jour. Si ces régions existent, elles sont aussi grandes que l’univers observable, mais on ne connaît pas de mécanisme plausible pour séparer les baryons et les antibaryons à de telles échelles.

*Particules du modèle standard de la physique des particules (Source : Wikipédia)*

![particules](https://i.imgur.com/Sb18hJB.png)

# La nucléosynthèse primordiale

*Sources*

- [Nucleosynthesis, star formation and evolution (part 1)](https://youtu.be/gsZ1vVs2T3o) - Cyril Georgy (Février 2016)
- [Primordial Nucleosynthesis](https://arxiv.org/pdf/1707.01004.pdf) - Coc et Vangioni (2017)
- [Primordial nucleosynthesis: A cosmological point of view](https://aip.scitation.org/doi/pdf/10.1063/1.4875284?class=pdf) - Mathews (2014)
- [La nucléosynthèse primordiale](https://www.astronomes.com/le-big-bang/nucleosynthese-primordiale) - Astronomie et astrophysique (Août 2017)
- [Primordial Nucleosynthesis in the Precision Cosmology Era](https://arxiv.org/ftp/arxiv/papers/0712/0712.1100.pdf) - Steigman, Annual Review of nuclear and particle science (2007)
- [Nucleosynthesis in the Big Bang](https://maken.wikiwijs.nl/userfiles/dad1a88ff2d4b138a92572a1246e0866.swf) - Animation interactive
- [BIG-BANG NUCLEOSYNTHESIS](http://pdg.lbl.gov/2016/reviews/rpp2016-rev-bbang-nucleosynthesis.pdf) Fields, Molaro et Sarkar (2016)
- [Hydrogène](https://fr.wikipedia.org/wiki/Hydrog%C3%A8ne#cite_note-Biologie-7) - Wikipédia

---

- Après l'anihilation de l'antimatière, l'univers est dominé par le rayonnement dont la longueur d'onde s'étend en même temps que l'univers. La température diminue au fil du temps.
- Pendant les 20 premières minutes qui ont suivi le Big Bang, l'univers est juste assez chaud et dense que des réactions nucléaires ont pu avoir lieu, ce qui a donné naissance aux premiers noyaux d'atomes : hélium 4, hélium 3, deutérium et lithium 7 (et quelques traces d'éléments légèremet plus lourds). 
> * Les protons et les neutrons se combinent sous l'action de la force nucléaire forte
> * Noyau de deutérium  = un proton et un neutron (aussi appelé deutéron)
> * Noyau d'hélium 3 = deux protons et un neutron
> * Noyau d'hélium 4 = deux protons et deux neutrons
- La nucléosynthèse primordiale commence quelques minutes après le Big Bang (~200s, ie ~3 minutes), lorsque la température de l’Univers descend sous la barre du milliard de degrés, et que les photons deviennent trop peu énergétiques pour casser la liaison interne des noyaux tentent de se former.
> Les premiers noyaux de deutérium se forment dès 1s après le Big Bang (T=10GK), mais ils sont instantanément détruits par les photons environnants (photodissociation).
> Le début de la nucléosynthèse primordiale correspond à l'époque où la formation des premiers noyaux de deutérium dépasse leur destruction
- La nucléosynthèse primordiale se termine ~20min après le Big Bang, lorsque la densité et la température sont trop basses pour que les réactions de fusion continuent
> A partir de ce moment, il n'y a plus de neutrons libres (ils sont presque tous dans des noyaux d'hélium 4), et la barrière coulombienne est suffisante pour repousser les protons entre eux.
- A la fin de la nucléosynthèse primordiale, la matière (baryonique) dans l'univers est composée à 75% d'hydrogène, à 25% d'hélium-4, à 0.01% de deuterium et d'hélium-3, de quelques traces (de l'ordre de $10^{−10}$) de lithium, et de quantités négligeables d'éléments plus lourds (fraction en masse).
> Le fait qu'il n'existe pas de noyaux stables avec un nombre de particules de 5 ou 8 empêche la formation d'un nombre significatif de noyaux plus lourds pendant la nucléosynthèse primordiale. Elle s'arrête avant que des noyaux avec A>=12 puissent être créés. 
- La nucléosynthèse primordiale est l'une des 3 "preuves" du modèle du Big Bang (un des 3 pilliers de la cosmologie moderne), avec l'expansion de l'univers et le fond diffus cosmologique (CMB).
- Il y a un très bon accord entre les abondances observées et prédites par la théorie d'hélium 4, d'hélium 3, de deutérium et de lithium 7, ce qui est particulièrement remarquable car ces abondances (en nombres d'atomes par atome d'hydrogène) couvrent 9 ordres de grandeur.
- *Controverse :* Il y a un facteur 3 de différence entre les abondances primordiales de lithium observées et prédites, qui n'a pas encore d'explication consensuelle (problème du lithum).
- Sans la nucléosynthèse primordiale, il n'y aurait pas de neutrons dans l'univers aujourd'hui vu que la durée de vie d'un neutron libre est de 15 minutes.
>  le neutron se désintègre en un proton, un électron et un antineutrino électronique (désintégration béta)
- L'hydrogène représente 63 % des atomes et 10 % de la masse du corps humain. Ces atomes sont aussi vieux que le cosmos !
- 99 % des atomes de la voie lactée sont de l’hydrogène (90%) et de l’hélium (9%). En masse : Hydrogène 70 %, Hélium 28 % 
- ***Note sur les temps utilisés dans l'univers primordial*** : Les repères temporels mentionnés ci-dessus dépendent des modèles. La grandeur la plus fiable pour calculer l'évolution des grandeurs quand on fait de la cosmologie primordiale c'est la température de l'univers.

# La croissance des trous noirs supermassifs

*Sources*

- [Supermassive black holes in the early universe](https://www.tandfonline.com/doi/full/10.1080/00107514.2019.1615715?scroll=top&needAccess=true&role=tab) - Smith et Bromm (2019)
- [Origin of supermassive black holes](https://arxiv.org/abs/0709.0070) - Dokuchaev et al (2007)
- [Titans of the Early Universe: The Prato Statement on the Origin of the First Supermassive Black Holes](https://arxiv.org/abs/1810.12310) - Woods et al (2018)
- [Formation and growth of the first supermassive black holes](https://www.theses.fr/2017PA066386) - Thèse de Tilman Hartwig (2017)
- [The Assembly of the First Massive Black Holes](https://www.annualreviews.org/doi/abs/10.1146/annurev-astro-120419-014455) - Inayoshi et al (2020)
- [Breaking the limit: Super-Eddington accretion onto black holes and neutron stars](https://arxiv.org/abs/1903.06844) - Brightman et al (2019)
- [The extremes of accretion : understanding super-Eddington accretion and feedback phenomena in Ultraluminous X-ray Sources](https://theses.hal.science/tel-03689746/) - Thèse de Andrés Gúrpide Lasheras (2022)
- [Supermassive Black Holes with High Accretion Rates in Active Galactic Nuclei. IX. 10 New Observations of Reverberation Mapping and Shortened Hβ Lags](https://iopscience.iop.org/article/10.3847/1538-4357/aaae6b) - Du et al (2018)
- [Un univers de disques](https://www.pourlascience.fr/sd/astrophysique/un-univers-de-disques-1384.php) - Pour la Science (2004)
- [Revealing the Origin and Cosmic Evolution of Supermassive Black Holes](https://arxiv.org/abs/1910.06346) - Woods et al (2019)
- [Observational evidence for intermediate-mass black holes](https://arxiv.org/abs/1705.09667) - Mezcua (2017)

---

- Il existe une grande variété de trous noirs dans l’univers. Certains peuvent être théoriquement aussi légers que la masse de Planck ( $10^{-8}$ kg), tandis que d’autres peuvent atteindre plusieurs dizaines de milliards de masses solaires. Astrophysiquement parlant, on distingue 3 types de trous noirs en fonction de leur masse :
> * ***Les trous noirs stellaires*** : entre 3 et 100 masses solaires
> * ***Les trous noirs intermédiaires*** (IMBH) : entre 100 et $10^{5}$ masses solaires
> * ***Les trous noirs supermassifs*** (SMBH) : entre $10^6$ et $10^{10}$ masses solaires
- La formation des trous noirs stellaires est aujourd’hui relativement bien comprise. On sait qu’ils proviennent de la mort explosive des étoiles massives. Par contre, la formation des trous noirs supermassifs et intermédiaires constitue un mystère à résoudre.
- L’un des plus grands obstacles à une compréhension de la formation des SMBH est la découverte de quasars (noyaux actifs de galaxies) de plusieurs milliards de masses solaires qui existaient lorsque l’univers n’était âgé que de 800 millions d’années (z ~ 6 - 7). Comment ces trous noirs ont-ils pu acquérir une si grosse masse si peu de temps ?
> On a même découvert un quasar de près de 10 milliards de masses solaires (SDSS J010013.02+280225.8) à z ~ 6,3.
- Pour modéliser la croissance des SMBH, on peut jouer sur essentiellement deux paramètres : la masse initiale des premières « graines » de trous noirs, et le taux d’accrétion de matière.
- En pratique, il existe une limite physique à la vitesse à laquelle un trou noir peut accréter de la matière : le ***taux d’accrétion d’Eddington*** (Eddington accretion rate).
> * Une particule de gaz qui tombe dans un trou noir émet une partie de son énergie sous forme de rayonnement, et le reste alimente le trou noir en matière. Par conséquent, plus le taux d’accrétion est grand, plus la pression de radiation est grande. Au-delà d’une certaine limite, la pression de radiation est suffisante pour contrer la gravité et le gaz est éjecté hors de l’astre. Le taux d’accrétion d’Eddington correspond donc au taux de croissance maximal d’un trou noir.
> * Le calcul du taux d’accrétion d’Eddington requiert quelques simplifications, en particulier le fait que l’accrétion est un processus à symétrie sphérique. En pratique, cette condition n’est pas vérifiée. Dans ce cadre, le taux d’accrétion d’Eddington peut être dépassé. On parle alors d’***accrétion super-Eddington***. À ce jour, une poignée de noyaux actifs de galaxies ont été observé présentant un tel mode d’accrétion (super-Eddington accreting massive black holes, SEAMBHs). C’est aussi le cas de la majorité de ce qu’on appelle des ***sources X ultralumineuses*** (ULX). Par contre, la nature de ces sources reste encore inconnue.
- Une autre barrière à l’accrétion de matière est la conservation du moment cinétique, qui empêche la matière de tomber directement dans le trou noir mais forme plutôt un disque d’accrétion dont la rotation contre la force de gravité.
- Un autre problème concerne la nature des premières graines de SMBH de l’histoire du cosmos. Plusieurs scénarios sont envisagés :
> * ***L’effondrement des étoiles de population III*** (remnants of PopIII stars) : On pense que les premières étoiles (dites de ***Population III***) se sont formées au cours des 100-200 premiers millions d’années après le Big Bang (z ~20 – 30), à partir de mini-halos de matière noire remplis de gaz d’hydrogène moléculaire. Ces étoiles étaient extrêmement massives (10-1000 masses solaires) comparées aux étoiles actuelles, et ont donc pu donner naissance à des graines de trous noirs de quelques dizaines à quelques centaines de masses solaires tout au plus (après un temps de vie inférieur à 3 millions d’années). Ces graines auraient ensuite pu fusionner et/ou accréter du gaz pour donner naissance à des SMBH. Il y a plusieurs problèmes avec ce scénario. D’une part, il requiert des conditions extrêmes d’accrétion ou des masses de graines de trous noirs trop massives pour correspondre aux observations. Ainsi, un trou noir qui accrète constamment de la masse au taux d’accrétion d’Eddington double sa masse en une quarantaine de millions d’années, et peut passer d’une masse solaire à quelques milliards en un milliard d’années, soit beaucoup plus que les 800 millions d’années des quasars observés. De plus, on s’attend à ce que ces trous noirs « naissent affamés » (born starving) : les supernovae dont ils sont issus ont éjecté une bonne partie du gaz environnant loin d’eux, et les rayonnements ionisants (UV) produits par leurs disques d’accrétion ont tendance à chauffer le gaz alentour et à le repousser (outflows). Tous ces processus constituent des freins à l’accrétion de gaz sur ces graines de SMBH, du moins initialement. Pour faire grandir ces graines de trous noirs suffisamment pour correspondre aux observations, il faudrait qu’ils trouvent un moyen d’accréter de la matière à des taux super-Eddington suite à leur naissance.
> * ***L’effondrement de nuages de gaz*** (direct collapse black holes, DCBH) : un nuage de gaz proto-galactique qui ne contient pas d’éléments plus lourds que l’hélium (metal-free) et qui baigne dans une mer de rayonnement UV suffisamment énergétique pour briser l’hydrogène moléculaire en ses composants atomiques (photodissociation) est incapable de se fragmenter en nuages plus petits qui donneraient d’ordinaire naissance à des étoiles « normales ». En effet, le seul moyen pour ce nuage de se refroidir est via l’émission de certaines raies de l’atome d’hydrogène (comme la raie Lyman-alpha). Dans ces conditions très spécifiques, ce nuage (atomic cooling halo) s’effondre de manière monolithique et forme ce qu’on appelle une ***étoile supermassive*** (supermassive star, SMS) de $10^5$ - $10^6$ masses solaires qui finit par donner naissance à une graine de SMBH de $10^4$ à $10^6$ masses solaires (masse typique : $10^5$ masses solaires).
> * ***L’effondrement des cœurs d’amas d’étoiles*** (runaway core collapse in star clusters) : certains amas d’étoiles ont un cœur si dense que les collisions entre les étoiles ne sont pas rares. Ces fusions stellaires rapides peuvent donner naissance à des étoiles très massives, qui produisent à la fin de leur vie des trous noirs intermédiaires de plus de 1000 masses solaires. Ces derniers pourraient alors accréter du gaz jusqu’à atteindre $10^5$ masses solaires tout au plus. Ce scénario ne permet donc pas encore de former des SMBH.
> * ***Les trous noirs primordiaux*** : ces trous noirs hypothétiques pourraient avoir été formé à partir de fluctuations quantiques qui avaient lieu dans l’univers primordial. Leur masse initiale pourrait être aussi petite que la masse de Planck, et ils auraient pu grandir dans les régions centrales des galaxies. On ne sait que peu de choses sur ces trous noirs primordiaux et sur la manière dont ils accrètent de la matière.
- La prochaine génération de télescopes devrait nous en dire plus sur la nature des premiers SMBH et leurs modes de croissance.
> * Des observations du cosmos via la raie à 21 cm de l’hydrogène par le SKA vont contraindre le contenu en gaz primordial lors des âges sombres et de l’époque de la réionisation.
> * Le JWST va notamment pouvoir détecter les traces des premiers SMBH, et va notamment être utilisé pour chercher des potentiels DCBHs.
> * On estime qu’1 % des fusions de trous noirs détectés par LIGO pourraient provenir des rémanents des premières étoiles. Le développement de l’astronomie multi-messagers pourra donc contribuer à notre compréhension de ces objets.

*Scénarios possibles de formation de trous noirs supermassifs. Crédit : [Mezcua 2017](https://arxiv.org/abs/1705.09667)*

![pathwaysSMBH](https://i.imgur.com/BsjYHQe.png)

# L'ajustement fin de l'univers

*Sources*

- [Fine-tuning](https://plato.stanford.edu/archives/fall2017/entries/fine-tuning/) - Stanford Encyclopedia of Philosophy
- [In What Sense Is the Early Universe Fine-Tuned?](https://authors.library.caltech.edu/47263/1/1406.3057v1.pdf) - Carroll (2014)
- [The Fine-Tuning Argument](https://core.ac.uk/download/pdf/33752944.pdf) - Landsman (2015)

---


