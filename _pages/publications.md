---
title: Publications
layout: page
permalink: "/publications"
---

#### [Google Scholar](https://scholar.google.com/citations?user=7O6Qq_kAAAAJ&hl=en) and [Scopus](https://www.scopus.com/authid/detail.uri?authorId=56912954900)

<head>
    <script src="https://code.highcharts.com/highcharts.js"></script>
</head>
<div id="container" style="height: 400px; width: 600px;"></div>

<script>
document.addEventListener('DOMContentLoaded', function () {
    const data = [
        { year: 2015, papers: 2, citations: 0 },
        { year: 2016, papers: 2, citations: 7 },
        { year: 2017, papers: 5, citations: 23 },
        { year: 2018, papers: 4, citations: 42 },
        { year: 2019, papers: 10, citations: 101 },
        { year: 2020, papers: 7, citations: 131 },
        { year: 2021, papers: 4, citations: 171 },
        { year: 2022, papers: 9, citations: 281 },
        { year: 2023, papers: 9, citations: 264 },
        { year: 2024, papers: 12, citations: 299 },
        { year: 2025, papers: 5, citations: 170 }
    ];

    const seriesData = (field) => data.map(item => [Date.UTC(item.year, 0, 1), item[field]]);
    
    Highcharts.chart('container', {
        chart: { zoomType: 'xy' },
        title: { text: 'Total Citations: 1,490 &  H-index: 18 (Scopus)' },
        xAxis: { type: 'datetime', title: { text: 'Year' }, labels: { format: '{value:%Y}' } },
        yAxis: [
            { title: { text: 'Papers' }, opposite: true },
            { title: { text: 'Citations' }, opposite: false }
        ],
        tooltip: { shared: true, split: false, enabled: true },
        series: [
            { name: 'Papers', type: 'column', data: seriesData('papers'), color: '#979a9a' },
            { name: 'Citations', type: 'line', data: seriesData('citations'), yAxis: 1, marker: { enabled: true }, color: '#229954', lineWidth: 2 }
        ]
    });
});
</script>


