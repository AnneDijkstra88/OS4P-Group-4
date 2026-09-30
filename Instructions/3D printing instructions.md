# To 3D print the components for the gearbox, follow this guide. 

## **Step 1: Uploading the hardware:**
  
Open the program PrusaSlicer. Before importing a component, download the corresponding file from the Hardware folder.
To import the component into PrusaSlicer, click the left-most icon in the top toolbar, as shown in Figure 1, and select the desired file. 
![Uploading a component to PrusaSlicer](picture1.png)
*Figure 1: Home screen of PrusaSlicer program. Click the left-most icon in the toolbar to insert a file.*
<p>When importing the component, you will be asked to select the quality of the mesh. Select Medium and click OK, as shown in Figure 2. 
  
![Component orientation in PrusaSlicer](picture2.png)
*Figure 2: Import the file corresponding to the component you will print and choose Medium mesh quality.*
<p>The component will now appear on the build plate. Before printing, each component should be oriented so that its largest flat surface is placed on the build plate. This provides a stable base for printing and reduces the need for support material. This can be done by clicking on the desired component. On the left side or your screen will appear different options. Select the option called 'place to face' as shown in picture 3. 
  
![Place to face option](picture3.png)
*Figure 3: Choose a component and select 'place to face' to place the largest flat surface on the build plate.*
<p>Now you can click on the side of the component that you want to face down on the build plate. Repeat this for all the components and arrange them on the board, making sure that the components do not overlap or touch each other. In figure 4 you can see all the components. The circled components are the parts that need to be flipped to make sure the biggest surface is on the build plate. Once all components are correctly positioned on the build plate, click Slice now in the bottom-right corner of the screen, as indicated by the red arrow in Figure 4.

![Components on build plate](picture4.png)
*Figure 4: All of the components loaded on the build plate, with the ones that have to be flipped circled. Click 'Slice now' to move forward.*


## **Step 2: Making support for the components:**
  
After slicing, a vertical slider will appear on the right side of the screen. Use this slider to inspect the different layers of the print. Move the handles of the slider up and down to check the components layer by layer. If a dark blue part appears in the component, it needs support. To give this support, there are 3 different options on the right of the screen under 'supports'. For the components that we are printing, it suffices to select 'support on build plate only'. This is shown in Figure 5. 
![Figure 5: Printer and filament settings in PrusaSlicer](picture5.png)
*Figure 5: Printer and filament settings in PrusaSlicer. Choose 'Support on plate only' to ensure support on the components. Once set, click 'Send to printer' to export the file to the 3D printer you chose.*

## **Step 3: Setting up the printer:**


Before starting the print, make sure that the correct filament is loaded into the 3D printer. On the printer's control panel, select Filament.
If there is already a filament inside, first choose 'unload filament'. Remove the filament and place the new filament spool onto the hanger. Now select 'load filament' and put the filament in the hole of the nozzle. The printer will preheat the filament and drop the residue of the old filament. Remove this old filament. Place a smooth sheet on the bottom plate of the printer. Clean this with resin and a paper towel. You are now ready to print. 

## **Step 4: Upload hardware to printer:**


In the top-right corner of the screen, you can find the Print settings, Filament, and Printer options, as shown in Figure 5.
For Print settings, select 0.20 mm STRUCTURAL. For Filament, select ESun PLA+, and for Printer, select one of the available printers with a 0.4 mm nozzle.
Once all settings are correct, click 'Send to printer' in the bottom-right corner of the screen, as indicated by the red arrow at the bottom right corner of Figure 5. The file will then be sent to the printer. On the printer, click print and you are set! :)
