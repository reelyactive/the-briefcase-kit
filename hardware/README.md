# The Briefcase Kit: Hardware Files

This folder contains files useful for the creation of the hardware for the briefcase kit:

## Hardware Case Vector Files

- nanukCasePanels.ai/dxf/svg : Vector graphics, at scale, of the case's false bottom and upper rim. Suitable for laser cutter or CNC machine. DXF, SVG, and AI files are the same.

## Assembly Notes

- We recommend using .25" (6mm) HDPE for the panels, as it is a good combination of strength and flexibility. Most laser cutter operations will not want to cut HDPE, so you'll need to use a CNC machine to cut the panels if you use this material. If you want to use a laser cutter, .25" (6mm) wood is recommended over acrylic, as acrylic will likely be too brittle for this purpose. 

- Most of the work is assembling the false bottom, with the components attached to it, and the wires successfully tucked underneath for the cleanest look. The half-circle holes on the sides of the false bottom are for passing wires from the devices, so they traverse underneath the false bottom. 

- We've used extra-strong velco to attach the power supply components under the false bottom, and it has worked well.

- The current assembly process involves a lot of screws on the upper lip piece, I reommend panhead screws for the best look. However, this means if you need to make modifications to the assembly on the false bottom, there are a lot of screws to undo. Therefore, double check your wiring before screwing the upper lip in place.

## Resources

- There's a 3D model of the Nanuk 935  case here, which we used for modeling the false bottom and other panels: https://nanukcases.ca/products/nanuk-935#downloads

- A 3d model for the IMPINJ R700 is here: [IMPINJ R700](https://impinj.sharepoint.com/sites/CustomerSupport/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FCustomerSupport%2FShared%20Documents%2FSupport%20Portal%2FSystems%2FR700%20Series%2FR700%2FDocumentation%2FDrawings%20%28CAD%2DSTEP%29&p=true&ga=1), but this model is too complex for printing, so I made a simplified, but size-accurate version which can be found in this folder, as IMPINJRemodeled.stl.
