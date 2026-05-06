# Techniques-Used-In-The-Evolution-of-Transistor-Architecture
My research report is on the evolution of transistor architecture from MOSFET/CMOS→FinFET→GAAFET, specifically on the gate formation and its effects on yield and electrostatic control. This report outlines major nanofabrication techniques used in the design and fabrication of transistors and their gates. The techniques described in this report are shown below, along with the abstract and conclusion for convenience.

MOSFET/CMOS:\
STI (Shallow Trench Isolation)\
Gate Oxidation\
Polysilicon Gate Patterning\

FinFET:\
SADP/SAQP (Self Aligned Double/Quadruple Patterning)\
High-k/Metal Gate\
3D Etching Techniques\
Spacer Engineering\

GAAFET:\
Epitaxial Si/SiGe SuperLattice Stack Formation\
Inner Spacer Formation\
Conformal ALD (Atomic layer deposition)\
BDI (Bottom Dielectric Isolation)\

Abstract:

  Historically, Moore’s Law followed a two-year transistor density doubling cadence;
however, the constraints of economics, thermodynamics and physics have extended this cadence
to nearly three years or longer. Therefore, as we continue to scale transistors, we will need
advancements in nanofabrication techniques to further reduce dimensions of devices. This report
reviews the transition of device architectures based on fabrication improvements from Planar
MOSFETs to FinFETs and Gate-All-Around FETs (GAAFETs). We focus our review on the
process innovations responsible for transitioning from one architecture to another. Planar CMOS
provided the basic framework for fabricating the first CMOS chips using Shallow Trench
Isolation (STI); STI replaced LOCOS to prevent bird's beak encroachment into shallow trench
isolation and provide sub 250nm isolation. Thermal gate oxidation using the Deal-Grove model
defined the Si/SiO2 interface quality at the root of transistor reliability. Anisotropic reactive ion
etch (RIE) was used to pattern self-aligned polysilicon gates eliminating gate-to-source/drain
misalignment as a potential yield loss mechanism. Once gate lengths fell below forty nanometers
due to the limitations of lithographic resolution and short channel effects in MOSFETs, a
transition to a three-dimensional structure became necessary. The ability to create FinFETs was
made possible due to advances in self-aligned double and quadruple patterning (SADP/SAQP),
which extended 193 nm immersion lithography below its resolution limits; high-k/metal gate
(HKMG) stacks formed using atomic layer deposition (ALD), replacing the traditional SiO2 with
HfO2 and reducing the gate leak current; anisotropic reactive ion etching (RIE) forming
vertically oriented fins with high aspect ratios; and highly accurate control of spacers to locate
source/drains while minimizing parasitic capacitance in non-planar structures. To achieve the
sub-five nanometer node, the GAAFET nanosheet structure was created. Along with the creation
of this new architecture, four new fabrication modules were required to have no historical
precedent in previously established CMOS architectures. These included: reduced pressure CVD
epitaxial Si/SiGe superlattice stack formation defining multiple nanosheet channels; selective
channel release etching that achieved SiGe-to-Si selectivity of >100:1 suspending the silicon
nanosheets; the formation of inner spacers using gas-phase lateral cavity etching and LPCVD
silicon nitride filling to electrically isolate the gate from source/drain areas between sheets; and
conformal ALD gate stack formation to form HfO2/TiN layers uniformly across the sub-ten
nanometer inter-sheet gaps. In addition to these modules, BDI was also developed to mitigate
parasitic sub-fin conduction associated with nanosheet architecture. As each architecturally
related advancement has been realized, there has been an increase in fabrication complexity; the
number of masks used; tightness of process controls; and introduction of new yield loss
mechanisms including: fin height non-uniformity; metal gate granularity induced threshold
voltage variability; nanosheet release induced mechanical deformation; and time dependent
dielectric breakdown of inner spacers. The progression from two-dimensional planar transistor to
three-dimensional transistor represents a fabrication driven approach to overcome fundamental
scaling limitations.

Conclusion:

  The trajectory of the development of transistor manufacturing processes from planar
CMOS through FinFET to finally the Gate-All-Around nanosheet architecture represents one of
the longest-sustained, yet arguably most complex, engineering endeavors in the history of
manufacturing. Each architectural generation was not based on preference for a particular theory;
however, it was based on the necessities of the fabrication limitations of the prior process
technologies. Therefore, the fabrication needs of the previous generation defined the
requirements for developing the next generation of architectures.

  The manufacturing discipline established by planar CMOS fabrication continues to
govern the practices of the entire semiconductor industry today. STI provided a solution to the
isolation scaling problems presented by LOCOS. Additionally, since STI relied on CMP
planarization to provide a planar surface, planarity became an essential component of all
subsequent lithographic processing steps. Thermal gate oxidation and self-aligned polysilicon
gate patterning together created a self-aligned transistor structure that allowed for the massproduction of large numbers of integrated circuits at reasonable yields and costs. Absent these
fundamental techniques, there would be no present-day cost and yield economics for producing
large quantities of functional transistors used in integrated circuits today.

  FinFETs extended the semiconductor industry's ability to continue scaling for another
