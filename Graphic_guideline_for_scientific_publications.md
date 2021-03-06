## Guide to Preparing Figures for Scientific Publication
> by Pengfei Liu (pengfei.liu@eas.gatech.edu)

### Overview
Figures are the centerpiece of a scientific paper. The aim of this document is to provide guidelines for graduate students and postdocs in my group on how to prepare figures for publications based on my personal experiences and some best practices in publishing industry. Note that different journals may have different requirements. However, figures prepared following this guide should work for most of journals.

### What software should I use?

I personally use MATLAB and Python for most of the data analysis and visualization (Matlab for experimental datasets and Python for modeling/satellite datasets). For research involving mass spectrometer data, Igor might be very useful. You may use other software (e.g., R) if you like. Excel is great for making some quick plots. However, I would recommend to learn at least one programming language (and master it!) other than Excel. 

I use Adobe Acrobat to make simple edits on PDF files (e.g., adding (a), (b) labels, rearranging panels, etc).

### General figure guide

Below is the formatting guide for figures from Nature: 
https://www.nature.com/nature/for-authors/formatting-guide

> Figures should be as small and simple as is compatible with clarity. The goal is for figures to be comprehensible to readers in other or related disciplines, and to assist their understanding of the paper. Unnecessary figures and parts (panels) of figures should be avoided: data presented in small tables or histograms, for instance, can generally be stated briefly in the text instead. Avoid unnecessary complexity, colouring and excessive detail.

> Figures should not contain more than one panel unless the parts are logically connected; each panel of a multipart figure should be sized so that the whole figure can be reduced by the same amount and reproduced on the printed page at the smallest size at which essential details are visible. For guidance, Nature’s standard figure sizes are 89 mm (single column) and 183 mm (double column) and the full depth of the page is 247 mm.

### Figure size, font, and file format

Always set the paper size (US letter, 8.5" * 11") and figure size in your software. This will ensure that your font size in figures are consistent. It is recommended to plot figures in their actual sizes that appear in publication. For a simple, single panel figure, use single column size (width < 89 mm/3.5" for Nature journals or <3.25" for ACS journals). For a complex, multiple-panel figure, you may use double column size (width < 183 mm/7.2" or 7"). The length should be < 9.5" so it fits into a single-page US letter paper. 

All text in figures should be in a sans-serif typeface (e.g., Arial, Calibri, Helvetica). Use Times New Roman only for the main text of your manuscript, but not for text in figures. 

If you plot figures in their actual sizes, font size 8 should be large enough. If you plot the figure 50% larger than actual size (not recommended), use font size 12.  

It is recommended to save your figures in vector format (e.g., PDF, eps). If you plot colored maps (e.g., pcolormesh, contour plots), you may rasterize the image part (using a resolution of 300 DPI or higher), because the file size of vectorized colored map can be very large and it is slow to open. However, the background (i.e., axes, ticks, labels) should still be in vector format and editable. Do not rasterize line art or text.

### Color maps

Use perceptually uniform color maps. See details in the article below:
https://www.nature.com/articles/s41467-020-19160-7

For colored plots showing differences (with both positive and negative values), it is ok to use diverging color maps.

Use RGB format (not CMYK).

### Axes, ticks, and grids

See this article in the link below:
https://www.nature.com/articles/nmeth.2337


