---
layout: post
---
The notion of automation is becoming increasingly important in the building industry and the built environment at large.
This is timely, as the productivity of the construction industry has essentially not increased since the end of the Second World War (McKinsey 2017). 
The construction industry is one of the last to be “disrupted,” which means that currently a lot of venture capital is channeled in
startups promising a future share of the market. Wework has become the biggest office owner in London. AirBnB
has already deeply impacted many cities, but is now also seeking to design and build its own housing with project Samara.
Katerra has received significant amounts of funding with its promise to overhaul timber construction through vertically integrating the entire production chain.
Alphabet’s Sidewalk Labs is set to develop Toronto’s Eastern Waterfront in return for data. 

Theorist and architect Neil Leach argues that "while there is clearly a practice of designing that involves the use of digital tools, there is no product as such
that might be described as digital" (Leach 2015).
Digital design and fabrication tools merely allow a specific type of design to be realised, but they can as well be used for objects which do
not appear "digital" or "parametric". This critique ties into a contemporary discussion on the post-digital. 
The use of digital tools and techniques has matured to such an extent that their use is more critically questioned. So what does it mean for buildings 
or material organisations to be digital ? Can material be organised in the same way as data? Or is there really no such thing as a digital architecture?

<h2>Prefabrication and Programmable Matter</h2>
This work on discrete building blocks and robotics relates to Hod Lipson’s Programmable Matter research, MIT’s CIAL modular robotics, 
and the Digital Material Research at the Centre for Bits and Atoms, with projects such as Flexural Materials by Kenneth Cheung, or Bill-E by Benjamin
Jennett. The Harvard Wyss Institute's work on the TERMES project is another reference, where a distributed robot assembles serialised building blocks. 
While these examples are mainly situated in the fields of mechanical engineering, the research agenda and projects in this paper attempt to
define large-scale functional architectural parts that share some of the properties of the generally small-scale digital
materials or programmable matter building blocks. In scaling up these systems, not all properties need to be kept,
while also new constraints are imposed. The principles of programmable and digital materials are combined with
existing knowledge of prefabrication, modular construction, and design for manufacturing and assembly (DfMa) in the building construction. 

<h2>Discrete Computation</h2>
The Tallinn Architecture Biennale (TAB) installation is the first 1:1 scale, large prototype of the digital-discrete
discourse. It was designed as a case-study, a Dominolike abstract model of a larger, scalable, and repeatable construction system for housing. 
Therefore, the starting point of the project was the design of a large-scale housing block, from which the installation was later
extracted.
There are a number of Discrete Design Methods, one commonly used starts from a voxel-space where every
voxel contains a generic part that can be combined in different orientations, in respect to its neighbours and or data that is embedded 
in the voxel space itself (Retsin, Jimenez-Garcia 2017). The parts in the voxel can be exchanged for other types dependent on the neighbours,
etc. Other methods are graph-based and start from the part and its inherent connection possibilities. In this case, specific patterns
can be developed beforehand, which can then be applied and evaluated with either brute force or more advanced learning principles.

<h2>Mereology</h2>
The emphasis on the part or bit re-emphasizes the discussion of part-to-whole relations. This notion, which has traditionally been important for architecture,
disappeared from the discussions surrounding the digital as a result of an interest in holistic, continuous tropes such as topology and surface. Mereology
(from the Greek mereo or "part") is the study of the relations between parts and the wholes they construct.
Mereology specifically deals with hierarchies in partwhole relationships - a concept referred to as Meronomy or Partonomy (Simmons 2000). Object Oriented
Programming has a mereological character through its structure of classes and inheritance of classes. 
Although mereology is an actual scientific study, developed by the Polish mathematician Lesniewski, it was initially the work of Levi Bryant 
which was important for the development of the projects below. In the Democracy of Objects, Bryant describes the concept
of "Strange Mereology", as a relation where every part is in itself a whole which is not reducible to its parts
and where every part is not reducible to the whole (Bryant 2011). This kind of democratic part to whole relationships are typical for Object-Oriented philosophy.
It can be argued that Architectural part-towhole relations are traditionally a non-strange Mereology, which means that the parts are never really autonomous from the whole, but are always reducible
to the whole. They have no existence outside of the whole. This non-strange mereological character is typical for top-down design methods, but essentially
also for continuous design in general. To establish continuity, every part has to be reduced to a derivation of the whole. A good example of non-strange
mereological structures is parametric surface panelisation. In panelisation, every piece is unique, and derived from a specific location on a surface. The large
differentiation of pieces requires micromanagement of thousands of components, resulting in excessive labour and energy in assembly. Gramazio Kohler's
Programmed Wall, previously mentioned, also falls in this category, as the orientation of every brick is a result of a continuous parametric function.

