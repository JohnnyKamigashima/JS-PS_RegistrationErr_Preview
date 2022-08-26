***
# PS Registration Error Preview
***
Copyright Johnny Kamigashima 2021

 Photoshop JSX script to preview possible printing registration errors on an image, this script will make use of Offset filter to unalign channels in order to make visible possible registration issues twithin the artwork.

 It is expected that the file of professionally coilor separated with correct trappings and set up in CMYK or Multichannel mode.

 The original file will not be changed, this script will generate a clone file, flattered and apply the actions in it and return to daved state every after iteration.

It is best if you use GScript or ESKO Automation Imaging to generate a PSD file from a PDF at at least 300 dpi resolution, you can also generate a PDF separated file from any application using Adobe PdfWriter or Adobe PPD to a PS file and Distill it in Acrobat distiller then recomposite the page-separated file in PS prior to running this script.

The first time you run this script in any file, it will ask for Offset in mm, resolution (better the most accurate rewult but slower depending on your computer), how many times it will automatically loop each run and delay between runs.
