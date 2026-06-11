# Cue Card Booklet Generator

Try it out with [Compatible Mode](https://hezsystemscorporation.github.io/Cue-Card-Maker/CueCardMaker.html) or [Beautified Mode](https://hezsystemscorporation.github.io/Cue-Card-Maker/CueCardMaker_pro.html). 

Better using with a computer. **Star** it if this little website really helps you. 

This application is a specialized web tool designed for speakers, educators, and presenters to create cue card booklets from standard A4 paper. By allowing users to pair presentation slides with their corresponding speaker notes, it streamlines the preparation process. The core magic lies in its automated booklet imposition engine: simply add your slides in chronological order, and the app will calculate the complex print layout for you. Once printed double-sided (flip on long edge) with A4 Portrait and cut horizontally, the pages fold into a perfect mini-booklet where the visual slide always appears on the left page and the script on the right. This allows users to give speeches with carefully made booklets instead of large plain paper or just their phones, making it more elegant. 

## **Key Features**

* **Smart Layout Imposition:** Automatically arranges pages into a 3-strip A4 layout, guaranteeing the correct reading sequence when folded.  
* **Drag-and-Drop & Batch Import:** Supports easy image uploading via drag-and-drop or by batch importing a local folder of images.  
* **Manual Drag Sorting:** We deliberately omitted auto-sorting upon import to prevent disrupting naturally ordered or pre-numbered files. Instead, a manual drag-and-drop sorting feature ensures you have complete control over the sequence.  
* **Offline Support & Local Caching:** All progress is automatically saved to the browser's local storage, protecting your work from accidental reloads or network disconnections.  
* **ZIP Export & Import:** Package your entire project-including the JSON structure and image assets into a single .zip file for offline backup or transferring between devices.  
* **Batch Management:** Quickly select, delete, or clear all pages.  
* **Blank Layouts for Handwriting:** You can intentionally leave text areas or image zones blank; the generator will create empty frames perfect for manual handwriting or sketching after printing.

## **Design Considerations & Limitations**

* **Character Limits & Overflow:** To ensure the printed booklet remains legible and visually balanced within the small 1/6 A4 panel, extremely long text may be cut off or require manual summarization. The layout is optimized for concise cue card notes rather than full essays.  
* **Image Optimization:** While high-resolution images can be imported, they are scaled down to fit the booklet dimensions. For optimal performance, especially when exporting to ZIP, pre-compressing images is recommended.

## **Future Roadmap**

* **Built-in Customization Editor:** We plan to introduce a visual editor allowing users to customize font sizes, typography, spacing, and borders before printing to accommodate different reading preferences and text lengths.  
* **Auto-Pagination for Long Texts:** Future updates may intelligently split overflowing text across multiple pages automatically.  
* **More Formats:** Expanding beyond the 3-strip A4 format to support other standard card sizes and folding methods.

&copy;Copyright 2026 Michael Hertz @ HEZ Group. All rights reserved.
