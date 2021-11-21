# Universal Scrolling Frame

**Universal Scrolling Frame** is an *interactive feature* to the standard Adobe DPS panel that enables users to insert an interactive overlay into a frame with scroll bars, allowing the readers to *scroll* the content published in a folio format.


# Overview

Universal Scrolling Frame maximizes layout usage by allowing the user to scroll content within a limited area.


## How to use Scrolling frames

  

 - Launch the latest Adobe InDesign version and open or create a project.
 - To make a scrolling frame create a **content frame** and a **container frame**.
	 > The **content frame** houses the content that scrolls within the container. It can be a text frame, an image, or a group of objects. It can include any interactive object except a slideshow . Either add the interactive objects to the text frame as **anchored objects** or **group** interactive objects with other objects.
 
 
	 > To create the **container frame** click the "Rectangle Frame Tool" in the toolbar at the left of the application window. Then click and drag to create a new rectangle frame in your document. *The rectangle can be of any size.*

 - 	Choose the **Selection Tool** tool in the toolbar. Hold the "*Shift*" key and click on **content frame** and a **container frame** to select both objects.
 - Open the **Align** panel on the right of the application window and click the "*Align left edges*" and "*Align top edges*" icons to align the content frame to the upper left corner of the frame, leaving a blank space on the right side of the frame for a scroll bar.
	> Make the content frame about 10px smaller than the container frame to leave room for the scroll bar that appears to the right or at the bottom of the scrolling frame. That prevents the scroll bar from overlapping any of the content.
 - Select the content frame, and choose **Edit** > **Cut**.
 - Select the container frame, and choose **Edit** > **Paste Into**.
	 > When you paste the content frame into the container frame, any button with an MSO state action loses its action. Select the button and add the action again. (*The selection buttons in the toolbar are especially useful for selecting hidden buttons. The Layers panel is another way to select nested objects*).
 - With the container frame still selected, open the Window panel. Click the Universal Scrolling Frames, and then specify these options:
***SCROLL DIRECTION***
	>***Auto Detect*** to determine the scroll direction based on the height and width of the container frame and content frame. If the heights of the frames are the same, but the widths are different, the content scrolls only horizontally. 
***Horizontal or Vertical*** to make sure that the content scrolls in only one direction even if the container frame is narrower and shorter than the content frame.
***Auto Detect*** to determine the scroll direction based on the height and width of the container frame and content frame. If the heights of the frames are the same, but the widths are different, the content scrolls only horizontally. 
																																						
	***SCROLL INDICATORS***																																					
																																							
	>Select **Hide** if you don’t want scroll bars to appear when scrolling.

 - To check if the scrolling frame has been successfully integrated go to **Window** > **Interactive** > **EPUB Interactivity Preview** and press the **Play** button. 
