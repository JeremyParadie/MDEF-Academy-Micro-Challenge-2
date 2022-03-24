# FAB-ACADEMY-2
Welcome to our group documentation of fabacademy micro challenge 2 ;)

<h3> Markdown Layout: </h3>
<h4> (https://www.markdownguide.org/basic-syntax/#images-1) </h4>

<h3> Group Members:</h3>
Angel, Aparna, Jose

<h3> Project Description: Biography of Dead Objects </h3>
<p align="center">
<img title="miro" alt="brainstorm" src="/images/collage_objects.JPG" width="590"/>
</p>

<p>During term2 of our MDEF program, each of us has experienced a range of emotions within our design process. At times we have felt hope and excitement and at times frustration and failure. Within this journey, many ideas and things have been created and many have been laid to death.

We want to open up the “black box” of our design processes, and gather these moments which we consider failures and mistakes. By collecting the “dead” artifacts, the ones that did not make it alive, from individual processes, we hope to explore the connections between these objects and generate new narratives. Through these new narratives, we aim to open up an alternative understanding of failure within the design process and expose the power of the collective.

In the coming design dialogues, we aim to investigate death, failure, and vulnerability within the design process and how these individual moments can collectively be brought to life to create new and collective emergent narratives.

As designers, we usually present only the final outcomes of our designs to the public, while the process tends to stay hidden in the “black box”.

In a way, we want to think about what can emerge from the connections of our collective “dead” ideas?
</p>

<h3> Brainstorming:</h3>
Link to our miro board: (https://miro.com/app/board/uXjVOErRQPQ=/)
<p>We used the Venn Diagram format to fill out our personal interests and then added our intersecting interests between the group. It was interesting to see how the other team members describe the common theme in relation to their personal interests. The recurring theme within the group were collective biographies, new narratives and culture.</p>

<p>It was a bit challenging at think of concepts which could be made tangible with the abstract keywords we chose to work with. We had to find a middle ground between defamiliarising the object but the stories relatable for everyone too.</p>

<p>To start off with, we asked our classmates to get one object that is (or was) significant for their design process, it could be whatever: a tool, a drawing, a prototype, a failure or anything else.</p>

<h3> References </h3>
<li> Everything We Touch book by Paula Zuccotti </li>
<li> Paper Circuits by </li>

<h3>Plan and Execution of the Project: </h3>
<p>Before going into the form and technical details, we wanted the idea to be clear and to make sure all of us are on the same page, we decided to keep the first day (Monday) to think about what kind of possibilities could emerge with these "dead" objects. </p>

<p>While discussing our idea with Kate, we realised to "display" our idea it was quite important to keep two things in mind: the interaction of the people with objects (how would they hold it intuitively and not to interfere with their movements) and to keep the presentation of the objects and the speaker appealing.</p>

<p>Images of different forms for the base (horizontal circle, vertical display, objects in a black box, octopus)</p>

<p>Various ways of making the object conductive </p>

<p>The concept of generating a haiku (segments of each sentence told by the person who contributed the object) by touching each object </p>

<h3> Materials and Tools Used: </h3>
<p> Materials: </p>
<li> Cardboard (diameter 90 cm)</li>
<li> Wood (diameter 90 cm) </li>
<li> Vinyl Cut Circles (diameter 1 cm) </li> <br>

<p> Electronics: </p>
<li> Makey Makey </li> <br>

<p> Softwares: </p>
<li> Ableton Live </li>
<li> Rhino 7 </li> <br>

<h3> Iteration Process: </h3>
<li> Images of Cardboard Prototype </li>
<li> Conductive Dots made by Vinyl Cutter </li>
<li> Makey Makey Prototype attached with wires </li>
<li> Collage of all objects received </li>

<h3> Step by Step Fabrication </h3>
<h4> CNC Mill Process </h4>
<p float="left">
  <img src="/images/cnc2.png" width="250" />
  <img src="/images/rhinocam.png" width="250" />
  <img src="/images/cnc5.png" width="250" />
</p>
<li> As we were clear on cutting the plywood for the base. We sketched it on Rhino and used Rhino Cam plugin to convert it into the code.
</li>
<p align="center">
  <img src="/images/cnc4.png" width="350" />
</p>

<li>To fit the 2 sets of elevated planks, we made the structure into dog-bone shaped-joinery. We left an edge of 0.2 mm for the material that gets cut during the mill process
</li>
<li>During the process we also learnt that the depth the CNC can cut in is in proportion the diameter of the mill. (for example the diameter was 6mm, so the maximum depth the wood would be cut in one go will be approx 3mm)
</li>
<li>While preparing the file for g-code, we made it into two layers. One for screws and then the other layer had pocketing and cut together in the required order
</li>
<li>Feed and Speed parameters: RPM: 21000, Feed Rate: 3800
</li>
<li>The pocketing moves from inside wheres profiling (cutting) works from the outside.
</li>
<li>We exported the file in Post processor output format.
</li>
<li>After the cnc cut was done, with the help of hammer and nail we removed the bridges we attached for the small pieces (elevator planks) in order to prevent them for flying while getting cut.
<p align="center">
<img src="/images/cnc1.png" width="250" />
<img src="/images/cnc3.png" width="250" />
</p>
<li>Before setting up, we took different grains of sandpaper to take off the splinters.</li>

<h4> Vinyl Cutting, Soldering and Heat Shrink </h4>
<li>To make sure the object "talks" when someone touches it means that circuit needs to be closed at this point of time till the contact is maintained.
<li>To do so, we used copper sheet as it is a conductive material (circle shaped) and attached it to the objects. When the ground (negative) and input pin connection (positive) are touched together the circuit is closed. If not, my default it's open.
</li>
<li>We cut 10 mm diameter circles for the small objects and 20mm diameter for the bigger ones with vinyl cutter via the Silhoutte Software.
<p align="center">
  <img src="/images/vinylcut.png" width="250" />
  <img src="/images/solder.png" width="250" />
</p>
<li>After cutting the circles, we soldered the wiring endings (total 18 in number- 9 ground pins and 9 input pins) with the soldering wire to make sure the connections remain intact
<li> To make sure the wires stay in place and don't look too messy, we heat shrunk plastic tubes onto each pair.

<h4> Setting Up </h4>
<p align="center">
<img title="miro" alt="brainstorm" src="/images/arrangement.png" width="350"/>
</p>

<h3> Reflection </h3>
.
.
.
<h3> Future Developments </h3>
.
.
.

<h3> What you will find in this repo </h3>
<li> Guide to making g-code file on Rhino Cam </li>
<li> CNC files of the base </li>
<li> Guide to Vinyl Cut and Solder
<li> Electronic Documentation of using Makey Makey </li>

<h3> Links to our personal posts </h3>
<li> Angel: (https://miro.com/app/board/uXjVOErRQPQ=/) </li>
<li> Aparna: (https://miro.com/app/board/uXjVOErRQPQ=/)</li>
<li> Jose: (https://miro.com/app/board/uXjVOErRQPQ=/) </li>