### Papers in Peer-Reviewed Journal
(*: corresponding author; †: equal contribution)
### Preprints
69.  V. V. Thanh\* and **N. T. Hung**\*, [Strain effect on Rashba splitting and phonon scattering to improve thermoelectric performance of 2D heterobilayer MoTe2/PtS2](https://doi.org/10.48550/arXiv.2504.16781), ***arXiv:2504.16781*** submitted.
68. **N. T. Hung**\*, V. V. Thanh\*, M. Li and T. Shimada, [Strain effect on optical properties and quantum weight of 2D magnetic topological insulators MnBi2X4 (X = Te, Se, S)](https://doi.org/10.48550/arXiv.2504.10879), ***arXiv:2504.10879*** submitted.
67. C. L. Fu\*†, M. Cheng†, **N. T. Hung**†, E. Rha, Z. Chen, R. Okabe, D. C. Carrizales, M. Mandal, Y. Cheng and M. Li\*, [AI‑driven defect engineering for advanced thermoelectric materials](https://doi.org/10.48550/arXiv.2503.19148), ***arXiv:2503.19148*** submitted.
66. M. Cheng\*†, C. L. Fu†, R. Okabe†, A. Chotrattanapituk, A. Boonkird, **N. T. Hung** and M. Li\*, [AI‑driven approaches for materials design and discovery](https://doi.org/10.48550/arXiv.2502.02905), ***arXiv:2502.02905*** submitted.
65. R. Okabe\*, M. Cheng, A. Chotrattanapituk, M. Mandal, D. C. Carrizales, **N. T. Hung**, X. Fu, B. Han, Y. Wang, W. Xie, R.
J. Cava, T. S. Jaakkola, Y. Cheng\* and M. Li\*, [Structural constraint integration in generative model for discovery of quantum material candidates](https://doi.org/10.48550/arXiv.2407.04557), ***arXiv:2407.04557*** submitted.
{: reversed="reversed"}
{:start="69"}
### 2025
64. N. Muhammad, W. Mu, **N. T. Hung**\*, T. Yang\* and D. Zejun\*, [Highly in-plane anisotropic 2D-ZrGeTe4: A promising thermoelectric material with high power factor and figure of merit](https://doi.org/10.1021/acsaem.5c00023), ***ACS Appl. Energy Mater.*** accepted (2025).
63. N. T. G. Bao, T. N. Q. Trang, N. Thoai, P. B. Thang, V. T. H. Thu\* and **N. T. Hung**\*, [Rational design 2D heterobilayers transition‑metal dichalcogenide and their Janus for efficient water splitting](https://doi.org/10.1021/acsaem.5c00175), ***ACS Appl. Energy Mater.*** 8, 5209-5221 (2025).
62. W. Mu, N. Muhammad, B. Dong, **N. T. Hung**\*, H. Guo\*, R. Saito, W. Gong, T. Yang\* and Z. Zhang, [Enhanced thermoelectric properties of the topological phase of monolayer HfC](https://doi.org/10.1088/1674-1056/adbd17), ***Chin. Phys. B*** 34, 057301-1-9 (2025)
61. D. P. Gulo, **N. T. Hung**, W. L. Chen, S. Wang, M. Liu, E. I. Kauppinen, H. Takehara, A. Taguchi, T. Taniguchi, S. Maruyama, Y. M. Chang, R. Saito\* and H. L. Liu\*, [Quenching of defect-induced photoluminescence in a boron-nitride and carbon hetero-nanotube](https://doi.org/10.1021/acs.jpclett.4c03681), ***J. Phys. Chem. Lett.*** 16, 1711-1719  (2025)
60. H. Gao, D. Zhou, L. Ping, Z. Wang, **N. T. Hung**, J. Cao, M. Geiwitz, G. Natale, Y. C. Lin, K. S. Burch, R. Saito, M. Terrones and X. Ling\*, [Downscaling of non-van der Waals semimetalic W5N6 with resistivity preservation](https://doi.org/10.1021/acsnano.4c12155), ***ACS Nano*** 19, 3362-3371 (2025).
59. Y. Zhang, R. Liu, J. Huang\*, **N. T. Hung**, R. Saito, T. Yang\* and Z. Zhang, [DUV double-resonant Raman spectra and interference effect in graphene: first-principles calculations](https://doi.org/10.1002/jrs.6768), ***J. Raman Spectrosc.*** 56, 316-323 (2025).
{: reversed="reversed"}
{:start="64"}
### 2024
58. R. Liu, L. Li, Y. Zhang, J. Huang\*, M. Lin, **N. T. Hung**, Z. Wang, Z. Zhang, R. Saito, P. Tan\* and T. Yang\*, [Helicity selection rule of double resonance Raman spectra for monolayer MoSe2](https://doi.org/10.1103/PhysRevB.110.245422), ***Phys. Rev. B*** 110, 245422-1-9 (2024).
57. C. H. Yao, H. Gao, L. Ping, D. P. Gulo, H. L. Liu, **N. T. Hung**, R. Saito\* and X. Ling\*, [Nontrivial Raman characteristics in 2D non-van der Waals Mo5N6](https://doi.org/10.1021/acsnano.4c06250), ***ACS Nano*** 18, 32458-32467 (2024).
56. **N. T. Hung**\*, R. Okabe,  A. Chotrattanapituk and M. Li\*, [Universal ensemble-embedding graph neural network for direct prediction of optical spectra from crystal structure](https://doi.org/10.1002/adma.202409175), ***Adv. Mat.*** 36, 2409175-1-11 (2024).
>Press release: “[AI speeds up the discovery of energy and quantum materials](https://www.tohoku.ac.jp/en/press/ai_speeds_up_discovery_of_energy_and_quantum_materials.html)” on Oct. 7, 2023 by Tohoku University. An illustration of this paper was also selected as a [frontispiece](https://doi.org/10.1002/adma.202470369).
55. M. Mandal\*, A. Chotrattanapituk, K. Woller, L. Wu, H. Xu, **N. T. Hung**, N. Mao, R. Okabe, A. Boonkird, T. Nguyen, N. C. Drucker, X. M. Chen, T. Momiki, J. Li, J. Kong, Y. Zhu\* and M. Li\*, [Precise Fermi level engineering in a topological Weyl semimetal via fast ion implantation](https://doi.org/10.1063/5.0181361), ***Appl. Phys. Rev.*** 11, 021429-1-8 (2024).
> Press release: “[A new approach to fine-tuning quantum materials](https://news.mit.edu/2024/new-approach-fine-tuning-quantum-materials-0812)” on Jul. 17, 2024, by MIT. This paper was selected as a featured article and highlighted in the newsletter: "[Fast H+-ion implantation enables precise Fermi level engineering in quantum materials](https://doi.org/10.1557/s43577-024-00822-6)" by MRS Bulletin 49, 1189 (2024).
54. H. L. Liu\*, H. W. Chen, **N. T. Hung**, Y. C. Chen, H. J. Liu, C. T. Chen, Y. L. Chueh, Y. H. Chu, and R. Saito, [Temperature-dependent indirect gaps for two-dimensional bismuth oxychalcogenides probed by spectroscopic ellipsometry](https://doi.org/10.1088/2053-1583/ad50ad), ***2D Mater.*** 11, 035029-1-11 (2024).
53. **N. T. Hung**\*, N. Thanh, V. V. Thanh, S. Wang, R. Saito\* and M. Li\*,  [Symmetry breaking in 2D materials for optimizing second-harmonic generation](https://doi.org/10.1088/1361-6463/ad4a80), ***J. Phys. D: Appl. Phys.*** 57, 333002-1-16 (2024). (Invited review)
52. S. N. Kajale, T. Nguyen, **N. T. Hung**, M. Li and D. Sarkar\*, [Field-free deterministic switching of all-van der Waals spin-orbit torque system above room temperature](https://doi.org/10.1126/sciadv.adk8669), ***Sci. Adv.*** 10, eadk8669-1-7 (2024).
> Press release: “[Propelling atomically layered magnets toward green computers](https://news.mit.edu/2024/propelling-atomically-layered-magnets-toward-green-computers-0404)” on Apr. 04, 2024, by MIT. This paper was also highlighted in the newsletter: "[Van der Waals magnet integration for energy-efficient spintronics](https://doi.org/10.1038/s44287-024-00048-3)" by Nature Reviews Electrical Engineering 1, 217 (2024).
51. R. Saito\*, **N. T. Hung**\*, T. Yang, J. Huang, H. L. Liu\*, D. P. Gulo, S. Han and L. Tong\*, [Deep-ultraviolet and helicity-dependent Raman spectroscopy for carbon nanotubes and 2D materials](https://doi.org/10.1002/smll.202308558), ***Small*** 2308558-1-17 (2024). (Invited review)
50. **N. T. Hung**\*, J. Huang, Y. Tatsumi, T. Yang and R. Saito\*, [QERaman: An open-source program for calculating resonance Raman spectra based on Quantum ESPRESSO](https://doi.org/10.1016/j.cpc.2023.108967), ***Comput. Phys. Commun.*** 295, 108967-1-9 (2024).
>GitHub source: [https://github.com/nguyen-group/QERaman](https://github.com/nguyen-group/QERaman).
49. V. V. Thanh\*, D. V. Truong and **N. T. Hung**\*, [Janus 2D B2P6: A promising anisotropic thermoelectric material with high power factor](https://doi.org/10.1016/j.surfin.2023.103829), ***Surf. Interfaces*** 44, 103829-1-8 (2024).
{: reversed="reversed"}
{:start="58"}
### 2023
48. **N. T. Hung**\*, [The role of spin-orbit interaction in low thermal conductivity of Mg3Bi2](https://doi.org/10.1063/5.0183615), ***Appl. Phys. Lett.*** 123, 252109-1-5 (2023).
47. D. P. Gulo, **N. T. Hung**, W. L. Chen, S. Wang, M. Liu, E. I. Kauppinen, S. Maruyama, Y. M. Chang, R. Saito and H. L. Liu\*, [Interacting phonons between layers in Raman spectra of carbon nanotubes inside boron-nitride nanotubes](https://doi.org/10.1021/acs.jpclett.3c02528), ***J. Phys. Chem. Lett.*** 14, 10263-10270 (2023).
46. **N. T. Hung**\*†, K. Zhang†, V. V. Thanh, Y. Guo, A. A. Puretzky, D. B. Geohegan, J. Kong, S. Huang\* and R. Saito\*, [Nonlinear optical responses of Janus MoSSe/MoS2 heterobilayers optimized by stacking order and strain](https://doi.org/10.1021/acsnano.3c04436), ***ACS Nano*** 17, 19877-19886 (2023) († Equal contribution).
>Press release: “[Stacking order and strain boosts second-harmonic generation with 2D Janus hetero-bilayers](https://www.tohoku.ac.jp/en/press/stacking_order_strain_boosts_second_harmonic_generation.html)” on Sep. 26, 2023 by Tohoku University. An illustration of this paper was also selected as a [front cover](https://pubs.acs.org/cms/10.1021/ancac3.2023.17.issue-20/asset/ancac3.2023.17.issue-20.xlargecover-2.jpg).
45. S. Han, **N. T. Hung**, Y. Xie, R. Saito\*, J. Zhang and L. Tong\*, [Observing axial chirality of chiral single-wall carbon nanotube by helicity‐dependent Raman spectra](https://doi.org/10.1021/acs.nanolett.3c01791), ***Nano Lett.*** 23, 8454-8459 (2023).
44. H. L. Liu\*, B. D. Annawati, **N. T. Hung**, D. P. Gulo, P. Solis-Fernandez, K. Kawahara, H. Ago and R. Saito, [Interference of excitons and surface plasmons in the optical absorption spectra of monolayer and bilayer graphene](https://doi.org/10.1103/PhysRevB.107.165421), ***Phys. Rev. B*** 107, 165421-1-10 (2023).
43. D. P. Gulo, **N. T. Hung**, R. Sankar, R. Saito and H. L. Liu\*, [Exploring optical properties of 2H- and 1T'-MoTe2 single crystals by spectroscopic ellipsometry](https://doi.org/10.1103/PhysRevMaterials.7.044001), ***Phys. Rev. Mater.*** 7, 044001-1-13 (2023).
42. R. Natsui, H. Shimizu, Y. Nakanishi\*, Z. Liu, A. Shimamura, **N. T. Hung**, Y. C. Lin, T. Endo, J. Pu, I. Kikuchi, T. Takenobu, S. Okada, K. Suenaga, R. Saito\* and Y. Miyata\*, [Vapor-phase indium intercalation in van der Waals nanofibers of atomically thin W6Te6 wires](https://doi.org/10.1021/acsnano.2c10997), ***ACS Nano*** 17, 5561-5569 (2023).
>Press release: “[Scientists thread rows of metal atoms into nanofiber bundles](https://www.eurekalert.org/news-releases/981243)” on Mar. 4, 2023 by Tokyo Metropolitan University. An illustration of this paper was also selected as a [front cover](https://pubs.acs.org/cms/10.1021/ancac3.2023.17.issue-6/asset/ancac3.2023.17.issue-6.xlargecover-3.jpg).
41. V. V. Thanh\*, D. V. Truong and **N. T. Hung**\*, [Janus γ-GeSSe monolayer as a high-performance material for photocatalysis and thermoelectricity](https://doi.org/10.1021/acsaem.2c03316), ***ACS Appl. Energy Mater.*** 6, 910-919 (2023).
{: reversed="reversed"}
{:start="48"}
### 2022
40. F. R. Pratama\*, R. Saito and **N. T. Hung**\*, [Magneto-Seebeck coefficient of the Fermi liquid in three-dimensional Dirac and Weyl semimetals](https://doi.org/10.1103/PhysRevB.106.L081304), ***Phys. Rev. B: Lett.*** 106, L081304 (2022).
39. D. P. Gulo, **N. T. Hung**, T. J. Yang, G. J. Shu, R. Saito and H. L. Liu\*, [Exploring unusual temperature-dependent optical properties of graphite single crystal by spectroscopic ellipsometry](https://doi.org/10.1016/j.carbon.2022.06.032), ***Carbon*** 197, 485-493 (2022).
38. **N. T. Hung**\*, A. R. T. Nugraha, J. M. Adhidewata and R. Saito, [Enhanced thermoelectric performance by van Hove singularities in the density of states of type-II nodal-line semimetals](https://doi.org/10.1103/PhysRevB.105.115142), ***Phys. Rev. B*** 105, 115142-1-5 (2022).
37. L. X. Dien\*, T. Murayama, **N. T. Hung**, Q. D. Truong, H. D. Chinh, M. Yoshimura, M. Haruta and T. Ishida\*, [Efficient non-volatile organogold complex for TiO2-supported gold cluster catalysts: Preparation and catalytic activity for CO oxidation](https://doi.org/10.1016/j.jcat.2022.03.008), ***J. Catal.*** 408, 236-244 (2022).
36. V. V. Thanh\*, N. D. Van, D. V. Truong and **N. T. Hung**\*, [Effects of strain and electric field on electronic and optical properties of monolayer γ-GeX (X = S, Se and Te)](https://doi.org/10.1016/j.apsusc.2021.152321), ***Appl. Surf. Sci.*** 582, 152321-1-10 (2022).
35. S. Han†, Y. Zhao†, **N. T. Hung**†, B. Xu, R. Saito\*, J. Zhang and L. Tong\*, [Complex Raman tensor in helicity-changing Raman spectra of black phosphorus by circularly polarized light](https://doi.org/10.1021/acs.jpclett.1c03826), ***J. Phys. Chem. Lett.*** 13, 1241–1248 (2022). († Equal contribution)
{: reversed="reversed"}
{:start="40"}
### 2021
34. W. V. Sinambela, S. A. Wella, F. S. Arsyad, **N. T. Hung** and A. R. T. Nugraha\*, [Electronic, optical, and thermoelectric properties of bulk and monolayer germanium tellurides](https://doi.org/10.3390/cryst11111290), ***Crystals*** 11, 1290‐1‐12 (2021).
33. S. Wang\*, **N. T. Hung**, H. Tian, M. S. Islam and R. Saito, [Switching behavior of a heterostructure based on periodically doped graphene nanoribbon](https://doi.org/10.1103/PhysRevApplied.16.024030), ***Phys. Rev. Appl.*** 16, 024030 (2021).
32. R. Saito\*, M. S. Ukhtary, S. Wang and **N. T. Hung**, [Selection rule for Raman spectra of two‐dimensional materials using circularly‐polarized vortex light](https://doi.org/10.1039/D1CP02209A), ***Phys. Chem. Chem. Phys.*** 23, 17271-17278 (2021).
31. **N. T. Hung**\* and R. Saito, [The origin of quantum effects in low-dimensional thermoelectric materials](https://doi.org/10.1002/qute.202000115), ***Adv. Quantum Technol.*** 4, 2000115 (2021). (Invited review)
>An illustration of this review paper was selected as a [back cover](https://doi.org/10.1002/qute.202170013).
30. V. V. Thanh\*, N. D. Van, D. V. Truong and **N. T. Hung**\*, [Charge-induced high-performance actuation of borophene](https://doi.org/10.1088/1361-6463/abc8b5), ***J. Phys. D: Appl. Phys.*** 54, 105504-1-8 (2021).
{: reversed="reversed"}
{:start="34"}
### 2020
29. K. Zhang, T. Wang, X. Pang, F. Han, S. L. Shang, **N. T. Hung**, Z. K. Liu, M. Li\*, R. Saito\* and S. Huang\*, [Anisotropic Fano resonance in the Weyl semimetal candidate LaAlSi](https://doi.org/10.1103/PhysRevB.102.235162), ***Phys. Rev. B*** 102, 235162-1-8 (2020).
28. S. D. N. Luu\*, A. R. Supka, V. H. Nguyen, D. V. N. Vo, **N. T. Hung**, K. T. Wojciechowski, M. Fornari and P. Vaqueiro\*, [Origin of low thermal conductivity in In4Se3](https://doi.org/10.1021/acsaem.0c02489), ***ACS Appl. Energy Mater.*** 3, 12549-12556 (2020).
27. V. V. Thanh\*, N. D. Van, D. V. Truong, R. Saito and **N. T. Hung**\*, [First-principles study of mechanical, electronic and optical properties of Janus monolayer of transition metal dichalcogenides](https://dx.doi.org/10.1016/j.apsusc.2020.146730), ***Appl. Surf. Sci.*** 526, 146730-1-8 (2020).
26. **N. T. Hung**\*, A. R. T. Nugraha, T. Yang and R. Saito, [Confinement effect in thermoelectric properties of two-dimensional materials](https://dx.doi.org/10.1557/adv.2020.128), ***MRS Adv.*** 5, 469-479 (2020). (Invited review)
25. K. Zhang, X. Pang, T. Wang, F. Han, S. L. Shang, **N. T. Hung**, A. R. T. Nugraha, Z. K. Liu, M. Li\*, R. Saito\* and S. Huang\*, [Anomalous phonon-mode dependence of polarization-resolved Raman spectroscopy in topological semimetal TaP](https://doi.org/10.1103/PhysRevB.101.014308), ***Phys. Rev. B*** 101, 014308-1-9 (2020).
>Press release: “[New class of materials shows strange electron properties](https://www.psu.edu/news/research/story/new-class-materials-shows-strange-electron-properties/)” on Feb. 13, 2020 by Pennsylvania State University.
24. Q. D. Truong\*, L. C. Yin, **N. T. Hung**, D. N. Nguyen, Y. Gambe, K. Nayuki, Y. Sasaki, H. Kobayashi, R. Saito, P. D. Tran and I. Honma, [Anionic redox in a-(Mo3S11)n polymer cathode for all-solid-state Li-ion battery](https://doi.org/10.1016/j.electacta.2019.135218), ***Electrochim. Acta*** 332, 135218-1-8 (2020).
{: reversed="reversed"}
{:start="29"}
### 2019
23. **N. T. Hung**\*, L. C. Yin, P. D. Tran and R. Saito, [Simultaneous anionic and cationic redox in Mo3S11 polymer electrode of sodium-ion battery](https://doi.org/10.1021/acs.jpcc.9b09325), ***J. Phys. Chem. C*** 123, 30856-30862 (2019).
22. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Thermoelectric properties of carbon nanotubes](https://doi.org/10.3390/en12234561), ***Energies*** 12, 4561 (2019). (Invited review)
21. V. V. Thanh\*, D. V. Truong and **N. T. Hung**\*, [Charge-induced electromechanical actuation of two- dimensional hexagonal and pentagonal materials](https://doi.org/10.1039/C9CP03129D), ***Phys. Chem. Chem. Phys.*** 21, 22377-22384 (2019).
20. S. Li, Y. Xia, M. Amachra, **N. T. Hung**, Z. Wang\*, S. P. Ong\* and R. J. Xie\*, [Data-driven discovery of full-visible-spectrum phosphor](https://doi.org/10.1021/acs.chemmater.9b02505), ***Chem. Mater.*** 31, 6286-6294 (2019).
19. E. H. Hasdeo\*, L. P. A. Krisna, M. Y. Hanna, B. E. Gunara, **N. T. Hung** and A. R. T. Nugraha\*, [Optimal band gap for improved thermoelectric performance of two-dimensional Dirac materials](https://doi.org/10.1063/1.5100985), ***J. Appl. Phys.*** 126, 035109 (2019).
18. M. Vila, **N. T. Hung**, S. Roche and R. Saito, [Tunable circular dichroism and valley polarization in the modified Haldane model](https://doi.org/10.1103/PhysRevB.99.161404), ***Phys. Rev. B: Rap. Comm.*** 99 161404R (2019).
{: reversed="reversed"}
{:start="23"}
### Before PhD
17. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Designing high-performance thermoelectrics in two-dimensional tetradymites](https://doi.org/10.1016/j.nanoen.2019.02.015), ***Nano Energy*** 58, 743-749 (2019).
16. B. Dong, Z. Wang\*, **N. T. Hung**, A. R. Oganov, T. Yang\*, R. Saito and Z. Zhang, [New two-dimensional phase of tin chalcogenides: candidates for high-performance thermoelectric materials](https://doi.org/10.1103/PhysRevMaterials.3.013405), ***Phys. Rev. Mater.*** 3, 013405-1-9 (2019).
15. **N. T. Hung**\*, A. R. T. Nugraha, T. Yang, Z. Zhang and R. Saito, [Thermoelectric performance of monolayer InSe improved by convergence of multivalley bands](https://doi.org/10.1063/1.5040752), ***J. Appl. Phys.*** 125, 082502 (2019). 
14. V. V. Thanh\*, **N. T. Hung**\* and D. V. Truong, [Charge-induced electromechanical actuation of Mo- and W-dichalcogenide monolayers](http://dx.doi.org/10.1039/C8RA08248K), ***RSC Adv.*** 8, 38667-38672 (2018).
13. Q. D. Truong†, **N. T. Hung**†, Y. Nakayasu, K. Nayuki, Y. Sasaki, D. M. Kempaiah, L. C. Yin, T. Tomai, R. Saito and I. Honma\*, [Inversion domain boundaries in MoSe2 layers](https://doi.org/10.1039/C8RA07205A), ***RSC Adv.*** 8, 33391–33397 (2018). († Equal contribution)
12. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Universal curve of optimum thermoelectric figure of merit for bulk and low-dimensional semiconductors](https://doi.org/10.1103/PhysRevApplied.9.024019), ***Phys. Rev. Appl.*** 9, 024019 (2018). 
>This paper belonging to the collection: [Millie Dresselhaus: Her living scientific legacy](https://journals.aps.org/prapplied/collections/mildred-dresselhaus).
11. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Two-dimensional MoS2 electrochemical actuator](https://doi.org/10.1088/1361-6463/aaa68f), ***J. Phys. D: Appl. Phys.*** 51, 075306 (2018).
10. R. Saito\*, A. R. T. Nugraha, E. H. Hasdeo, **N. T. Hung** and W. Izumida,  [Electronic and optical properties of single wall carbon nanotubes](https://doi.org/10.1007/s41061-016-0095-2), ***Top. Curr. Chem.*** 375, 1-24 (2017). (Invited review)
9. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Three-dimensional carbon Archimedean lattices for high-performance electromechanical actuators](https://doi.org/10.1016/j.carbon.2017.09.083), ***Carbon*** 125, 472-479 (2017).
8. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Size effect in thermoelectric power factor of nondegenerate and degenerate low-dimensional semiconductors](https://doi.org/10.1016/j.matpr.2017.10.005), ***Mater. Today: Proc.*** 4, 12368-12373 (2017).
7. **N. T. Hung**\*, A. R. T. Nugraha\* and R. Saito, [Two-dimensional InSe as a potential thermoelectric material](https://dx.doi.org/10.1063/1.5001184), ***Appl. Phys. Lett.*** 111, 092107 (2017).
6. **N. T. Hung**\*, A. R. T. Nugraha and R. Saito, [Charge-induced electrochemical actuation of armchair carbon nanotube bundles](https://dx.doi.org/10.1016/j.carbon.2017.03.036), ***Carbon*** 118, 278-284 (2017).
5. **N. T. Hung**\*, E. H. Hasdeo, A. R. T. Nugraha, M. S. Dresselhaus and R. Saito, [Quantum effects in the thermoelectric power factor of low-dimensional semiconductors](https://dx.doi.org/10.1103/PhysRevLett.117.036602), ***Phys. Rev. Lett.*** 117, 036602 (2016). 
>Press release: “[Theory of thermoelectric properties updated after 23 years](https://www.tohoku.ac.jp/en/press/thermoelectric_properties_theory_updated.html)” on Aug. 23, 2016 by Tohoku Univeristy. This paper was highlighted in the newsletter: "[IoT devices could tap ambient heat for power - Triangular quantum wells quadruple the performance of thermoelectric materials](https://spectrum.ieee.org/thermoelectric-effect-iot)" on Jan. 19, 2024, by IEEE Spectrum.
4. **N. T. Hung**\*, D. V. Truong, V. V. Thanh and R. Saito, [Intrinsic strength and failure behaviours of ultra-small single-walled carbon nanotubes](https://dx.doi.org/10.1016/j.commatsci.2015.12.036), ***Comput. Mater. Sci.*** 114, 167-171 (2016).
3. **N. T. Hung**\*, A. R. T. Nugraha\*, E. H. Hasdeo, M. S. Dresselhaus and R. Saito, [Diameter dependence of thermopower of semiconducting carbon nanotubes](https://dx.doi.org/10.1103/PhysRevB.92.165426), ***Phys. Rev. B*** 92, 165426 (2015). 
>This paper was highlighted in the newsletter: "[Thermoelectrics: Carbon nanotubes get high](https://doi.org/10.1038/nenergy.2016.37)" on Apr. 04, 2016, by Nature Energy.
2. **N. T. Hung** and D. V. Truong\*, [Ab initio study of the structural transformations and pseudoelasticity in Cu nanowires](https://dx.doi.org/10.1016/j.susc.2015.05.004), ***Surf. Sci.*** 641, 1-5 (2015).
1. D. V. Truong\*, **N. T. Hung**, T. Shimada and T. Kitamura, [Ab initio study of shear strain effects on ferroelectricity at PbTiO3 thin films](https://dx.doi.org/10.1016/j.susc.2012.04.024), ***Surf. Sci.*** 606, 1331-1339 (2012).
{: reversed="reversed"}
{:start="17"}
### Conference papers
5. V. V. Thanh\*, D. V. Truong and **N. T. Hung**, [Ab initio calculations of ideal strength and electronic property of hydrogenated biphenylene monolayer](https://doi.org/10.1007/978-3-031-39090-6_47), *in Proceedings of the 3rd Annual International Conference on Material, Machines and Methods for Sustainable Development (MMMS2022)*, ***Lecture Notes in Mechanical Engineering***, Springer, Singapore 415-421 (2024).
4. V. V. Thanh\*, N. T. Dung, D. V. Truong and **N. T. Hung**, [Turning electronic and optical properties of monolayer Janus Sn-dichalcogenides by biaxial strain](https://doi.org/10.1007/978-981-16-3239-6_77), *in Modern Mechanics and Applications*, ***Lecture Notes in Mechanical Engineering***, Springer, Singapore 981-989 (2022).
3. L. X. Bach, V. V. Thanh\*, H. V. Bao, D. V. Truong and **N. T. Hung**, [Electromechanical properties of monolayer Sn-dichalcogenides](https://doi.org/10.1007/978-981-16-3239-6_87), *in Modern Mechanics and Applications*, ***Lecture Notes in Mechanical Engineering***, Springer, Singapore 1113-1119 (2022).
2. N. V. Duy, V. V. Thanh\*, **N. T. Hung** and D. V. Truong, [Electromechanical actuators based on monolayer borophene with 𝛽12 and Χ3 structures](https://doi.org/10.1007/978-981-19-1968-8_58), *in The AUN/SEED-Net Joint Regional Conference in Transportation, Energy, and Mechanical Manufacturing Engineering. RCTEMME 2021*, ***Lecture Notes in Mechanical Engineering***, Springer, Singapore 710-718 (2022).
1. V. V. Thanh\*, **N. T. Hung**, T. T. Quang and D. V. Truong, [Determining ideal strength and electronic properties of Ge/Si core-shell nanowires](http://doi.org/10.7736/KSPE.2019.36.8.699), ***J. Korean Soc. Precis. Eng.*** 36, 1-6 (2019).
{: reversed="reversed"}
{:start="5"}
### Popular articles (in Vietnamese)
3. **N. T. Hung**\* and V. V. Thanh, [Thermal power and future applications in the automotive industry](https://vjol.info.vn/index.php/khcn/article/view/68899/58291), ***Vietnam J. Sci. Tech. Eng.*** 7A, 62-64 (2022).
2. **N. T. Hung**\* and V. V. Thanh, [Artificial muscle: When materials overcome nature's evolution](https://vjol.info.vn/index.php/khcn/article/view/51816/42670), ***Vietnam J. Sci. Tech. Eng.*** 9A, 62-64 (2020).
1. **N. T. Hung**\*, [Low-dimensional materials - Solution for thermoelectric development](https://vjol.info.vn/index.php/khcn/article/view/36278/29657), ***Vietnam J. Sci. Tech. Eng.*** 7A, 54-57 (2018).
{: reversed="reversed"}
{:start="3"}
