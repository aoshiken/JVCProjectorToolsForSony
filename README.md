# JVCProjectorToolsForSony

creating your own Gamma curves for Sony projectors which can directly be uploaded to the projector with Sony Image Director software (tested with V3.1).
This Tool is a modified version of ARVEHJ's project which can be found under:https://github.com/arvehj/jvcprojectortools)

The following changes had been made in comparison to V0.0.2 developed by ARVEHJ:
- Creates 1024 (10Bit) steps Gamma curves for Sony-Projectors instead of only 256 (8Bit) curves for JVC projectors
- Creates Sony Image Director compatible files which can directly be uploaded to a compatible Sony projector via Image Director
- Disable JVC specific menu entries
- Bugfix to avoid corruption of config files
- naming convention of config files has been changed to .sconf, because existing .conf files for JVC projectors are NOT compatible with this tool

Prerequisites

    Python 3.6 or later installed
    Sony Projector with Sony Image Director (latest V3.1 tested)
