# eXplora Tailsitter VTOL

**Every single printable part of the project can be viewed in 3D on [OnShape](https://cad.onshape.com/documents/4c689e5b54cac6902d5813ec/w/fb80a5d05358b4e7959139db/e/8ae4df59a9bf6fdd0ec86a21)**

<img
  src="https://github.com/robustini/eXploraVTOL/blob/main/resources/explora_vtol_000.jpg"
  alt="eXplora Tailsitter VTOL"
  title="eXplora Tailsitter VTOL"
  style="display: inline-block; margin: 0 auto; max-width: 200px">

<img
  src="https://github.com/robustini/eXploraVTOL/blob/main/resources/explora_vtol_001.jpg"
  alt="eXplora Tailsitter VTOL"
  title="eXplora Tailsitter VTOL"
  style="display: inline-block; margin: 0 auto; max-width: 200px">

## Work in progress! ##

Given the massive requests we decided to make the repository public but it is still currently lacking documentation and specifications.

This will still give you the opportunity to view the entire project and print out all the individual components in order to finalize it.

We will complete the repository with everything we need as soon as possible.

To print the right wing you will need to mirror all the parts of the left wing in slicing, it is a very simple operation.

---

**eXplora Tailsitter VTOL** it was born from a concept by [Marco Robustini](https://www.linkedin.com/in/marco-robustini-a48a49a8/) four years ago.

Is a fully 3D printed vertical take-off UAS, a multi-role drone suitable for FPV, photogrammetry and other purposes, printed in PLA, ABS and TPU filament.

It comes in three formats: STL, 3MF and STEP, that way anyone can collaborate to improve it.

The slicing of this taislitter is complex, which is why all 3MF-format designs run with the powerful open source slicing software [SuperSlicer](https://github.com/supermerill/SuperSlicer) are provided.

![](https://github.com/robustini/eXploraVTOL/blob/main/resources/wing1_superslicer.gif)

If you decide to use other slicing software such as [Cura](https://3dgbire.com/pages/ultimaker-cura) you should consider adding reinforcements at crucial points, taking a cue from the 3MF projects we provide as an example, compatible only with SuperSlicer and PrusaSlicer.
In this case you will not have to use this 3MFs but import the STLs into your slicing software.

We used the [Gyroid](https://3dsolved.com/3d-printing-with-gyroid-infills-all-you-need-to-know/) infill for most of the profiles, it comes from Nature, butterflies have an identical structure inside their wings, and Nature is never wrong.
It guarantees lightness and incredible strength.

<img
  src="https://github.com/robustini/eXploraVTOL/blob/main/resources/gyroid.jpg"
  alt="Gyroid"
  title="Gyroid"
  style="display: inline-block; margin: 0 auto; max-width: 200px">


## How it works and what it takes to finish it ##

eXplora Tailsitter VTOL it requires flight control and other electronic components to operate.

It has been tested with [Ardupilot](https://ardupilot.org) and [PX4](https://px4.io).

This is the provisional [BOM](https://github.com/robustini/eXploraVTOL/tree/main/resources/BOM.md) to complete the UAS, continuously being updated, absent for now of screws and nuts.


## Videos ##

- [The first version of eXplora](https://youtu.be/43UC-_kWp0w)
- [The second version of eXplora](https://youtu.be/K6R6v6_kQL0)
- [Flight tests of the V0.9.0](https://youtu.be/hy-UXrUSplU)
- [Full automatic mission](https://youtu.be/9AJqqBkgcXk)
- [Acro capability test](https://youtu.be/VbT0gd1w8IY)
- [Ardupilot weathervaning feature](https://youtu.be/qcV7hz61uzA)


## User support ##

- [Discord channel](https://discord.gg/TCjNnfAEsB)
- [Ardupilot Discuss](https://discuss.ardupilot.org/t/explora-tailsitter-vtol-3d-printable-dual-motor-tailsitter/92341)


## How to get involved ##

- The eXplora Tailsitter VTOL project is open source and we encourage participation, if you can help in any way you are welcome!

- We have an active group of Beta Testers to help us improve our eXplora Tailsitter VTOL.

- Desired enhancements and issue can be posted to the [issues list](https://github.com/robustini/eXploraVTOL/issues).

- You can also open a [discussion](https://github.com/robustini/eXploraVTOL/discussions) to look for information or anything else.


## Simulation ##

<img
  src="https://github.com/robustini/eXploraVTOL/blob/main/resources/eXplora_Realflight.jpg"
  alt="eXplora Tailsitter VTOL"
  title="eXplora Tailsitter VTOL"
  style="display: inline-block; margin: 0 auto; max-width: 200px">

If you would like to try our VTOL the [model](https://github.com/robustini/eXploraVTOL/tree/main/simulation/eXplora_Tailsiter_VTOL.RFX) for Realflight is available.


## The team ##

- [Davide Silimbani](https://www.linkedin.com/in/davide-silimbani/): 3d design
- [Roberto Casoni](https://www.linkedin.com/in/roberto-casoni-463a5914a/): test pilot
- [Lorenzo Franco](https://www.linkedin.com/in/lorenzing/): GCS support
- [Edoardo Nunzi](https://www.linkedin.com/in/edoardo-nunzi-8176a31a2/): FPV test pilot
- Antonios Antzoulatos: 3d print test
- [Brandon MacDougall](https://www.linkedin.com/in/brandon-macdougall-b273907/): Realflight model
- [Marco Robustini](https://www.linkedin.com/in/robustini/): concept design, SuperSlicer project, in-flight tuning and tests


## License ##

The eXplora Tailsitter VTOL project is licensed under the [GNU General Public License, version 3](https://github.com/robustini/eXploraVTOL/blob/main/LICENSE).


## Credits ##

We would like to publicly thank the development team of Ardupilot, and to all the beta testers who helped us.

## Donate ##

If you would like to support this project you can make a [donation](https://paypal.me/marcopter).