decade beyond what can be achieved using planar geometries. By demonstrating that lithography
resolution limits do not need to be insurmountable obstacles, but rather they are simply processengineering challenges, SADP and SAQP allowed for the creation of features at pitches that were
not directly resolvable due to the wavelength limitations of the exposure tool used for
lithography. HKMG removed the "gate-leakage wall" that resulted from SiO2 thickness scaling.
This allowed the gate dielectric to once again become a controlled process variable, rather than a
fixed physical limitation. Using high-aspect ratio anisotropic RIE, the 3-D fin geometry allows
for electrostatic control over three sides of the gate versus just one side in traditional planar
structures. This directly improves sub-threshold operation and decreases leakage current at nodes
that would otherwise be non-operational. Collectively, these advances enabled the 22 nm, 14 nm,
10 nm, and 7 nm process nodes that underlie many of the processors, graphics chips, and SoCs
found in mobile systems and other areas that constitute much of today's computing
infrastructure.

  GAAFET nanosheet architecture has similarly continued this trajectory even longer. With
Samsung's 3 nm GAA process going into production in 2022 and TSMC and Intel working
toward their own nanosheet-based nodes at 2 nm and below, the fabrication innovations
necessary to create GAAFET epitaxial superlattice growth, selective-release etching with greater
than 100:1 selectivity, inner-spacer integration, conformal ALD gate deposition in sub-10 nm
enclosed spaces, and bottom-dielectric isolation are examples of fabrication complexity that were
previously thought to be outside the realm of manufacturable technology as little as ten years
ago. Each of these techniques contributes directly to both the yield and performance
characteristics of devices that are now being fabricated at commercial volumes. Improved
electrostatic control afforded by the nanosheet gate results in reduced operating voltage levels,
decreased leakage-power consumption, and increased transistor densities. All of these result in
quantifiable improvements in energy efficiency and computational throughput in chips utilized in
global data centers, AI-accelerator hardware, and consumer-electronics applications.

  Similarly significant in terms of their actual-world impacts are the yield improvements
realized with each successive generation. Pattern-loading solutions developed for STI-CMP
influenced the dummy-fill layouts and design rules governing all advanced chip designs today.
CDU/LER control techniques developed for SADP/SAQP fin-patterning account for the
threshold-voltage uniformities allowing billions of transistors per chip to be manufactured at
commercially acceptable yields. The multi-step channel-release technique developed to eliminate
mechanical distortion resulting from GAAFET fabrication is a clear illustration of how atomiclevel process engineering translates into practical, ship-able silicon. Every yield-related
challenge solved during research-and-development stages lowers the cost-per-functionally-useful
transistor at commercial production stages. Lowering this cost-per-transistor ultimately
determines if a specific technological node is economical enough to move out of a laboratory
environment and into commercial production.

  In addition to establishing the technical foundation for future post-GAAFET device
concepts currently being explored, the fabrication innovations developed across these three
architectural generations have also established a wealth of process knowledge that precedes
them. For example, complementary FET (CFET) architecture depends on stacking two
complementary MOSFETS (PMOS/NMOS) vertically in the same foot-print area. CFET
architecture is dependent on several key fabrication techniques developed specifically for
GAAFET including epitaxial stack formation, selective etching, and conformal ALD deposition.
Similarly, two-dimensional channel-materials such as Molybdenum Disulphide (MoS2) and
Transition Metal Dichalcogenides (TMDs), which are presently under investigation as
alternatives to Silicon channels at sub-1 nm EOT (effective oxide thickness), depend on identical
atomic-level control over ALD and selective etching that existed during nanosheet fabrication.
As such, while historic, this body of process knowledge is also entirely relevant as the direct
basis of precedent upon which future generations of transistor architectures will be built.

  This documented report illustrates that semiconductor scaling is fundamentally a
fabrication issue. Device architecture follows wherever process innovation provides sufficient
capabilities to allow. Therefore, continued advancements in computing capability whether in AI,
HPC (high-performance computing), mobile technology or elsewhere remain reliant on
continuous development of those nanofabrication methods that provide sufficient capabilities to
manufacture each succeeding generation of transistors at acceptable yields.

Citation:\
If this repository is used for academic work, cite the repository and any related project report, thesis, or paper
@software{Techniques-Used-In-The-Evolution-of-Transistor-Architecture,\
  title  = {Manufacturing the Third Dimension: Nanofabrication Process Evolution from},\
  author = {Nathan Lablanc},\
  year   = {2026},\
  url    = {https://github.com/Natedog367/Techniques-Used-In-The-Evolution-of-Transistor-Architecture}\
}
