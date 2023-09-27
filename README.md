# Hi, you are reading CD3's weekly progress reports :)
by Wanlun Ding, TDF fall 2023, MDes'24

## Table of Contents (by week)

- Week of 08/31/2023:
  - [Report 1](https://github.com/Berkeley-MDes/tdf-fa23-wanlun-ding/edit/main/README.md#report-1---week-of-08312023)

- Week of 09/06/2023
  
  - [Report 2](https://github.com/Berkeley-MDes/tdf-fa23-wanlun-ding/edit/main/README.md#report-2---week-of-09062023)

- Week of 09/14/2023
  
  - [Report 3](https://github.com/Berkeley-MDes/tdf-fa23-wanlun-ding/edit/main/README.md#report-3---week-of-09142023)

- Week of 09/21/2023

  - [Report 4](https://github.com/Berkeley-MDes/tdf-fa23-wanlun-ding/edit/main/README.md#report-4---week-of-09212023)

- Week of 09/28/2023

  - [Report 5](https://github.com/Berkeley-MDes/tdf-fa23-wanlun-ding/edit/main/README.md#report-5---week-of-09282023)

## Report 5 - Week of 09/28/2023 

### Assessment & Reflections

For the past week, we have been working on more ways to play with the Photon 2 IoT development board 

### Speculations

---
    
## Report 4 - Week of 09/21/2023 

### Assessment & Reflections & Speculations 

🥳 Kickstarting the new phase of Project 2 - digital ecosystem, I was very excited about getting into the physical connected with the digital and getting my hands on hardware I had no experience with. This was particularly exciting for me, given my longstanding interest in cyborgs, wearables, and IoT technologies.

🤩 Since we were mainly working on setting up the Particle Photon 2 IoT Development Board, I would like to take this entry to delve deeper into understanding the concept of a digital ecosystem and gain insights into the functioning of microcontrollers. 

[Simply showing off my connected Photon 2 board below]

<img alt="Connecting my Photon 2 kit" src="./weekly-reports/w4-0921/photon-connect-1.jpg" height="400">   <img alt="Connecting my Photon 2 kit continued" src="./weekly-reports/w4-0921/photon-connect-2.JPG" height="400">

🍄 _**Digital Ecosystem**_: Despite how frequently I use the two words "digital" and "ecosystem", I had never heard of the pair. After the introduction in class, I decided to look into this realm, given my past theoretical focus. 

- I came across this article ["Everything you need to know about Digital Ecosystems"](https://www.imd.org/reflections/digital-ecosystems/#item1), which discussed it more from the business perspective, according to which the digital ecosystem is a complex network involving people, businesses, and systems that use technology to interact. It integrates physical devices, data, and apps, enabling seamless interactions. Unlike traditional business models, digital ecosystems encourage networked collaboration and rapid adaptation. These ecosystems find applications in companies (e.g., Meta, Amazon), government agencies (e.g., MyData for transparency), and individuals (e.g., healthcare apps). Key components include centralized databases, SaaS for data sharing, APIs as the backbone, and platforms as central hubs.

- From a more academic research-focused and critical perspective, this journal article ["Digital ecosystem: The journey of a metaphor"](https://www.sciencedirect.com/science/article/pii/S2666378323000090#s0050) underscores the pivotal role of metaphors in comprehending digital nature, with a specific focus on the "digital ecosystem" metaphor in the context of digital political economy. The author highlights how this metaphor has been crucial in lending legitimacy to the idea that digital technology can emulate biophysical ecosystems, suggesting that data and digitalization alone can tackle environmental challenges. Moreover, the widespread adoption of the "digital ecosystem" concept has shifted the emphasis towards technological solutions while diverting attention from political aspects in environmental policy and business strategies. The concept promotes technological optimism while concealing critiques of capitalism, thus shaping perceptions and actions in the digital and economic realms in complex ways.

I would like to continue the research and look for a more experimental approach to engage with the concept and find in the midst of these ways one in which I would like to develop my project. 

---

## Report 3 - Week of 09/14/2023 

### Assessment & Reflections

This week has been a dynamic and transformative period for our cohort's individual projects, as we worked intensively toward the completion of Project 1. One challenge was that I found myself experimenting with basic operations during the first few weeks before realizing the need to pivot and come up with new design concepts in the past week. I was surprised at how much and how fast I could learn in a short period of time when prompted to do a project. Even though I have been looking at some beginner tutorials and getting used to the interface, it wasn't until working on the project this week that I really became more familiar with the commands and their actual use.

💡 I was inspired by the various projects our cohort came up with, from a 3D printed hollow spheric phone stand, and a smoothly curved laptop stand, to a large architecture-like bowl consisting of several pieces inserted into one another. Their early initiation of the design process allowed them ample time for testing and evaluation, ultimately leading to more refined outcomes. Additionally, their diverse approaches to designing homeware and tools tailored to their daily needs showcased the versatility of their creative thinking. 

To set my own project challenges, I decided to come up with a 2D phone stand design and build from scratch to help me understand the fundamental logic and step-by-step building process of Grasshopper. However, I didn't yet have a deep understanding of what computational design can achieve other than the complex examples and architectural projects shown in class. Therefore, thinking mostly about customization based on parameter changing, I borrowed the same concept from the given design file to design 2D physical components that can be put together. To start with the pieces needed for support, I drew a cat-shaped stand and refined the idea with more sketches in Illustrator. I also made a paper mockup but couldn't really figure out if the design would work in reality as I'm not sure how the pieces would support each other. 

<img alt="Sketches of idea" src="./weekly-reports/w3-0914/drawing.JPG" height="350">   <img alt="Sketches of idea" src="./weekly-reports/w3-0914/sketches.png" height="350">

Diving into designing with Grasshopper, I was quite overwhelmed at the very beginning and had to look for tutorials on how to make similar designs. Most of the simple product designs focused on building computing-generated structures based on simple geometries rather than pre-designed shapes like the cat illustrations I had. I traced the cat shapes in Rhino first and started adjusting the geometries to build each piece of the stand. This required me to shift between thinking in 3D forms, 2D shapes, and individual points seamlessly. extracting specific numeric values from points on a surface involved not only finding the correct command but also identifying the precise value to utilize. To maintain clarity in my workflow, I relied on notes at various stages to document and remind myself of each step.

<img alt="Grasshopper model full view" src="./weekly-reports/grasshopper-model.png" height="300">

To simulate the phone placement, I imported the phone model into the provided design stack. There are two key parameters that can be adjusted to tailor the simulation: the vertical and horizontal positioning, in addition to the viewing angle in the original file. In addition, I can modify the width and length of the phone model, according to which the dimensions of the rear surface of the phone stand will align.

<img alt="Rendering of the phone model imported" src="./weekly-reports/w3-0914/phone model.JPG" height="300">   <img alt="Grasshopper componentes of the phone model imported" src="./weekly-reports/w3-0914/phone-model-input.png" height="300">

The back plate's dimensions can be adjusted with tolerance sliders, adding to the phone's original dimensions. I can also fine-tune the back plate's angle and the distance between the two cat stands. However, these adjustments are necessary due to design limitations, as these parameters were not initially linked to the phone's angle and center of gravity and cannot automatically optimize themselves. The corner radius is also available to adjust for aesthetic purposes. There are also sliders that control the inserts' shape, size, and the cable hole's scale. Two hollow rectangular spaces accommodate cat tails, with extension direction determined by negative maths in Grasshopper.

<img alt="Grasshopper componentes of the phone model imported" src="./weekly-reports/w3-0914/phone-connected.png" height="300">
<img alt="Grasshopper sliders to adjust the circular inputs" src="./weekly-reports/w3-0914/inserts-input.png" height="300">   <img alt="Grasshopper sliders to adjust the circular inputs" src="./weekly-reports/w3-0914/inserts-input.png" height="300">

I employed red notes to highlight lingering questions and uncertainties. These questions underscored the challenges of comprehending mathematics, particularly when dealing with interconnected elements back and forth. 

<img alt="Problem of why using different methods in Grasshopper would lead to different origin points" src="./weekly-reports/w3-0914/point-option.png" height="350">  

The exported 2D Illustrator file contained some errors that could be easily fixed. During the fabrication process, I had to make several iterations, tweaking certain parameters in an attempt to assemble the design, but I still couldn't ensure the stability of the stand. I suspected that this problem might have originated from the initial design concept. While the digital tools allowed the geometries to fit together, they could not provide sufficient information about the effectiveness of the supporting structure.

<img alt="Exported Illustrator file with extra lines and separated hollow cut shapes" src="./weekly-reports/w3-0914/export-error.png" height="200">   <img alt="Fixing lines and shapes of hollow cuts in Illustrator" src="./weekly-reports/w3-0914/ai-fix.png" height="200">
<img alt="Demonstration of rendered cat stand and laser-cut stand" src="./weekly-reports/w3-0914/cat-stand-demonstration.png" height="400">

Reflecting on my experience, I found that working with Grasshopper involved more geometric and logical configurations compared to building with visual aids in Rhino. While I was able to make progress through trial and error, I realized that I tended to focus too narrowly on individual components in Grasshopper rather than viewing the entire project as a holistic system design effort. For my future endeavors in computational design, I aspire to develop a more holistic way of thinking that enables me to better harness these tools for creative purposes.

### Speculations

In terms of our work, I believe we should continue to prioritize adaptability and flexibility. The past week has shown us how quickly project requirements can change, and our ability to pivot and adapt will be essential in staying competitive and relevant in the industry. Additionally, we should strive for early project initiation and thorough planning to allow for iterative design and testing, as demonstrated by successful team members like Roshan, Charon, and Fareha.

I have identified several areas where I aim to enhance the design:
- Refine the stand's mechanism and components to ensure it can securely support various phone models.
- Explore building the project without relying on the Pufferfish plug-in or refining my workflow using it.
- Investigate the possibility of creating a workflow that can incorporate supporting stands with different shapes, perhaps customized with other animal patterns.
- Experiment with designing a 3D model using a single extruded car shape to hold the phone.

**Futures of the Tools**

The Nvidia Omniverse Connector plug-in allows Rhino and Grasshopper to function seamlessly within Nvidia Omniverse's real-time simulation and virtual collaboration platform. Multiple stakeholders can work with their own preferred tools and workflows while accessing and revising the shared live-sync model generated by group effort. This collaborative approach, supported by the platform's rendering capabilities and compatibility across different design tools, has the potential to accelerate the design and engineering process. Moreover, Nvidia's AI expertise may produce AI tools for designing, optimizing, and automating tasks in Rhino and Grasshopper. This integration can also offer new 3D design and parametric modeling education possibilities.

---

## Report 2 - Week of 09/06/2023 

### Assessment & Reflections

🤔 The first week's progress focused mainly on adjusting the existing parameters in Grasshopper and understanding how the changes appeared in Rhino, which gave me a vague and simplified sense of what computational design could do. The second week was more fruitful in terms of grasping the system design in Grasshopper with [the walkthrough tutorial on Cell Phone Stand Design by TJ](https://www.youtube.com/watch?v=GHtWNAPiAoE) ...

🤦‍♀️ First, continuing in last week's 2D phone stand export, I examined and exported my customized design to Illustrator for laser cutting. After baking, exporting, and opening Illustrator files thrice upon not finding the lines, I finally figured out and got used to grabbing the exported objects from the far wild.

<img alt="Error in Illustrator export" src="./weekly-reports/w2-0906/ai-out.png" width="300">

📐 Before proceeding with laser cutting, I noticed this tiny pointy part generated by my parameter input, which I felt unsure whether it would be able to cut safely and correctly and provide proper support for the other pieces of the stand. So I opted to cut the example file instead. However, I would still like to cut it after further experimentation with the parameters more since design failures might be more enlightening than getting the right result at this stage. Moreover, warnings of overlapping or broken structures and seemingly unfeasible or unusable parts could illustrate constraints and possibilities in design.

<img alt="Tiny pointy structure in 2D phone stand design" src="./weekly-reports/w2-0906/pointy.png" height="250">  <img alt="Laser cutting" src="./weekly-reports/w2-0906/laser.JPG" height="250">

📊 Another inquiry I had was the production cost of an ideal phone stand. I looked up and used the "area" function to calculate the surface area of two phone stand designs given different parameters. Before comparing the "failed" design above with another version, I found myself increasing the height of the pointed parts in the second version. My primary goal was to achieve better visual balance, although I questioned whether this height adjustment had practical benefits, such as stability.

This led me to ponder how designers strike a balance between cost, usability, and aesthetics in computational design. I considered that the second version would use slightly more material than the first one and wondered how designers navigate such decisions.

While the 2D phone stand might not be the perfect example for addressing this complex challenge of the "unattainable triangle", I remained curious about the extent to which designers can rely on computational output and when they should step in to make manual adjustments.

<img alt="Surface area of 2D phone stand laser cut export 1" src="./weekly-reports/w2-0906/area-1.png" height="200">`  <img alt="2D phone stand 1" src="./weekly-reports/w2-0906/cut-1.png" height="200">
<img alt="Surface area of 2D phone stand laser cut export 2" src="./weekly-reports/w2-0906/area-2.png" height="200">  <img alt="2D phone stand 2" src="./weekly-reports/w2-0906/cut-2.png" height="200">

🖲 The simple 3D phone stand file might serve as a more suitable case to investigate the balance, especially when I followed the tutorial to compare the sphere versus cylinder versions. Estimating the baked output's approximate volume by eyeing was hard, but I noticed that the cylinder's height and radius had the most significant impact on the result. However, if considering the stability factor, I couldn't tell if having higher back support in the cylinder version or making a wider base support in the sphere version worked better. The volumes can also differ more than in the 2D designs. 

Although the parametric design approach can be a lot more efficient in producing a usable design, given the established relationship between objectives and responses, I had yet to see how it could make the ideal decisions in such cases and what designers should do to achieve the balance. How can I embed a decision-making mechanism through designing the system in Grasshopper? 

<img alt="Phone stand sphere" src="./weekly-reports/w2-0906/cylinder-landscape.png" height="300">  <img alt="Volume of 3D phone stand bake 1" src="./weekly-reports/w2-0906/volume-1.png" height="300">
<img alt="Phone stand cylinder" src="./weekly-reports/w2-0906/cylinder-solid.png" height="300">  <img alt="Volume of 3D phone stand bake 2" src="./weekly-reports/w2-0906/volume-2.png" height="300">

❓ Next step in figuring out the design of inputs: I would like to learn how to increase the recessed space for placing the phone horizontally. In the current version, there were only very shallow indents on the two sides to hold the phone. Once again, I was only eyeing and had doubts about usability before going into the actual printing. 

In addition, in the landscape version, the camera lens appeared to be suspended in mid-air, potentially indicating an issue with the phone's structural design. Unfortunately, I couldn't locate the source of this problem within the phone's design, as it worked out correctly with the portrait placement. 

I also wonder how to introduce the user context, like activity points, into the simple 3D phone stand design and how it would affect the design output. 

<img alt="3D phone stand landscape" src="./weekly-reports/w2-0906/landscape.png" height="400">  <img alt="3D phone stand portrait" src="./weekly-reports/w2-0906/portrait.png" height="400">

<img alt="Phone projection simulated" src="./weekly-reports/w2-0906/projection.png" width="600">

🏷 Finally, I learned good practices from following the tutorial: duplicating an item multiple times throughout the system whenever necessary to maintain better visibility. Additionally, incorporating notes to explain the purpose of each section is another effective method for staying informed and quickly locating relevant information. Much like in coding, having a well-organized and documented system design can significantly boost productivity and efficiency.

<img alt="Good practice of copying names" src="./weekly-reports/w2-0906/copy-name.png" width="600">

### Speculations

1. _**Enhancements in Grasshopper and Rhino 3D:**_ As I continue my journey with these tools, I anticipate that they will undergo continual improvements, such as the incorporation of an AI assistant to aid users, especially beginners. Currently, both tools demand the memorization of numerous commands. But is it possible that in the near future, we'll have the capability to simply ask a chatbot for guidance, and have a series of commands seamlessly provided and executed?
   
2. _**Increased Focus on Practical Applications and Deeper Understanding of Computational Design:**_ While I've been primarily experimenting and learning so far, I'm excited about applying computational design to real-world challenges toward finishing Project 1.

   - I want to tackle complex design problems by leveraging the full potential of these tools, which could involve optimizing product designs for manufacturing efficiency.
   - The notion of striking a balance between aesthetics, cost, and usability fascinates me and will continue to be a main topic to explore in Project 1.
   - I'm drawn to designs that consider the needs and behaviors of end-users. For instance, how can I leverage parametric design to create ergonomic office products or design equipment in public spaces that encourage accessible social interaction?
   - Can the design output be modular for easier testing and evaluation? This is still a vague question to be composed more accurately, but I'm interested in how to design for a larger-scale system with very complex inputs, constraints, and intents.
   - 
3. _**Decision-Making Mechanisms:**_ Embedding decision-making mechanisms into designs intrigues me. For instance, if I'm designing a modular housing system, I might explore how computational design can help me generate layouts that maximize space utilization while adhering to local building codes and regulations.

---

## Report 1 - Week of 08/31/2023 

### Process Doc & Assessment

🕳 In the first week, I delved into the realm of parametric design using Rhino 3D and Grasshopper 3D... 
At first, I couldn't navigate the files as I kept receiving this error message, which still popped up later even though I [looked it up](https://discourse.mcneel.com/t/error-loading-tutorial-files/157563). Thankfully, my cohort members helped me with bypassing this problem, but I'm still looking for a proper solution.

<img alt="Error message context" src="./weekly-reports/error.png" width="600"><img alt="Error message detail" src="./weekly-reports/error-etopanelview.png" width="286">

👀 I resized the table based on the desk at my home, adjusted the human figure to my height, and set the phone's dimensions and camera positions according to the iPhone 11 Pro Max model. I wonder what is a good practice to locate the precise data of the original phone design since I didn't find the information and had to search for Figma mockups and do hand measurements. 

<img alt="Table resized" src="./weekly-reports/table.png" width="600">
<img alt="Sketch of phone" src="./weekly-reports/phone-sketch.jpg" width="300">
<img alt="Phone customized to my case" src="./weekly-reports/phone-dimensions.png" width="600">
<img alt="Phone camera repositioned" src="./weekly-reports/camera-position.png" width="600">
<img alt="Context after adjustment" src="./weekly-reports/context.png" width="300">

🚶 However, I wasn't able to find the slider to move the phone on the table, so I turned to move the student's position instead.

<img alt="Student position adjusted instead of phone position" src="./weekly-reports/student-position.png" width="600">

❗ Another obstacle I encountered was when I edited the phone viewing angle, and the entire stand model was shown in red to indicate an error as the two identical holding pieces would break. I wonder why the rest of the pieces could not change to reflect the parameter adjustments and if this gap existed in the structural design. Moreover, I couldn't figure out what the phone screen offset from edge meant by changing the related number. 

<img alt="Phone angle error" src="./weekly-reports/angle.png" width="600">
<img alt="Screen offset scenario 1" src="./weekly-reports/screen-offset-1.png" width="600">
<img alt="Screen offset scenario 2" src="./weekly-reports/screen-offset-2.png" width="600">

:warning: The final laser-cut design resulted in misplaced, non-overlapped shapes and lines, which only happened after some slider adjustments. In addition, I could not find where and how to bake the 2D design after changes and doubted if I accidentally moved the outline. I wonder if this would affect the export to Illustrator and laser cutting.

<img alt="2D phone stand linework error" src="./weekly-reports/2d-error.png" width="400">


### Reflections (what and how I learned)

🤯 Though having played with Rhino modeling a few years ago, I used it primarily for grasping 3D concepts rather than precision. This became evident when my attempt to export a design for laser cutting resulted in ill-fitting pieces back then. Reopening Rhino years later, I faced a steep relearning curve of the interface.
- I could not understand the blank viewports in the beginning, the unselectable geometries, and the baking concept until I read [this article](https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-1/3_talking-to-rhino.html) explaining how Grasshopper communicates with Rhino.

  - 🍰 _**Baking**_
is like turning a recipe into a dish. Grasshopper designs provide rules for Rhino to follow, but it doesn't actually create any real objects by itself. When you want to use Grasshopper-designed shapes in Rhino, like selecting, editing, or transforming, you must "bake" them. Baking is like taking a snapshot of your Grasshopper design and making it real in the Rhino world. Once you've baked something, it becomes part of your Rhino project and won't change automatically if you change your Grasshopper instructions.

🪩 Though I only tested the tools with ready-made sliders of parameters guiding the ultimate 2D and 3D designs, the project turned out more constructive when I took a step back to consider the qualitative decisions about parameters. 

- I questioned the elements making up the current context: the CellPhoneStand_all file included various basic components like the floor, table, student user, phone screen, camera, and lens view. These were assembled to create a functional stand for shooting videos. The central focus was on accurately representing the user's actions, considering how the student's body and the table's geometry interacted with the phone's lens view.
  
- By searching "qualitative computational design," I came across a study, [HUMANISING THE COMPUTATIONAL DESIGN PROCESS Integrating Parametric Models with Qualitative Dimensions](https://papers.cumincad.org/data/works/att/ascaad2016_003.pdf), that discusses social and cultural contextual aspects. This analysis prepared:
    > "Socio-spatial grammar for generating parametric solutions for contemporary tall residential buildings that encourage social interaction between families, while respecting their needs, lifestyles and context."
    
- To rethink the system of parameters while observing."how the current components are connected (without much understanding of how they are designed), I noted down a few components that could personalize the solution inspired by the article mentioned above and my real-life situation:

  - Design for multiple shooting perspectives in a confined space. For instance, I have an L-shaped desk at home that can support shooting from either direction (as illustrated below). Although the table's dimensions may not matter much, the room layout could affect the lens view depth and other camera components. How far or close does the user usually stay from the phone, given the limits of the room or the best shooting distance? The floor is set to be a regular rectangular platform whereas, in a real user scenario, there could be irregular layouts, furniture blocks, and other factors (e.g., the user starts a knitting YouTube channel but does not want roommates or parents to find out about the video shooting, thus needing to find a spot that allows the user to quickly stop and "cover the scene" when others ask to enter the room).
   <img alt="Desk example" src="./weekly-reports/table-real.jpg" width="300">
   
   - Consider more contextual data and user preferences. Where are the windows, and where does the best natural lighting come in? Is the generated design suitable for users with various difficulties in vision, mobility, etc.? Is the computational model powerful enough to inform such accessible design? Is it possible to lay the foundation for a further manually modified design intended for enjoyment beyond usability?

  - How is parametric design more or less suitable for designing different user scenarios compared to generative and algorithmic design? In what cases should I generate a collection of designs or seek one solution? How does the quantity of produced designs or the algorithmic process "in the black box" affect the ideal working method of evaluating results? I would revisit these questions after printing and laser cutting the designs and as I explore computational design and the 3D tools more.  

✅ Next thing for gaining knowledge of Rhino and Grasshopper includes: 
- Learn the [Rhino](http://docs.mcneel.com/rhino/7/help/en-us/commandlist/command_list.htm) and [Grasshopper](http://docs.mcneel.com/rhino/7/help/en-us/commands/grasshopper.htm) command list and vocabulary for better communication and understanding (sources linked).

### Speculations (tools, work, and news)

🤖 As a neophyte, I (of course) asked ChatGPT about the parameters helpful for generating a good phone stand design. Here is a list in which I highlighted the design opportunities I missed. I would like to learn if and how Grasshopper can incorporate these factors. While I assumed the aesthetics-related ones would be more difficult for AI or computing to solve, I also wondered if the other aspects could be successfully translated into feasible numeric parameters. For example, when considering portability or easy assembly, should the design consist of smooth edges and corners so that users won't get hurt or experience damage to their belongings kept together with the stand? How does a designer communicate this consideration with the tools? 

1. User ergonomics and comfort
2. Table dimensions and stability
3. Camera angle and view
4. Lighting conditions
5. Phone model and size
6. Material and aesthetics
7. 🏖 _**Portability and storage**_
8. 🔌 _**Cable management**_
9. Hands-free operation
10. Ease of assembly and customization
11. Stability and vibration damping
12. 🛋 _**Contextual aesthetics**_


🧙 Furthermore, imagine if users can all adjust the parameters through a designed AI-powered interface without interacting with the complex tool and 3D print the product from home; how can they give feedback, and what feedback data are needed for improvements once they try it out? I researched and discovered the seemingly contradictory yet promising paring of a concept, "mass customization," through [this article](https://t.ly/cXR72). I was thinking more about design for a highly personalized fit, especially in the realm of healthcare, fitness, and everyday safety equipment. The applications can be more creative and aesthetics-oriented. But what does creativity even mean with computational design? Is leveraging computational design to design a medical device necessarily a less creative process than producing a fashionable keychain? For the final thought, please see some of my product findings below, all of which I appreciated and learned a lot from. 

<img width="400" alt="Nike 3D-printed sneakers" src="https://sourcingjournal.com/wp-content/uploads/2018/03/Nike_Zoom_Superfly_Flyknit_Profile_hd_1600_hd_1600.jpg?w=800&h=511&crop=1">

[Nike's performance-enhancing 3D-printed sneakers](https://techcrunch.com/2018/04/17/nikes-vaporfly-elite-flyprint-leans-hard-into-computational-design/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAJBe7TnddiJgDio7OvVoDagrGf23X6nx3oG5ThJ0FRdxpAO7B5zww0oY1lIRXQj6QAGVKdMucl7uy_gx47RHG-IMkZCCEuBQ3o0y2SucEpd2o_z6-z-PUvvcn4foGm5vVeZmBkXIdxZda-9Z3HGBwUenSb-hpoTTzX8b30YepGwu)

<img alt="Personomic's custom-made bike grips" src="./weekly-reports/bike.png" width="400">

[Personomic's maximum comfort custom-made bike grips](https://personomic.de/en/products/bike-grips)

<img width="400" alt="Nik Lee's bubble boots" src="https://images.squarespace-cdn.com/content/v1/5bbd9952d7819e538a611efd/4d260bb0-d8bb-44ee-b935-f0869f24b067/Final+Development+Sheet1.jpg?format=2500w">

[Nik Lee's bubble boots idea by AI](https://nikleedesign.com/bubble-boots)

🤓 Thanks for reading.
