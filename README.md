# Hi, I'm Tarun Kumar 👋

I'm a physics grad student at IIT Gandhinagar working on gravitational wave detection. I spend most of my time thinking about how to make template banks more efficient and exploring ways machine learning can help us catch signals from merging black holes and neutron stars.

## What I'm working on

Right now, I'm deep into gravitational wave data analysis. My main focus has been on making template banks – the tool we use to search for gravitational wave signals – work better with fewer computational resources.

### 🌌 Recent Research

<table>
<tr>
<td width="60%">

**Smarter Template Placement**  
*Summer 2024, IIT Gandhinagar*

Working with Dr. Anand Sengupta, I found that using Halton sequences instead of random sampling can cover the same parameter space with 5-6% fewer templates. Sounds small, but when you're dealing with hundreds of thousands of templates, that adds up fast. Built everything from scratch using a ball-tree approach in chirp mass coordinates.

</td>
<td width="40%">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Halton_sequence_2D.svg/400px-Halton_sequence_2D.svg.png" alt="Halton sequence" width="100%"/>
<sub>Halton sequence pattern</sub>
</td>
</tr>
</table>

<table>
<tr>
<td width="40%">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Chirp_signal.svg/500px-Chirp_signal.svg.png" alt="Chirp signal" width="100%"/>
<sub>Gravitational wave chirp</sub>
</td>
<td width="60%">

**Testing Metric Approximations**  
*Jan-Apr 2025*

Dug into the math behind how we approximate gravitational waveform matches. Constructed the metric using Fisher information matrices and validated it against exact calculations. Basically making sure our shortcuts are actually accurate.

</td>
</tr>
</table>

<table>
<tr>
<td width="60%">

**Signal Extraction with Hilbert-Huang Transform**

Collaborated with Dr. Amit Reza from the Austrian Academy of Sciences on using HHT for pulling gravitational wave signals out of noisy detector data. Found that the first intrinsic mode function gives cleaner trigger times than the raw data, which could help pinpoint where signals come from in the sky.

</td>
<td width="40%">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/LIGO_measurement_of_gravitational_waves.svg/500px-LIGO_measurement_of_gravitational_waves.svg.png" alt="GW detection" width="100%"/>
<sub>LIGO gravitational wave detection</sub>
</td>
</tr>
</table>
### Side Projects

- Compared different regression methods (OLS, TLS, Huber) on noisy data – turns out Huber regression handles outliers way better
- Simulated quantum wave packet scattering using time-dependent Schrödinger equation (because sometimes you need a break from GWs)

## Background

- MSc Physics @ IIT Gandhinagar (2023-2025)
- BSc Physics @ Cluster University of Jammu
- Cleared JAM 2023, top 10% in NGPE-2023

## What I use

Python is my go-to (NumPy, SciPy, Matplotlib, PyCBC, scikit-learn, pandas). Also comfortable with LaTeX for writing papers and Wolfram for quick symbolic calculations.

## What's next

Planning to pursue a PhD in gravitational wave data analysis. I want to work on improving detection pipelines and parameter estimation methods – basically making LIGO and future detectors even better at catching these cosmic ripples.

## Outside research

When I'm not debugging code or reading papers, I'm usually:
- Stargazing or trying to photograph astronomical objects
- Thinking about how to explain complex physics to non-physicists
- Exploring new machine learning techniques that might be useful for GW analysis

## Get in touch

- Email: kumar.tarun@iitgn.ac.in
- [LinkedIn](https://www.linkedin.com/in/tarun-jindwan-324b69299/)
- [GitHub](https://github.com/Tarun354)

Always happy to chat about gravitational waves, template banks, or how ML can help with astrophysics research!
