# JVCProjectorToolsForSony

With this tool it is possible to create Gamma curves for Sony projectors which can directly be uploaded with the Sony Image Director software (tested with latest V3.1).
This Tool is a modified version of ARVEHJ's project which can be found under:https://github.com/arvehj/jvcprojectortools)

The following changes had been made in comparison to the V0.0.2 developed by ARVEHJ:
- Creates 1024 (10Bit) steps Gamma curves for Sony-Projectors instead of only 256 (8Bit) curves for JVC projectors
- Creates Sony Image Director compatible files which can directly be uploaded to a compatible Sony projector via Image Director
- Disable JVC specific menu entries
- Bugfix to avoid corruption within config files
- naming convention of config files has been changed to .sconf, because existing .conf files for JVC projectors are NOT compatible with this tool

Prerequisites

    Python 3.6 or later installed
    Sony Projector with Sony Image Director (latest V3.1 tested)
    
Creating Gamma curves

    Please use the several available tutorials available for the JVC based version.
    
