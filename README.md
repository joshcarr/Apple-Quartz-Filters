A handful of quartz filters for saving PDFs.

With all due respect to Jerome Colas:

https://discussions.apple.com/thread/1292868?start=0&tstart=0

https://public.me.com/jcolas

The following text is his:

It uses the poorly documented Quartz filtering ability for PDFs in Preview. There are a couple of articles I found here or elsewhere on the web, but they still don't make things simple.

You can manually edit those same settings (using Colorsync Utility) but can also benefit from my trial-and-error process and directly download from my iDisk.
After download and decompressions, *simply drag the downloaded "Filters" folder to your Library folder* (inside your user folder to install it just for this user, or at the root level of your hard disk in order to install it for all users) - And if you already have such a folder, simply copy the contents of the downloaded folder into it.

Feel free to use, download, copy, use the idea ... in any way you like.

*Then, in order to create a compressed PDF with decent quality :*

- Open your existing PDF in preview, or Print any document using "Open PDF in Preview" from the PDF pop-up menu in the Print dialog
- Choose Save As in the File Menu (pretty easy I guess), then choose PDF as format, and one of the "Reduce to XXX dpi ..." Quartz filters, and click Save.

I included 8 settings which produce increasingly large files, with increasingly better quality. I find the 150 dpi / average JPEG compression to be quite suitable for most purposes. I have tried (before Leopard) PDF compression software like PDFshrink but was not satisifed with the results and interface.

These filters produce much better (better being in terms of consistency, file size and quality) than the filter Apple includes with Leopard (and maybe Tiger ?).
The Apple "Reduce file size filter" scales images by 50%, with target dimensions between 128 and 512 pixels, which can give very unusable results.

The filters I use 2 two things:

- resample images to 75, 150, 300 or 600 dpi (I do not not if there is upsampling)
- compress the images using Jpeg compression at average or low quality

Once installed, you can visualize, edit or copy them using Colorsync Utility (in the Applications/ Utilities folder)

As an example, using a 73 MB PDF from a 55 page Powerpoint presentation, the compressed files have the following sizes:

- 75 dpi low quality : 2.7 MB
- 75 dpi average quality : 3.2 MB
- 150 dpi low quality : 4.2 MB
- 150 dpi average quality : 5.3 MB
- 300 dpi low quality : 7.6 MB
- 300 dpi average quality : 10.2 MB
- 600 dpi low quality : 16.0 MB
- 600 dpi average quality : 20.3 MB