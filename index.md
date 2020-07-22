---
layout: default
---

Hi, I am Shourya Bose, incoming PhD candidate at University of California, Santa Cruz. My research interests span control theory, networked control, and power systems.

Currently I am a visiting researcher at the Department of Electrical Engineering
at Indian Institute of Science in the [Control and Network Systems Group](http://www.ee.iisc.ac.in/people/faculty/pavant/group.html).

I graduated from with a Dual Degree from BITS Pilani (KK Birla Goa Campus) on December, 2019. I majored in M.Sc. (_Hons._) Mathematics, and B.E. (_Hons._) Electrical and
Electronics Engineering. I graduated with a First Class grade in both the subjects.

You can download my CV [_**here**_](./shourya_bose_curr_vitae.pdf).

_Jump to section:_ [Research](#research), [Other Works](#other-works), [Hobby Codes](#hobby-codes)

# Research

### Control Under Action-Dependent Markov PacketDrops: An Event-Triggered Approach ([Link](https://arxiv.org/abs/1912.03728), [PDF](./bose_iet2020.pdf))

**Submitted to IET Control Theory and Applications**.

This paper builds on the ICC conference paper (see below) and considers stabilization of a linear system with noisy evolution over a class of channels called **action-dependent Markov**.
This is a general class of packet-based channels wherein the channel state on the next timestep is dependent on both the channel state on the current timestep, as well as the action taken on the current timestep. In the current paper, said action refers to a transmission being made over the channel.

We propose a transmission policy to stabilize the system by transmitting plant state via the sensor to the controller over this channel. The algorithm determining the necessity of transmission on a given timestep is based on the philosophy of event-triggering, which aims to carry out control actions only when necessary, as opposed to actions carried out on every timestep. We provide a theoretical performance guarantee, and use the idea of _transmission fraction_ to demonstrate the effectiveness of our algorithm in achieving a lower utilization of the channel.

### Event-Triggered Second Moment Stabilization under Markov Packet Drops ([Link](https://ieeexplore.ieee.org/document/8715576), [PDF](./bose_icc2019.pdf))

**Presented at the Fifth Indian Control Conference, IIT Delhi, 2019**

This paper deals with networked control systems wherein the system evolution is noisy.
Furthermore, in the considered system, state measurements are made by a sensor and control action is applied by a controller. However,
the sensor and the controller are not co-located, and must instead communicate over an unreliable communication channel.

In this specific setting, we consider a system whose evolution is linear with additive noise. Furthermore, we model the channel
as a **Markov channel**, which is a class of channels broad enough to cover practical channels with packet-based communications,
wherein packet losses are possible. Assuming that the system is stabilizable in closed-loop, we propose a transmission policy
which ensures that the stabilization of the system also takes place over said channel. We provide a theoretical proof to demonstrate
the same.

Furthermore, we carry out a transmission fraction analysis, which demonstrates that our algorithm leads to a judicious use of channel resources.
Simulations carried out in MATLAB to validate the theoretical result, are also presented.

### Numerical Solution for a System of Fractional Differential Equations with Applications in Fluid Dynamics and Chemical Engineering ([Link](https://www.degruyter.com/view/j/ijcre.2017.15.issue-5/ijcre-2017-0093/ijcre-2017-0093.xml), [PDF](./bose_ijcre2017.pdf))

**Published in International Journal of Chemical Reactor Engineering (DeGruyter)**

This paper deals with numerical solution of Fractional Order Differential Equations (FODE's) over a finite time horizon.
We consider a system of n nonlinear coupled FODE's, with them possibly having different fractional indices. We decompose the fractional
derivative using the Haar Wavelet as a functional basis, and then use a Galerkin-based residual method to get a finite-basis representation
of the fractional derivative.

The solution methodology involves computing the fractional integral of the haar wavelet, for which a closed-form matrix representation
already exists in literature. We then carry out an optimization involving minimization of the residual, and this allows
us to demonstrate that as the number of haar wavelet bases used increases, the error between the proposed numerical solution and the
actual solution vanishes.

We validate our algorithm by solving several non-trivial ODE's proposed in chemical engineering literature using
our method on MATLAB.

# Other Works

### Pixxel Space

I am working as an intern in Pixxel Space, a startup company which is aiming to launch a constellation of earth observing satellites.
Data collected from this constellation will be fed to advanced AI for predictive analysis of soil components for customers.

As a part of the company, I helped in co-writing **Orbital Debris Assessment Report (ODAR)** ([what is ODAR?](https://docs.fcc.gov/public/attachments/DOC-354773A1.pdf)), which is
required by any satellite operator for FCC to license their satellite launch.

I also gained exposure to softwares such as NASA's GMAT, AGI's STK, and a.i. Solutions' FreeFlyer.

### Multibeam Satellite Precoding

I undertook a graded Design Project under the guidance of Dr. Nitin Sharma at BITS Pilani KK Birla Goa Campus. As a part of
the project, I understood the concept of signal power management and precoding in communication systems. I also proposed a few methods for efficient
precoding in a SATCOM (Satellite Communication) system.

### Hult Prize 2016 (Dubai Finals)

Hult Prize is an annual entrepreneurship competition organized on a global scale to encourage innovative entrepreneurial solutions to big world problems.

I was a part of _Project Vriddhi_, a team of 4 BITS Pilani, Goa students. We proposed an idea for urban decongestion using scheduled & shared transportation.
This was in response to solve the problem of [urban crowded slums](http://www.hultprize.org/wp-content/uploads/2017/07/Hult-Prize-2016-Case-Study_FINAL.compressed.pdf),
which was the Hult Prize Challenge for 2016. 

Our model included spatial decongestion of slums by an innovtive transport management system, which would include app notifications/SMS alerts for the employed residents,
which would be networked with the employers and transport vehicles. This would allow precise co-ordination of manpower through networked transportation, even if the 
job requirement was far away from the slum. This would enable the slum-dwelling labour to become competitive in the job market and earn a respectable living.

We implemented a prototype in the Zari slum of Goa, and the results allowed us to win the Hult Regional Finals at Goa. We then presented our idea at the Dubai finals
in front of eminent investors, technocrats, and social workers.

# Hobby Codes

### Unwinnable Tic-tac-toe ([Link](https://github.com/shourya01/minimax_implementation))

I wrote a basic code in C++ to implement a console-based tic-tac-toe game that is un-winnable by the human player.
This was achieved by using the Minimax algorithm to minimize a loss function corresponding to the possibility
of the machine losing. This loss function is re-evaluated after every human player move to provide provable impossibility
of the human player winning.