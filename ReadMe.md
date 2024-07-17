## Immunoprecipitation Device

The purpose of this repository is to store design files for a microfluidics device that can be used for immunoprecipitating epitope presenting phage/yeast without the use of magnetic beads.

Custom microfluidic footprints can be found in another repository: https://github.com/robertpuccinelli/PCBs/tree/master/libraries/custom-kicad/custom-footprints.pretty

## Change Log

### Rev B - 20240715
* Added a PDMS peristaltic micropump to allow for recirculation of contents in flow channels. See DOI: 10.1063/1.1947893
* Added valves to seal inlet and outlet.
* Lengthened serpentine channel to ~1250mm by reducing the spacing between adjacent paths.
* Reduced number of devices per wafer to (4) to reduce the impact of non-uniform wafer edges.
* Lengthened section of valves that uses positive photoresist to aid alignment and reduce rigidity.
* Added support structure to section of control lines that cross flow paths to prevent the formation of sieve valves.
* Added fiducial markers near the center of the mask to aid with flow layer alignment on translationally-limited mask aligners.
* Converted files to KiCAD 8
* Added a cat to an unused section of the "Flow.Pos" mask

