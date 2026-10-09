# Formula Student, D.A.R.T. Daedalus Racing Team

Ioanna Texakalidou, Powertrain and Electronics Subteam Leader, International Hellenic University, 2023 to 2025

D.A.R.T. was a newly founded Formula Student team, so my two years were spent in the vehicle design phase. I led a subteam of about 10 people working on powertrain and electronics hardware, and I also took on the impact attenuator.

## Impact attenuator (December 2023)

The impact attenuator is the crushable nose at the very front of the car that protects the driver in a frontal crash. The Formula Student 2023 rules require it to absorb at least 7,350 J when hitting a barrier at 7 m/s, while keeping the deceleration under 20 g average and 40 g peak.

I read through published IA designs and test papers and the 2023 rules, then designed a new IA shape in Fusion 360 as an alternative to the team's first concept. The version shown here has 18 mm fillets on the edges.

![Engineering drawing of my IA proposal](figures/drawing.png)

As a first check I ran linear static FEA in Fusion 360 for three load directions, frontal, diagonal and side, and looked at stress, displacement, strain and safety factor. The images show the displacement results.

| Frontal load | Diagonal load | Side load |
|---|---|---|
| ![](figures/fea_frontal.png) | ![](figures/fea_diagonal.png) | ![](figures/fea_side.png) |

Looking back, these runs were an early stiffness check and not a crash analysis. The applied loads were a few kN, while the rules imply about 59 kN on average (300 kg at 20 g) and up to about 118 kN at the 40 g peak. Some local areas near the mounting points also went below a safety factor of 1. An impact attenuator is meant to crush and absorb 7,350 J, which means plastic deformation over at least about 125 mm, so linear static FEA can't show whether it works. The proper next step would be an explicit dynamic simulation (for example LS-DYNA) and a drop test. The team was still in the design phase and hadn't reached that point.

## Powertrain parts

Two of the powertrain parts I designed in Fusion 360 for the engine.

| 4-into-1 exhaust header | Intake runners |
|---|---|
| ![](figures/exhaust_header.png) | ![](figures/intake_runners.png) |

## Tools

Fusion 360 (CAD, drawings, static FEA), Formula Student Rules 2023

Contact: j.texakalidou@gmail.com | [Portfolio](https://ioannatexakalidou.github.io)
