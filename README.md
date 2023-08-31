# Hi, you are reading CD3's weekly progress reports :)
by Wanlun Ding, TDF fall 2023, MDes'24

## Report 1 - Week of 08/31/2023 #

### Process Doc & Assessment

In the first week, I delved into the realm of parametric design using Rhino 3D and Grasshopper 3D... 




<img alt="Error message context" src="./weekly-reports/error.png" width="600">
<img alt="Error message detail" src="./weekly-reports/error-etopanelview.png" width="200">


<img alt="2D phone stand linework error" src="./weekly-reports/2d-error.png" width="300">

<img alt="Phone angle error" src="./weekly-reports/angle.png" width="500">

<img alt="Phone position not adjusted" src="./weekly-reports/camera-position.png" width="500">

<img alt="Context after adjustment" src="./weekly-reports/context.png" width="200">

<img alt="Editing range of numeric slider" src="./weekly-reports/numeric-range.png" width="300">

<img alt="Phone customized to my case" src="./weekly-reports/phone-dimensions.png" width="500">

<img alt="Screen offset scenario 1" src="./weekly-reports/screen-offset-1.png" width="500">
<img alt="Screen offset scenario 2" src="./weekly-reports/screen-offset-2.png" width="500">
<img alt="Student position adjusted instead of phone position" src="./weekly-reports/student-position.png" width="500">
<img alt="Table resized" src="./weekly-reports/table.png" width="500">

### Reflections (what and how I learned)

🤯 Though having played with Rhino modeling a few years ago, I used it primarily for grasping 3D concepts rather than precision. This became evident when my attempt to export a design for laser cutting resulted in ill-fitting pieces back then. Reopening Rhino years later, I faced a steep relearning curve of the interface.
- I could not understand the blank viewports in the beginning, the unselectable geometries, and the baking concept until I read [this article](https://modelab.gitbooks.io/grasshopper-primer/content/1-foundations/1-1/3_talking-to-rhino.html) explaining how Grasshopper communicates with Rhino.

  - 🍰 _**Baking**_
is like turning a recipe into a dish. Grasshopper designs provide rules for Rhino to follow, but it doesn't actually create any real objects by itself. When you want to use Grasshopper-designed shapes in Rhino, like selecting, editing, or transforming, you must "bake" them. Baking is like taking a snapshot of your Grasshopper design and making it real in the Rhino world. Once you've baked something, it becomes part of your Rhino project and won't change automatically if you change your Grasshopper instructions.

🪩 Though I only tested the tools with ready-made sliders of parameters guiding the ultimate 2D and 3D designs, the project turned out more constructive when I took a step back to consider the qualitative decisions about parameters. 
- I questioned the elements making up the current context: the CellPhoneStand_all file included various basic components like the floor, table, student user, phone screen, camera, and lens view. These were assembled to create a functional stand for shooting videos. The central focus was on accurately representing the user's actions, considering how the student's body and the table's geometry interacted with the phone's lens view. 
- By searching "qualitative computational design", I came across a study, [HUMANISING THE COMPUTATIONAL DESIGN PROCESS Integrating Parametric Models with Qualitative Dimensions](https://papers.cumincad.org/data/works/att/ascaad2016_003.pdf), that discusses social and cultural contextual aspects and took note of its conclusion. The analysis prepared:
    > "Socio-spatial grammar for generating parametric solutions for contemporary tall residential buildings that encourage social interaction between families, while respecting their needs, lifestyles and context".
- To rethink the system of parameters while observing how the current components are connected (without much understanding of how they are designed), I first thought of 


Consider: What other contextual observations would be useful to capture?
Consider: What other evaluations of results would be useful to provide as feedback?

✅ A set of to-dos for gaining knowledge of Rhino and Grasshopper includes: 
- Learn the [Rhino](http://docs.mcneel.com/rhino/7/help/en-us/commandlist/command_list.htm) and [Grasshopper](http://docs.mcneel.com/rhino/7/help/en-us/commands/grasshopper.htm) command list and vocabulary for better communication and understanding (sources linked).

### Speculations (tools, work, and news)
* speculation on future direction for the tools [so much is changing very quickly right now, where do you think this is going? Why do you think this?]
* speculation on future direction for the work
* bonus: thoughtful descriptions of something interesting and relevant you heard about in the news or industry publications. include text, an image, a link, and a reference that you can follow up on later and share with your peers.

* Consider: Are there points in the process where you think AI…
Could be used to assist?
Could be trained on input and output?
Other?


