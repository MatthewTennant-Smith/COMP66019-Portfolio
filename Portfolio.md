# Robotics modelling and drone skin design

By Matthew Tennant-Smith

Introduction

The world of Robotic modelling has become an increasingly more prevalent field within the entertainment industry with animatronics becoming more mainstream, having models both in set environments as well as the open world (Walt Disney Audio-Animatronics Timeline', 2019). Based on these real-world applications and how much of an effect they have on the industry; with thousands of people travelling to see these life-like models of their favourite characters, it is important to understand the techniques that go into the development of the models.

Project Aim

In this project an aim is set out to research into existing techniques utilised within industry and to develop a prototype model utilising current means and approaches, outlining the stages of development from the conceptualisation of the animatronic to the finished prototype as well as the relevancy and appropriateness of other techniques within development.

The first step is the conceptualisation of the model. There were two requirements: a hinge joint and a covered element. The full MoSCoW criteria can be found in appendix 1.

Conceptualisation

Fundamentally, the proposal for this model was to be a smaller scale animatronic model that meets the above requirements as a basepoint. There is a plethora of options available within this requirement as such it was decided to narrow the model down to a character statue of Yoda from Star Wars. This was selected as the design animatronic due to Yoda's popularity within the entertainment industry and having widespread popularity in Star Wars and being easily distinguishable due to his appearance and in general being a quite intriguing looking character.

Based on this requirement the project was designed to be a small-scale Yoda animatronic designed with a hinge as well as his cloak and a coloured skin. The requirements for this model can be found below(Appendix 1) as well as the scale and costs (Appendix 2).

Design Development

Once the animatronic had been conceptualised the next stage was the design development stage where individual parts were designed within a modelling software to create a 3D prototype for the model to understand how the model could look and function. There were several different options available with the notable options being A form of Computer Aided Design (CAD) software, 3D scanning or use of a haptic pen in modelling software.

3D scanning is a technique commonly used in industry to get hyper-realistic features by scanning an existing item into software via optical recognition markers that are placed on the object and using those makers to scan in geographic marks for the object (He G. et al., 2022). This allows a backtracking to take a 3D object and create a digital rendition of that object that can then be modified in a way that suits the development of the new model. This technique could be utilised to generate an item such as Yoda's head that by itself is a technically difficult design to make due to the complexity of the mould for his head; This was considered but a model for Yoda's head was available as an open-source 3D scanned model (Bmoshe, 2011), so due to time constraints the previously scanned model was used to then adjust to the right scale.

"Link to Head Stl file"

A haptic pen was also considered as a form to design a virtual prototype that acts as modelling software that utilises a stylus style pen to carve the design into a cube structure, this allows a more natural and fluent modelling process but as a result can be difficult to use without experience and was ultimately decided against due to little experience in the tool ('3D Pen Delivers Force Feedback' 1998). As such a CAD approach was decided.

With a typical CAD approach being selected to design the prototype, different software were considered. Fusion360 is a popular modelling software with many tools available, such as a generative design allowing parameters to be selected and the software creates the model albeit sometimes with errors in the design. Fusion360 is typically used in industry to create ridged models such as a motorcycle engine (Angamuthu K., et al.,2021). This could be used for structural parts of the design such as the torso which will ultimately be covered, however making other parts would be more challenging to create in a natural aesthetic such as hands (Song, P.P., Qi Y.M. and Cai D.C., 2018). This can be somewhat fixed with the use of textures available with great availability to completely customise textures (figure 1) aiding the development of a more organic model. Ultimately this was not chosen due to the necessity of an organic looking Yoda model and with the covering making the use of the texture all but obsolete.

![alt_text](https://github.com/MatthewTennant-Smith/COMP66019-Portfolio/blob/main/Images/Fusion360.png)

Figure 1 – foot rendered in Fusion360

Blendr is a Modelling software better equipped to modelling organic looking models where Blender serves as an effective modelling software in creating game characters due to the ability to apply natural textures and life-like features to the models (Totten, C., 2012). This would be more appropriate for this project due to the Yoda needing to look realistic. The software being completely open source makes it easy to access and learn with, and also has rendering capabilities to use inline with the organic models; however due to the requirements the rendering textures are obsolete. The extensive organic character modelling capabilities make it an adequate tool for the model; however, it was not chosen primarily due to experience in AutoDesk123d.

Autodesk123d is currently discontinued however, there are ways to access it, this was chosen as the platform due to experience within the software to allow a smoother modelling experience. Autodesk123d has several addons that can be used to aid organic modelling of pieces such as mesh mixer which is used to aid the modelling of high-resolution pieces. The familiarity of this software has made it the ideal choice for modelling the prototype.

Once the software had been decided the initial design was created exclusively as a virtual model to iterate through design processes for the model. This was split into six different pieces being: Arms, shoulders, torso, feet, hands, head

Each part was designed individually as an initial iteration, with the torso having holes in the design for wires to be passed through for the servo motors. Holes were also designed in the top of the torso for space for the Arduino board.

The hands and feet were then designed in conjunction with mesh mixer to aid with the organic aesthetics of the character like parts that would be visible to ensure that the design looked natural. The hand was created initially and then mirrored to create an identical copy with a mirrored effect for a left and right hand to reduce modelling time in creating two separate hands, the feet were copied as identical and not mirrored as Yoda's feet were the same for each leg.

"stl file for hands "

"stl file for feet " -

The next part designed was the shoulder which left space for the servo's to be fit into to ensure a secure fit that would allow the functionality of the turning within the model and the scanned head was cropped and had a hole placed in the bottom for the neck servo motor. The last piece designed was arm which was designed as a simple arm piece.

"upper torso stl file" Y

" hinge 1 stl file " Y

This was then iterated through again to adjust the sizes of the upper torso to match the servo motor size and the rest of the pieces were adjusted to match that size and the Arduino board size, and in a third iteration the torso and feet pieces were combined into a singular piece to make assembly easier later.

"Torso and feet stl file" Y

Within this stage no physical model was created due to time constraints however, reflecting on this stage; using a physical prototype might have allowed better insight into what changes could been made within the design and been able to see if the balancing and counterweighting would have been able to let the model stand without a base which could have made the Yoda function better as a model. Ultimately this wasn't decided due to time but could be considered for a different project. Another change that could be considered is utilising blender as the modelling platform due to its benefits and tools in organic modelling which may have allowed a better design of pieces

Overall, the design stage has gone well with each piece being designed in a way that accounts for the motors and the scaling of the model has been proportioned well. The use of the familiar software allowed a smooth transition modelling of each part quickly to ensure that the project could progress seamlessly without much trouble and with each iteration improving a particular aspect of the virtual model. This put the project in a good standing when moving to the detail development stage where the hinge and physical model were designed.

Detail Development

Once the initial design had been created, the hinge was then discussed as to where it should be. This was decided to go on the arms to that Yoda could have moveable arms to add a level of realism, the next debate was what hinge the elbow should be. The main considerations were a living hinge and a print-in-place hinge. The living hinge is a hinge joint where the material is cut out to make the hinge giving the hinge bending capabilities and making the joint flexible which is common in applications where a more flexible joint is needed that can bend into place such as frictionless mechanical inerters. (John E.D.A. and Wagg D.J., 2019). The print-in-place hinge is a joint that is built up from material using 3D printing to create a structural hinge that reduces the assembly time and clean-up due to being printed in place as a single piece. This is not typically used within industry but is commonly seen in prototypes for designs that can then be scaled using mechanisms to create the same effect on industry models (Hauck B.C., Ruprecht B.R. and Riley P.C., 2022). This was chosen as the joint due to its more natural hinge movement that could be associated with Yoda following the natural movement of an elbow.

Once the hinge joint was decided the arm was iterated through another design where the hinge was added in place of the existing arm piece and scaled to a proportionate size.

" hinge stl file"

Due to the hinge joint selected, the only way to generate the physical hinge is via 3D printing making it so that is a necessary inclusion within the generation of the physical images. Within industry there are several techniques used and during the project several of these were investigated to evaluate the best methods available for the project.

Motion capture is a technique commonly used in industry using reflective markers and optical map imagery to map movements in software; allowing hyper-realistic movements to be mapped. This is commonly used within industry particularly within animatronics that require smooth movements such as spider-man (Mehta D. et al., 2020). Within the realms of this project fluid motions were not required and just a hinge joint was needed so this was not considered. When moving from a prototype this might be considered to get realistic movements on a full-scale Yoda.

Laser cutting was another technique investigated, using a laser to act as a cutting blade to pinpoint exact marks to cut. This typically leads to a flat object depending on the thickness of the material but can create an assembly by cutting slots in pieces to assemble. This makes the process much more complicated; this could be used to have a stand for the Yoda model to help counteract the model which is a common use for fixed place models to help the model balance its centre of mass (Visser L., 2023).

Overall 3D printing was decided to be used for each of the STL files. 3D printing is a form of additive design wherein the material is added to the structure through a nozzle that prints the object in place, opposed to cutting it out such as with laser cutting which sculpts the design into the material. There are two types of printers: Fused deposition modelling (FDM) and a Stereolithography (SLA). The FDM printer is commonly used in industry due to its ability to print Acrylonitrile butadiene styrene (ABS) and other plastics such as poly lactic acid (PLA) (Lechner C. and Pervaiz A., 2020). The SLA printer uses a specific resin in its printing and doesn't have the capability to use other materials making it less useful in this project due to the limitations on material hindering the possibilities with resin not being considered due to time constraints in taking longer to print and the fragility of the plastic. The FDM printer can also be used to print metals and woods making the materials available not limited and allows a rapid prototyping of allowing pieces to be injected into place for the model; allowing a quick physical prototype to be developed (Algarni M. and Ghazali S., 2021).

Due to all the files being 3D printed they were moved into a single STL file to be printed overnight to save on time.

" ALL STL FILE "

Before printing the material was first needed to be selected, Wood would be hard to 3D print and would have to be a fused wood with plastic creating a sort of paste type material to set in the shape of the material providing a sustainable biodegradable material. This was ultimately not selected due to potential splintering when trying to screw the wood together ruining material. Metal was also considered but ultimately decided against due to little access to metals and having difficulty with applying to the scope of the prototype. Typically metals such as aluminium will be used for animatronics in conjunction with hydraulics such as the use for the Spinosaurus (Goldman M., 2001). Plastics are broadly available within the project; each having their own advantages. ABS is the most common implementation for industry models being a strong, durable plastic and having the ability to work with mechanical properties. Typical instances of ABS include Lego statues which are in an uncontrolled environment and so the plastic needs to be strong (Turner A., Arnold R. and Williams T., 2020). The notable downsides of ABS are that it is incredibly toxic and needs to be manufactured in a controlled environment due to toxic fumes emitted during production make it a difficult material to produce in this project. Thermoplastic polyurethane (TPU) is a rubber-based plastic was also considered due to the nature of the plastic having a similar texture to Yoda which is typically a silicon-based puppet, TPU is typically used in industry for rubbery materials such as tires (Jiang J. _et al._, 2021). The rubbery texture of the plastic makes it hard to engrave, struggling to make use of the wrinkles in Yoda's head as well as having the added layer being a requirement the TPU would not meet that criterion and consequently would not be fitting for Yoda. PLA is a notable plastic typically used in prototyping due to its cheapness (Sadeghi Ghari H. and Nazockdast H., 2022). PLA is a corn-starch-based plastic that is biodegradable and a somewhat durable material. Its main disadvantage is with it being not a completely durable and being somewhat brittle and vulnerable to the environment, however this will not be an issue due to the model being kept in a controlled environment making it the most suitable approach for Yoda.

Another key element of the model is the stand so the model can be supported; as such a base stand would need to be designed for the model to be placed upon, the design for the stand will be simple to offset the balance; the materials for this stand are unimportant and should be cheap and easy to manufacture. As such an acrylic stand would be a feasible option due to being a cheap option and easy to obtain as well as laser cut (Khan M.M.A. et al., 2021).

Within this stage more details were developed for the model including the material, hinge and production method. Within this stage the overall stage was a success with both the hinge and the printing being a success. Upon reflection, ABS might have been a more suitable material due to its strength and resistance to the environment and would be more considered if the project was to move into a realistic environment and not be kept indoors. The overall design is reproducible with the STL files and thus could be mass produced if required. This stage was a large success with the STL files fully prepared and ready to be printed and with the selection of materials being fit for purpose for the model even if not the most optimal in hindsight; they still are effective in the prototype. Overall, the hinge joint and choice to 3D print the pieces was very successful in timing as well as the functionality of the model still being upheld to a good standard with the hinge.

Assembly

Once the files had been received by the printer the first piece to be printed was the head, this was printed using supports and rafts, with the supports being the additional pieces of plastic printed along floating aspects such as the ears to ensure the plastic didn't droop during printing and to keep structural support, the raft is a sticky layer at the bottom to support the piece and ensure it is held in place while printing (figure 2). This allows the piece to be printed optimally and not skewed. Once this was printed successfully; other pieces were printed.

![](RackMultipart20230526-1-6wrb00_html_35b139ac7c788e45.jpg)

Figure 2 – supports and rafts

Once each part was printed the assembly stage began where the parts were screwed with the torso being screwed to the Arduino board (figure 3), with the speaker added on for audio capabilities. The three servo motors were added to the shoulder pads and the wires thread through (figure 4) to complete the main chassis of Yoda, the hands were then attached to the arms and the arms placed through the servo motors and the head attached to complete the main aesthetic for Yoda (figure 5).

![](RackMultipart20230526-1-6wrb00_html_72447a3621b52eb3.jpg)

Figure 3 – Arduino board screwed in

![](RackMultipart20230526-1-6wrb00_html_944e38933b4ef90e.png)

Figure 4 – servo motors added to shoulders

![](RackMultipart20230526-1-6wrb00_html_ccf6f6775c5fe469.jpg)

Figure 5 – finished Yoda body.

This was made this way to allow an easy assembly process with screws used to hold pieces together and to allow movement between the hands and head to rotate with the servo motors.

Once the model was assembled it was apparent that the left arm hinge was rather loose and as such was dangling down, to resolve this issue a thin strip of glue was added to help add some friction in the hinge joint once the glue had solidified. With the fixing of this hinge joint the assembly was complete; the model was still unfinished though as it needed the texture applied.

The final stage was to finish up the model with cosmetic touch-ups, this was decided to be with a green colour scheme as well as a robe to cover the Arduino to make the animatronic look good, the colour scheme also gives a realistic appearance as well (figure 6). The material selection for this was not an important consideration and as such a simple test robe was designed out of cloth to give the appearance of the robes the character wears as well as adding a lightsabre and his signature cane. The only point of consideration left was the colour as although a colour had already been chosen it was not a complete match to Yoda and was relatively dark comparatively to his proper skin colour, as such this was revised, and a new lighter green was applied as the colour for Yoda.

![](RackMultipart20230526-1-6wrb00_html_c676eee7d4362839.png)

Figure 6 – Yoda with aesthetic touches

Once the green colouring was adjusted the final model was ready with an acrylic stand laser cut to screw to the Yoda to stop the model from falling over, once this stand was added the model was finished with the aesthetic touches (figure 7).

![](RackMultipart20230526-1-6wrb00_html_2a49ff36e72a8bf6.png)

Figure 7 – final Yoda model

This stage was a success with the colouring being adjusted well, and the finished covering being very appropriate for the model, reflecting back latex was an option for the skin to give a realistic texture to the Yoda model, if given more time this approach would have allowed a more realistic Yoda, with latex being common in industry for human and non-human animatronics including fish (Fate K., 2014). Without the latex whilst the model still looks very professional it lacks that distinct Yoda aesthetic with the skin and looks somewhat plasticky compared to a more natural aesthetic that could have been possible with latex.

Overall, this project was a large success and followed the journey from the concept and design of the materials through to the virtual development of the model and then the physical printing of the Yoda and assembly with the finishing touches. The prototype model itself was a success in its creation as it has a hinge as well as aesthetic touches as well as bonus motorised capabilities with turning of the head and swinging arms. Generation of the model could have been possible between both blender and fusion 360 with the life-like parts being modelled in blender and the structural components in fusion360 as a different approach if 123d was not the chosen method; potentially optimising the standards of the parts and the design. One key aspect that would have been changed is the material to ABS; whilst PLA was an effective for prototyping, the durability of ABS would have aided the toughness of the model and its ability to be kept in an uncontrolled environment as well as the inclusion of latex as a finishing design choice to make Yoda look more realistic. Looking forward, this model could potentially be scaled up and whilst that would require different hardware due to the servo motors and joints, motion capture could be potentially used in conjunction with hydraulics to design a full-scale model as seen within entertainment parks such as Disney. To conclude, the project was a large success aiming the key parts of the design prototype with room to improve and be developed further upon to get the model ready for a more open environment.

REFERENCES:

'_Walt Disney Audio-Animatronics Timeline' (2019) IEEE potentials, 38(5), pp. 24–25. Available at:_ [_https://doi.org/10.1109/MPOT.2019.2921531_](https://doi.org/10.1109/MPOT.2019.2921531)_.+_

_Goldman, M. (2001) 'Winston's Animatronic Behemoth', Millimeter, 29(2), p. 11–._

_Sathish, T. et al. (2022) 'Novel study on improvement of plastics properties by blending of waste micro plastics into ABS plastics', Chemosphere (Oxford), 303(Pt 1), pp. 134997–134997. Available at:_ [_https://doi.org/10.1016/j.chemosphere.2022.134997_](https://doi.org/10.1016/j.chemosphere.2022.134997)_._

_Sadeghi Ghari, H. and Nazockdast, H. (2022) 'Morphology development and mechanical properties of PLA/differently plasticized starch (TPS) binary blends in comparison with PLA/dynamically crosslinked "TPS+EVA" ternary blends', Polymer (Guilford), 245, p. 124729–. Available at:_ [_https://doi.org/10.1016/j.polymer.2022.124729_](https://doi.org/10.1016/j.polymer.2022.124729)_._

_Jiang J. et al. (2021) 'Evolution of ordered structure of TPU in high-elastic state and their influences on the autoclave foaming of TPU and inter-bead bonding of expanded TPU beads', Polymer (Guilford), 228, p. 123872–. Available at: https://doi.org/10.1016/j.polymer.2021.123872._

_Khan, M.M.A. et al. (2021) 'Optimization of Laser Engraving of Acrylic Plastics from the Perspective of Energy Consumption, CO2 Emission and Removal Rate', Journal of Manufacturing and Materials Processing, 5(3), p. 78–. Available at:_ [_https://doi.org/10.3390/jmmp5030078_](https://doi.org/10.3390/jmmp5030078)_._

_Mehta, D. et al. (2020) 'XNect: real-time multi-person 3D motion capture with a single RGB camera', ACM transactions on graphics, 39(4), pp. 82:1–82:17. Available at:_ [_https://doi.org/10.1145/3386569.3392410_](https://doi.org/10.1145/3386569.3392410)_._

_He, G. et al. (2022) 'A novel bone registration method using impression molding and structured‐light 3D scanning technology', Journal of orthopaedic research, 40(10), pp. 2340–2349. Available at:_ [_https://doi.org/10.1002/jor.25275_](https://doi.org/10.1002/jor.25275)_._

_Algarni, M. and Ghazali, S. (2021) 'Comparative study of the sensitivity of pla, abs, peek, and petg's mechanical properties to fdm printing process parameters', Crystals (Basel), 11(8), p. 995–. Available at:_ [_https://doi.org/10.3390/cryst11080995_](https://doi.org/10.3390/cryst11080995)_._

_Visser, L. (2023) 3D modeling for 3D printing and laser cutting on Fusion 360. [First edition]. Place of publication not identified: Packt Publishing._

_Bmoshe (2011) "Yoda". Available at:_ [_https://www.thingiverse.com/thing:106500_](https://www.thingiverse.com/thing:106500)

'_3D Pen Delivers Force Feedback' (1998) Computer graphics world, pp. 8–8._

_Song, P.P., Qi, Y.M. and Cai, D.C. (2018) 'Research and Application of Autodesk Fusion360 in Industrial Design', IOP Conference Series: Materials Science and Engineering, 359(1), p. 12037–. Available at:_ [_https://doi.org/10.1088/1757-899X/359/1/012037_](https://doi.org/10.1088/1757-899X/359/1/012037)_._

_Totten, C. (2012) Game character creation with Blender and Unity. 1st ed. Indianapolis: John Wiley & Sons_

_Angamuthu, K. et al. (2021) 'Modeling and simulation studies of 100 cc motor cycle engine cylinder with groove and perforated fin design using different materials', in Materials Today: Proceedings. Elsevier Ltd, pp. 1447–1455. Available at: https://doi.org/10.1016/j.matpr.2021.01.249._

_John, E.D.A. and Wagg, D.J. (2019) 'Design and testing of a frictionless mechanical inerter device using living-hinges', Journal of the Franklin Institute, 356(14), pp. 7650–7668. Available at: https://doi.org/10.1016/j.jfranklin.2019.01.036._

_Hauck, B.C., Ruprecht, B.R. and Riley, P.C. (2022) 'Accurate and on-demand chemical sensors: A print-in-place ion mobility spectrometer', Sensors and actuators. B, Chemical, 362, p. 131791–. Available at: https://doi.org/10.1016/j.snb.2022.131791._

_Lechner, C. and Pervaiz, A. (2020) 'From invention to industry from a social movement perspective: the emergence of the 3D printing industry', Journal of innovation and entrepreneurship, 9(1), pp. 1–28. Available at: https://doi.org/10.1186/s13731-020-00124-6. - 3d printing applications_

_Turner, A., Arnold, R. and Williams, T. (2020) 'Weathering and persistence of plastic in the marine environment: Lessons from LEGO', Environmental pollution (1987), 262, pp. 114299–114299. Available at: https://doi.org/10.1016/j.envpol.2020.114299._

_Fate, K. (2014) BRIEF: Singing fish spooks would-be burglar. Washington: Tribune Content Agency LLC._

Appendix:

Appendix 1 - Requirements

Must –

Animatronic must have hinge-based arm joints to allow for movement

Animatronic must have a covered layer of robes as well as painted green skin to resemble the colour scheme of Yoda making it look more realistic

Animatronic must be able to stand on a base without falling over to allow the animatronic to stand in a controlled environment

Animatronic must be modelled in design stages on software

Should –

Animatronic should have space for servo motors for enhanced movement capabilities with shoulder movement as well as head movement within the servo motors

Could –

Animatronic could have speaker capabilities for speech output of the animatronic of pre-loaded messages and audio.

Wont –

Animatronic won't have full walking motion capabilities.

Appendix 2 – Costs and Scaling

Arduino - £15

Servo Motors £5 (x3)

Mp3 - £5

Speaker £5

Total - £40

The Yoda model will follow a design of 17cm as a 1/3rd replica scale of a full-size Yoda. The criteria should allow for a fluid development as well as an achievable set of goals for the model to be able to be considered a success. The use of programmable motors will allow articulation of the parts of the model.
