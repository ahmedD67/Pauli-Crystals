<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="image1.png" alt="Logo" width="80" height="80">

  <h3 align="center">Pauli-Crystals-ReadME</h3>

  <p align="center">
    A project to generate images of the so called Pauli Crystals, a graphical representation of how particles in quantum systems arrange themselves.
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Five Particle Pauli Crystal][N6PauliCrystal]](https://example.com)

Pauli Crystals provide a spatial representation of the internal structure of a system of fermions in a 2D potential well. These crystals were frist hypothesized and simulated in Nov. 2015 by M Gajda et al. Experimental results were later confirmed in Jan 2021 by S. Jochim et al. A given 2D potential will admit a set of occupiable quantum states. When multiple fermionic particles are trapped in such a potential, each particle will occupy one of the quantum states with a corresponding wavefunction. The joint wavefunction for all the particles is given by the Slater determinant, whose absolute squared value is used as a probability density function (p.d.f).

The implementation of the MonteCarlo and Metropolis Hastings algorithms are used to generate a sample of 2N-dimensional position vectors for the particles in the trap. Each vector in the sample is rotated about the origin to align it as best as possible with the maximum probability vector. Doing so yields a new modified sample which results in a 2D histogram corresponding to the crystals generated.


### Built With

The two main libraries used in this project for the purposes of data manipulation.

* [![Numpy][Numpy-logo]][Numpy-url]
* [![Scipy][SciPy-logo]][SciPy-url]






<!-- GETTING STARTED -->
## Getting Started

To try this out, simply download the script and run it locally.

## Usage

At the moment, this script is exclusively useful in generating crystals belonging to two dimensional harmonic potentials with a deformation factor.





<!-- ROADMAP -->
## Roadmap

- [x] Add Circular Potential
- [x] Add Elliptical Potential
- [ ] Add Eigenstate solver
- [ ] Add 3D Spherical Potential





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

No, don't reach out.

Project Link: [https://github.com/ahmedD67/Pauli-Crystals/](https://github.com/ahmedD67/Pauli-Crystals/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Numpy-logo]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[Numpy-url]: https://numpy.org/
[SciPy-logo]: https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white
[SciPy-url]: https://scipy.org/
[N6PauliCrystal]: N5CircularPauli.png