<h2>Blokhut</h2>

The Blokhut (2015) is a study for a villa in the Belgian community of Wetteren. The term "Blokhut" is a Dutch for Log Cabin - a hut built of whole or split
logs. As a response to budget constraints, and at the same time a request for a differentiated and highly
articulated space, the project aimed to extensively use serialised building elements. The Blokhut establishes a differentiated and adaptive architectural system which consists for 90% of serially repeated, discrete, prefabricated concrete elements, and for 10%
of unique, customized elements (Figure 2). To test the design method, a large-scale prototype of 2 x 1.5 x 0.3m was developed. It was assembled using
more than four thousand pre-cast plaster components, intersecting and joining around a number of customized, 3D printed zones (Figure 4)

<img src="https://raw.githubusercontent.com/evergreencircle/research/master/doubleblokhut_670.jpg" alt="Blokhut">

While computation can reduce the drudgery of repetitive tasks, generative design methods also help design and construction
teams reach the ultimate goal of reducing waste and cost.

<h2>Diamond Strata</h2>
Diamond Strata (2016) is a further development of the Blokhut project, but does not require any customised pieces . The project brief was a multi-family
house with three apartments in a rural area close to Brussels, Belgium.The project is an aggregation of a single, beam-like timber element. In this
case, a hierarchical digital material was used - a discrete building element with multiple different scales which can cross-connect. The system consists of a
linear and L-shaped element with a lego-like malefemale connection( Figure 5). The elements can connect through sliding joints on the lateral faces of the
piece. The hierarchical system is similar to OcTree optimisation, a procedure used in 3D graphics where space is partitioned with different scales of voxels dependent on the resolution required. Assembly time
can be reduced as the scale of the parts is adaptable to the resolution desired.

<img src="https://raw.githubusercontent.com/evergreencircle/research/master/Retsin_Diamonds_house-1_1340_c.jpg" alt="Diamond Strata">

<img src="https://raw.githubusercontent.com/evergreencircle/research/master/aRetsin_Diamonds_house-3_1340_c.jpg" alt="Diamond Strata">


<h2>Robotic assembly</h2>
Robotic assembly is only feasible and scalable in the context of digital materials and discrete computation, which has a limited set of connectivity problems. The high degree of serial repetition in the
projects presented make a robotic assembly process more feasible. Parts are organised in a grid or voxel-like pattern, the connection between elements
is repetitive, and the connection problems themselves are always discrete, neighbour-neighbour or part-part problems. In contrast to projects based
on continuous variation, these projects can be fabricated through very simple, serialised actions. The elements' weight has to be limited to 150 kg to be
feasible for assembly with large industrial robots. In the case of the proposed projects, assembly could be
done with a gantry robot. This gantry robot could assemble chunks or parts of the building off-site, which can then be transported to the site on a normal truck.
The inherent disadvantage of this method is the lack of scalability: only one gantry robot can be used at
a time. The previously mentioned hierarchical digital materials used in the Diamonds house take into account a certain degree of scalability, so a gantry structure could be feasible in this context. Distributed
robots would become more desirable if the scale of the elements would be smaller, but bring more constraints for the design. Next iterations of work should
look into material efficiencies and structural optimisation. Further research with robotics could test assembly sequences and optimise the proposed geometries for robotic handling.

<h2>Used Materials</h2>
<ol>
  <li><a  href="http://papers.cumincad.org/data/works/att/ecaade2016_221.pdf">Discrete Assembly and Digital Materials in Architecture
</a></li>
<li><a href="https://discovery.ucl.ac.uk/id/eprint/10117335/1/Toward_Discrete_Architecture_Automation.pdf">Toward Discrete Architecture:
Automation takes Command</a></li>
 <li><a href="https://www.e-flux.com/architecture/becoming-digital/248060/discrete-automation/#:~:text=Discrete%20architecture%20seeks%20to%20take,disciplines%20of%20the%20built%20environment.&text=She%20is%20Director%20of%20Automated%20Architecture%2C%20a%20design%20and%20technology%20consultancy.">Discrete Automation
</a></li>

